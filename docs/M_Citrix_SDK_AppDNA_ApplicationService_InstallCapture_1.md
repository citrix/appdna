# ApplicationService.InstallCapture Method (IEnumerable(InstallCaptureSourceDetails), InstallCaptureConfiguration)
 

Imports application data utilizing Install Capture technology.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Import InstallCapture(
	IEnumerable<InstallCaptureSourceDetails> importDetails,
	InstallCaptureConfiguration config
)
```

###VB
```vbnet
Public Function InstallCapture ( 
	importDetails As IEnumerable(Of InstallCaptureSourceDetails),
	config As InstallCaptureConfiguration
) As Import
```


#### Parameters
&nbsp;<dl><dt>importDetails</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> representing the capture details for each application to be imported. Each <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that particular import.</dd><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">Citrix.SDK.AppDNA.InstallCaptureConfiguration</a><br />The configuration details to be used by this import.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Import">Import</a><br />An <a href="T_Citrix_SDK_AppDNA_Import">Import</a> object which can be used to track the import.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_InstallCapture">InstallCapture Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />