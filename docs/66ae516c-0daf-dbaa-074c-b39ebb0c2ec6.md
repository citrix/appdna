# ReportConfigurationService.GetAsync Method (ReportingConfigurationFilter, Object, Int32, Int32, ReportingConfigurationFilter)
 

Returns a collection of <a href="65f3ee4f-5129-5083-b4da-0f1e23fc3784">ReportConfiguration</a> objects that respects filtering and paging requirements.

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public Task<Collection<ReportConfiguration>> GetAsync(
	ReportingConfigurationFilter filterBy,
	Object filterValue,
	int count,
	int offset,
	ReportingConfigurationFilter orderBy
)
```

**VB**
```vbnet
Public Function GetAsync ( 
	filterBy As ReportingConfigurationFilter,
	filterValue As Object,
	count As Integer,
	offset As Integer,
	orderBy As ReportingConfigurationFilter
) As Task(Of Collection(Of ReportConfiguration))
```


#### Parameters
&nbsp;<dl><dt>filterBy</dt><dd>Type: <a href="45536631-95e5-0f23-16f3-272918617af8">Citrix.SDK.AppDNA.ReportingConfigurationFilter</a><br />Specifies the field that *filterValue* is compared against to filter the results.</dd><dt>filterValue</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />Specifies a value that is used to filter the results if *filterBy*is not NONE.</dd><dt>count</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The maximum number of <a href="65f3ee4f-5129-5083-b4da-0f1e23fc3784">ReportConfiguration</a> objects to return. Use -1 to retrieve all report configurations that match the other parameters.</dd><dt>offset</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />This represents the number of results to skip.</dd><dt>orderBy</dt><dd>Type: <a href="45536631-95e5-0f23-16f3-272918617af8">Citrix.SDK.AppDNA.ReportingConfigurationFilter</a><br />This specifies a property of the ReportConfiguration objects by which to order the result set.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(<a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="65f3ee4f-5129-5083-b4da-0f1e23fc3784">ReportConfiguration</a>))<br />Returns a collection of the requested <a href="65f3ee4f-5129-5083-b4da-0f1e23fc3784">ReportConfiguration</a> objects.

## Remarks
The results are filtered, then ordered according to *orderBy*, then *offset* is applied, then *count* is applied, before returning the results.

## See Also


#### Reference
<a href="1d24c8d7-633d-8fcb-0e0a-e524dc26c7b3">ReportConfigurationService Class</a><br /><a href="fe542d08-0cf5-9ec4-ac5d-c7ef6456fac8">GetAsync Overload</a><br /><a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />