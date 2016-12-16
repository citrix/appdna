# Application.Profile Method 
 

Starts profiling an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> application directly from the source file using Install Capture technology.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Import Profile(
	ProfileApplicationConfiguration config,
	ProfileApplicationSourceDetails sourceDetails
)
```

###VB
```vbnet
Public Function Profile ( 
	config As ProfileApplicationConfiguration,
	sourceDetails As ProfileApplicationSourceDetails
) As Import
```


#### Parameters
&nbsp;<dl><dt>config</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ProfileApplicationConfiguration">Citrix.SDK.AppDNA.ProfileApplicationConfiguration</a><br />The configuration details to be used for profiling.</dd><dt>sourceDetails</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ProfileApplicationSourceDetails">Citrix.SDK.AppDNA.ProfileApplicationSourceDetails</a><br />The source details to be used for profiling.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Import">Import</a><br />An object for monitoring a progress.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />