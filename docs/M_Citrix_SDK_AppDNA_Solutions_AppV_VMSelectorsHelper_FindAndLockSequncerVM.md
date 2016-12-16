# VMSelectorsHelper.FindAndLockSequncerVM Method (Application, AppVServer, ReadOnlyObservableCollection(AppVVirtualMachineConfig), AppVVirtualMachineConfig)
 

Looking for VM configuration and try lock Sequencer VM

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static bool FindAndLockSequncerVM(
	Application application,
	AppVServer appVServer,
	ReadOnlyObservableCollection<AppVVirtualMachineConfig> vmConfigs,
	out AppVVirtualMachineConfig findedVmConfig
)
```

###VB
```vbnet
Public Shared Function FindAndLockSequncerVM ( 
	application As Application,
	appVServer As AppVServer,
	vmConfigs As ReadOnlyObservableCollection(Of AppVVirtualMachineConfig),
	<OutAttribute> ByRef findedVmConfig As AppVVirtualMachineConfig
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>application</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Application">Citrix.SDK.AppDNA.Application</a><br />Processed application</dd><dt>appVServer</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_AppVServer">Citrix.SDK.AppDNA.Solutions.AppV.AppVServer</a><br />AppV Server</dd><dt>vmConfigs</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/ms668620" target="_blank">System.Collections.ObjectModel.ReadOnlyObservableCollection</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_AppVVirtualMachineConfig">AppVVirtualMachineConfig</a>)<br />All existing vmConfigurations for current solution</dd><dt>findedVmConfig</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_AppVVirtualMachineConfig">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines.AppVVirtualMachineConfig</a><br />Found VM configuration for application</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />Result of capturing VM

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VMSelectorsHelper">VMSelectorsHelper Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_AppV_VMSelectorsHelper_FindAndLockSequncerVM">FindAndLockSequncerVM Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />