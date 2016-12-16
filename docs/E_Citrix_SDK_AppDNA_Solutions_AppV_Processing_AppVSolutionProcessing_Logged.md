# AppVSolutionProcessing.Logged Event
 

Occurs when new application action is occurred.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Processing">Citrix.SDK.AppDNA.Solutions.AppV.Processing</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public event EventHandler<DataEventArgs<Tuple<ApplicationWorkflow, WorkflowStep, StepLogEntry>>> Logged
```

###VB
```vbnet
Public Event Logged As EventHandler(Of DataEventArgs(Of Tuple(Of ApplicationWorkflow, WorkflowStep, StepLogEntry)))
```


#### Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/db0etb8x" target="_blank">System.EventHandler</a>(<a href="T_Citrix_SDK_AppDNA_DataEventArgs_1">DataEventArgs</a>(<a href="http://msdn2.microsoft.com/en-us/library/dd387150" target="_blank">Tuple</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_ApplicationWorkflow">ApplicationWorkflow</a>, <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_WorkflowStep">WorkflowStep</a>, <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Workflow_StepLogEntry">StepLogEntry</a>)))

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Processing_AppVSolutionProcessing">AppVSolutionProcessing Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Processing">Citrix.SDK.AppDNA.Solutions.AppV.Processing Namespace</a><br />