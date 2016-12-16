# Report.Export Method 
 

Exports a particular view of the report to a file.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void Export(
	string fileName,
	ReportType type,
	ReportExportFormat format,
	TimeSpan timeout
)
```

###VB
```vbnet
Public Sub Export ( 
	fileName As String,
	type As ReportType,
	format As ReportExportFormat,
	timeout As TimeSpan
)
```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the output file.</dd><dt>type</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportType">Citrix.SDK.AppDNA.ReportType</a><br />The type of view of the report data to export. Warning! Only <a href="T_Citrix_SDK_AppDNA_ReportType">ApplicationActions</a>, <a href="T_Citrix_SDK_AppDNA_ReportType">ApplicationIssues</a>,<a href="T_Citrix_SDK_AppDNA_ReportType">ActionView</a>,<a href="T_Citrix_SDK_AppDNA_ReportType">IssueView</a>,<a href="T_Citrix_SDK_AppDNA_ReportType">EstateView</a>,are supported.</dd><dt>format</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportExportFormat">Citrix.SDK.AppDNA.ReportExportFormat</a><br />The format in which to export the report.</dd><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />A timeout for which to wait for the export to complete. Throws an exception if the timeout expires.</dd></dl>

## Remarks
Not all values of *type* are supported

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Report">Report Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />