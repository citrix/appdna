# Import.Cancel Method 
 

Requests that the specified import sources cancel both on the client and on the server side. Also, call this method to cancel work (e.g. Web Spider capturing) before the actual import has started.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void Cancel(
	IEnumerable<IImportDetails> sources
)
```

###VB
```vbnet
Public Sub Cancel ( 
	sources As IEnumerable(Of IImportDetails)
)
```


#### Parameters
&nbsp;<dl><dt>sources</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_IImportDetails">IImportDetails</a>)<br />Import sources as <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">IEnumerable(T)</a> to cancel that must belong to the current import.</dd></dl>

## Remarks
Import sources can be null if the current import should be cancelled before the actual import has started.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Import">Import Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />