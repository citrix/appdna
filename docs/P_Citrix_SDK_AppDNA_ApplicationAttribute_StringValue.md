# ApplicationAttribute.StringValue Property 
 

**Note: This API is now obsolete.**

Retrieves the string value assigned to this <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Property is obsolete, use ApplicationAttribute{T} instead")]
public string StringValue { get; }
```

###VB
```vbnet
<ObsoleteAttribute("Property is obsolete, use ApplicationAttribute{T} instead")>
Public ReadOnly Property StringValue As String
	Get
```


#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The string value of this <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> if the ApplicationAttributeDefinition.DataType is String or StringList. Throws an exception otherwise.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />