# Application.GetReport Method (String)
 

Retrieves the specified report information.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report GetReport(
	string reportConfigurationIdentifier
)
```

###VB
```vbnet
Public Function GetReport ( 
	reportConfigurationIdentifier As String
) As Report
```


#### Parameters
&nbsp;<dl><dt>reportConfigurationIdentifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The identifier of the required <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />A report for this application.

## Remarks
Any algorithms that cross reference other applications, such as interoperability algorithms, will effectively be disabled, since the report only utilizes this application. For interoperability algorithms, use 
```
ServerToken.Report.Get
```


## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Application_GetReport">GetReport Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />