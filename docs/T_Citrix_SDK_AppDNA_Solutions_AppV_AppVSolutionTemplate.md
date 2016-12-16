# AppVSolutionTemplate Class
 

Represents an App-V solution template.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.AppV.AppVSolutionTemplate<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class AppVSolutionTemplate : INotifyPropertyChanged, 
	IEquatable<AppVSolutionTemplate>
```

###VB
```vbnet
Public Class AppVSolutionTemplate
	Implements INotifyPropertyChanged, IEquatable(Of AppVSolutionTemplate)
```

The AppVSolutionTemplate type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Description">Description</a></td><td>
Gets the description of the solution template.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Enabled">Enabled</a></td><td>
Gets a value indicating whether the solution template is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Identifier">Identifier</a></td><td>
Gets the identifier of the solution template.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Name">Name</a></td><td>
Gets the name of the solution template.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Version">Version</a></td><td>
Gets the version of the solution template.</td></tr></table>&nbsp;
<a href="#appvsolutiontemplate-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Delete">Delete</a></td><td>
Deletes this solution template.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>, is equal to this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Equals">Equals(AppVSolutionTemplate)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_OnPropertyChanged">OnPropertyChanged</a></td><td>
Called when property value is changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#appvsolutiontemplate-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_Deleted">Deleted</a></td><td>
Occurs when the template is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolutionTemplate_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#appvsolutiontemplate-class">Back to Top</a>

## Remarks
The solution template is a pluggable wrapper for existing functionality in AppDNA.

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />