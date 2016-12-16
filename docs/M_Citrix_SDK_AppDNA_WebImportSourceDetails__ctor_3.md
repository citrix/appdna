# WebImportSourceDetails Constructor (Uri, String, String, String)
 

Constructor

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public WebImportSourceDetails(
	Uri url,
	string sourceFolder,
	string sourceFilePath,
	string name
)
```

###VB
```vbnet
Public Sub New ( 
	url As Uri,
	sourceFolder As String,
	sourceFilePath As String,
	name As String
)
```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/txt7706a" target="_blank">System.Uri</a><br />A url of a web application to be imported.</dd><dt>sourceFolder</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />A source folder of a web applications to be imported, exposed via the property.</dd><dt>sourceFilePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />A source file path to the MSI media.</dd><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />An application name.</dd></dl>

## Remarks
At least one source of a web application (URL, source folder or MSI media) must be provided.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_WebImportSourceDetails">WebImportSourceDetails Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_WebImportSourceDetails__ctor">WebImportSourceDetails Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />