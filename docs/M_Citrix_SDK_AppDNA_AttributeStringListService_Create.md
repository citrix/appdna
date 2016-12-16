# AttributeStringListService.Create Method 
 

Creates an <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a> object.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public AttributeStringList Create(
	string name,
	string description,
	IEnumerable<string> strings
)
```

###VB
```vbnet
Public Function Create ( 
	name As String,
	description As String,
	strings As IEnumerable(Of String)
) As AttributeStringList
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a>.</dd><dt>description</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The description of the <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a>.</dd><dt>strings</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />A collection of strings that are to comprise the <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a>.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a><br />The newly created <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a> object.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_AttributeStringListService">AttributeStringListService Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />