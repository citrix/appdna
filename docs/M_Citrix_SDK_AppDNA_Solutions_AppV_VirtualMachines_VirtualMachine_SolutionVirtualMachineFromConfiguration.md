# VirtualMachine.SolutionVirtualMachineFromConfiguration Method 
 

Gets a virtual machine for a solution specific configuration.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static ISolutionVirtualMachine SolutionVirtualMachineFromConfiguration(
	VirtualMachineConfiguration configuration,
	Dictionary<string, string> replaceables = null
)
```

###VB
```vbnet
Public Shared Function SolutionVirtualMachineFromConfiguration ( 
	configuration As VirtualMachineConfiguration,
	Optional replaceables As Dictionary(Of String, String) = Nothing
) As ISolutionVirtualMachine
```


#### Parameters
&nbsp;<dl><dt>configuration</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_VirtualMachineConfiguration">Citrix.SDK.AppDNA.VirtualMachineConfiguration</a><br />The virtual machine configuration as <a href="T_Citrix_SDK_AppDNA_VirtualMachineConfiguration">VirtualMachineConfiguration</a>.</dd><dt>replaceables (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/xfhwa508" target="_blank">System.Collections.Generic.Dictionary</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>, <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />The additional parameters as key-value collection.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_ISolutionVirtualMachine">ISolutionVirtualMachine</a><br />The solution virtual machine as <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_ISolutionVirtualMachine">ISolutionVirtualMachine</a>.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_VirtualMachine">VirtualMachine Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines Namespace</a><br />