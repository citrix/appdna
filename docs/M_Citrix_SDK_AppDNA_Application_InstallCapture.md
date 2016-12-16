# Application.InstallCapture Method 
 

Imports an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object directly from the source file into previously created application, using Install Capture technology (for non-MSI files).

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Application InstallCapture(
	InstallCaptureSourceDetails source,
	InstallCaptureConfiguration config
)
```

###VB
```vbnet
Public Function InstallCapture ( 
	source As InstallCaptureSourceDetails,
	config As InstallCaptureConfiguration
) As Application
```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">Citrix.SDK.AppDNA.InstallCaptureSourceDetails</a><br />A collection of <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> representing the capture details for each application to be imported. Each <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that particular import.</dd><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">Citrix.SDK.AppDNA.InstallCaptureConfiguration</a><br />The configuration details to be used by this import.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Application">Application</a><br />The imported application.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />