# ReportService.ExportApplicationRemediationActions Method (String, ReportExportFormat, Application, IEnumerable(ReportConfiguration), OSImage, OSImage, TimeSpan)
 

Exports the Application Remediation Actions report for the specified application, optionally combining the results from multiple report configurations.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void ExportApplicationRemediationActions(
	string fileName,
	ReportExportFormat format,
	Application application,
	IEnumerable<ReportConfiguration> reportConfigurations,
	OSImage postImage,
	OSImage preImage,
	TimeSpan timeout
)
```

###VB
```vbnet
Public Sub ExportApplicationRemediationActions ( 
	fileName As String,
	format As ReportExportFormat,
	application As Application,
	reportConfigurations As IEnumerable(Of ReportConfiguration),
	postImage As OSImage,
	preImage As OSImage,
	timeout As TimeSpan
)
```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the output file.</dd><dt>format</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportExportFormat">Citrix.SDK.AppDNA.ReportExportFormat</a><br />The format in which to export the report.</dd><dt>application</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Application">Citrix.SDK.AppDNA.Application</a><br />The <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object for which to export the report data.</dd><dt>reportConfigurations</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>)<br />A set of one or more ReportConfiguration objects for which to retrieve data.</dd><dt>postImage</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_OSImage">Citrix.SDK.AppDNA.OSImage</a><br />The <a href="T_Citrix_SDK_AppDNA_OSImage">OSImage</a> object representing the target image, for algorithms that compare results between two OS images.</dd><dt>preImage</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_OSImage">Citrix.SDK.AppDNA.OSImage</a><br />The <a href="T_Citrix_SDK_AppDNA_OSImage">OSImage</a> object representing the source image, for algorithms that compare results between two OS images.</dd><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />A timeout for which to wait for the export to complete. Throws an exception if the timeout expires.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportService">ReportService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediationActions">ExportApplicationRemediationActions Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />