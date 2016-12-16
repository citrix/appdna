# XenAdoptionServer Class
 

Represents an instance of a Xen Adoption solution (i.e., a specific AppDNA solution within a specific database).


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.XenAdoption.XenAdoptionServer<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenAdoption (in Citrix.SDK.AppDNA.Solutions.XenAdoption.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class XenAdoptionServer : IXenServer<XenAdoptionSolution, XenSolutionEdit>, 
	IEquatable<XenAdoptionServer>
```

###VB
```vbnet
Public Class XenAdoptionServer
	Implements IXenServer(Of XenAdoptionSolution, XenSolutionEdit), 
	IEquatable(Of XenAdoptionServer)
```

The XenAdoptionServer type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer__ctor">XenAdoptionServer</a></td><td>
Initializes a new instance of the XenAdoptionServer class.</td></tr></table>&nbsp;
<a href="#xenadoptionserver-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_Application">Application</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_ReportConfiguration">ReportConfiguration</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_OsImage">OsImage</a></td><td>
Gets an object that provides functionality related to <a href="T_Citrix_SDK_AppDNA_OSImage">OSImage</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_Report">Report</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_ReportConfiguration">ReportConfiguration</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_ReportConfiguration">ReportConfiguration</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_ReportConfiguration">ReportConfiguration</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_ServerUrl">ServerUrl</a></td><td>
Gets the URL of the AppDNA server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_XenAdoptionSolution">XenAdoptionSolution</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_XenAdoptionSolution">XenAdoptionSolution</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_XenAdoptionSolutionTemplate">XenAdoptionSolutionTemplate</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_XenAdoptionSolutionTemplate">XenAdoptionSolutionTemplate</a> objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_XenSolution">XenSolution</a></td><td>
Gets an object that provides functionality related to <a href="P_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_XenSolution">XenSolution</a> objects.</td></tr></table>&nbsp;
<a href="#xenadoptionserver-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>, is equal to this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_Equals">Equals(XenAdoptionServer)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenAdoption_XenAdoptionServer_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#xenadoptionserver-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_XenAdoption">Citrix.SDK.AppDNA.Solutions.XenAdoption Namespace</a><br />