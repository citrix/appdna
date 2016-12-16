# XenAdoptionEdit.GetXenAdoptionSolution Method 
 

Gets the created or updated <a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionSolution">XenAdoptionSolution</a> object

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenAdoption (in Citrix.SDK.AppDNA.Solutions.XenAdoption.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public XenAdoptionSolution GetXenAdoptionSolution()
```

###VB
```vbnet
Public Function GetXenAdoptionSolution As XenAdoptionSolution
```


#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionSolution">XenAdoptionSolution</a><br />Created or updated <a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionSolution">XenAdoptionSolution</a> object

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="http://msdn2.microsoft.com/en-us/library/2asft85a" target="_blank">InvalidOperationException</a></td><td>ProcessingState.IsFinished must be true before calling GetXenAdoptionSolution().</td></tr><tr><td><a href="http://msdn2.microsoft.com/en-us/library/dd270641" target="_blank">TaskCanceledException</a></td><td>Editing was canceled</td></tr><tr><td><a href="T_Citrix_SDK_AppDNA_ServerTaskException">ServerTaskException</a></td><td /></tr></table>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionEdit">XenAdoptionEdit Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption Namespace</a><br />