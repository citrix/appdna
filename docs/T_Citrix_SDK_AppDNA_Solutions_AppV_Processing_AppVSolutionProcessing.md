# AppVSolutionProcessing Class
 

Exposes app-v conveyor


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.AppV.Processing.AppVSolutionProcessing<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Processing">Citrix.SDK.AppDNA.Solutions.AppV.Processing</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class AppVSolutionProcessing : IDisposable
```

###VB
```vbnet
Public Class AppVSolutionProcessing
	Implements IDisposable
```

The AppVSolutionProcessing type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_IsFinished">IsFinished</a></td><td>
Gets a value indicating whether this instance is finished.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_IsRunning">IsRunning</a></td><td>
Gets a value indicating whether this instance is running.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_State">State</a></td><td>
Gets the state of processing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_Steps">Steps</a></td><td>
Gets the steps.</td></tr></table>&nbsp;
<a href="#appvsolutionprocessing-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_Begin">Begin</a></td><td>
Begins this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_Cancel">Cancel</a></td><td>
Cancels this processing.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_CancelWithReset">CancelWithReset</a></td><td>
Cancels this processing and resets state.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_Dispose">Dispose</a></td><td>
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_Reset">Reset</a></td><td>
Reset this processing.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_WaitForCompletion">WaitForCompletion()</a></td><td>
Returns when <a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_IsFinished">IsFinished</a> is `true`.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_WaitForCompletion_1">WaitForCompletion(TimeSpan)</a></td><td>
Returns a value indicating whether <a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_IsFinished">IsFinished</a> has become `true` before the *timeout* elapses.</td></tr></table>&nbsp;
<a href="#appvsolutionprocessing-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing_Logged">Logged</a></td><td>
Occurs when new application action is occurred.</td></tr></table>&nbsp;
<a href="#appvsolutionprocessing-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Processing">Citrix.SDK.AppDNA.Solutions.AppV.Processing Namespace</a><br />