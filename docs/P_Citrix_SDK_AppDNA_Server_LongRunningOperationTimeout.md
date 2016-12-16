# Server.LongRunningOperationTimeout Property 
 

Some operations are run asynchronously on the server. However for simplicity these operations are exposed synchronously within the SDK. This property determines how long the synchronous operations within the SDK will wait for the server side operations to complete. The default value is 5 minutes.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public TimeSpan LongRunningOperationTimeout { get; set; }
```

###VB
```vbnet
Public Property LongRunningOperationTimeout As TimeSpan
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">TimeSpan</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Server">Server Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />