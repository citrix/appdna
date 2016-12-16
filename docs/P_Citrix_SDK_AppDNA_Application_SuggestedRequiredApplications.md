# Application.SuggestedRequiredApplications Property 
 

Returns a list of applications that the current application may require.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Collection<Application> SuggestedRequiredApplications { get; }
```

###VB
```vbnet
Public ReadOnly Property SuggestedRequiredApplications As Collection(Of Application)
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/ms132397" target="_blank">Collection</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)

## Remarks
The returned collection is not updated when applications are deleted or imported.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />