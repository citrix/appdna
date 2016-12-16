# Application Class
 

Represents an application.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Application<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class Application : INotifyPropertyChanged, 
	IEquatable<Application>
```

###VB
```vbnet
Public Class Application
	Implements INotifyPropertyChanged, IEquatable(Of Application)
```

The Application type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_ApplicationGroups">ApplicationGroups</a></td><td>
Returns the collection of <a href="T_Citrix_SDK_AppDNA_ApplicationGroup">ApplicationGroup</a> objects that this application belongs to.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Attachments">Attachments</a></td><td>
Gets the collection of application attachments.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Attributes">Attributes</a></td><td>
Gets a value that represents the collection of application attributes that are associated with this application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_CustomerKey">CustomerKey</a></td><td>
Gets the customer key (standard attribute) value for an app.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Identifier">Identifier</a></td><td>
Gets a value that is a unique identifier for the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_ImportWarnings">ImportWarnings</a></td><td>
A string that holds any issues that were encountered during import but that did not cause the import to fail.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_IsUserFramework">IsUserFramework</a></td><td>
If this application is a user framework</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Loaded">Loaded</a></td><td>
Gets a value that is the date when the application is loaded.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_LoadedBy">LoadedBy</a></td><td>
Gets a value that is the user name of the account that loaded the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Manufacturer">Manufacturer</a></td><td>
Gets a value that is the application manufacturer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Name">Name</a></td><td>
Gets a value that is the application name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_OriginalSourceFile">OriginalSourceFile</a></td><td>
Gets a value that is the path of the installation file specified when the application was imported.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_ProfileData">ProfileData</a></td><td>
Gets the application performance profiling data.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_RequiredApplications">RequiredApplications</a></td><td>
The current applications this application requires</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_SourceCategory">SourceCategory</a></td><td>
Gets a value that is the type of application, determined by the import method.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_State">State</a></td><td> **Obsolete. **
Gets a state of the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Status">Status</a></td><td>
Geta a status of the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_SuggestedRequiredApplications">SuggestedRequiredApplications</a></td><td>
Returns a list of applications that the current application may require.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Application_Version">Version</a></td><td>
Gets a value that is the application version.</td></tr></table>&nbsp;
<a href="#application-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_AddAttachment">AddAttachment</a></td><td>
Adds the attachment to application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_AddRequiredApplications">AddRequiredApplications(Application[])</a></td><td>
Adds applications to the list of required application for the current application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_AddRequiredApplications_1">AddRequiredApplications(IEnumerable(Application))</a></td><td>
Adds applications to the list of required application for the current application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_ClearAllAttributes">ClearAllAttributes</a></td><td>
Removes all non-system application attributes values from this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_ClearAttribute">ClearAttribute</a></td><td>
Removes the matching non-system application attribute values from this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_ClearAttributes">ClearAttributes</a></td><td>
Removes all matching non-system application attribute values from this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_ClearCustomProductDetails">ClearCustomProductDetails</a></td><td>
Clears the previously set up product details(name, manufacturer, version) and reverts it back to values created during application import.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Delete">Delete()</a></td><td>
Deletes this application from AppDNA.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Delete_1">Delete(ApplicationDeleteOptions)</a></td><td>
Deletes this application from AppDNA.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_DeleteAttachments">DeleteAttachments</a></td><td>
Deletes the attachments by the specified hashes.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified object is equal to the current application.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Equals">Equals(Application)</a></td><td>
Indicates whether the current application is equal to another application.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_GetHashCode">GetHashCode</a></td><td>
Gets a hash code for the current application.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_GetReport_1">GetReport(String)</a></td><td>
Retrieves the specified report information.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_GetReport">GetReport(ReportConfiguration)</a></td><td>
Retrieves the specified report information.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Import">Import(String)</a></td><td>
Imports an Application object directly from the source file into previously created application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Import_1">Import(String, Boolean)</a></td><td>
Imports an Application object directly from the source file into previously created application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Import_2">Import(String, IEnumerable(String), ApplicationImportConfiguration, String, Boolean)</a></td><td>
Imports an Application object directly from the source file into previously created application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_InstallCapture">InstallCapture</a></td><td>
Imports an Application object directly from the source file into previously created application, using Install Capture technology (for non-MSI files).</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_Profile">Profile</a></td><td>
Starts profiling an Application application directly from the source file using Install Capture technology.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_RemoveRequiredApplications">RemoveRequiredApplications(Application[])</a></td><td>
Removes applications from the list of required applications for the current application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_RemoveRequiredApplications_1">RemoveRequiredApplications(IEnumerable(Application))</a></td><td>
Removes applications from the list of required applications for the current application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SaveProfilingData">SaveProfilingData</a></td><td>
Saves profiling data for the current application after the profiling is finished</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute">SetAttribute(String, Ragu)</a></td><td>
Sets an `ApplicationAttribute` value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_2">SetAttribute(String, Boolean)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_4">SetAttribute(String, DateTime)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_6">SetAttribute(String, Double)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_8">SetAttribute(String, String)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_1">SetAttribute(String, Ragu, String)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_3">SetAttribute(String, Boolean, String)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_5">SetAttribute(String, DateTime, String)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_7">SetAttribute(String, Double, String)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute_9">SetAttribute(String, String, String)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute__1">SetAttribute(T)(ApplicationAttributeDefinition, T)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute__1_2">SetAttribute(T)(String, T, ReportConfiguration)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetAttribute__1_1">SetAttribute(T)(ApplicationAttributeDefinition, T, ReportConfiguration)</a></td><td>
Sets an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute">ApplicationAttribute</a> value for this application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetProductDetails">SetProductDetails(String, String, String)</a></td><td>
Sets the product name, manufacturer and version.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetProductDetails_1">SetProductDetails(String, String, Version)</a></td><td>
Sets the product name, manufacturer and version.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_SetProductName">SetProductName</a></td><td>
Sets the product name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Application_ToString">ToString</a></td><td>
Returns a string that represents the current object.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#application-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Application_Deleted">Deleted</a></td><td>
An event triggered when the application is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Application_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#application-class">Back to Top</a>

## Remarks
An application is the result of importing from some installation media. Once imported, an application can be analyzed and reported against. Applications are identified using a fingerprinting mechanism, rather than the import details. Imports that have a very similar fingerprint are considered the same application and the subsequent import will overwrite the initial import. Imports from the same installation media that have different fingerprints will be considered separate applications. This is often observed when snapshotting during Install Capture and the snapshot includes spurious file or registry changes.

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />