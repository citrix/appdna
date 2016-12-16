# ApplicationImportStateChangedEventHandler Delegate
 

This delegate defines the `ApplicationImportStateChanged` event exposed by the <a href="T_Citrix_SDK_AppDNA_Import">Import</a> class.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public delegate void ApplicationImportStateChangedEventHandler(
	Import sender,
	IImportDetails importDetails,
	ProcessingState processingState
)
```

###VB
```vbnet
Public Delegate Sub ApplicationImportStateChangedEventHandler ( 
	sender As Import,
	importDetails As IImportDetails,
	processingState As ProcessingState
)
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Import">Citrix.SDK.AppDNA.Import</a><br />The Import object that raised the event.</dd><dt>importDetails</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_IImportDetails">Citrix.SDK.AppDNA.IImportDetails</a><br />The IImportDetails that the ProcessingState is associated with.</dd><dt>processingState</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ProcessingState">Citrix.SDK.AppDNA.ProcessingState</a><br />The <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a> object that contains the state of the application server-side import defined by *importDetails*.</dd></dl>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />