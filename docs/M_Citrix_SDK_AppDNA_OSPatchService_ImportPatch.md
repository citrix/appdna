# OSPatchService.ImportPatch Method 
 

Imports a Patch into AppDNA

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public PatchImportResult ImportPatch(
	string patchPath,
	string name,
	string description,
	string kbArticle,
	SynchronizationContext synchronizationContext
)
```

###VB
```vbnet
Public Function ImportPatch ( 
	patchPath As String,
	name As String,
	description As String,
	kbArticle As String,
	synchronizationContext As SynchronizationContext
) As PatchImportResult
```


#### Parameters
&nbsp;<dl><dt>patchPath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br /></dd><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Patch Name</dd><dt>description</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Patch Description</dd><dt>kbArticle</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Microsoft Knowledge Base Article Number</dd><dt>synchronizationContext</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/wx31754f" target="_blank">System.Threading.SynchronizationContext</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_PatchImportResult">PatchImportResult</a><br />

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_OSPatchService">OSPatchService Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />