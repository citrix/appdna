# ApplicationService.GetAllAttachmentsMetaData Method (Int32)
 

**Note: This API is now obsolete.**

Returns a collection of ApplicationAttachment objects for a given application.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Use strongly typed GetAllAttachmentsMetaData(Application application) method")]
public List<ApplicationAttachment> GetAllAttachmentsMetaData(
	int sticky_application_id
)
```

###VB
```vbnet
<ObsoleteAttribute("Use strongly typed GetAllAttachmentsMetaData(Application application) method")>
Public Function GetAllAttachmentsMetaData ( 
	sticky_application_id As Integer
) As List(Of ApplicationAttachment)
```


#### Parameters
&nbsp;<dl><dt>sticky_application_id</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br /></dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">List</a>(<a href="T_Citrix_SDK_AppDNA_ApplicationAttachment">ApplicationAttachment</a>)<br />Returns the requested <a href="T_Citrix_SDK_AppDNA_ApplicationAttachment">ApplicationAttachment</a> objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_GetAllAttachmentsMetaData">GetAllAttachmentsMetaData Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />