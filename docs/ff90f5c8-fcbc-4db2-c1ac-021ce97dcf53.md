# VMSelectorsHelper.FindAndLockSequncerVM Method (String, ReadOnlyObservableCollection(AppVVirtualMachineConfig), AppVVirtualMachineConfig)
 

Looking for VM configuration and try lock Sequencer VM

**Namespace:**&nbsp;<a href="a638ea88-d709-bd82-5735-d58961438ce5">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public static bool FindAndLockSequncerVM(
	string applicationPath,
	ReadOnlyObservableCollection<AppVVirtualMachineConfig> vmConfigs,
	out AppVVirtualMachineConfig findedVmConfig
)
```

**VB**
```vbnet
Public Shared Function FindAndLockSequncerVM ( 
	applicationPath As String,
	vmConfigs As ReadOnlyObservableCollection(Of AppVVirtualMachineConfig),
	<OutAttribute> ByRef findedVmConfig As AppVVirtualMachineConfig
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>applicationPath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Processed application path</dd><dt>vmConfigs</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/ms668620" target="_blank">System.Collections.ObjectModel.ReadOnlyObservableCollection</a>(<a href="9cd60ac7-2743-04e8-4529-aa98afc88a94">AppVVirtualMachineConfig</a>)<br />All existing vmConfigurations for current solution</dd><dt>findedVmConfig</dt><dd>Type: <a href="9cd60ac7-2743-04e8-4529-aa98afc88a94">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines.AppVVirtualMachineConfig</a><br />Found VM configuration for application</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />Result of capturing VM

## See Also


#### Reference
<a href="0860e23c-c44b-027b-78e8-5b6e38467a45">VMSelectorsHelper Class</a><br /><a href="21628586-aac6-bbbf-9d3e-832d5656862a">FindAndLockSequncerVM Overload</a><br /><a href="a638ea88-d709-bd82-5735-d58961438ce5">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />