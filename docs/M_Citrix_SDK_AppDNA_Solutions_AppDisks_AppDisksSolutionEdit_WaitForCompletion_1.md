# AppDisksSolutionEdit.WaitForCompletion Method (TimeSpan)
 

Waits for the specified *timeout* for the processing task to complete.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppDisks">Citrix.SDK.AppDNA.Solutions.AppDisks</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppDisks (in Citrix.SDK.AppDNA.Solutions.AppDisks.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public bool WaitForCompletion(
	TimeSpan timeout
)
```

###VB
```vbnet
Public Function WaitForCompletion ( 
	timeout As TimeSpan
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The maximum time to wait for the processing task to complete.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if the processing task completes before the time out elapses; otherwise, `false`.

## Remarks
Completion will occur regardless of success, failure or cancellation. Use the <a href="P_Citrix_SDK_AppDNA_Solutions_AppDisks_AppDisksSolutionEdit_State">State</a> property to determine the state in which the task completed.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppDisks_AppDisksSolutionEdit">AppDisksSolutionEdit Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_AppDisks_AppDisksSolutionEdit_WaitForCompletion">WaitForCompletion Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppDisks">Citrix.SDK.AppDNA.Solutions.AppDisks Namespace</a><br />