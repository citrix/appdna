# Sequencing.IsFinished Property 
 

Gets a value indicating whether the server-side processing is complete.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public bool IsFinished { get; }
```

###VB
```vbnet
Public ReadOnly Property IsFinished As Boolean
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if the server-side processing is complete; otherwise, `false`

## Remarks
The return value of this does not indicate success, error or cancellation, simply whether or not the server-side processing is complete.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Sequencing">Sequencing Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />