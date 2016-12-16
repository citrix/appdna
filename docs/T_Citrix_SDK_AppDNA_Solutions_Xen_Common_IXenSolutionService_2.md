# IXenSolutionService(*TXenSolution*, *TXenSolutionEditor*) Interface
 

Exposes common functionality for SDK's services for xen solutions

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public interface IXenSolutionService<out TXenSolution, out TXenSolutionEditor>
where TXenSolution : XenSolution
where TXenSolutionEditor : XenSolutionEdit

```

###VB
```vbnet
Public Interface IXenSolutionService(Of Out TXenSolution As XenSolution, Out TXenSolutionEditor As XenSolutionEdit)
```


#### Type Parameters
&nbsp;<dl><dt>TXenSolution</dt><dd>The type of the xen solution.</dd><dt>TXenSolutionEditor</dt><dd>The type of the object than can be used to track editing.</dd></dl>&nbsp;
The IXenSolutionService(TXenSolution, TXenSolutionEditor) type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_Create">Create</a></td><td>
Creates solution with the specified solution configuration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_CreateInBackground">CreateInBackground</a></td><td>
Creates solution with the specified solution configuration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_Get">Get()</a></td><td>
Gets collection of <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_Get_1">Get(String)</a></td><td>
Gets the solution with specified solution identifier.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_Update">Update</a></td><td>
Updates solution with the specified solution configuration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_UpdateApplications">UpdateApplications</a></td><td>
Updates the applications for platform. It is short cut to update <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution</a> instead of <a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_Update">Update(IXenSolutionConfig)</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_IXenSolutionService_2_UpdateInBackground">UpdateInBackground</a></td><td>
Updates solution with the specified solution configuration.</td></tr></table>&nbsp;
<a href="#ixensolutionservice(*txensolution*,-*txensolutioneditor*)-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />