# XenAnalysisDataProvider.GetSelectedApplicationsForPlatforms Method 
 

Gets the selected applications for platforms.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
protected static List<int> GetSelectedApplicationsForPlatforms(
	XenSolution solution,
	Func<XenSolutionPlatform, bool> platformPredicate
)
```

###VB
```vbnet
Protected Shared Function GetSelectedApplicationsForPlatforms ( 
	solution As XenSolution,
	platformPredicate As Func(Of XenSolutionPlatform, Boolean)
) As List(Of Integer)
```


#### Parameters
&nbsp;<dl><dt>solution</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolution</a><br />The solution.</dd><dt>platformPredicate</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/bb549151" target="_blank">System.Func</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionPlatform">XenSolutionPlatform</a>, <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>)<br />The platform selector.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">List</a>(<a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>)<br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider">XenAnalysisDataProvider Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />