# InstallCaptureConfiguration.HideUserInterface Property 
 

Set this to true to hide the controls for the execution profile and the VM console. IMPORTANT: The <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_InstallCommand">InstallCommand</a> property of each <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> must be set to do an unattended installation of the software. If necessary, you can use the VM provider's software to access the VM console independently of AppDNA to troubleshoot when the Install Capture has stalled.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public bool HideUserInterface { get; set; }
```

###VB
```vbnet
Public Property HideUserInterface As Boolean
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">InstallCaptureConfiguration Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />