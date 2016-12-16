# OsHelper.DesktopMigrationOS Method 
 

Chooses operation system for the Desktop Hosted deployment model for a pair of *serverPlatform* and *targetPlatform*

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static string DesktopMigrationOS(
	XenSolutionPlatform serverPlatform,
	XenSolutionPlatform targetPlatform,
	out bool isSuitable
)
```

###VB
```vbnet
Public Shared Function DesktopMigrationOS ( 
	serverPlatform As XenSolutionPlatform,
	targetPlatform As XenSolutionPlatform,
	<OutAttribute> ByRef isSuitable As Boolean
) As String
```


#### Parameters
&nbsp;<dl><dt>serverPlatform</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionPlatform">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolutionPlatform</a><br />The server platform.</dd><dt>targetPlatform</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionPlatform">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolutionPlatform</a><br />The target platform.</dd><dt>isSuitable</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />if set to `true` [is suitable].</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_OsHelper">OsHelper Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />