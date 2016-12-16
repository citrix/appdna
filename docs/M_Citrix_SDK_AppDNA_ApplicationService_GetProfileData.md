# ApplicationService.GetProfileData Method 
 

Gets the profile data.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ProfileDataCollection GetProfileData(
	Application application,
	bool forceRefresh = false
)
```

###VB
```vbnet
Public Function GetProfileData ( 
	application As Application,
	Optional forceRefresh As Boolean = false
) As ProfileDataCollection
```


#### Parameters
&nbsp;<dl><dt>application</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_Application">Citrix.SDK.AppDNA.Application</a><br />The application.</dd><dt>forceRefresh (Optional)</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />Causes the profile data to be reevaluated.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_ProfileDataCollection">ProfileDataCollection</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />