# Analysis Class
 

Represents a requested analysis. Use this to monitor the state of the analysis and retrieve the resulting report. An instance of this class is returned from a call to Analyze method of <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> class.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Analysis<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public sealed class Analysis : IDisposable
```

###VB
```vbnet
Public NotInheritable Class Analysis
	Implements IDisposable
```

The Analysis type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Analysis_Applications">Applications</a></td><td>
Gets an enumeration of the applications that were requested to be analyzed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Analysis_IsFinished">IsFinished</a></td><td>
Gets a value indicating whether the analysis has stopped running. Use the <a href="P_Citrix_SDK_AppDNA_Analysis_ProcessingState">ProcessingState</a> property to determine whether the analysis succeeded, failed or was cancelled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Analysis_Patches">Patches</a></td><td>
Gets an enumeration of the patches that were requested to be analyzed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Analysis_ProcessingState">ProcessingState</a></td><td>
Gets a <a href="P_Citrix_SDK_AppDNA_Analysis_ProcessingState">ProcessingState</a> object that represents the state of the analysis.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Analysis_ReportingConfigurations">ReportingConfigurations</a></td><td>
Gets an enumeration of the report configurations that were requested to be used in the analysis.</td></tr></table>&nbsp;
<a href="#analysis-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Analysis_Dispose">Dispose</a></td><td>
Disposes of the object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Analysis_GetReport">GetReport()</a></td><td>
Returns an instance of the <a href="T_Citrix_SDK_AppDNA_Report">Report</a> class that contains the results of the analysis. If more than one <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> was specified in the analysis, only the report for the first is returned. This must not be called unless <a href="P_Citrix_SDK_AppDNA_Analysis_IsFinished">IsFinished</a> is `true`.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Analysis_GetReport_1">GetReport(ReportConfiguration)</a></td><td>
Returns an instance of the <a href="T_Citrix_SDK_AppDNA_Report">Report</a> class that contains the results of the analysis. This must not be called unless <a href="P_Citrix_SDK_AppDNA_Analysis_IsFinished">IsFinished</a> is `true`.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Analysis_RequestCancel">RequestCancel</a></td><td>
Requests that the analysis stop running. Cancellation may take some time. <a href="M_Citrix_SDK_AppDNA_Analysis_WaitForCompletion">WaitForCompletion()</a> and <a href="P_Citrix_SDK_AppDNA_Analysis_ProcessingState">ProcessingState</a> can be used to check the state of the analysis.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Analysis_WaitForCompletion">WaitForCompletion()</a></td><td>
Returns when <a href="P_Citrix_SDK_AppDNA_Analysis_IsFinished">IsFinished</a> is `true`.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Analysis_WaitForCompletion_1">WaitForCompletion(TimeSpan)</a></td><td>
Waits a specific length of time for completion.</td></tr></table>&nbsp;
<a href="#analysis-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />