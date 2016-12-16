# ApplicationService.ImportWeb Method (IEnumerable(ImportSourceDetails), String)
 

**Note: This API is now obsolete.**

Imports multiple web <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from their previously captured msi files.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("This method is obsolete. Use another ImportWeb method that consumes web import source details and configuration.")]
public Import ImportWeb(
	IEnumerable<ImportSourceDetails> importDetails,
	string outputFolder
)
```

###VB
```vbnet
<ObsoleteAttribute("This method is obsolete. Use another ImportWeb method that consumes web import source details and configuration.")>
Public Function ImportWeb ( 
	importDetails As IEnumerable(Of ImportSourceDetails),
	outputFolder As String
) As Import
```


#### Parameters
&nbsp;<dl><dt>importDetails</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> objects which detail the source media to import. Each <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> object can be used with the returned Importer object as a key to get specific information about that file's import.</dd><dt>outputFolder</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the folder into which the output of the import process is to be placed.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Import">Import</a><br />An Import object that can be used to track the state of the import.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_ImportWeb">ImportWeb Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />