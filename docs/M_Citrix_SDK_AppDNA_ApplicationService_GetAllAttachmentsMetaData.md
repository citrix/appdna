# ApplicationService.GetAllAttachmentsMetaData Method (Application, Boolean)
 

Returns a collection of ApplicationAttachment objects for a given application.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public List<ApplicationAttachment> GetAllAttachmentsMetaData(
	Application application,
	bool forceRefresh = false
)
```

###VB
```vbnet
Public Function GetAllAttachmentsMetaData ( 
	application As Application,
	Optional forceRefresh As Boolean = false
) As List(Of ApplicationAttachment)
```


#### Parameters
&nbsp;<dl><dt>application</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Application">Citrix.SDK.AppDNA.Application</a><br /></dd><dt>forceRefresh (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br /></dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">List</a>(<a href="T_Citrix_SDK_AppDNA_ApplicationAttachment">ApplicationAttachment</a>)<br />Returns the requested <a href="T_Citrix_SDK_AppDNA_ApplicationAttachment">ApplicationAttachment</a> objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_GetAllAttachmentsMetaData">GetAllAttachmentsMetaData Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />