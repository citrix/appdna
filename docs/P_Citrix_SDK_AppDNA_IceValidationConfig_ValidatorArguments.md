# IceValidationConfig.ValidatorArguments Property 
 

Specifies the arguments to be passed to the <a href="P_Citrix_SDK_AppDNA_IceValidationConfig_ValidatorExe">ValidatorExe</a> on its command line.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public string ValidatorArguments { get; set; }
```

###VB
```vbnet
Public Property ValidatorArguments As String
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>

## Remarks
The arguments can contain the replaceables "{cub}" which will be replaced by the value of <a href="P_Citrix_SDK_AppDNA_IceValidationConfig_Cub">Cub</a>. "{output}" which will be replaced by the full path to a temporary file which is loaded as the ICE validation output and "{MSI}" which will be replaced by the msi-file that is being imported.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_IceValidationConfig">IceValidationConfig Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />