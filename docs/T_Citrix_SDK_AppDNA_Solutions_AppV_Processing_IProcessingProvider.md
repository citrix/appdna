# IProcessingProvider Interface
 

Exposes App-V solution processing step functionality

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Processing">Citrix.SDK.AppDNA.Solutions.AppV.Processing</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public interface IProcessingProvider : IDisposable
```

###VB
```vbnet
Public Interface IProcessingProvider
	Inherits IDisposable
```

The IProcessingProvider type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_IProcessingProvider_Identifier">Identifier</a></td><td>
Gets the identifier.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_IProcessingProvider_IsRunning">IsRunning</a></td><td>
Checks whether a processing provider is busy or not at the moment</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_Processing_IProcessingProvider_Name">Name</a></td><td>
Gets or sets the name.</td></tr></table>&nbsp;
<a href="#iprocessingprovider-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/es4s3w1d" target="_blank">Dispose</a></td><td>
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/aax125c9" target="_blank">IDisposable</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_IProcessingProvider_Queue">Queue</a></td><td>
Adds applications to be processed by the current provider.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_Processing_IProcessingProvider_Start">Start</a></td><td>
Starts the underlying processing provider to process applications.</td></tr></table>&nbsp;
<a href="#iprocessingprovider-interface">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_Processing_IProcessingProvider_ApplicationProcessed">ApplicationProcessed</a></td><td>
Event occuring when an application is processed by the underlying provider.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_Processing_IProcessingProvider_PostedMessage">PostedMessage</a></td><td>
Occurs when provider posted message.</td></tr></table>&nbsp;
<a href="#iprocessingprovider-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Processing">Citrix.SDK.AppDNA.Solutions.AppV.Processing Namespace</a><br />