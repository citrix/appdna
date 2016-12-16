# AttributeStringListService.Get Method (Int32)
 

**Note: This API is now obsolete.**

Retrieves a specific <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a> object.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Use Get(long id) overload")]
public AttributeStringList Get(
	int id
)
```

###VB
```vbnet
<ObsoleteAttribute("Use Get(long id) overload")>
Public Function Get ( 
	id As Integer
) As AttributeStringList
```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The Id of the <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a> to retrieve.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a><br />The specified AttributeStringList object. Throws an exception if it cannot be found.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_AttributeStringListService">AttributeStringListService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_AttributeStringListService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />