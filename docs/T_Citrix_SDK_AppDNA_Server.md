# Server Class
 

Represents an instance of AppDNA (i.e. a specific AppDNA database). Create by calling <a href="M_Citrix_SDK_AppDNA_Server_Connect">Connect(String, String, String)</a> one of the overloads.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Server<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class Server : IEquatable<Server>, 
	ICloneable, IDisposable
```

###VB
```vbnet
Public Class Server
	Implements IEquatable(Of Server), ICloneable, 
	IDisposable
```

The Server type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_Application">Application</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_Application">Application</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_ApplicationAttributeDefinition">ApplicationAttributeDefinition</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_ApplicationForm">ApplicationForm</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_ApplicationForm">ApplicationForm</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_ApplicationGroup">ApplicationGroup</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_ApplicationGroup">ApplicationGroup</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_AttributeStringList">AttributeStringList</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_AttributeStringList">AttributeStringList</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_DatabaseIdentifier">DatabaseIdentifier</a></td><td>
The database identifier.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_LongRunningOperationTimeout">LongRunningOperationTimeout</a></td><td>
Some operations are run asynchronously on the server. However for simplicity these operations are exposed synchronously within the SDK. This property determines how long the synchronous operations within the SDK will wait for the server side operations to complete. The default value is 5 minutes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_OSImage">OSImage</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_OSImage">OSImage</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_OSPatch">OSPatch</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_OSPatch">OSPatch</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_Performance">Performance</a></td><td>
Gets an object that provides functionality related to <a href="T_Citrix_SDK_AppDNA_PerformanceCounter">PerformanceCounter</a> and <a href="T_Citrix_SDK_AppDNA_ApplicationPerformanceCounter">ApplicationPerformanceCounter</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Citrix_SDK_AppDNA_Server_ReferenceTracking">ReferenceTracking</a></td><td>
Gets or sets an SDK wide option to enable reference tracking.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_Report">Report</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_Report">Report</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_ReportConfiguration">ReportConfiguration</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_ReportConfiguration">ReportConfiguration</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_ServerUrl">ServerUrl</a></td><td>
The URL of the AppDNA server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_Settings">Settings</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_Settings">Settings</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_Solution">Solution</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_Solution">Solution</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_SolutionTemplate">SolutionTemplate</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_SolutionTemplate">SolutionTemplate</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_StaticAttribute">StaticAttribute</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_StaticAttribute">StaticAttribute</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_UserName">UserName</a></td><td>
The user name that was used when connecting to the server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Server_VirtualMachineConfiguration">VirtualMachineConfiguration</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Server_VirtualMachineConfiguration">VirtualMachineConfiguration</a> objects.</td></tr></table>&nbsp;
<a href="#server-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Server_ClearCache">ClearCache</a></td><td>
This function is used to clear the tracking cache in the SDK.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Clone">Clone</a></td><td>
Creates a new object that is a copy of the current instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Connect_1">Connect(Uri, String)</a></td><td>
Connects to a specific AppDNA database served by the AppDNA server instance at a given URI. It uses the AppDNA Integrated login mechanism to authenticate as the current windows principle (user name).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Connect">Connect(String, String, String)</a></td><td>
Connects to a default AppDNA server installation on the specified machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Connect_2">Connect(Uri, String, String, SecureString)</a></td><td>
Connects to a specific AppDNA database served by the AppDNA server instance at a given URI.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Connect_3">Connect(Uri, String, String, String)</a></td><td>
Connects to a specific AppDNA database served by the AppDNA server instance at a given URI.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Dispose">Dispose</a></td><td>
Disconnects from the server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Equals_1">Equals(Object)</a></td><td>
Compares two server tokens for equality.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Server_Equals">Equals(Server)</a></td><td>
Compares two server tokens for equality.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Server_GetDatabases">GetDatabases</a></td><td>
Returns a list of databases available on this AppDNA server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Server_GetHashCode">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#server-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />