# OSPatchService.ImportMsuPatch Method 
 

Imports an MSU Patch into AppDNA

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public int ImportMsuPatch(
	string patchPath,
	string name,
	string description,
	string kbArticle,
	SynchronizationContext synchronizationContext
)
```

**VB**
```vbnet
Public Function ImportMsuPatch ( 
	patchPath As String,
	name As String,
	description As String,
	kbArticle As String,
	synchronizationContext As SynchronizationContext
) As Integer
```


#### Parameters
&nbsp;<dl><dt>patchPath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br /></dd><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br /></dd><dt>description</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br /></dd><dt>kbArticle</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br /></dd><dt>synchronizationContext</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/wx31754f" target="_blank">System.Threading.SynchronizationContext</a><br /></dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Int32</a>

## See Also


#### Reference
<a href="2e946539-dc5f-62e8-5405-e89731ee69a1">OSPatchService Class</a><br /><a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />