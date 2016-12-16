# XenAnalysisDataProvider.AlgorithmGroupInfos Method 
 

Constructs <a href="T_Citrix_SDK_AppDNA_Reporting_AlgorithmGroupInfo">AlgorithmGroupInfo</a> based in the *reportingRequirements* and *algorithms*

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
protected static IEnumerable<AlgorithmGroupInfo> AlgorithmGroupInfos(
	ReportConfiguration reportingRequirements,
	List<Algorithm> algorithms
)
```

###VB
```vbnet
Protected Shared Function AlgorithmGroupInfos ( 
	reportingRequirements As ReportConfiguration,
	algorithms As List(Of Algorithm)
) As IEnumerable(Of AlgorithmGroupInfo)
```


#### Parameters
&nbsp;<dl><dt>reportingRequirements</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">Citrix.SDK.AppDNA.ReportConfiguration</a><br />The reporting requirements.</dd><dt>algorithms</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">System.Collections.Generic.List</a>(<a href="T_Citrix_SDK_AppDNA_Algorithm">Algorithm</a>)<br />The algorithms.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Reporting_AlgorithmGroupInfo">AlgorithmGroupInfo</a>)<br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider">XenAnalysisDataProvider Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />