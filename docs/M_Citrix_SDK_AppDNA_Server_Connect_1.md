# Server.Connect Method (Uri, String)
 

Connects to a specific AppDNA database served by the AppDNA server instance at a given URI. It uses the AppDNA Integrated login mechanism to authenticate as the current windows principle (user name).

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public static Server Connect(
	Uri serverUrl,
	string databaseIdentifier
)
```

###VB
```vbnet
Public Shared Function Connect ( 
	serverUrl As Uri,
	databaseIdentifier As String
) As Server
```


#### Parameters
&nbsp;<dl><dt>serverUrl</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/txt7706a" target="_blank">System.Uri</a><br />The Uri of the required AppDNA web server.</dd><dt>databaseIdentifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The database identifier for the AppDNA database. This database must be configured on the AppDNA server at *serverUrl* using the AppDNAConfuigurationWizard. A database identifier is of the form "<sql server instance>:<database name>".</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Server">Server</a><br />A server which is used when calling many functions in the SDK.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Server">Server Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Server_Connect">Connect Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />