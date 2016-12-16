# Application.ApplicationGroups Property 
 

Returns the collection of <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a> objects that this application belongs to.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ApplicationGroupCollection ApplicationGroups { get; }
```

###VB
```vbnet
Public ReadOnly Property ApplicationGroups As ApplicationGroupCollection
	Get
```


#### Property Value
Type: <a href="T_Citrix_SDK_AppDNA_ApplicationGroupCollection">ApplicationGroupCollection</a>

## Remarks
This collection cannot be used to modify the application groups of an application. For that, call the relevant methods in the <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a> class.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />