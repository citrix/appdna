# InstallCaptureSourceDetails.SourceFilePath Property 
 

Gets or sets a value that is full path to the installation media.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public string SourceFilePath { get; set; }
```

###VB
```vbnet
Public Property SourceFilePath As String
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>

#### Implements
<a href="P_Citrix_SDK_AppDNA_IImportDetails_SourceFilePath">IImportDetails.SourceFilePath</a><br />

## Remarks
This value can be used within the AppDNA client to help distinguish between applications with the same product details.\ It is also used to determine the default value for <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_LoadSourceFile">LoadSourceFile</a>.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />