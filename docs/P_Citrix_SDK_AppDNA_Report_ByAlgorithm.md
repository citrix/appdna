# Report.ByAlgorithm Property 
 

Returns a collection of the <a href="T_Citrix_SDK_AppDNA_Report">Report</a> result objects for each algorithm that can be indexed by <a href="T_Citrix_SDK_AppDNA_Algorithm">Algorithm</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ReportedAlgorithmCollection ByAlgorithm { get; }
```

###VB
```vbnet
Public ReadOnly Property ByAlgorithm As ReportedAlgorithmCollection
	Get
```


#### Property Value
Type: <a href="T_Citrix_SDK_AppDNA_ReportedAlgorithmCollection">ReportedAlgorithmCollection</a>

## Remarks
Accessing the report data by application provides access to application RAGs which are summaries over all algorithms. Accessing by algorithm does not provide this information.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Report">Report Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />