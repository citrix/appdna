# Import Methods
 

The <a href="T_Citrix_SDK_AppDNA_Import">Import</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_Cancel">Cancel</a></td><td>
Requests that the specified import sources cancel both on the client and on the server side. Also, call this method to cancel work (e.g. Web Spider capturing) before the actual import has started.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_Dispose">Dispose</a></td><td>
Halts the import and releases resources. Failure to dispose of this object may leak resources.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_GetApplication">GetApplication(IImportDetails)</a></td><td>
Returns the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object resulting from the import defined by *details*.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_GetApplication_1">GetApplication(IImportDetails, TimeSpan)</a></td><td>
Returns the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object resulting from the import defined by *details*.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_GetLogFilePath">GetLogFilePath</a></td><td>
Returns the full path to the text log file that holds the log of the import defined by *details*.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_GetOutputDirectory">GetOutputDirectory</a></td><td>
Returns the Output directory which is to contain install capture files, which is generated on the fly (with timestamp + application name).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_GetProcessingState">GetProcessingState</a></td><td>
Returns the <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a> object that represents the state of the import defined by *details*.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_RequestCancel">RequestCancel</a></td><td>
Requests that the current import stops. <a href="P_Citrix_SDK_AppDNA_Import_IsFinished">IsFinished</a> is set to `true` subsequently, not immediately.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_WaitForCompletion">WaitForCompletion()</a></td><td>
Returns when <a href="P_Citrix_SDK_AppDNA_Import_IsFinished">IsFinished</a> is `true`.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Import_WaitForCompletion_1">WaitForCompletion(TimeSpan)</a></td><td>
Returns true if <a href="P_Citrix_SDK_AppDNA_Import_IsFinished">IsFinished</a> is `true` before *timeout* elapses.</td></tr></table>&nbsp;
<a href="#import-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Import">Import Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />