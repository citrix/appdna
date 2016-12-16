# OSImport.WaitForCompletion Method (TimeSpan)
 

Returns true if <a href="P_Citrix_SDK_AppDNA_OSImport_IsFinished">IsFinished</a> is `true` before *timeout* elapses.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public bool WaitForCompletion(
	TimeSpan timeout
)
```

###VB
```vbnet
Public Function WaitForCompletion ( 
	timeout As TimeSpan
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The maximum time to wait for <a href="P_Citrix_SDK_AppDNA_OSImport_IsFinished">IsFinished</a> to become `true`.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />True if <a href="P_Citrix_SDK_AppDNA_OSImport_IsFinished">IsFinished</a> becomes true before *timeout* elapses.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_OSImport">OSImport Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_OSImport_WaitForCompletion">WaitForCompletion Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />