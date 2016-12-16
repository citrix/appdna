# VMSelectorsHelper.FindVMConfig Method 
 

Finding VM for application based on suitable VMs list

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static AppVVirtualMachineConfig FindVMConfig(
	Application application,
	AppVServer appVServer,
	ReadOnlyObservableCollection<AppVVirtualMachineConfig> vmConfigs
)
```

###VB
```vbnet
Public Shared Function FindVMConfig ( 
	application As Application,
	appVServer As AppVServer,
	vmConfigs As ReadOnlyObservableCollection(Of AppVVirtualMachineConfig)
) As AppVVirtualMachineConfig
```


#### Parameters
&nbsp;<dl><dt>application</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Application">Citrix.SDK.AppDNA.Application</a><br />Application</dd><dt>appVServer</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_AppVServer">Citrix.SDK.AppDNA.Solutions.AppV.AppVServer</a><br />App V Solution server</dd><dt>vmConfigs</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/ms668620" target="_blank">System.Collections.ObjectModel.ReadOnlyObservableCollection</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_AppVVirtualMachineConfig">AppVVirtualMachineConfig</a>)<br />Existing VMs</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_AppVVirtualMachineConfig">AppVVirtualMachineConfig</a><br />Suitable free VM if any or suitable busy VM

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VMSelectorsHelper">VMSelectorsHelper Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />