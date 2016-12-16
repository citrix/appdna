# ApplicationService.GetAsync Method (IEnumerable(Int64))
 

Returns a collection of Application objects with matching identifiers.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Task<Collection<Application>> GetAsync(
	IEnumerable<long> applicationIds
)
```

###VB
```vbnet
Public Function GetAsync ( 
	applicationIds As IEnumerable(Of Long)
) As Task(Of Collection(Of Application))
```


#### Parameters
&nbsp;<dl><dt>applicationIds</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">Int64</a>)<br />A collection of application identifier values used to find the matching <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(<a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>))<br />Returns the requested <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_GetAsync">GetAsync Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />