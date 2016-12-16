# XenSolution.GetSelectionScope Method 
 

**Note: This API is now obsolete.**

Gets the selection scope.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Use ApplicationSelectionScope method")]
public Collection<int> GetSelectionScope(
	ReportOptions reportData
)
```

###VB
```vbnet
<ObsoleteAttribute("Use ApplicationSelectionScope method")>
Public Function GetSelectionScope ( 
	reportData As ReportOptions
) As Collection(Of Integer)
```


#### Parameters
&nbsp;<dl><dt>reportData</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />Report data which selection detects for</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>)<br />Collection of identifiers

#### Implements
<a href="M_Citrix_SDK_AppDNA_Interfaces_ISolution_GetSelectionScope">ISolution.GetSelectionScope(ReportOptions)</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />