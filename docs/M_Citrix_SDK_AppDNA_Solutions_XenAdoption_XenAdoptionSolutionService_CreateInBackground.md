# XenAdoptionSolutionService.CreateInBackground Method 
 

Creates a <a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionSolution">XenAdoptionSolution</a> with the specified solution configuration.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenAdoption (in Citrix.SDK.AppDNA.Solutions.XenAdoption.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public XenAdoptionEdit CreateInBackground(
	IXenSolutionConfig solutionConfig
)
```

###VB
```vbnet
Public Function CreateInBackground ( 
	solutionConfig As IXenSolutionConfig
) As XenAdoptionEdit
```


#### Parameters
&nbsp;<dl><dt>solutionConfig</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionConfig">Citrix.SDK.AppDNA.Solutions.Xen.Common.IXenSolutionConfig</a><br />The solution configuration.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionEdit">XenAdoptionEdit</a><br />An object that can be used to track the progress of the solution creation.

#### Implements
<a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_CreateInBackground">IXenSolutionService(TXenSolution, TXenSolutionEditor).CreateInBackground(IXenSolutionConfig)</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionSolutionService">XenAdoptionSolutionService Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption Namespace</a><br />