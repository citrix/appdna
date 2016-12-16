# AttributeStringList.ReplaceString Method 
 

Replaces one string with another.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void ReplaceString(
	string existingValue,
	string newValue
)
```

###VB
```vbnet
Public Sub ReplaceString ( 
	existingValue As String,
	newValue As String
)
```


#### Parameters
&nbsp;<dl><dt>existingValue</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The string to replace in the list. If it doesn't exist, then the *newValue* string is added to the list.</dd><dt>newValue</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The string that will replace *existingValue*</dd></dl>

## Remarks
Any <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute_1">ApplicationAttribute(T)</a> referencing the old string will reference the new string.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />