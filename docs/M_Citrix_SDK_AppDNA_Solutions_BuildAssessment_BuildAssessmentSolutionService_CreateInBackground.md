# BuildAssessmentSolutionService.CreateInBackground Method 
 

Creates a new Build Assessment solution on a background process.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.BuildAssessment (in Citrix.SDK.AppDNA.Solutions.BuildAssessment.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public BuildAssessmentSolutionEdit CreateInBackground(
	IBuildAssessmentSolutionConfig<IOsBuild> solutionConfig
)
```

###VB
```vbnet
Public Function CreateInBackground ( 
	solutionConfig As IBuildAssessmentSolutionConfig(Of IOsBuild)
) As BuildAssessmentSolutionEdit
```


#### Parameters
&nbsp;<dl><dt>solutionConfig</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_BuildAssessment_IBuildAssessmentSolutionConfig_1">Citrix.SDK.AppDNA.Solutions.BuildAssessment.IBuildAssessmentSolutionConfig</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_BuildAssessment_IOsBuild">IOsBuild</a>)<br />The solution configuration.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolutionEdit">BuildAssessmentSolutionEdit</a><br />An <a href="T_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolutionEdit">BuildAssessmentSolutionEdit</a> object that can be used to track the progress of the solution creation operation.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolutionService">BuildAssessmentSolutionService Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment Namespace</a><br />