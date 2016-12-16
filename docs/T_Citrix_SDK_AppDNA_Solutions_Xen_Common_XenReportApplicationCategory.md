# XenReportApplicationCategory Enumeration
 

Indicates whether application can be used on target platform

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public enum XenReportApplicationCategory
```

###VB
```vbnet
Public Enumeration XenReportApplicationCategory
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.Solutions.Xen.Common.XenReportApplicationCategory.Unknown">**Unknown**</td><td>0</td><td>Application can't be used on target platform because it is locked, non-analysed of non-applicable for any reason</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.Solutions.Xen.Common.XenReportApplicationCategory.Server">**Server**</td><td>1</td><td>Application can be used on target platform without any additional effort</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.Solutions.Xen.Common.XenReportApplicationCategory.ServerWithRemediation">**ServerWithRemediation**</td><td>2</td><td>Application can be used on target platform after some remediation</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.Solutions.Xen.Common.XenReportApplicationCategory.DesktopOnly">**DesktopOnly**</td><td>3</td><td>Application can be used on target platform only in scope of Desktop Hosted Deployment model</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.Solutions.Xen.Common.XenReportApplicationCategory.NotSuitable">**NotSuitable**</td><td>4</td><td>Application can't be used in target platform due to analysis issues</td></tr></table>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />