# ApplicationService.Import Method (String, IEnumerable(String), ApplicationImportConfiguration, String)
 

Imports an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object directly from the source file.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Application Import(
	string filePath,
	IEnumerable<string> transforms,
	ApplicationImportConfiguration config,
	out string logFile
)
```

###VB
```vbnet
Public Function Import ( 
	filePath As String,
	transforms As IEnumerable(Of String),
	config As ApplicationImportConfiguration,
	<OutAttribute> ByRef logFile As String
) As Application
```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the file to import.</dd><dt>transforms</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />A collection of full paths to transform files to apply to the msi specified by fileName. The transforms are applied in the order they are enumerated.</dd><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">Citrix.SDK.AppDNA.ApplicationImportConfiguration</a><br />The configuration details to be used by this import.</dd><dt>logFile</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />On return, this specifies the full path to a log file that contains the details of the import. Useful for troubleshooting. Even if this function throws an exception, if logFile is non-null, then it may contain useful information for troubleshooting the failure.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Application">Application</a><br />The imported application.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_Import">Import Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />