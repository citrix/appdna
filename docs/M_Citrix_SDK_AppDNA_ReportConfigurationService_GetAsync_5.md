# ReportConfigurationService.GetAsync Method (IEnumerable(String))
 

Returns a collection with all the ReportConfiguration objects.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Task<Collection<ReportConfiguration>> GetAsync(
	IEnumerable<string> identifiers
)
```

###VB
```vbnet
Public Function GetAsync ( 
	identifiers As IEnumerable(Of String)
) As Task(Of Collection(Of ReportConfiguration))
```


#### Parameters
&nbsp;<dl><dt>identifiers</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />The identifiers of the ReportConfigurations</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(<a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>))<br />Returns the collection of the ReportConfiguration objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportConfigurationService">ReportConfigurationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportConfigurationService_GetAsync">GetAsync Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />