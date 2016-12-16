# BuildAssessmentSolution.ExportReport Method (String, ReportOptions, ReportExportFormat, TimeSpan, OSImage)
 

Exports the report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.BuildAssessment (in Citrix.SDK.AppDNA.Solutions.BuildAssessment.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void ExportReport(
	string fileName,
	ReportOptions reportOptions,
	ReportExportFormat format,
	TimeSpan timeout,
	OSImage targetBuild
)
```

###VB
```vbnet
Public Sub ExportReport ( 
	fileName As String,
	reportOptions As ReportOptions,
	format As ReportExportFormat,
	timeout As TimeSpan,
	targetBuild As OSImage
)
```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Name of the file.</dd><dt>reportOptions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report data from <a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Reports">Reports</a> collection.</dd><dt>format</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportExportFormat">Citrix.SDK.AppDNA.ReportExportFormat</a><br />The format.</dd><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The timeout.</dd><dt>targetBuild</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_OSImage">Citrix.SDK.AppDNA.OSImage</a><br />The target build.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution">BuildAssessmentSolution Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ExportReport">ExportReport Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment Namespace</a><br />