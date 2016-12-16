# ApplicationService.ImportWeb Method (IEnumerable(WebImportSourceDetails), WebApplicationImportConfiguration)
 

Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects as web applications.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Import ImportWeb(
	IEnumerable<WebImportSourceDetails> importDetails,
	WebApplicationImportConfiguration config = null
)
```

###VB
```vbnet
Public Function ImportWeb ( 
	importDetails As IEnumerable(Of WebImportSourceDetails),
	Optional config As WebApplicationImportConfiguration = Nothing
) As Import
```


#### Parameters
&nbsp;<dl><dt>importDetails</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_WebImportSourceDetails">WebImportSourceDetails</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> objects with web applications details to import. Each <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that 's import.</dd><dt>config (Optional)</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_WebApplicationImportConfiguration">Citrix.SDK.AppDNA.WebApplicationImportConfiguration</a><br />The configuration details (e.g. Spider configuration) to be used by this import. If not specified, the default configuration is used.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Import">Import</a><br />An Import object that can be used to track the state of the import.

## Remarks
If it is needed to import a web application directly from MSI, methods with <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> or with the MSI file path should be used instead.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_ImportWeb">ImportWeb Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />