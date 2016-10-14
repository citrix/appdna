# ImportSourceDetails Class
 

Holds details about an application import. An instance of this class may also be used with an <a href="45bef3fc-5396-1e03-f577-fb7fe3ec23f9">Import</a> object as a key to retrieve details of the matching import.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.ImportSourceDetails<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="0139f17c-4766-6d80-dd6d-57e9b2b924ed">Citrix.SDK.AppDNA.WebImportSourceDetails</a><br />
**Namespace:**&nbsp;[Citrix.SDK.AppDNA](index.md)<br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public class ImportSourceDetails : IImportDetails
```

**VB**
```vbnet
Public Class ImportSourceDetails
	Implements IImportDetails
```

The ImportSourceDetails type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="d8854f93-8a5e-a043-aaa1-7358bc817c96">ImportSourceDetails(String)</a></td><td>
Constructor</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="625da7d1-7383-b521-aa58-cd39016a9e09">ImportSourceDetails(String, IEnumerable(String))</a></td><td>
Constructor</td></tr></table>&nbsp;
<a href="#importsourcedetails-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="72823d38-0fb7-a07f-f2e1-a3f9398f12e6">SourceFilePath</a></td><td>
Gets or sets a value that is the full path to the installation media.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="a39a668b-568f-f3be-de88-085651a2f6a0">Transforms</a></td><td>
A collection of full paths to transforms that are to be applied, in order, to the msi specified by <a href="72823d38-0fb7-a07f-f2e1-a3f9398f12e6">SourceFilePath</a>.</td></tr></table>&nbsp;
<a href="#importsourcedetails-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
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
<a href="#importsourcedetails-class">Back to Top</a>

## See Also


#### Reference
<a href="fe2d265b-410b-8b11-1eb4-a790e0b062bf">Citrix.SDK.AppDNA Namespace</a><br />