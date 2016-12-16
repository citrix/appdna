# ImportSourceDetails Constructor (String, IEnumerable(String))
 

Constructor

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ImportSourceDetails(
	string sourceFilePath,
	IEnumerable<string> transforms
)
```

###VB
```vbnet
Public Sub New ( 
	sourceFilePath As String,
	transforms As IEnumerable(Of String)
)
```


#### Parameters
&nbsp;<dl><dt>sourceFilePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the installation media.<a href="P_Citrix_SDK_AppDNA_ImportSourceDetails_SourceFilePath">SourceFilePath</a></dd><dt>transforms</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />A collection of full paths to transforms that are to be applied in order to the msi-file specified by *sourceFilePath* before import.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ImportSourceDetails__ctor">ImportSourceDetails Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />