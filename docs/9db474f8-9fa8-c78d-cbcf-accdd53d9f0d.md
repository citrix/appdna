# ApplicationAttributeDefinitionService.Get Method (IEnumerable(String))
 

Retrieves the specified <a href="6abacc77-38ad-8572-e2dd-e6f19ca0f74c">ApplicationAttributeDefinition</a> objects.

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public Collection<ApplicationAttributeDefinition> Get(
	IEnumerable<string> identifiers
)
```

**VB**
```vbnet
Public Function Get ( 
	identifiers As IEnumerable(Of String)
) As Collection(Of ApplicationAttributeDefinition)
```


#### Parameters
&nbsp;<dl><dt>identifiers</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />A collection of identifier strings of the desired <a href="6abacc77-38ad-8572-e2dd-e6f19ca0f74c">ApplicationAttributeDefinition</a> instances.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="6abacc77-38ad-8572-e2dd-e6f19ca0f74c">ApplicationAttributeDefinition</a>)<br />A collection containing all the requested <a href="6abacc77-38ad-8572-e2dd-e6f19ca0f74c">ApplicationAttributeDefinition</a> objects. If one or more could not be found, they will be omitted from the return value.

## See Also


#### Reference
<a href="ea8d208e-2e45-940c-103d-bff3bbef2876">ApplicationAttributeDefinitionService Class</a><br /><a href="5f858199-5ae3-e5df-e871-99b74ce569ad">Get Overload</a><br /><a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />