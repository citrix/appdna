# InstallCaptureConfiguration.HideUserInterface Property 
 

Set this to true to hide the controls for the execution profile and the VM console. IMPORTANT: The <a href="5806b325-7fcb-90b9-cd16-537ae83368ef">InstallCommand</a> property of each <a href="df8a3890-8c6e-59f4-1152-dfdd9a4a18c0">InstallCaptureSourceDetails</a> must be set to do an unattended installation of the software. If necessary, you can use the VM provider's software to access the VM console independently of AppDNA to troubleshoot when the Install Capture has stalled.

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public bool HideUserInterface { get; set; }
```

**VB**
```vbnet
Public Property HideUserInterface As Boolean
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>

## See Also


#### Reference
<a href="e17f570a-63db-91c5-d15b-1067a2151672">InstallCaptureConfiguration Class</a><br /><a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />