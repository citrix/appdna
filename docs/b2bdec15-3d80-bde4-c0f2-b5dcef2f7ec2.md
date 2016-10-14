# IXenSolutionService(*TXenSolution*, *TXenSolutionEditor*).UpdateApplications Method 
 

Updates the applications for platform. It is short cut to update <a href="599f6061-d94a-ac2f-f6a0-2b211ae83ae4">XenSolution</a> instead of <a href="5ec314fe-4195-e457-03ae-5a1b57cd2dd8">Update(IXenSolutionConfig)</a>.

**Namespace:**&nbsp;[Citrix.SDK.AppDNA.Solutions.Xen.Common](013dc694-c357-448d-ed5a-b5c48a7f6852.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
void UpdateApplications(
	XenSolutionPlatform solutionPlatform,
	IEnumerable<Application> applications
)
```

**VB**
```vbnet
Sub UpdateApplications ( 
	solutionPlatform As XenSolutionPlatform,
	applications As IEnumerable(Of Application)
)
```


#### Parameters
&nbsp;<dl><dt>solutionPlatform</dt><dd>Type: <a href="0e04915f-6b1a-0016-6a11-cd519e55dcbe">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolutionPlatform</a><br />The solution platform.</dd><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="1779bfff-4b29-0f26-8a09-10acdd530bbc">Application</a>)<br />The applications.</dd></dl>

## See Also


#### Reference
<a href="2be94c2a-7033-091c-56dc-00aacd0d0b6b">IXenSolutionService(TXenSolution, TXenSolutionEditor) Interface</a><br /><a href="013dc694-c357-448d-ed5a-b5c48a7f6852">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />