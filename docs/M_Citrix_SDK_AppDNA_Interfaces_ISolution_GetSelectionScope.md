# ISolution.GetSelectionScope Method 
 

**Note: This API is now obsolete.**

Gets the application identifiers collection which can be selected for solution report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Interfaces">Citrix.SDK.AppDNA.Interfaces</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Use ApplicationSelectionScope method")]
Collection<int> GetSelectionScope(
	ReportOptions reportOptions
)
```

###VB
```vbnet
<ObsoleteAttribute("Use ApplicationSelectionScope method")>
Function GetSelectionScope ( 
	reportOptions As ReportOptions
) As Collection(Of Integer)
```


#### Parameters
&nbsp;<dl><dt>reportOptions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report options which selection scope is returned for.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>)<br />Collection of identifiers

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Interfaces_ISolution">ISolution Interface</a><br /><a href="N_Citrix_SDK_AppDNA_Interfaces">Citrix.SDK.AppDNA.Interfaces Namespace</a><br />