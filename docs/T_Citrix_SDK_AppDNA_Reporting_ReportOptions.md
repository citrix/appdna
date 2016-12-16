# ReportOptions Class
 

Exposes information required to identify a report


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Reporting.ReportOptions<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Reporting">Citrix.SDK.AppDNA.Reporting</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ReportOptions : IEquatable<ReportOptions>
```

###VB
```vbnet
Public Class ReportOptions
	Implements IEquatable(Of ReportOptions)
```

The ReportOptions type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions__ctor">ReportOptions()</a></td><td>
Initializes a new instance of the ReportOptions class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions__ctor_1">ReportOptions(ReportType, String)</a></td><td>
Initializes a new instance of the ReportOptions class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions__ctor_2">ReportOptions(ReportType, String, String, String)</a></td><td>
Initializes a new instance of the ReportOptions class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions__ctor_3">ReportOptions(ReportType, String, String, String, Boolean, Boolean, IEnumerable(ReportDescription))</a></td><td>
Initializes a new instance of the ReportOptions class.</td></tr></table>&nbsp;
<a href="#reportoptions-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_AdditionalData">AdditionalData</a></td><td>
Gets or sets the additional data.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_IsChangeSelectionAllowed">IsChangeSelectionAllowed</a></td><td>
Gets or sets a value indicating whether this report allows to change selection.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_IsTopLevel">IsTopLevel</a></td><td>
Gets or sets a value indicating whether this report is top level and should appears on the menu level.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_ModuleIdentifier">ModuleIdentifier</a></td><td>
Gets or sets the module identifier.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_PageUrl">PageUrl</a></td><td>
Gets or sets the report page.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_ReportViews">ReportViews</a></td><td>
Gets or sets the report views.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_Title">Title</a></td><td>
Gets or sets the report title.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Reporting_ReportOptions_Type">Type</a></td><td>
Gets or sets the type.</td></tr></table>&nbsp;
<a href="#reportoptions-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions_Equals">Equals(ReportOptions)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions_UpdateReportPage">UpdateReportPage</a></td><td>
Updates the report page.</td></tr></table>&nbsp;
<a href="#reportoptions-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions_op_Equality">Equality</a></td><td></td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Reporting_ReportOptions_op_Inequality">Inequality</a></td><td></td></tr></table>&nbsp;
<a href="#reportoptions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Reporting">Citrix.SDK.AppDNA.Reporting Namespace</a><br />