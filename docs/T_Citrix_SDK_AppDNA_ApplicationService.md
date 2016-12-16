# ApplicationService Class
 

This class is accessible from <a href="P_Citrix_SDK_AppDNA_Server_Application">Application</a> property and provides access to application-related functionality.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.ApplicationService<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ApplicationService
```

###VB
```vbnet
Public Class ApplicationService
```

The ApplicationService type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Create">Create(String)</a></td><td>
Create an application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Create_1">Create(String, String, String)</a></td><td>
Create an application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Create_2">Create(String, String, String, String)</a></td><td>
Create an application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_CreateAsync">CreateAsync</a></td><td>
Create an application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Delete">Delete(Application[])</a></td><td>
Delete a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Delete_1">Delete(IEnumerable(Application))</a></td><td>
Delete a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Delete_2">Delete(IEnumerable(Application), ApplicationDeleteOptions)</a></td><td>
Delete a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get">Get()</a></td><td>
Returns a collection with all the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get_5">Get(IEnumerable(Int64))</a></td><td>
Returns a collection of Application objects with matching identifiers.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get_6">Get(Int64)</a></td><td>
Returns the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object with the matching identifier.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get_7">Get(String)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get_1">Get(ApplicationFilter, Object)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get_2">Get(ApplicationFilter, Object, Int32)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering requirements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get_3">Get(ApplicationFilter, Object, Int32, Int32)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering and paging requirements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Get_4">Get(ApplicationFilter, Object, Int32, Int32, ApplicationFilter)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering and paging requirements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAllAttachmentsMetaData_1">GetAllAttachmentsMetaData(Int32)</a></td><td> **Obsolete. **
Returns a collection of ApplicationAttachment objects for a given application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAllAttachmentsMetaData">GetAllAttachmentsMetaData(Application, Boolean)</a></td><td>
Returns a collection of ApplicationAttachment objects for a given application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAsync">GetAsync()</a></td><td>
Returns a collection with all the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAsync_5">GetAsync(IEnumerable(Int64))</a></td><td>
Returns a collection of Application objects with matching identifiers.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAsync_1">GetAsync(ApplicationFilter, Object)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAsync_2">GetAsync(ApplicationFilter, Object, Int32)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering requirements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAsync_3">GetAsync(ApplicationFilter, Object, Int32, Int32)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering and paging requirements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAsync_4">GetAsync(ApplicationFilter, Object, Int32, Int32, ApplicationFilter)</a></td><td>
Returns a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that respects filtering and paging requirements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetAttachmentData">GetAttachmentData</a></td><td>
Returns the data for a specific attachment_data_id</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetCount">GetCount</a></td><td>
Returns a total count of imported <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetCountAsync">GetCountAsync</a></td><td>
Returns a collection with all the <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetProfileData">GetProfileData</a></td><td>
Gets the profile data.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_GetSystemFrameworks">GetSystemFrameworks</a></td><td>
Returns a collection of Application objects that are marked as frameworks</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Import">Import(IEnumerable(ImportSourceDetails), ApplicationImportConfiguration)</a></td><td>
Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from source files.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Import_2">Import(IEnumerable(ImportSourceDetails), String)</a></td><td>
Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from source files.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Import_3">Import(String, ApplicationImportConfiguration, String)</a></td><td>
Imports an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object directly from the source file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Import_6">Import(String, String, String)</a></td><td>
Imports an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object directly from the source file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Import_4">Import(String, IEnumerable(String), ApplicationImportConfiguration, String)</a></td><td>
Imports an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object directly from the source file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Import_5">Import(String, IEnumerable(String), String, String)</a></td><td>
Imports an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object directly from the source file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_Import_1">Import(IEnumerable(ImportSourceDetails), ApplicationImportConfiguration, Nullable(Int64), Boolean)</a></td><td>
Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from source files.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_ImportWeb">ImportWeb(IEnumerable(ImportSourceDetails), ApplicationImportConfiguration)</a></td><td> **Obsolete. **
Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from source files.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_ImportWeb_1">ImportWeb(IEnumerable(ImportSourceDetails), String)</a></td><td> **Obsolete. **
Imports multiple web <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects directly from their previously captured msi files.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_ImportWeb_2">ImportWeb(IEnumerable(WebImportSourceDetails), WebApplicationImportConfiguration)</a></td><td>
Imports multiple <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects as web applications.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_ImportWeb_3">ImportWeb(String, ApplicationImportConfiguration, String)</a></td><td>
Imports a previously captured web <a href="T_Citrix_SDK_AppDNA_Application">Application</a> directly from the capture msi.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_ImportWeb_4">ImportWeb(String, String, String)</a></td><td>
Imports a previously captured web <a href="T_Citrix_SDK_AppDNA_Application">Application</a> directly from the capture msi.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_InstallCapture_1">InstallCapture(IEnumerable(InstallCaptureSourceDetails), InstallCaptureConfiguration)</a></td><td>
Imports application data utilizing Install Capture technology.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_InstallCapture_2">InstallCapture(IEnumerable(InstallCaptureSourceDetails), InstallCaptureConfiguration, Nullable(Int64))</a></td><td>
Imports application data utilizing Install Capture.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_InstallCapture">InstallCapture(InstallCaptureSourceDetails, String, String, String)</a></td><td>
Imports application data utilizing Install Capture.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_InstallCapture_3">InstallCapture(IEnumerable(InstallCaptureSourceDetails), String, String, String)</a></td><td>
Imports application data utilizing Install Capture.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_SetAttachment">SetAttachment(Application, FileInfo)</a></td><td>
Attach a file to a given application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_SetAttachment_2">SetAttachment(Int32, String, Byte[], Byte[])</a></td><td> **Obsolete. **
Attach a file to a given application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_SetAttachment_1">SetAttachment(Application, String, Byte[], Byte[])</a></td><td>
Attach a file to a given application</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_SetProfilingData">SetProfilingData(Application, Dictionary(String, Double))</a></td><td>
Sets the profiling data.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationService_SetProfilingData_1">SetProfilingData(Application, IEnumerable(ApplicationPerformanceCounter))</a></td><td>
Sets the profiling data.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#applicationservice-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />