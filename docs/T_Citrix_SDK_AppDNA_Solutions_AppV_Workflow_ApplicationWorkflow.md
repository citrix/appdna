# ApplicationWorkflow Class
 

Contains application and it's own workflow state and history


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.AppV.Workflow.ApplicationWorkflow<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Workflow">Citrix.SDK.AppDNA.Solutions.AppV.Workflow</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ApplicationWorkflow : INotifyPropertyChanged, 
	IEquatable<ApplicationWorkflow>, IDisposable
```

###VB
```vbnet
Public Class ApplicationWorkflow
	Implements INotifyPropertyChanged, IEquatable(Of ApplicationWorkflow), 
	IDisposable
```

The ApplicationWorkflow type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_Application">Application</a></td><td>
Gets the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_ApplicationPath">ApplicationPath</a></td><td>
Gets the non imported application path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_AssignedVMConfig">AssignedVMConfig</a></td><td>
Get application assigned VMs</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_CurrentStep">CurrentStep</a></td><td>
Gets the current step.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_IsSequenceable">IsSequenceable</a></td><td>
Indicates whether the application can be sequenced or not.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_PackageIssuesPath">PackageIssuesPath</a></td><td>
Gets the package issues path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_PackageLocalFolderPath">PackageLocalFolderPath</a></td><td>
Gets or sets the local package folder.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_PackagePath">PackagePath</a></td><td>
Gets the package path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_RequiredApplications">RequiredApplications</a></td><td>
Gets the required applications.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_State">State</a></td><td>
Gets the state.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_Steps">Steps</a></td><td>
Gets the applications steps in workflow.</td></tr></table>&nbsp;
<a href="#applicationworkflow-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_Dispose">Dispose</a></td><td>
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>, is equal to this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_Equals">Equals(ApplicationWorkflow)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_IsFinished">IsFinished</a></td><td>
Determines whether the specified last step is finished.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_IsImported">IsImported</a></td><td>
Determines whether application is imported.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_MoveToNewStep">MoveToNewStep</a></td><td>
Moves to new step.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#applicationworkflow-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_Deleted">Deleted</a></td><td>
Occurs when flow is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_Logged">Logged</a></td><td>
Occurs when new step action is logged.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_PostedMessage">PostedMessage</a></td><td>
Occurs when a current processing sends a message.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#applicationworkflow-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Workflow">Citrix.SDK.AppDNA.Solutions.AppV.Workflow Namespace</a><br />