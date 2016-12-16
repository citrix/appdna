# XenUpgradeSolutionService.UpdateApplications Method 
 

Updates the applications for a given platform.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade (in Citrix.SDK.AppDNA.Solutions.XenUpgrade.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void UpdateApplications(
	XenSolutionPlatform solutionPlatform,
	IEnumerable<Application> applications
)
```

###VB
```vbnet
Public Sub UpdateApplications ( 
	solutionPlatform As XenSolutionPlatform,
	applications As IEnumerable(Of Application)
)
```


#### Parameters
&nbsp;<dl><dt>solutionPlatform</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionPlatform">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolutionPlatform</a><br />The solution platform.</dd><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The applications.</dd></dl>

#### Implements
<a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_UpdateApplications">IXenSolutionService(TXenSolution, TXenSolutionEditor).UpdateApplications(XenSolutionPlatform, IEnumerable(Application))</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolutionService">XenUpgradeSolutionService Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade Namespace</a><br />