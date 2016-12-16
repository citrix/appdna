# XenReportedApplication Class
 

Application in scope of xen report


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common.XenReportedApplication<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public abstract class XenReportedApplication
```

###VB
```vbnet
Public MustInherit Class XenReportedApplication
```

The XenReportedApplication type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication__ctor">XenReportedApplication</a></td><td>
Initializes a new instance of the XenReportedApplication class</td></tr></table>&nbsp;
<a href="#xenreportedapplication-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_AfterActionDesktopRag">AfterActionDesktopRag</a></td><td>
Gets the after action desktop rag.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_AfterActionServerRag">AfterActionServerRag</a></td><td>
Gets the after action server rag.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_Application">Application</a></td><td>
Gets the <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_Application">Application</a> object.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_BeforeActionDesktopRag">BeforeActionDesktopRag</a></td><td>
Gets the before action desktop rag.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_BeforeActionServerRag">BeforeActionServerRag</a></td><td>
Gets the before action server rag.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_Category">Category</a></td><td>
Gets the category of application in scope of Xen Report.</td></tr><tr><td>![Protected property](media/protproperty.gif "Protected property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_DesktopHostedMergedModuleIdentifiers">DesktopHostedMergedModuleIdentifiers</a></td><td>
Gets the identifiers of the <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> objects which need to be merged to receive data for Desktop Hosted Deployment model.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_DesktopPostImage">DesktopPostImage</a></td><td>
Gets the image for target platform on desktop hosted deployment model.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_DesktopPreImage">DesktopPreImage</a></td><td>
Gets the image for source platform on desktop hosted deployment model.</td></tr><tr><td>![Protected property](media/protproperty.gif "Protected property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_MergedModuleIdentifiers">MergedModuleIdentifiers</a></td><td>
Gets the identifiers of the <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> objects which need to be merged to receive data for Server Hosted Deployment model.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_ServerPostImage">ServerPostImage</a></td><td>
Gets the image for target platform on server hosted deployment model.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_ServerPreImage">ServerPreImage</a></td><td>
Gets the image for source platform on server hosted deployment model.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_SolutionPlatform">SolutionPlatform</a></td><td>
Gets the <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionPlatform">XenSolutionPlatform</a> object for source platform application is reported against.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_TargetPlatform">TargetPlatform</a></td><td>
Gets the <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolutionPlatform">XenSolutionPlatform</a> object for target platform application is reported against.</td></tr></table>&nbsp;
<a href="#xenreportedapplication-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_GetDesktopRemediationReport">GetDesktopRemediationReport</a></td><td>
Gets the remediation report for a desktop hosted deployment model.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenReportedApplication_GetRemediationReport">GetRemediationReport</a></td><td>
Gets the remediation report for a server hosted deployment model.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#xenreportedapplication-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />