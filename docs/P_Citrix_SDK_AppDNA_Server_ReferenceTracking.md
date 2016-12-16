# Server.ReferenceTracking Property 
 

Gets or sets an SDK wide option to enable reference tracking.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static bool ReferenceTracking { get; set; }
```

###VB
```vbnet
Public Shared Property ReferenceTracking As Boolean
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>

## Remarks
By default, the SDK provides a self-consistent view of the AppDNA data, by tracking in-memory objects that represents the same AppDNA object (application, group, etc). A change to one object, such as changing its name, will be immediately reflected in all other in-memory objects that represent the same AppDNA object. e.g. calling app.AddToGroup( "group" ) will be immediately reflected in the Applications property of all in-memory objects that represent "group". Notifications of all in-memory object changes are provided through INotifyPropertyChanged and INotifyCollectionChanged implemented by the updated objects. To isolate in-memory objects that represent the same AppDNA object, set ReferenceTracking to false. This isolation will only apply to objects retrieved after setting the property to false. This can sometimes be useful for increased performance or where cross-threading issues might arise.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Server">Server Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />