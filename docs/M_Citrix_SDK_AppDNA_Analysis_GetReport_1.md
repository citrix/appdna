# Analysis.GetReport Method (ReportConfiguration)
 

Returns an instance of the <a href="T_Citrix_SDK_AppDNA_Report">Report</a> class that contains the results of the analysis. This must not be called unless <a href="P_Citrix_SDK_AppDNA_Analysis_IsFinished">IsFinished</a> is `true`.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report GetReport(
	ReportConfiguration config
)
```

###VB
```vbnet
Public Function GetReport ( 
	config As ReportConfiguration
) As Report
```


#### Parameters
&nbsp;<dl><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">Citrix.SDK.AppDNA.ReportConfiguration</a><br />The <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> for which to return the report. This must be the same object as was passed to the Analyze method that returned this <a href="T_Citrix_SDK_AppDNA_Analysis">Analysis</a> object.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />An instance of the <a href="T_Citrix_SDK_AppDNA_Report">Report</a> class that contains the results of the analysis.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Analysis">Analysis Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Analysis_GetReport">GetReport Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />