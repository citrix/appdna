# Server.ClearCache Method 
 

This function is used to clear the tracking cache in the SDK.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static void ClearCache()
```

###VB
```vbnet
Public Shared Sub ClearCache
```


## Remarks
Many objects returned by SDK functions are tracked, so that when they are modified using the SDK collections of objects are updated to reflect the changes and notifications are raised to the SDK client code. Calling this function clears the tracking cache. This will have the effect of causing any new data that comes from the AppDNA server to be separated from any previously retrieved data. Modifying the newly retrieved objects will not cause any previously retrieved objects to be kept in a consistent state. However if data has been changed on the server by some other AppDNA client, then calling ClearCache will cause the SDK to retrieve that fresh data as it needs to.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Server">Server Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />