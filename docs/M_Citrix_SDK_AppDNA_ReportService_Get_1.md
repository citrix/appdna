# ReportService.Get Method (ReportConfiguration, OSImage, OSImage)
 

Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report Get(
	ReportConfiguration config,
	OSImage image,
	OSImage preImage
)
```

###VB
```vbnet
Public Function Get ( 
	config As ReportConfiguration,
	image As OSImage,
	preImage As OSImage
) As Report
```


#### Parameters
&nbsp;<dl><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">Citrix.SDK.AppDNA.ReportConfiguration</a><br />The the <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> for which to retrieve the report data.</dd><dt>image</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_OSImage">Citrix.SDK.AppDNA.OSImage</a><br />The <a href="T_Citrix_SDK_AppDNA_OSImage">OSImage</a> object representing the target image, for algorithms that compare results between two OS images.</dd><dt>preImage</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_OSImage">Citrix.SDK.AppDNA.OSImage</a><br />The <a href="T_Citrix_SDK_AppDNA_OSImage">OSImage</a> object representing the source image, for algorithms that compare results between two OS images.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />A <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportService">ReportService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />