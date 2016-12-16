# WebImportSourceDetails Class
 

Holds details about a web application import. An instance of this class may also be used with an <a href="T_Citrix_SDK_AppDNA_Import">Import</a> object as a key to retrieve details of the matching import.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">Citrix.SDK.AppDNA.ImportSourceDetails</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.WebImportSourceDetails<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class WebImportSourceDetails : ImportSourceDetails
```

###VB
```vbnet
Public Class WebImportSourceDetails
	Inherits ImportSourceDetails
```

The WebImportSourceDetails type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_WebImportSourceDetails__ctor">WebImportSourceDetails(String)</a></td><td>
A source MSI file path of a web application to be imported.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_WebImportSourceDetails__ctor_1">WebImportSourceDetails(String, String)</a></td><td>
Constructor</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_WebImportSourceDetails__ctor_2">WebImportSourceDetails(Uri, String)</a></td><td>
Constructor</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_WebImportSourceDetails__ctor_3">WebImportSourceDetails(Uri, String, String, String)</a></td><td>
Constructor</td></tr></table>&nbsp;
<a href="#webimportsourcedetails-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebImportSourceDetails_Name">Name</a></td><td>
Gets or sets the name of the web application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ImportSourceDetails_SourceFilePath">SourceFilePath</a></td><td>
Gets or sets a value that is the full path to the installation media.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebImportSourceDetails_SourceFolder">SourceFolder</a></td><td>
Gets or sets the source folder of the web application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ImportSourceDetails_Transforms">Transforms</a></td><td>
A collection of full paths to transforms that are to be applied, in order, to the msi specified by <a href="P_Citrix_SDK_AppDNA_ImportSourceDetails_SourceFilePath">SourceFilePath</a>.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebImportSourceDetails_UniqueName">UniqueName</a></td><td>
Gets or sets a unique name of the web application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebImportSourceDetails_Url">Url</a></td><td>
Gets or sets the url of the web application.</td></tr></table>&nbsp;
<a href="#webimportsourcedetails-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#webimportsourcedetails-class">Back to Top</a>

## Remarks
If it is needed to import a web application directly from MSI, <a href="T_Citrix_SDK_AppDNA_ImportSourceDetails">ImportSourceDetails</a> must be used instead.

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />