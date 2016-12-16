# ReportService.Get Method (String, IEnumerable(Application), IEnumerable(Algorithm))
 

Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results against a specific set of algorithms for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report Get(
	string reportConfigurationIdentifier,
	IEnumerable<Application> requestedApplications,
	IEnumerable<Algorithm> requestedAlgorithms
)
```

###VB
```vbnet
Public Function Get ( 
	reportConfigurationIdentifier As String,
	requestedApplications As IEnumerable(Of Application),
	requestedAlgorithms As IEnumerable(Of Algorithm)
) As Report
```


#### Parameters
&nbsp;<dl><dt>reportConfigurationIdentifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The identifier of the <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> for which to retrieve the Report data.</dd><dt>requestedApplications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The set of applications for which to retrieve report data.</dd><dt>requestedAlgorithms</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Algorithm">Algorithm</a>)<br />The set of algorithms for which to retrieve report data.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />A <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results against a specific set of algorithms for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportService">ReportService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />