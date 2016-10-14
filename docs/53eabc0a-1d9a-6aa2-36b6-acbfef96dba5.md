# AppDisksSolution.ApplicationSelectionScope Method 
 

Gets a collection of applications that will be used to generate the solution's report.

**Namespace:**&nbsp;<a href="3c384851-470e-e1e2-019f-9fa48f730a55">Citrix.SDK.AppDNA.Solutions.AppDisks</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppDisks (in Citrix.SDK.AppDNA.Solutions.AppDisks.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public IEnumerable<Application> ApplicationSelectionScope(
	ReportOptions reportOptions
)
```

**VB**
```vbnet
Public Function ApplicationSelectionScope ( 
	reportOptions As ReportOptions
) As IEnumerable(Of Application)
```


#### Parameters
&nbsp;<dl><dt>reportOptions</dt><dd>Type: <a href="82524f79-8658-d7a8-74fa-851734eb48fa">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report for which the application selection is required.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">IEnumerable</a>(<a href="1779bfff-4b29-0f26-8a09-10acdd530bbc">Application</a>)<br />A collection of applications.

#### Implements
<a href="41411ab5-156b-895a-b52c-95f7b91b2c06">ISolution.ApplicationSelectionScope(ReportOptions)</a><br />

## See Also


#### Reference
<a href="c558efde-3ed2-f446-b9f0-43e9bdfd40c2">AppDisksSolution Class</a><br /><a href="3c384851-470e-e1e2-019f-9fa48f730a55">Citrix.SDK.AppDNA.Solutions.AppDisks Namespace</a><br />