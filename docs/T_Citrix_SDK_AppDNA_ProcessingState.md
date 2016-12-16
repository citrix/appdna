# ProcessingState Class
 

Represents the state of a processing action that is running asynchronously. Typically, this is a server-side processing task.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.ProcessingState<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public sealed class ProcessingState : INotifyPropertyChanged, 
	IDisposable
```

###VB
```vbnet
Public NotInheritable Class ProcessingState
	Implements INotifyPropertyChanged, IDisposable
```

The ProcessingState type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_CancelRequested">CancelRequested</a></td><td>
Gets a value specifying whether there is a request to cancel the task or not. After cancellation is requested, the task may complete, fail or take time to stop due to cancellation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_CurrentAction">CurrentAction</a></td><td>
Gets a string specifying the current action that the processing task is performing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_CurrentActionDetail">CurrentActionDetail</a></td><td>
Gets a string specifying more detail of the current action.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_DateEnded">DateEnded</a></td><td>
Gets a DateTime that specifies the time that the task finished. Will be null if it has not yet finished.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_DateStarted">DateStarted</a></td><td>
Gets a DateTime that specifies the time that the task was created.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_Description">Description</a></td><td>
Gets a description of the task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_HasWarnings">HasWarnings</a></td><td>
Gets whether the task has warnings</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_InitiatingUserName">InitiatingUserName</a></td><td>
Gets the AppDNA username of the user that initiated the task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_IsFinished">IsFinished</a></td><td>
Gets a value specifying if the server side processing has no more work to do.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_LogFile">LogFile</a></td><td>
Gets a log file path, if any, associated with the current processing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_Name">Name</a></td><td>
Gets the name of the task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_Progress">Progress</a></td><td>
Gets the current progress as a percentage. May be null if the task has not yet started or the task does not support progress reporting.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_Result">Result</a></td><td>
Gets a string representing the result of the task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProcessingState_State">State</a></td><td>
Gets a value specifying the current running state of the task.</td></tr></table>&nbsp;
<a href="#processingstate-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ProcessingState_Dispose">Dispose</a></td><td>
Immediately frees up resources held by this object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ProcessingState_WaitForCompletion">WaitForCompletion()</a></td><td>
Waits for long running operation completes. Completion will occur regardless of success, failure or cancellation. Use a <a href="P_Citrix_SDK_AppDNA_ProcessingState_State">State</a> property to detect the reason.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ProcessingState_WaitForCompletion_1">WaitForCompletion(TimeSpan)</a></td><td>
Waits for long running operation completes. Completion will occur regardless of success, failure or cancellation. Use a <a href="P_Citrix_SDK_AppDNA_ProcessingState_State">State</a> property to detect the reason.</td></tr></table>&nbsp;
<a href="#processingstate-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ProcessingState_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#processingstate-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />