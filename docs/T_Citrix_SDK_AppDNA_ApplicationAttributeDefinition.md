# ApplicationAttributeDefinition Class
 

Represents the definition of an attribute, which can be used to assign arbitrary values to an application.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.ApplicationAttributeDefinition<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ApplicationAttributeDefinition : INotifyPropertyChanged, 
	IEquatable<ApplicationAttributeDefinition>
```

###VB
```vbnet
Public Class ApplicationAttributeDefinition
	Implements INotifyPropertyChanged, IEquatable(Of ApplicationAttributeDefinition)
```

The ApplicationAttributeDefinition type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_DataType">DataType</a></td><td>
Gets the type of the data that can be set in an <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute_1">ApplicationAttribute(T)</a> that is associated with this definition.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Identifier">Identifier</a></td><td>
Gets the unique identifier of the ApplicationAttributeDefinition.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_IsLocked">IsLocked</a></td><td>
Gets a value that is true if the user cannot modify <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute_1">ApplicationAttribute(T)</a> for this ApplicationAttributeDefinition.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_IsReportDependent">IsReportDependent</a></td><td>
Gets a value that is true if associated <a href="T_Citrix_SDK_AppDNA_ApplicationAttribute_1">ApplicationAttribute(T)</a> objects must specify a <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a> along with the value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_IsSystem">IsSystem</a></td><td>
Gets a value indicating if the ApplicationAttributeDefinition was defined by the AppDNA product rather than user defined.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Name">Name</a></td><td>
Gets the name of the ApplicationAttributeDefinition.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Order">Order</a></td><td>
Gets the display order of the ApplicationAttributeDefinition.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_ShowInAppList">ShowInAppList</a></td><td>
Indicates whether associated application attributes should be shown in the application list.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_ShowInIssuesActions">ShowInIssuesActions</a></td><td>
Indicates whether associated application attributes should be shown in the Issues and Actions reports.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_ShowInOverview">ShowInOverview</a></td><td>
Indicates whether associated application attributes should be shown in the Overview reports.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_ShowInRemediation">ShowInRemediation</a></td><td>
Indicates whether associated application attributes should be shown in the Remediation reports.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_StringList">StringList</a></td><td>
Gets the <a href="T_Citrix_SDK_AppDNA_AttributeStringList">AttributeStringList</a> of this definition, if <a href="P_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_DataType">DataType</a> is <a href="T_Citrix_SDK_AppDNA_AttributeDefinitionDataType">StringList</a>.</td></tr></table>&nbsp;
<a href="#applicationattributedefinition-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Delete">Delete</a></td><td>
Deletes the ApplicationAttributeDefinition object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Equals_1">Equals(Object)</a></td><td>
Compares two instances of ApplicationAttributeDefinition class for equality.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Equals">Equals(ApplicationAttributeDefinition)</a></td><td>
Compares two instances of ApplicationAttributeDefinition class for equality.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_GetHashCode">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Rename">Rename</a></td><td>
Renames the specified attribute name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#applicationattributedefinition-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_Deleted">Deleted</a></td><td>
This event is raised when the ApplicationAttributeDefinition is deleted using the SDK.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ApplicationAttributeDefinition_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#applicationattributedefinition-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />