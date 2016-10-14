# ApplicationDeleteOptions Enumeration
 

Options that will control the checks and balances made when applications are deleted.

**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
[FlagsAttribute]
public enum ApplicationDeleteOptions
```

**VB**
```vbnet
<FlagsAttribute>
Public Enumeration ApplicationDeleteOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ApplicationDeleteOptions.None">**None**</td><td>0</td><td>Use the default behaviour</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ApplicationDeleteOptions.RemoveApplicationsDependencies">**RemoveApplicationsDependencies**</td><td>1</td><td>Allow the deletion of applications which have dependency relationships marking them as required by other applications</td></tr></table>

## See Also


#### Reference
<a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />