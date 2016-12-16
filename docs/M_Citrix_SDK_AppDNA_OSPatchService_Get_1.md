# OSPatchService.Get Method (IEnumerable(Int64))
 

Returns a collection of Patch objects with matching identifiers.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Collection<OSPatch> Get(
	IEnumerable<long> patchIds
)
```

###VB
```vbnet
Public Function Get ( 
	patchIds As IEnumerable(Of Long)
) As Collection(Of OSPatch)
```


#### Parameters
&nbsp;<dl><dt>patchIds</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">Int64</a>)<br />A collection of application identifier values used to find the matching <a href="T_Citrix_SDK_AppDNA_OSPatch">OSPatch</a> objects.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_OSPatch">OSPatch</a>)<br />Returns the requested <a href="T_Citrix_SDK_AppDNA_OSPatch">OSPatch</a> objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_OSPatchService">OSPatchService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_OSPatchService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />