# InstallCaptureSourceDetails.InstallCommand Property 
 

Gets or sets a value that is the command used by the execution profile to install the application.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public string InstallCommand { get; set; }
```

###VB
```vbnet
Public Property InstallCommand As String
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>

## Remarks
If this is not set, then the <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_SourceFilePath">SourceFilePath</a> is used as the install command. If <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_SourceFilePath">SourceFilePath</a> is an msi, then it is: msiexec /i "<SourceFilePath>"

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />