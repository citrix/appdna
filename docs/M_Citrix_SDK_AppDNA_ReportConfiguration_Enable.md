# ReportConfiguration.Enable Method 
 

If set *state* to `true` enables the specified report configurations, algorithm groups and algorithms. Otherwise disables all above.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void Enable(
	IEnumerable<AlgorithmGroup> algorithmGroups,
	IEnumerable<Algorithm> algorithms,
	bool state
)
```

###VB
```vbnet
Public Sub Enable ( 
	algorithmGroups As IEnumerable(Of AlgorithmGroup),
	algorithms As IEnumerable(Of Algorithm),
	state As Boolean
)
```


#### Parameters
&nbsp;<dl><dt>algorithmGroups</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_AlgorithmGroup">AlgorithmGroup</a>)<br />The algorithm groups.</dd><dt>algorithms</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Algorithm">Algorithm</a>)<br />The algorithms.</dd><dt>state</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />if set to `true` [enable].</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />