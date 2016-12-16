# Application.SetAttribute Method (String, DateTime, String)
 

Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ApplicationAttribute SetAttribute(
	string attributeIdentifier,
	DateTime value,
	string reportConfigurationIdentifier
)
```

###VB
```vbnet
Public Function SetAttribute ( 
	attributeIdentifier As String,
	value As DateTime,
	reportConfigurationIdentifier As String
) As ApplicationAttribute
```


#### Parameters
&nbsp;<dl><dt>attributeIdentifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The <a href="T_Citrix_SDK_AppDNA_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> identifier.</dd><dt>value</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/03ybds8y" target="_blank">System.DateTime</a><br />The <a href="http://msdn2.microsoft.com/en-us/library/03ybds8y" target="_blank">DateTime</a> value to set.</dd><dt>reportConfigurationIdentifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> identifier.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a><br />The <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> object that represents the newly set attribute value.

## Remarks
The matching <a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_IsReportDependent">IsReportDependent</a> property must be set to `true`.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Application_SetAttribute">SetAttribute Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />