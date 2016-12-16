# ISolution.ApplicationSelectionScope Method 
 

Gets the applications collection which can be selected for solution report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Interfaces">Citrix.SDK.AppDNA.Interfaces</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
IEnumerable<Application> ApplicationSelectionScope(
	ReportOptions reportOptions
)
```

###VB
```vbnet
Function ApplicationSelectionScope ( 
	reportOptions As ReportOptions
) As IEnumerable(Of Application)
```


#### Parameters
&nbsp;<dl><dt>reportOptions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">Citrix.SDK.AppDNA.Reporting.ReportOptions</a><br />The report options which selection scope is returned for.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />Collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Interfaces_ISolution">ISolution Interface</a><br /><a href="N_Citrix_SDK_AppDNA_Interfaces">Citrix.SDK.AppDNA.Interfaces Namespace</a><br />