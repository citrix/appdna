# OSImportStateChangedEventHandler Delegate
 

This delegate defines the `ImportStateChanged` event exposed by the <a href="T_Citrix_SDK_AppDNA_OSImport">OSImport</a> class.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public delegate void OSImportStateChangedEventHandler(
	OSImport sender,
	ProcessingState processingState
)
```

###VB
```vbnet
Public Delegate Sub OSImportStateChangedEventHandler ( 
	sender As OSImport,
	processingState As ProcessingState
)
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_OSImport">Citrix.SDK.AppDNA.OSImport</a><br />The OSImport object that raised the event.</dd><dt>processingState</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ProcessingState">Citrix.SDK.AppDNA.ProcessingState</a><br />The <a href="T_Citrix_SDK_AppDNA_ProcessingState">ProcessingState</a> object that contains the state of the import.</dd></dl>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />