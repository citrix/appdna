# Application.InstallCapture Method 
 

Imports an <a href="1779bfff-4b29-0f26-8a09-10acdd530bbc">Application</a> object directly from the source file into previously created application, using Install Capture technology (for non-MSI files).

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public Application InstallCapture(
	InstallCaptureSourceDetails source,
	InstallCaptureConfiguration config
)
```

**VB**
```vbnet
Public Function InstallCapture ( 
	source As InstallCaptureSourceDetails,
	config As InstallCaptureConfiguration
) As Application
```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: <a href="df8a3890-8c6e-59f4-1152-dfdd9a4a18c0">Citrix.SDK.AppDNA.InstallCaptureSourceDetails</a><br />A collection of <a href="df8a3890-8c6e-59f4-1152-dfdd9a4a18c0">InstallCaptureSourceDetails</a> representing the capture details for each application to be imported. Each <a href="df8a3890-8c6e-59f4-1152-dfdd9a4a18c0">InstallCaptureSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that particular import.</dd><dt>config</dt><dd>Type: <a href="e17f570a-63db-91c5-d15b-1067a2151672">Citrix.SDK.AppDNA.InstallCaptureConfiguration</a><br />The configuration details to be used by this import.</dd></dl>

#### Return Value
Type: <a href="1779bfff-4b29-0f26-8a09-10acdd530bbc">Application</a><br />The imported application.

## See Also


#### Reference
<a href="1779bfff-4b29-0f26-8a09-10acdd530bbc">Application Class</a><br /><a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />