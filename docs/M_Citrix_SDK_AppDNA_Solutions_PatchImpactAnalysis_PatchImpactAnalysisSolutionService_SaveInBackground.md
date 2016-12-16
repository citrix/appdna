# PatchImpactAnalysisSolutionService.SaveInBackground Method 
 

Creates a new Patch Impact Analysis solution on a background process.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis (in Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

###C#
```csharp
public PatchImpactAnalysisSolutionEdit SaveInBackground(
	IPatchImpactAnalysisSolutionConfig<IOsBuild> solutionConfig,
	bool isNew
)
```

###VB
```vbnet
Public Function SaveInBackground ( 
	solutionConfig As IPatchImpactAnalysisSolutionConfig(Of IOsBuild),
	isNew As Boolean
) As PatchImpactAnalysisSolutionEdit
```


#### Parameters
&nbsp;<dl><dt>solutionConfig</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_IPatchImpactAnalysisSolutionConfig_1">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis.IPatchImpactAnalysisSolutionConfig</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_IOsBuild">IOsBuild</a>)<br />The solution configuration.</dd><dt>isNew</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />if set to `true` [is new].</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_PatchImpactAnalysisSolutionEdit">PatchImpactAnalysisSolutionEdit</a><br />An <a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_PatchImpactAnalysisSolutionEdit">PatchImpactAnalysisSolutionEdit</a> object that can be used to track the progress of the solution creation operation.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis_PatchImpactAnalysisSolutionService">PatchImpactAnalysisSolutionService Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_PatchImpactAnalysis">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis Namespace</a><br />