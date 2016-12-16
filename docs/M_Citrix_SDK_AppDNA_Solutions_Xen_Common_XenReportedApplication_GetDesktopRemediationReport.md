# XenReportedApplication.GetDesktopRemediationReport Method 
 

Gets the remediation report for a desktop hosted deployment model.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public abstract MergedReportedApplication GetDesktopRemediationReport(
	ReportType reportType
)
```

###VB
```vbnet
Public MustOverride Function GetDesktopRemediationReport ( 
	reportType As ReportType
) As MergedReportedApplication
```


#### Parameters
&nbsp;<dl><dt>reportType</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportType">Citrix.SDK.AppDNA.ReportType</a><br />Type of the report.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_MergedReportedApplication">MergedReportedApplication</a><br />Collection of <a href="T_Citrix_SDK_AppDNA_ReportedApplication">ReportedApplication</a> and aggregates data from it

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication">XenReportedApplication Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />