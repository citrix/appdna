# ApplicationService.InstallCapture Method (IEnumerable(InstallCaptureSourceDetails), InstallCaptureConfiguration, Nullable(Int64))
 

Imports application data utilizing Install Capture.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Application InstallCapture(
	IEnumerable<InstallCaptureSourceDetails> importDetails,
	InstallCaptureConfiguration config,
	Nullable<long> applicationID
)
```

###VB
```vbnet
Public Function InstallCapture ( 
	importDetails As IEnumerable(Of InstallCaptureSourceDetails),
	config As InstallCaptureConfiguration,
	applicationID As Nullable(Of Long)
) As Application
```


#### Parameters
&nbsp;<dl><dt>importDetails</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> representing the capture details for each application to be imported. Each <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that particular import.</dd><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">Citrix.SDK.AppDNA.InstallCaptureConfiguration</a><br />The configuration details to be used by this import.</dd><dt>applicationID</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/b3h38hb0" target="_blank">System.Nullable</a>(<a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">Int64</a>)<br />The application identifier to import into (in case of stub application).</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Application">Application</a><br />An <a href="T_Citrix_SDK_AppDNA_Import">Import</a> object which can be used to track the import.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="http://msdn2.microsoft.com/en-us/library/27426hcy" target="_blank">ArgumentNullException</a></td><td>config</td></tr></table>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_InstallCapture">InstallCapture Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />