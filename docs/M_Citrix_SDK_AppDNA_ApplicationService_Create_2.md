# ApplicationService.Create Method (String, String, String, String)
 

Create an application

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Application Create(
	string name,
	string manufacturer,
	string version,
	string appId
)
```

###VB
```vbnet
Public Function Create ( 
	name As String,
	manufacturer As String,
	version As String,
	appId As String
) As Application
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the application.</dd><dt>manufacturer</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The manufacturer of the application.</dd><dt>version</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The version of the application.</dd><dt>appId</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The AppId of the application.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Application">Application</a><br />Returns the newly created <a href="T_Citrix_SDK_AppDNA_Application">Application</a> application object.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationService">ApplicationService Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ApplicationService_Create">Create Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />