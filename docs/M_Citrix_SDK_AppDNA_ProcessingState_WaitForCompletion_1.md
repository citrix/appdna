# ProcessingState.WaitForCompletion Method (TimeSpan)
 

Waits for long running operation completes. Completion will occur regardless of success, failure or cancellation. Use a <a href="P_Citrix_SDK_AppDNA_ProcessingState_State">State</a> property to detect the reason.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

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
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The timeout to wait for a completion.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if completes before time out, otherwise `false`.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ProcessingState_WaitForCompletion">WaitForCompletion Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />