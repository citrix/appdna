# IVirtualMachine.Revert Method 
 

Reverts the virtual machine to the snapshot.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
void Revert(
	string snapshotName = null
)
```

###VB
```vbnet
Sub Revert ( 
	Optional snapshotName As String = Nothing
)
```


#### Parameters
&nbsp;<dl><dt>snapshotName (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />A snapshot name to revert to, if not specified, reverted to the snapshot from the initial VM configuration.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_IVirtualMachine">IVirtualMachine Interface</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines Namespace</a><br />