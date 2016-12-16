# ApplicationService.GetCount Method 
 

Returns a total count of imported <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public int GetCount(
	IEnumerable<SourceCategory> categories
)
```

###VB
```vbnet
Public Function GetCount ( 
	categories As IEnumerable(Of SourceCategory)
) As Integer
```


#### Parameters
&nbsp;<dl><dt>categories</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_SourceCategory">SourceCategory</a>)<br /></dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a><br />Count of all imported <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />