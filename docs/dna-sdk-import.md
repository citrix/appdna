#Import applications
Before an application can be analyzed, it must be imported into AppDNA. Two types of import are available using the SDK: direct import and install capture.1.	**Direct import**. Use this where the application source media is available in a form that can be directly imported; for example; msi files with optional transforms, and App-V streams.2.	**Install capture**. Use this when the application source media is a legacy executable installer or when you want added functionality to be performed as you import the file; for example, generating an App-V sequence.
##Direct importAll imports are performed through the object returned by the Server.Applications property. You can use any of the overloaded Import methods to perform a Direct import. For each import, you must specify an output folder where log files will be stored.
The following example illustrates how to import a single msi.
```
using AppDNA = Citrix.SDK.AppDNA;
AppDNA.Server appdna;
// Connect the appdna variable to the serverpublic AppDNA.Application Import(string msiSourceFile){	//Create a folder for the log files and other output.	string outputFolder = Environment.GetFolderPath(Environment.SpecialFolder.ApplicationData);	outputFolder = Path.Combine(outputFolder, "AppDNASample");
	Directory.CreateDirectory(outputFolder);
	string logFile = null;
	AppDNA.Application app = appdna.Application.Import(msiSourceFile, outputFolder, out logFile);	Console.WriteLine("Import log saved to " + logFile);
	return app;}```
The other overloads allow you to specify transform files that must be applied before importing an msi, as well as other configuration information.##Batch importAlthough convenient, the overloads of Import that return an Application object are inefficient for importing multiple applications. The AppDNA SDK supports batch importing where you specify the import details for multiple applications. An Import object is returned which allows the SDK to monitor the progress of the batch import and retrieve the resulting Application object for each imported file.The Import object uses each ImportSourceDetails object passed to the Import function as a key to retrieve the results, together with other information.
The following example shows how to perform a batch import for an enumerable collection of source file paths.
```
public Dictionary<string,AppDNA.Application> Import(IEnumerable<string> msiSourceFiles){	//Create a folder for the log files and other output.	string outputFolder = Environment.GetFolderPath(Environment.SpecialFolder.ApplicationData);	outputFolder = Path.Combine(outputFolder, "AppDNASample");
	Directory.CreateDirectory(outputFolder);
	// Build a list of ImportSourceDetails	var importDetails = new List<AppDNA.ImportSourceDetails>();
	foreach (var sourceFile in msiSourceFiles)
	{		importDetails.Add(new AppDNA.ImportSourceDetails(sourceFile));	}	// Build a result object to hold the imported applications
	var result = new Dictionary<string, AppDNA.Application>();
	// Start the import and wait for completion
	using (var import = appdna.Application.Import(importDetails, outputFolder))	{		import.WaitForCompletion();		//Enumerate through the ImportSourceDetails objects and use them as a key to get the results.		foreach (var detail in importDetails)		{			string msg = string.Format("Import log for {0} saved to {1}", detail.SourceFilePath, import.GetLogFilePath(detail));
			Console.WriteLine(msg);
			AppDNA.Application app = null;
			try			{				app = import.GetApplication(detail);			}			catch (Exception error)			{				msg = string.Format("Failed to import {0} due to error: {1}", detail.SourceFilePath, error.Message);				Console.WriteLine(msg);			}			if (app != null)
				result.Add(detail.SourceFilePath, app);		}	}	return result;}```You can further configure the import using an overload of the Import method that accepts an ApplicationImportConfiguration object. You can also use the other properties of ImportSourceDetails class.##Install captureInstall capture uses a VM Configuration and an Execution Profile to run a set of commands within a VM to generate an install that can be imported into AppDNA. For example, a legacy setup.exe can be snapshotted to generate an msi, which is then imported.
Before using Install Capture, configure the VM Configuration and Execution Profile using the AppDNA GUI client. Install capture uses the same batch importing method shown above.
```
public Dictionary<string, AppDNA.Application> InstallCapture(IEnumerable<string> legacySetupFiles){	//Create a folder for the log files and other output.	string outputFolder = Environment.GetFolderPath(Environment.SpecialFolder.ApplicationData);	outputFolder = Path.Combine(outputFolder, "AppDNASample");
	Directory.CreateDirectory(outputFolder);
	// Build a list of InstallCaptureSourceDetails
	var importDetails = new List<AppDNA.InstallCaptureSourceDetails>();
	foreach (var sourceFile in legacySetupFiles)
	{		importDetails.Add(new AppDNA.InstallCaptureSourceDetails(sourceFile));	}	// Build a result object to hold the imported applications
	var result = new Dictionary<string, AppDNA.Application>();
	// Start the install capture specifying the VMConfiguration and Execution Profile and wait for completion	using (var import = appdna.Application.InstallCapture(importDetails, "MyVMConfiguration", "Snapshot", outputFolder))	{		import.WaitForCompletion();		//Enumerate through the ImportSourceDetails objects and use them as a key to get the results.		foreach (var detail in importDetails)		{
		string msg = string.Format("Import log for {0} saved to {1}", detail.SourceFilePath, import.GetLogFilePath(detail));
		Console.WriteLine(msg);
		AppDNA.Application app = null;
		try		{			app = import.GetApplication(detail);		}		catch (Exception error)		{			msg = string.Format("Failed to import {0} due to error: {1}", detail.SourceFilePath, error.Message);
			Console.WriteLine(msg);		}		if (app != null)
			result.Add(detail.SourceFilePath, app);		}	}	return result;}```You can further configure install capture using an overload of the InstallCapture method that accepts an InstallCaptureConfiguration object. You can also use the other properties of the InstallCaptureSourceDetails class.##Display import progressTo obtain the state of the import for any given file when performing a batch import, use the Import.GetProcessingState method. This returns an object that provides details about the current state of the import for that file. It also implements INotifyPropertyChanged so that you can register for notifications when the import state changes.##SynchronizationContextsThe ApplicationImportConfiguration and InstallCaptureConfiguration classes expose a SynchronizationContext property. This defines which thread is used to raise any events you may have registered; for example, when registering for the ProcessingState.PropertyChanged event.By default, the SynchronizationContext used is the value of SynchronizationContext.Current when the ApplicationImportConfiguration and InstallCaptureConfiguration classes are constructed. In a background thread or a console application, usually this is null; you can also set this property to null manually. A null SynchronizationContext means events are raised on an arbitrary ThreadPool thread. To access GUI controls from your event handlers, direct the calls to your GUI thread.In the GUI thread of a WinForms or WPF application, the SynchronizationContext defaults to an appropriate SynchronizationContext, and the events are raised on the same GUI thread, allowing direct access to any GUI controls.The Import.WaitForCompletion() method does not block the current thread's SynchronizationContext but continues to service, for example, GUI events when invoked from a GUI thread. If you want to wait for completion without servicing GUI events, you can loop until Import.IsFinished is complete with a Thread.Sleep(â€¦) call inside the loop.