# Import.GetApplication Method (IImportDetails)
 

Returns the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object resulting from the import defined by *details*.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Application GetApplication(
	IImportDetails details
)
```

###VB
```vbnet
Public Function GetApplication ( 
	details As IImportDetails
) As Application
```


#### Parameters
&nbsp;<dl><dt>details</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_IImportDetails">Citrix.SDK.AppDNA.IImportDetails</a><br />This must be one of the objects that was passed to the initiating Application.Import function and is used as a key to find the respective imported application.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Application">Application</a><br />The specified <a href="T_Citrix_SDK_AppDNA_Application">Application</a>. Throws an exception if the application import failed or was cancelled. Use <a href="M_Citrix_SDK_AppDNA_Import_GetLogFilePath">GetLogFilePath(IImportDetails)</a> to view the details of the failure.

## Remarks
This function cannot be called until <a href="P_Citrix_SDK_AppDNA_Import_IsFinished">IsFinished</a> is `true`.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Import">Import Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Import_GetApplication">GetApplication Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />