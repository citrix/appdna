# Application.GetReport Method (ReportConfiguration)
 

Retrieves the specified report information.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report GetReport(
	ReportConfiguration reportConfiguration
)
```

###VB
```vbnet
Public Function GetReport ( 
	reportConfiguration As ReportConfiguration
) As Report
```


#### Parameters
&nbsp;<dl><dt>reportConfiguration</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">Citrix.SDK.AppDNA.ReportConfiguration</a><br />The desired <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />A report for this application against the specified report configuration.

## Remarks
Any algorithms that cross reference other applications, such as interoperability algorithms, will effectively be disabled, since the report only utilizes this application. For interoperability algorithms, use 
```
ServerToken.Report.Get
```


## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Application_GetReport">GetReport Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />