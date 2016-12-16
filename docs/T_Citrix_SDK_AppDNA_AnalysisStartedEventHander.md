# AnalysisStartedEventHander Delegate
 

This delegate defines the `AnalysisStarted` event exposed by the <a href="T_Citrix_SDK_AppDNA_Import">Import</a> class.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public delegate void AnalysisStartedEventHander(
	Import sender,
	Analysis analysis
)
```

###VB
```vbnet
Public Delegate Sub AnalysisStartedEventHander ( 
	sender As Import,
	analysis As Analysis
)
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Import">Citrix.SDK.AppDNA.Import</a><br />The Import object that raised the event.</dd><dt>analysis</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Analysis">Citrix.SDK.AppDNA.Analysis</a><br />The Analysis object that represents the analysis triggered by this import</dd></dl>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />