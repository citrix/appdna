# AppDisksSolution.GetSelectionScope Method 
 

**Note: This API is now obsolete.**

Gets a collection of application ids that will be used to generate the solution's report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppDisks">Citrix.SDK.AppDNA.Solutions.AppDisks</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppDisks (in Citrix.SDK.AppDNA.Solutions.AppDisks.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Use ApplicationSelectionScope method")]
public Collection<int> GetSelectionScope(
	ReportOptions reportOptions
)
```

###VB
```vbnet
<ObsoleteAttribute("Use ApplicationSelectionScope method")>
Public Function GetSelectionScope ( 
	reportOptions As ReportOptions
) As Collection(Of Integer)
```


#### Parameters
&nbsp;<dl><dt>reportOptions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report for which the application selection is required.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>)<br />A collection of application ids.

#### Implements
<a href="M_Citrix_SDK_AppDNA_Interfaces_ISolution_GetSelectionScope">ISolution.GetSelectionScope(ReportOptions)</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppDisks_AppDisksSolution">AppDisksSolution Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppDisks">Citrix.SDK.AppDNA.Solutions.AppDisks Namespace</a><br />