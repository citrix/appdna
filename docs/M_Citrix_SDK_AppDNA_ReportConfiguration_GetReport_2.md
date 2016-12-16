# ReportConfiguration.GetReport Method (IEnumerable(Application), IEnumerable(Algorithm))
 

Retrieves the Report object of this <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> for the specified applications.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report GetReport(
	IEnumerable<Application> requestedApplications,
	IEnumerable<Algorithm> requestedAlgorithms
)
```

###VB
```vbnet
Public Function GetReport ( 
	requestedApplications As IEnumerable(Of Application),
	requestedAlgorithms As IEnumerable(Of Algorithm)
) As Report
```


#### Parameters
&nbsp;<dl><dt>requestedApplications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The applications for which to retrieve the report data. Can be Report.RequestAllApplications.</dd><dt>requestedAlgorithms</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Algorithm">Algorithm</a>)<br />The algorithms for which to retrieve the report data. Can be Report.RequestAllAlgorithms.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />The Report object containing the report data.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportConfiguration_GetReport">GetReport Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />