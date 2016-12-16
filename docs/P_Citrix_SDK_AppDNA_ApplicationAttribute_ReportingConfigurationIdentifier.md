# ApplicationAttribute.ReportingConfigurationIdentifier Property 
 

Gets the identifier string of the <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public string ReportingConfigurationIdentifier { get; }
```

###VB
```vbnet
Public ReadOnly Property ReportingConfigurationIdentifier As String
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>

## Remarks
This will always be null if ApplicationAttributeDefinition.IsReportDependent is false.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />