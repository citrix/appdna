# XenUpgradeEdit.WaitForCompletion Method (TimeSpan)
 

Waits for a long running operation to complete. Completion will occur regardless of success, failure or cancellation. Use the <a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeEdit_State">State</a> property to detect the state in which the operation completed.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade (in Citrix.SDK.AppDNA.Solutions.XenUpgrade.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public override bool WaitForCompletion(
	TimeSpan timeout
)
```

###VB
```vbnet
Public Overrides Function WaitForCompletion ( 
	timeout As TimeSpan
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The legth of time to wait for completion to occur.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if the operation completes before the timeout expires, otherwise `false`.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeEdit">XenUpgradeEdit Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeEdit_WaitForCompletion">WaitForCompletion Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade Namespace</a><br />