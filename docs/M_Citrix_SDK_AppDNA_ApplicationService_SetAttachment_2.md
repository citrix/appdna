# ApplicationService.SetAttachment Method (Int32, String, Byte[], Byte[])
 

**Note: This API is now obsolete.**

Attach a file to a given application

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
[ObsoleteAttribute("Use strongly typed SetAttachment(Application application, string filename, byte[] valueToAttach, byte[] hash) method")]
public ApplicationAttachment SetAttachment(
	int sticky_application_id,
	string filename,
	byte[] valueToAttach,
	byte[] hash
)
```

###VB
```vbnet
<ObsoleteAttribute("Use strongly typed SetAttachment(Application application, string filename, byte[] valueToAttach, byte[] hash) method")>
Public Function SetAttachment ( 
	sticky_application_id As Integer,
	filename As String,
	valueToAttach As Byte(),
	hash As Byte()
) As ApplicationAttachment
```


#### Parameters
&nbsp;<dl><dt>sticky_application_id</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />Id of the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.</dd><dt>filename</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Name of the file to be attached.</dd><dt>valueToAttach</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/yyb1w04y" target="_blank">System.Byte</a>[]<br />Value to be attached.</dd><dt>hash</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/yyb1w04y" target="_blank">System.Byte</a>[]<br />Hash of the file.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_ApplicationAttachment">ApplicationAttachment</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_SetAttachment">SetAttachment Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />