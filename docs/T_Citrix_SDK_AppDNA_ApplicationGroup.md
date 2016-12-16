# ApplicationGroup Class
 

Represents a group of applications. Optionally, it may be the child of another ApplicationGroup object, which allows a tree of ApplicationGroup objects to be created.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">Citrix.SDK.AppDNA.ApplicationGrouping</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.ApplicationGroup<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ApplicationGroup : ApplicationGrouping, 
	IEquatable<ApplicationGroup>
```

###VB
```vbnet
Public Class ApplicationGroup
	Inherits ApplicationGrouping
	Implements IEquatable(Of ApplicationGroup)
```

The ApplicationGroup type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_Applications">Applications</a></td><td>
Gets the collection of application objects that belong to this grouping.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGroup_ChildGroups">ChildGroups</a></td><td>
Gets a collection of the ApplicationGroup objects that are children of this group. To add or remove an ApplicationGroup as a child, call ApplicationGroup.SetParent on the child group.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_Description">Description</a></td><td>
Gets a value that is the description of the grouping.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_IsDeleted">IsDeleted</a></td><td>
Returns true if the grouping object has been deleted using the SDK.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGrouping_Name">Name</a></td><td>
Gets a value that is the name of the grouping.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationGroup_ParentGroup">ParentGroup</a></td><td>
Gets an ApplicationGroup object which is a parent of this group. May be null.</td></tr></table>&nbsp;
<a href="#applicationgroup-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Add">Add(Application)</a></td><td>
Adds an application to this grouping.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Add_1">Add(IEnumerable(Application))</a></td><td>
Adds application objects to this grouping.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGroup_Delete">Delete</a></td><td>
Deletes this ApplicationGroup and all child groups.
 (Overrides <a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Delete">ApplicationGrouping.Delete()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGroup_Equals_1">Equals(Object)</a></td><td>
Compares two instances of ApplicationGroup class for equality.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGroup_Equals">Equals(ApplicationGroup)</a></td><td>
Compares two instances of ApplicationGroup class for equality.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Equals">Equals(ApplicationGrouping)</a></td><td>
Compares two <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a> objects for equality.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGroup_GetHashCode">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_NotifyPropertyChanged">NotifyPropertyChanged</a></td><td>
Raises the <a href="E_Citrix_SDK_AppDNA_ApplicationGrouping_PropertyChanged">PropertyChanged</a> event.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Remove">Remove(Application)</a></td><td>
Removes an application from this grouping.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGrouping_Remove_1">Remove(IEnumerable(Application))</a></td><td>
Removes applications from this grouping.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationGroup_SetParentGroup">SetParentGroup</a></td><td>
Changes the ApplicationGroup that is the parent of this ApplicationGroup.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#applicationgroup-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ApplicationGrouping_Deleted">Deleted</a></td><td>
An event that is raised when the grouping is deleted using the SDK.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ApplicationGrouping_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationGrouping">ApplicationGrouping</a>.)</td></tr></table>&nbsp;
<a href="#applicationgroup-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />