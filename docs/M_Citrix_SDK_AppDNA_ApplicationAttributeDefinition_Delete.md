# ApplicationAttributeDefinition.Delete Method 
 

Deletes the <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> object.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void Delete()
```

###VB
```vbnet
Public Sub Delete
```


## Remarks
<a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> objects for which <a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_IsSystem">IsSystem</a> is true cannot be deleted. All <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute_1">ApplicationAttribute(T)</a> objects that reference the deleted definition will also be deleted.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />