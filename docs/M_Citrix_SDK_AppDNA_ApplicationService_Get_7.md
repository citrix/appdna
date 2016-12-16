# ApplicationService.Get Method (String)
 

Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Collection<Application> Get(
	string filterQuery
)
```

###VB
```vbnet
Public Function Get ( 
	filterQuery As String
) As Collection(Of Application)
```


#### Parameters
&nbsp;<dl><dt>filterQuery</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The filter query string. See remarks for more details.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />Returns a collection of the requested <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.

## Remarks

The format for the query string is similar to the SQL WHERE clause. Allowed operators are: IS <NOT> NULL, = (Equals), > (Greater than), < (Less than), >= (Greater than or equal), <= (Less than or equal), <> (Not equal), LIKE (contains), AND, OR, and () for precedence String literals are delimited by apostrophes. Use a double apostrophe to represent an apostrophe in the string literal. Arbitrary field names are allowed. Field names will be assumed to represent a matching <a href="T_Citrix_SDK_AppDNA_Application">Application</a> property. If there is no matching property they will be assumed to an ApplicationAttributeDefinition identifier. To filter with an ApplicationAttributeDefinition identifier when it also matches a property name, prefix it with "Attribute.". e.g. 
```
Get("Attribute.Manufacturer='xxx'")
```
; If there is no ApplicationAttributeDefinition with the specified identifier, then an exception will be thrown. When comparing a property that holds a value that is from an enumeration, specify the enumeration value name as a string. e.g. 
```
Get("SourceCategory='WebApplication'")
```
. When an Application has not had a value set for a given ApplicationAttributeDefinition, it will behave as if it has NULL for that attribute. Where an ApplicationAttributeDefinition identifier contains spaces, surround it with square brackets. e.g. 
```
Get("[Application tester]='WebApplication'")
```
 ApplicationAttributeDefinitions for which IsReportDependent is true can be queried by using the ApplicationAttributeDefinition.Identifier value and the ReportConfiguration identifier separated by a period. e.g. 
```
Get("analyzed_date.Win7Module IS NOT NULL")
```
 Leaving off the ReportConfiguration identifier matches values for any ReportConfiguration for that ApplicationAttributeDefinition. e.g. 
```
Get("analyzed_date IS NOT NULL")
```
 When using datetime string literals, it is recommended to use the ISO 8601 format. YYYY-MM-DDThh:mm:ss[.mmm] or YYYYMMDD[ hh:mm:ss[.mmm]] or . e.g. 
```
Get("analyzed_date.Win7Module > 20140123")
```



## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_Get">Get Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />