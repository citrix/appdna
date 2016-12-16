# ApplicationAttributeDefinitionService.Delete Method (ApplicationAttributeDefinition[])
 

Deletes the specified <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> objects.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void Delete(
	params ApplicationAttributeDefinition[] definitions
)
```

###VB
```vbnet
Public Sub Delete ( 
	ParamArray definitions As ApplicationAttributeDefinition()
)
```


#### Parameters
&nbsp;<dl><dt>definitions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">Citrix.SDK.AppDNA.ApplicationAttributeDefinition</a>[]<br />A collection of <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> objects to delete.</dd></dl>

## Remarks
System <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> objects cannot be deleted. All <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> objects that reference the deleted definitions will also be deleted.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinitionService">ApplicationAttributeDefinitionService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationAttributeDefinitionService_Delete">Delete Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />