# IXenSolutionService(*TXenSolution*, *TXenSolutionEditor*).UpdateApplications Method 
 

Updates the applications for platform. It is short cut to update <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution</a> instead of <a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_Update">Update(IXenSolutionConfig)</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
void UpdateApplications(
	XenSolutionPlatform solutionPlatform,
	IEnumerable<Application> applications
)
```

###VB
```vbnet
Sub UpdateApplications ( 
	solutionPlatform As XenSolutionPlatform,
	applications As IEnumerable(Of Application)
)
```


#### Parameters
&nbsp;<dl><dt>solutionPlatform</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionPlatform">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolutionPlatform</a><br />The solution platform.</dd><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The applications.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2">IXenSolutionService(TXenSolution, TXenSolutionEditor) Interface</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />