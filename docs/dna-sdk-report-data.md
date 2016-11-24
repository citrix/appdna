#Use report dataAfter applications have been analyzed against a ReportingConfiguration, you can retrieve report data using ReportConfiguration.GetReport.##Get report data for applicationsThe following example shows how to retrieve report data for each report Configuration. Each report contains data for all applications.
```
	AppDNA.Server appdna;	//Connect appdna
	public void Report()
	{
		var allReportConfigs = appdna.ReportConfiguration.Get();
		foreach (var reportConfig in allReportConfigs)
		{
			//Get a report for all applications
			using (var report = reportConfig.GetReport())			{
				//Report handling code.
			}
		}
	}```While the Application object lets you retrieve a report just for that application, to get report information for multiple applications, call ReportConfiguration.GetReport and pass a collection of applications. This is a more efficient method than looping through a collection of applications calling Application.GetReport.
**Note**: the Report object uses a background thread to download data. While this allows the caller to retrieve data about applications sooner, it means you must call the Report object's Dispose method to clean up this thread. This is best done with a "using" statement.##Export report views to fileFrom a report object, you can export certain predefined views of the report to an MHT file. For example:
```
report.Export( targetFilename, AppDNA.ReportType.EstateView, AppDNA.ReportExportFormat.MimeHMimeHtml, TimeSpan.FromMinutes(5) );```For details of which report views can be exported, see the ReportType enumeration.Some report views can aggregate information from multiple ReportConfigurations. To export these, use the object returned from the Server.Report property. For example:
```
AppDNA.Server appdna;//Connect appdnaappdna.Report.ExportApplicationRemediation();```##Get detailed or aggregated report data

In addition to exporting pre-defined report views, the Report object provides access to detailed information about each application and algorithm combination, as well as aggregated information for each application over all enabled algorithms in the ReportConfiguration.

To access the aggregated information for a given application, use the object stored in the ByApplication property.

```
public void Report(AppDNA.Application app)	{		var allReportConfigs = appdna.ReportConfiguration.Get();
		foreach (var reportConfig in allReportConfigs)		{
			//Get application's report for reportConfig using (var report = app.GetReport(reportConfig))
			{
				//Get the result data for our app.
				var appResult = report.ByApplication[app];
				//Write out the overall rag.
				string msg = reportConfig.Name + " : " + appResult.Application.Name + " : " + appResult.OverallRag.ToString(); 
				Console.WriteLine(msg);
			}
		}
	}```The ByApplication property returns a collection that can be enumerated or indexed by Application. It contains ReportedApplication objects that provide access to the Application object it holds the report data for. It also contains aggregated results for that Application against all the enabled algorithms in the Report object's ReportConfiguration.

Detailed results for each Application and Algorithm combination are available using the ByApplication collection or its equivalent ByAlgorithm collection. The ByAlgorithm collection contains ReportedAlgorithm objects; for example:

```
AppDNA.ReportedAlgorithm algResult = report.ByAlgorithm["x32_001"];

```
- A ReportedAlgorithm object has a ResultsByApplication property. This returns a collection that can be enumerated or indexed by Application.- A ReportedApplication object has a ResultsByAlgorithm property. This returns a collection that can be enumerated or indexed by Algorithm.Both these collections hold ApplicationAlgorithmResult objects that contain detailed information for a given application and algorithm combination. For example:
```
AppDNA.ApplicationAlgorithmResult appAndAlg = report.ByApplication[app].ResultsByAlgorithm["x32_001"]AppDNA.ApplicationAlgorithmResult appAndAlg2 = report.ResultsByAlgorithm["x32_001"].ByApplication[app];```Since the algorithm and application specified are the same, both appAndAlg and appAndAlg2 hold the same object.

If the parent ReportedApplication.RAG property is Unanalyzed or Locked, the ApplicationAlgorithmResult will have no useful data and its RAG property will be green. For example:

```
foreach (var reportedApp in report.ByApplication){	if (reportedApp.OverallRag == AppDNA.ReportRag.Unanalyzed		|| reportedApp.OverallRag == AppDNA.ReportRag.Locked)	{		//No useful data.
		continue;	}
	foreach (var algorithmResult in reportedApp.ResultsByAlgorithm)
	{
		if (algorithmResult.Triggered)
		{
			string msg = algorithmResult.Application.Name + " triggered " + algorithmResult;
			Console.WriteLine(msg);		}	}}
```
The details of the elements of the application that triggered the algorithm are held in the Results property. If the Triggered property is false, this returns null, otherwise it returns a DataTable with columns specific to the algorithm. Each row contains the corresponding data of a specific element in the application that triggered the algorithm. For example:
```
foreach (var algorithmResult in reportedApp.ResultsByAlgorithm){	if (algorithmResult.Triggered)	{		string msg = algorithmResult.Application.Name + " triggered " + algorithmResult.AlgorithmResult.Algorithm.Name;
		Console.WriteLine(msg);		//Write a row with the column names		foreach (System.Data.DataColumn column in algorithmResult.Results.Columns)		{			//Format at 10 chars wide, left aligned			msg = string.Format( "{0,-10}", column.ColumnName );
			Console.WriteLine(msg);		}		//Write out the details of everything in the app that triggered the algorithm
		foreach (System.Data.DataRow row in algorithmResult.Results.Rows)		{			//Format at 10 chars wide, left aligned
			foreach (object field in row.ItemArray)
			{
				msg = string.Format("{0,-10}", field.ToString());
				Console.WriteLine(msg);			}		}	}}```