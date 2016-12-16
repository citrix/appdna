# InstallCaptureSourceDetails.LoadSourceFile Property 
 

Gets or sets a value that determines whether the file that is loaded into AppDNA is the output of the Install Capture execution profile or the file at <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_SourceFilePath">SourceFilePath</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public bool LoadSourceFile { get; set; }
```

###VB
```vbnet
Public Property LoadSourceFile As Boolean
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>

## Remarks
This can be of benefit when the ExecutionProfile is run to generate a byproduct during the import, such as generating an application virtualization sequence, but you want AppDNA to import the original msi-file for the purpose of analysis. Defaults to true if  ends with .msi. Defaults to false otherwise.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br /><a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_SourceFilePath">InstallCaptureSourceDetails.SourceFilePath</a><br />