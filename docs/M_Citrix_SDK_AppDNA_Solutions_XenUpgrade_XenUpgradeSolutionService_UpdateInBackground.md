# XenUpgradeSolutionService.UpdateInBackground Method 
 

Updates the <a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution">XenUpgradeSolution</a> with the specified solution configuration.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade (in Citrix.SDK.AppDNA.Solutions.XenUpgrade.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public XenUpgradeEdit UpdateInBackground(
	IXenSolutionConfig solutionConfig
)
```

###VB
```vbnet
Public Function UpdateInBackground ( 
	solutionConfig As IXenSolutionConfig
) As XenUpgradeEdit
```


#### Parameters
&nbsp;<dl><dt>solutionConfig</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionConfig">Citrix.SDK.AppDNA.Solutions.Xen.Common.IXenSolutionConfig</a><br />The solution configuration.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeEdit">XenUpgradeEdit</a><br />An object that can be used to track the progress of the update.

#### Implements
<a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_UpdateInBackground">IXenSolutionService(TXenSolution, TXenSolutionEditor).UpdateInBackground(IXenSolutionConfig)</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolutionService">XenUpgradeSolutionService Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade Namespace</a><br />