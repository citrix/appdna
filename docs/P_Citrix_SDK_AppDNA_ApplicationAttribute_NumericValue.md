# ApplicationAttribute.NumericValue Property 
 

**Note: This API is now obsolete.**

Retrieves the numeric value assigned to this <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Property is obsolete, use ApplicationAttribute{T} instead")]
public Nullable<double> NumericValue { get; }
```

###VB
```vbnet
<ObsoleteAttribute("Property is obsolete, use ApplicationAttribute{T} instead")>
Public ReadOnly Property NumericValue As Nullable(Of Double)
	Get
```


#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/b3h38hb0" target="_blank">Nullable</a>(<a href="http://msdn2.microsoft.com/en-us/library/643eft0t" target="_blank">Double</a>)<br />The numeric value of this <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> if the ApplicationAttributeDefinition.DataType is Numeric. Throws an exception otherwise.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />