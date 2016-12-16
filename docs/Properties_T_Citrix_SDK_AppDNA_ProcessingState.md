# ProcessingState Properties
 

The <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a> type exposes the following members.


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
<a href="#processingstate-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />