# AnalysisData Constructor (IEnumerable(IAnalysisModuleTargetInfo), Boolean, Boolean)
 

Initializes a new instance of the <a href="T_Citrix_SDK_AppDNA_Reporting_AnalysisData">AnalysisData</a> class.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Reporting">Citrix.SDK.AppDNA.Reporting</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public AnalysisData(
	IEnumerable<IAnalysisModuleTargetInfo> data,
	bool analyzed,
	bool forceReanalysis
)
```

###VB
```vbnet
Public Sub New ( 
	data As IEnumerable(Of IAnalysisModuleTargetInfo),
	analyzed As Boolean,
	forceReanalysis As Boolean
)
```


#### Parameters
&nbsp;<dl><dt>data</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Interfaces_IAnalysisModuleTargetInfo">IAnalysisModuleTargetInfo</a>)<br />The modules and application that need to be analyzed against each of them.</dd><dt>analyzed</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />If set to `true`<a href="P_Citrix_SDK_AppDNA_Reporting_AnalysisData_Data">Data</a> is analyzed.</dd><dt>forceReanalysis</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />If set to `true`, even analyzed modules are reanalyzed</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Reporting_AnalysisData">AnalysisData Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Reporting_AnalysisData__ctor">AnalysisData Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Reporting">Citrix.SDK.AppDNA.Reporting Namespace</a><br />