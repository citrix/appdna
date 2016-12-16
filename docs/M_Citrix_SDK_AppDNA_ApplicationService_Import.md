# ApplicationService.Import Method (IEnumerable(ImportSourceDetails), ApplicationImportConfiguration)
 

Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from source files.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Import Import(
	IEnumerable<ImportSourceDetails> importDetails,
	ApplicationImportConfiguration config
)
```

###VB
```vbnet
Public Function Import ( 
	importDetails As IEnumerable(Of ImportSourceDetails),
	config As ApplicationImportConfiguration
) As Import
```


#### Parameters
&nbsp;<dl><dt>importDetails</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> objects which detail the source media to import. Each <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that file's import.</dd><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">Citrix.SDK.AppDNA.ApplicationImportConfiguration</a><br />The configuration details to be used by this import.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Import">Import</a><br />An Import object that can be used to track the state of the import.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_Import">Import Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />