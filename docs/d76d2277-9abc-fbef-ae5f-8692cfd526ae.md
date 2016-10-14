# Application.SuggestedRequiredApplications Property 
 

Returns a list of applications that the current application may require.

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public Collection<Application> SuggestedRequiredApplications { get; }
```

**VB**
```vbnet
Public ReadOnly Property SuggestedRequiredApplications As Collection(Of Application)
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="1779bfff-4b29-0f26-8a09-10acdd530bbc">Application</a>)

## Remarks
The returned collection is not updated when applications are deleted or imported.

## See Also


#### Reference
<a href="1779bfff-4b29-0f26-8a09-10acdd530bbc">Application Class</a><br /><a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />