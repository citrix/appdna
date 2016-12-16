# ApplicationService.Delete Method (IEnumerable(Application), ApplicationDeleteOptions)
 

Delete a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public void Delete(
	IEnumerable<Application> applications,
	ApplicationDeleteOptions deleteOptions
)
```

###VB
```vbnet
Public Sub Delete ( 
	applications As IEnumerable(Of Application),
	deleteOptions As ApplicationDeleteOptions
)
```


#### Parameters
&nbsp;<dl><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />A collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects to delete.</dd><dt>deleteOptions</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ApplicationDeleteOptions">Citrix.SDK.AppDNA.ApplicationDeleteOptions</a><br />Indicates whether applications that have other applications depending on them can be deleted, thereby clearing the dependency relationships.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_Delete">Delete Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />