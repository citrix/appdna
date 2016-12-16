# ApplicationGroupService.GetApplicationGroupHierarchyRoot Method 
 

Retrieves an object that can be used to traverse the <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a> hierarchy. The object will be updated whenever an <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a> is created, deleted or changes parents from within the SDK. As such, it is useful for data binding.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ApplicationGroupHierarchyRoot GetApplicationGroupHierarchyRoot()
```

###VB
```vbnet
Public Function GetApplicationGroupHierarchyRoot As ApplicationGroupHierarchyRoot
```


#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_ApplicationGroupHierarchyRoot">ApplicationGroupHierarchyRoot</a><br />An <a href="T_Citrix_SDK_AppDNA_ApplicationGroupHierarchyRoot">ApplicationGroupHierarchyRoot</a> object that represents the hierarchy of <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a> objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationGroupService">ApplicationGroupService Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />