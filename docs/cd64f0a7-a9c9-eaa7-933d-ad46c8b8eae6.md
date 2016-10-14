# Sequencing.WaitForCompletion Method (TimeSpan)
 

Returns a value indicating whether <a href="5bf5267e-4647-ad54-56d9-0cc463737c55">IsFinished</a> has become `true` before the *timeout* elapses.

**Namespace:**&nbsp;<a href="a638ea88-d709-bd82-5735-d58961438ce5">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public bool WaitForCompletion(
	TimeSpan timeout
)
```

**VB**
```vbnet
Public Function WaitForCompletion ( 
	timeout As TimeSpan
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The maximum time to wait for <a href="5bf5267e-4647-ad54-56d9-0cc463737c55">IsFinished</a> to become `true`.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />`true` if <a href="5bf5267e-4647-ad54-56d9-0cc463737c55">IsFinished</a> becomes `true` before the *timeout* elapses; otherwise, `false`.

## See Also


#### Reference
<a href="e4a53a8f-f41d-538f-ea6c-8e8d13e3e7cd">Sequencing Class</a><br /><a href="9b5e9259-ac13-3669-bf55-ec5ef019c50d">WaitForCompletion Overload</a><br /><a href="a638ea88-d709-bd82-5735-d58961438ce5">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />