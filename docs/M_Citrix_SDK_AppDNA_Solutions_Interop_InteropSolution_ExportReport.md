# InteropSolution.ExportReport Method (String, ReportType, ReportExportFormat, TimeSpan, Application)
 

**Note: This API is now obsolete.**

Exports the report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Interop">Citrix.SDK.AppDNA.Solutions.Interop</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Interop (in Citrix.SDK.AppDNA.Solutions.Interop.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Use another overload of this method")]
public void ExportReport(
	string fileName,
	ReportType reportType,
	ReportExportFormat format,
	TimeSpan timeout,
	Application application
)
```

###VB
```vbnet
<ObsoleteAttribute("Use another overload of this method")>
Public Sub ExportReport ( 
	fileName As String,
	reportType As ReportType,
	format As ReportExportFormat,
	timeout As TimeSpan,
	application As Application
)
```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Name of the report file.</dd><dt>reportType</dt><dd>Type: ReportType<br />Type of the report.</dd><dt>format</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportExportFormat">Citrix.SDK.AppDNA.ReportExportFormat</a><br />The format of the export.</dd><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The timeout.</dd><dt>application</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Application">Citrix.SDK.AppDNA.Application</a><br />The application - used if *reportType* is ReportType.ApplicationDetail or ReportType.ActionDetail</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Interop_InteropSolution">InteropSolution Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_Interop_InteropSolution_ExportReport">ExportReport Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Interop">Citrix.SDK.AppDNA.Solutions.Interop Namespace</a><br />