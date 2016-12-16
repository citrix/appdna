# BuildAssessmentReport.Export Method (String, ReportExportFormat, TimeSpan, OSImage)
 

Exports the Build Assessment Summary report. In case *build* is specified - Comparison report is exported.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.BuildAssessment (in Citrix.SDK.AppDNA.Solutions.BuildAssessment.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void Export(
	string fileName,
	ReportExportFormat format,
	TimeSpan timeout,
	OSImage build
)
```

###VB
```vbnet
Public Sub Export ( 
	fileName As String,
	format As ReportExportFormat,
	timeout As TimeSpan,
	build As OSImage
)
```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Name of the file.</dd><dt>format</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportExportFormat">Citrix.SDK.AppDNA.ReportExportFormat</a><br />The format.</dd><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The timeout.</dd><dt>build</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_OSImage">Citrix.SDK.AppDNA.OSImage</a><br />The build.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentReport">BuildAssessmentReport Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentReport_Export">Export Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment Namespace</a><br />