# Analysis.GetReport Method 
 

Returns an instance of the <a href="T_Citrix_SDK_AppDNA_Report">Report</a> class that contains the results of the analysis. If more than one <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> was specified in the analysis, only the report for the first is returned. This must not be called unless <a href="P_Citrix_SDK_AppDNA_Analysis_IsFinished">IsFinished</a> is `true`.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Report GetReport()
```

###VB
```vbnet
Public Function GetReport As Report
```


#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Report">Report</a><br />An instance of the <a href="T_Citrix_SDK_AppDNA_Report">Report</a> class that contains the results of the analysis.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Analysis">Analysis Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Analysis_GetReport">GetReport Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />