# Import.GetLogFilePath Method 
 

Returns the full path to the text log file that holds the log of the import defined by *details*.

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public string GetLogFilePath(
	IImportDetails details
)
```

**VB**
```vbnet
Public Function GetLogFilePath ( 
	details As IImportDetails
) As String
```


#### Parameters
&nbsp;<dl><dt>details</dt><dd>Type: <a href="6f580b77-1cee-79a2-e04d-d77b7730fa50">Citrix.SDK.AppDNA.IImportDetails</a><br />This must be one of the objects that was passed to the initiating Application.Import function and is used as a key to find the respective log file path for that import.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The specified log file path.

## See Also


#### Reference
<a href="45bef3fc-5396-1e03-f577-fb7fe3ec23f9">Import Class</a><br /><a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />