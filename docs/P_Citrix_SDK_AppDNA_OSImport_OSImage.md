# OSImport.OSImage Property 
 

Returns the OSImage object resulting from the import.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public OSImage OSImage { get; }
```

###VB
```vbnet
Public ReadOnly Property OSImage As OSImage
	Get
```


#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_OSImage">OSImage</a><br />The specified OSImage. Throws an exception if the application import failed or was canceled. Use <a href="P_Citrix_SDK_AppDNA_OSImport_LogFilePath">LogFilePath</a> to view the details of the failure.

## Remarks
This property cannot be called until <a href="P_Citrix_SDK_AppDNA_OSImport_IsFinished">IsFinished</a> is `true`.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_OSImport">OSImport Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />