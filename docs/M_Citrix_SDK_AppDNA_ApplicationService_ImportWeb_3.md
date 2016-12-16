# ApplicationService.ImportWeb Method (String, ApplicationImportConfiguration, String)
 

Imports a previously captured web <a href="T_Citrix_SDK_AppDNA_Application">Application</a> directly from the capture msi.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Application ImportWeb(
	string filePath,
	ApplicationImportConfiguration config,
	out string logFile
)
```

###VB
```vbnet
Public Function ImportWeb ( 
	filePath As String,
	config As ApplicationImportConfiguration,
	<OutAttribute> ByRef logFile As String
) As Application
```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the msi file to import.</dd><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">Citrix.SDK.AppDNA.ApplicationImportConfiguration</a><br />The configuration details to be used by this import.</dd><dt>logFile</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />On return, this specifies the full path to a log file that contains the details of the import. Useful for troubleshooting. Even if this function throws an exception, if logFile is non-null, then it may contain useful information for troubleshooting the failure.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Application">Application</a><br />The imported application.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_ImportWeb">ImportWeb Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />