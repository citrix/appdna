# Import.GetLogFilePath Method 
 

Returns the full path to the text log file that holds the log of the import defined by *details*.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public string GetLogFilePath(
	IImportDetails details
)
```

###VB
```vbnet
Public Function GetLogFilePath ( 
	details As IImportDetails
) As String
```


#### Parameters
&nbsp;<dl><dt>details</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_IImportDetails">Citrix.SDK.AppDNA.IImportDetails</a><br />This must be one of the objects that was passed to the initiating Application.Import function and is used as a key to find the respective log file path for that import.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The specified log file path.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Import">Import Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />