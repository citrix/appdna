# Sequencing.WaitForCompletion Method (TimeSpan)
 

Returns a value indicating whether <a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Sequencing_IsFinished">IsFinished</a> has become `true` before the *timeout* elapses.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

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
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The maximum time to wait for <a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Sequencing_IsFinished">IsFinished</a> to become `true`.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if <a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Sequencing_IsFinished">IsFinished</a> becomes `true` before the *timeout* elapses; otherwise, `false`.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Sequencing">Sequencing Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_AppV_Sequencing_WaitForCompletion">WaitForCompletion Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />