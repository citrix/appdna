# ApplicationService.InstallCapture Method (IEnumerable(InstallCaptureSourceDetails), String, String, String)
 

Imports application data utilizing Install Capture.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Import InstallCapture(
	IEnumerable<InstallCaptureSourceDetails> importDetails,
	string vmConfigurationName,
	string executionProfileName,
	string outputFolder
)
```

###VB
```vbnet
Public Function InstallCapture ( 
	importDetails As IEnumerable(Of InstallCaptureSourceDetails),
	vmConfigurationName As String,
	executionProfileName As String,
	outputFolder As String
) As Import
```


#### Parameters
&nbsp;<dl><dt>importDetails</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> representing the capture details for each application to be imported. Each <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that particular import.</dd><dt>vmConfigurationName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of an already configured VM Configuration.</dd><dt>executionProfileName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of an already configured VM Execution Profile</dd><dt>outputFolder</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the folder into which the output of the import process is to be placed.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Import">Import</a><br />An Importer object which can be used to track the import.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_InstallCapture">InstallCapture Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />