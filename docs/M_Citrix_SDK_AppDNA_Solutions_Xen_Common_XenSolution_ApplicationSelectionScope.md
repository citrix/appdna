# XenSolution.ApplicationSelectionScope Method 
 

Gets the applications collection which can be selected for solution report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public IEnumerable<Application> ApplicationSelectionScope(
	ReportOptions reportOptions
)
```

###VB
```vbnet
Public Function ApplicationSelectionScope ( 
	reportOptions As ReportOptions
) As IEnumerable(Of Application)
```


#### Parameters
&nbsp;<dl><dt>reportOptions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report options which selection scope is returned for.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />Collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects

#### Implements
<a href="M_Citrix_SDK_AppDNA_Interfaces_ISolution_ApplicationSelectionScope">ISolution.ApplicationSelectionScope(ReportOptions)</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />