# ApplicationAttributeDefinitionService.CreateRagDefinition Method 
 

Creates an <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> with a <a href="T_Citrix_SDK_AppDNA_Rag">Rag</a> data type.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ApplicationAttributeDefinition CreateRagDefinition(
	string identifier,
	string name,
	bool isReportDependent,
	AttributeDefinitionVisibilities visibility,
	int order
)
```

###VB
```vbnet
Public Function CreateRagDefinition ( 
	identifier As String,
	name As String,
	isReportDependent As Boolean,
	visibility As AttributeDefinitionVisibilities,
	order As Integer
) As ApplicationAttributeDefinition
```


#### Parameters
&nbsp;<dl><dt>identifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The unique identifier for the <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a>.</dd><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name for the <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a>.</dd><dt>isReportDependent</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />A boolean value indicating whether or not an application can have one <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> per <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> when setting an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> for the new <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a>.</dd><dt>visibility</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_AttributeDefinitionVisibilities">Citrix.SDK.AppDNA.AttributeDefinitionVisibilities</a><br />A combination of <a href="T_Citrix_SDK_AppDNA_AttributeDefinitionVisibilities">AttributeDefinitionVisibilities</a> that specifies where the <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> values will be displayed.</dd><dt>order</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The display order of the new <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a>.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a><br />The created <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a>.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinitionService">ApplicationAttributeDefinitionService Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />