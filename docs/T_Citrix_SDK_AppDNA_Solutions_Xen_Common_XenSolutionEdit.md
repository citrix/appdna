# XenSolutionEdit Class
 

Base class to represent object that helps


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolutionEdit<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionEdit">Citrix.SDK.AppDNA.Solutions.XenAdoption.XenAdoptionEdit</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeEdit">Citrix.SDK.AppDNA.Solutions.XenUpgrade.XenUpgradeEdit</a><br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public abstract class XenSolutionEdit : IDisposable
```

###VB
```vbnet
Public MustInherit Class XenSolutionEdit
	Implements IDisposable
```

The XenSolutionEdit type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit__ctor">XenSolutionEdit</a></td><td>
Initializes a new instance of the XenSolutionEdit class</td></tr></table>&nbsp;
<a href="#xensolutionedit-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_ProcessingState">ProcessingState</a></td><td>
Gets or sets the object to track the processing.</td></tr></table>&nbsp;
<a href="#xensolutionedit-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_Dispose">Dispose()</a></td><td>
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_Dispose_1">Dispose(Boolean)</a></td><td>
Releases unmanaged and - optionally - managed resources.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_GetXenSolution">GetXenSolution</a></td><td>
Gets the Xen solution after the background process is finished.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_WaitForCompletion">WaitForCompletion()</a></td><td>
Waits for long running operation completes. Completion will occur regardless of success, failure or cancellation. Use a <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_ProcessingState">ProcessingState</a> property to detect the reason.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_WaitForCompletion_1">WaitForCompletion(TimeSpan)</a></td><td>
Waits for a long running operation to complete. Completion will occur regardless of success, failure or cancellation. Use a <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_ProcessingState">ProcessingState</a> property to detect the reason.</td></tr></table>&nbsp;
<a href="#xensolutionedit-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected field](media/protfield.gif "Protected field")</td><td><a href="F_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_disposed">disposed</a></td><td>
Indicates whether object is already disposed</td></tr></table>&nbsp;
<a href="#xensolutionedit-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />