# PatchImpactAnalysisSolutionService.Create Method 
 

Creates a new Patch Impact Analysis solution

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis (in Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

###C#
```csharp
public PatchImpactAnalysisSolution Create(
	IPatchImpactAnalysisSolutionConfig<IOsBuild> solutionConfig
)
```

###VB
```vbnet
Public Function Create ( 
	solutionConfig As IPatchImpactAnalysisSolutionConfig(Of IOsBuild)
) As PatchImpactAnalysisSolution
```


#### Parameters
&nbsp;<dl><dt>solutionConfig</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_IPatchImpactAnalysisSolutionConfig_1">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis.IPatchImpactAnalysisSolutionConfig</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_IOsBuild">IOsBuild</a>)<br />Configuration for the new Build Assessment solution.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_PatchImpactAnalysisSolution">PatchImpactAnalysisSolution</a><br />The <a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_PatchImpactAnalysisSolution">PatchImpactAnalysisSolution</a> entity for the newly created solution.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_PatchImpactAnalysisSolutionService">PatchImpactAnalysisSolutionService Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis Namespace</a><br />