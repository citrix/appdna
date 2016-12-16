# ReportConfigurationService.GetAsync Method (ReportingConfigurationFilter, Object, Int32, Int32)
 

Returns a collection of ReportConfiguration objects that respects filtering and paging requirements.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Task<Collection<ReportConfiguration>> GetAsync(
	ReportingConfigurationFilter filterBy,
	Object filterValue,
	int count,
	int offset
)
```

###VB
```vbnet
Public Function GetAsync ( 
	filterBy As ReportingConfigurationFilter,
	filterValue As Object,
	count As Integer,
	offset As Integer
) As Task(Of Collection(Of ReportConfiguration))
```


#### Parameters
&nbsp;<dl><dt>filterBy</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportingConfigurationFilter">Citrix.SDK.AppDNA.ReportingConfigurationFilter</a><br />Specifies the field that *filterValue* is compared against to filter the results.</dd><dt>filterValue</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />Specifies a value that is used to filter the results if *filterBy*is not NONE.</dd><dt>count</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The maximum number of ReportConfiguration objects to return. Use -1 to retrieve all report configurations that match the other parameters.</dd><dt>offset</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />This represents the number of results to skip.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(<a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>))<br />Returns a collection of the requested ReportConfiguration objects.

## Remarks
The results are filtered, then *offset* is applied, then *count* is applied, before returning the results.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportConfigurationService">ReportConfigurationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportConfigurationService_GetAsync">GetAsync Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />