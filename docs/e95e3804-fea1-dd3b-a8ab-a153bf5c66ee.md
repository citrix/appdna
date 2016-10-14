# IProcessingProvider Interface
 

Exposes App-V solution processing step functionality

**Namespace:**&nbsp;<a href="e89d7bb5-69e7-7aff-5732-d06b09ac746d">Citrix.SDK.AppDNA.Solutions.AppV.Processing</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public interface IProcessingProvider : IDisposable
```

**VB**
```vbnet
Public Interface IProcessingProvider
	Inherits IDisposable
```

The IProcessingProvider type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="64be474d-0c51-0505-28c7-7bca7dd98b00">Identifier</a></td><td>
Gets the identifier.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="b3c78dff-f3d5-366e-a593-b75a8395491a">IsRunning</a></td><td>
Checks whether a processing provider is busy or not at the moment</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="53de97f4-bc75-d54c-efac-ba44b7734e6f">Name</a></td><td>
Gets or sets the name.</td></tr></table>&nbsp;
<a href="#iprocessingprovider-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/es4s3w1d" target="_blank">Dispose</a></td><td>
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/aax125c9" target="_blank">IDisposable</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="f4a0a928-c7bd-efe3-bd9f-c1d903c28e41">Queue</a></td><td>
Adds applications to be processed by the current provider.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="97bb013b-93d5-6503-a9b4-4f8d47ac5b3f">Start</a></td><td>
Starts the underlying processing provider to process applications.</td></tr></table>&nbsp;
<a href="#iprocessingprovider-interface">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="b8ead30b-056d-c497-a1e9-03876fdfd66f">ApplicationProcessed</a></td><td>
Event occuring when an application is processed by the underlying provider.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="07e974c8-224c-c4d7-45ea-fc4940c28963">PostedMessage</a></td><td>
Occurs when provider posted message.</td></tr></table>&nbsp;
<a href="#iprocessingprovider-interface">Back to Top</a>

## See Also


#### Reference
<a href="e89d7bb5-69e7-7aff-5732-d06b09ac746d">Citrix.SDK.AppDNA.Solutions.AppV.Processing Namespace</a><br />