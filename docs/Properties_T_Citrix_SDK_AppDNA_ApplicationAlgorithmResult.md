# ApplicationAlgorithmResult Properties
 

The <a href="T_Citrix_SDK_AppDNA_ApplicationAlgorithmResult">ApplicationAlgorithmResult</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_AfterActionRag">AfterActionRag</a></td><td>
The RAG that would apply after the algorithm's action has been applied.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_Algorithm">Algorithm</a></td><td>
The Algorithm that this data applies to.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_Application">Application</a></td><td>
The Application that this data applies to.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_CustomizedRag">CustomizedRag</a></td><td>
The RAG from the analysis, with any customizations applied.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_Rag">Rag</a></td><td>
The RAG from the analysis.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_Results">Results</a></td><td>
Gets a <a href="http://msdn2.microsoft.com/en-us/library/9186hy08" target="_blank">DataTable</a> that holds the details of the application data that triggered the algorithm. `null` if the algorithm did not trigger or the results are not available.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_Triggered">Triggered</a></td><td>
True if <a href="P_Citrix_SDK_AppDNA_ApplicationAlgorithmResult_Results">Results</a> is not null. False may be due to no triggers or the application is unanalyzed or locked. See OverallRag in the ReportedApplication class.</td></tr></table>&nbsp;
<a href="#applicationalgorithmresult-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAlgorithmResult">ApplicationAlgorithmResult Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />