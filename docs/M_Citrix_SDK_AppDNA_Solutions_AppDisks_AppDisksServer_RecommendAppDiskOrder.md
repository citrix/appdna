# AppDisksServer.RecommendAppDiskOrder Method 
 

This will analyse the applications that represent AppDisks for layer ordering conflicts and will recomend the best order.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppDisks">Citrix.SDK.AppDNA.Solutions.AppDisks</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppDisks (in Citrix.SDK.AppDNA.Solutions.AppDisks.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public List<Application> RecommendAppDiskOrder(
	IEnumerable<Application> appDisks
)
```

###VB
```vbnet
Public Function RecommendAppDiskOrder ( 
	appDisks As IEnumerable(Of Application)
) As List(Of Application)
```


#### Parameters
&nbsp;<dl><dt>appDisks</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br /></dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">List</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The applications in the recommended order. If no order is suitable an empty list is returned

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppDisks_AppDisksServer">AppDisksServer Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppDisks">Citrix.SDK.AppDNA.Solutions.AppDisks Namespace</a><br />