# ApplicationAttributeDefinitionService.Get Method (IEnumerable(String))
 

Retrieves the specified <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> objects.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Collection<ApplicationAttributeDefinition> Get(
	IEnumerable<string> identifiers
)
```

###VB
```vbnet
Public Function Get ( 
	identifiers As IEnumerable(Of String)
) As Collection(Of ApplicationAttributeDefinition)
```


#### Parameters
&nbsp;<dl><dt>identifiers</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />A collection of identifier strings of the desired <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> instances.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a>)<br />A collection containing all the requested <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> objects. If one or more could not be found, they will be omitted from the return value.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinitionService">ApplicationAttributeDefinitionService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationAttributeDefinitionService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />