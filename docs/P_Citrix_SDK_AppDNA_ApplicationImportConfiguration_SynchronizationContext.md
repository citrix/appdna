# ApplicationImportConfiguration.SynchronizationContext Property 
 

A SynchronizationContext used to control the thread on which notifications are raised.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public SynchronizationContext SynchronizationContext { get; set; }
```

###VB
```vbnet
Public Property SynchronizationContext As SynchronizationContext
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/wx31754f" target="_blank">SynchronizationContext</a>

## Remarks
Importing utilizes multiple background worker threads. The Importer object and its ProcessingState objects raise notification events which the user can subscribe to. In order to allow the user to control which thread the user event handling code should be called on, this function accepts a SynchronizationContext. By default SynchronizationContext.Current at the time this class is constructed will be used. Note that SynchronizationContext.Current may still be null, in which case there is no guarantee over which thread the event handlers will be run on. If this value is not null, then the caller must ensure that the specified synchronization context is processing events in order to receive events. See http://msdn.microsoft.com/en-us/library/system.threading.synchronizationcontext.aspx for more information.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />