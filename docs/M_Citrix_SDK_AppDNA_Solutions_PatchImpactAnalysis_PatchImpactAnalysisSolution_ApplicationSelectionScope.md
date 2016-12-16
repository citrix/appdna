# PatchImpactAnalysisSolution.ApplicationSelectionScope Method 
 

Gets a collection of applications that will be used to generate the solution's report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis (in Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

###C#
```csharp
public IEnumerable<Application> ApplicationSelectionScope(
	ReportOptions reportOptions
)
```

###VB
```vbnet
Public Function ApplicationSelectionScope ( 
	reportOptions As ReportOptions
) As IEnumerable(Of Application)
```


#### Parameters
&nbsp;<dl><dt>reportOptions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report for which the application selection is required.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />A collection of applications.

#### Implements
<a href="M_Citrix_SDK_AppDNA_Interfaces_ISolution_ApplicationSelectionScope">ISolution.ApplicationSelectionScope(ReportOptions)</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_PatchImpactAnalysisSolution">PatchImpactAnalysisSolution Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis Namespace</a><br />