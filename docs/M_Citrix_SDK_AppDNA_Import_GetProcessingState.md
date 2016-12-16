# Import.GetProcessingState Method 
 

Returns the <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a> object that represents the state of the import defined by *details*.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ProcessingState GetProcessingState(
	IImportDetails details
)
```

###VB
```vbnet
Public Function GetProcessingState ( 
	details As IImportDetails
) As ProcessingState
```


#### Parameters
&nbsp;<dl><dt>details</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_IImportDetails">Citrix.SDK.AppDNA.IImportDetails</a><br />This must be one of the objects that was passed to the initiating Application.Import function and is used as a key to find the respective <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a> for that import.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a><br />The specified <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a> object.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Import">Import Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />