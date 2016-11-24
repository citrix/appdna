#Connect to the AppDNA serverThe SDK provides client-side access to the AppDNA server. The first step in using the SDK is to establish a connection to the server. A connection to the AppDNA server is maintained by a Server object. The Server object is obtained by calling Server.Connect;There are two overloads for Connect:1. The first overload connects to the server and database established during a default AppDNA installation:
```
using AppDNA = Citrix.SDK.AppDNA;private void Connect(string username, string password){//Connect to the default database on this machine.AppDNA.Server appdna = AppDNA.Server.Connect(Environment.MachineName, username, password);}```
2. The second overload lets you connect to a specific server instance and/or database:```
AppDNA.Server appdna = AppDNA.Server.Connect( new Uri("http://SomeServer/CustomAppDNASi "SomeServer\SQLServer:AppDNADB2", username, password );
```| Parameter        | Description           | 
| ------------- |-------------| 
| URI     |This is the address at which the Internet Information Server hosts the AppDNA web services.| 
| database identifier      | The database identifier follows the form: **SQLServerMachineName[\SQLInstanceName]:DatabaseName**. For a list of database identifiers the AppDNA server is configured for, browse to the URL of the server in a web browser.|


After obtaining a Server object, you can use it to interact with the AppDNA data.