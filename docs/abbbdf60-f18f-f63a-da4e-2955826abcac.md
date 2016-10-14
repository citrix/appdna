# AppDisksSolution.GetSelectionScope Method 
 

**Note: This API is now obsolete.**

Gets a collection of application ids that will be used to generate the solution's report.

**Namespace:**&nbsp;<a href="3c384851-470e-e1e2-019f-9fa48f730a55">Citrix.SDK.AppDNA.Solutions.AppDisks</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppDisks (in Citrix.SDK.AppDNA.Solutions.AppDisks.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
[ObsoleteAttribute("Use ApplicationSelectionScope method")]
public Collection<int> GetSelectionScope(
	ReportOptions reportOptions
)
```

**VB**
```vbnet
<ObsoleteAttribute("Use ApplicationSelectionScope method")>
Public Function GetSelectionScope ( 
	reportOptions As ReportOptions
) As Collection(Of Integer)
```


#### Parameters
&nbsp;<dl><dt>reportOptions</dt><dd>Type: <a href="82524f79-8658-d7a8-74fa-851734eb48fa">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report for which the application selection is required.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>)<br />A collection of application ids.

#### Implements
<a href="4883af2e-79ca-4c03-4f00-bddf19f71969">ISolution.GetSelectionScope(ReportOptions)</a><br />

## See Also


#### Reference
<a href="c558efde-3ed2-f446-b9f0-43e9bdfd40c2">AppDisksSolution Class</a><br /><a href="3c384851-470e-e1e2-019f-9fa48f730a55">Citrix.SDK.AppDNA.Solutions.AppDisks Namespace</a><br />