# XenSolutionEdit.WaitForCompletion Method (TimeSpan)
 

Waits for a long running operation to complete. Completion will occur regardless of success, failure or cancellation. Use a <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_ProcessingState">ProcessingState</a> property to detect the reason.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public abstract bool WaitForCompletion(
	TimeSpan timeout
)
```

###VB
```vbnet
Public MustOverride Function WaitForCompletion ( 
	timeout As TimeSpan
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The timeout to wait for a completion.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if completes before time out, otherwise `false`.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit">XenSolutionEdit Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionEdit_WaitForCompletion">WaitForCompletion Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />