# ApplicationService.Import Method (IEnumerable(ImportSourceDetails), ApplicationImportConfiguration, Nullable(Int64), Boolean)
 

Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from source files.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Import Import(
	IEnumerable<ImportSourceDetails> importDetails,
	ApplicationImportConfiguration config,
	Nullable<long> applicationID,
	bool Override = false
)
```

###VB
```vbnet
Public Function Import ( 
	importDetails As IEnumerable(Of ImportSourceDetails),
	config As ApplicationImportConfiguration,
	applicationID As Nullable(Of Long),
	Optional Override As Boolean = false
) As Import
```


#### Parameters
&nbsp;<dl><dt>importDetails</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> objects which detail the source media to import. Each <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that file's import.</dd><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">Citrix.SDK.AppDNA.ApplicationImportConfiguration</a><br />The configuration details to be used by this import.</dd><dt>applicationID</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/b3h38hb0" target="_blank">System.Nullable</a>(<a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">Int64</a>)<br />The application identifier to import into - applicable for <a href="T_Citrix_SDK_AppDNA_SourceCategory">Stub</a>.</dd><dt>Override (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />if set to `true` [override].</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Import">Import</a><br />An Import object that can be used to track the state of the import.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="http://msdn2.microsoft.com/en-us/library/27426hcy" target="_blank">ArgumentNullException</a></td><td>config</td></tr></table>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_Import">Import Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />