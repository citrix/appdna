# SolutionVmTaskAppvCheckResult Class
 

Represents the instance of Solution VM task checks result.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;VmTaskResult<br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines.SolutionVmTaskAppvCheckResult<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class SolutionVmTaskAppvCheckResult : VmTaskResult
```

###VB
```vbnet
Public Class SolutionVmTaskAppvCheckResult
	Inherits VmTaskResult
```

The SolutionVmTaskAppvCheckResult type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_SolutionVmTaskAppvCheckResult__ctor">SolutionVmTaskAppvCheckResult</a></td><td>
Creates an instance of SolutionVmTaskAppvCheckResult</td></tr></table>&nbsp;
<a href="#solutionvmtaskappvcheckresult-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_SolutionVmTaskAppvCheckResult_AppVInstalled">AppVInstalled</a></td><td>
Indicates whether AppV software installed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td>ErrorMessage</td><td> (Inherited from VmTaskResult.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td>LogMessage</td><td> (Inherited from VmTaskResult.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_SolutionVmTaskAppvCheckResult_OSBitness">OSBitness</a></td><td>
OS Bitness of virtual machine for AppV software.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_SolutionVmTaskAppvCheckResult_OSFamily">OSFamily</a></td><td>
OS Family of virtual machine for AppV software.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td>RebootRequired</td><td> (Inherited from VmTaskResult.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_SolutionVmTaskAppvCheckResult_Requirements">Requirements</a></td><td>
Requirements to meet AppV software installation as list of <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_AppvRequirementStatus">AppvRequirementStatus</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td>Success</td><td> (Inherited from VmTaskResult.)</td></tr></table>&nbsp;
<a href="#solutionvmtaskappvcheckresult-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines_SolutionVmTaskAppvCheckResult_Invalidate">Invalidate</a></td><td>
Invalidates this instance.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#solutionvmtaskappvcheckresult-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_VirtualMachines">Citrix.SDK.AppDNA.Solutions.AppV.VirtualMachines Namespace</a><br />