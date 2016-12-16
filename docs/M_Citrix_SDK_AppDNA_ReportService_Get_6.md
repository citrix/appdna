# ReportService.Get Method (String)
 

Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all analyzed application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report Get(
	string reportConfigurationIdentifier
)
```

###VB
```vbnet
Public Function Get ( 
	reportConfigurationIdentifier As String
) As Report
```


#### Parameters
&nbsp;<dl><dt>reportConfigurationIdentifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The identifier of the <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> for which to retrieve the Report data.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />A <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all analyzed application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportService">ReportService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />