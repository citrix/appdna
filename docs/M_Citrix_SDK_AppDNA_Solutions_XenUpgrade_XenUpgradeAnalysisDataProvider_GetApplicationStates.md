# XenUpgradeAnalysisDataProvider.GetApplicationStates Method 
 

Gets the application states for the specified report configurations.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade (in Citrix.SDK.AppDNA.Solutions.XenUpgrade.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
protected override Collection<IApplicationRuleModuleState> GetApplicationStates(
	Collection<Application> applications,
	IEnumerable<ReportConfiguration> reportConfigurations
)
```

###VB
```vbnet
Protected Overrides Function GetApplicationStates ( 
	applications As Collection(Of Application),
	reportConfigurations As IEnumerable(Of ReportConfiguration)
) As Collection(Of IApplicationRuleModuleState)
```


#### Parameters
&nbsp;<dl><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">System.Collections.ObjectModel.Collection</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />Applications collection.</dd><dt>reportConfigurations</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>)<br />Report configurations.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_IApplicationRuleModuleState">IApplicationRuleModuleState</a>)<br />Collection of <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_IApplicationRuleModuleState">IApplicationRuleModuleState</a> objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeAnalysisDataProvider">XenUpgradeAnalysisDataProvider Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade Namespace</a><br />