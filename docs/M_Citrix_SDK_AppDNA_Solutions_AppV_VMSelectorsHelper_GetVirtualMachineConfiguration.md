# VMSelectorsHelper.GetVirtualMachineConfiguration Method 
 

Gets a virtual machine configuration.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static VirtualMachineConfiguration GetVirtualMachineConfiguration(
	int vmConfigId,
	AppVServer server
)
```

###VB
```vbnet
Public Shared Function GetVirtualMachineConfiguration ( 
	vmConfigId As Integer,
	server As AppVServer
) As VirtualMachineConfiguration
```


#### Parameters
&nbsp;<dl><dt>vmConfigId</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The ID of the virtual machine configuration.</dd><dt>server</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_AppVServer">Citrix.SDK.AppDNA.Solutions.AppV.AppVServer</a><br />The solution server to read virtual machine configurations from.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_VirtualMachineConfiguration">VirtualMachineConfiguration</a><br />The virtual machine configuration

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VMSelectorsHelper">VMSelectorsHelper Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />