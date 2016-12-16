# ReportConfiguration Class
 

Represents a report configuration for one of the available AppDNA reporting modules. It provides access to which algorithms are available, which are disabled, the details of each algorithm, and any customizations or actions defined for those algorithms. A report configuration is used to trigger analysis (see <a href="M_Citrix_SDK_AppDNA_ReportConfiguration_Analyze">Analyze</a> and its overloads), as well as retrieving <a href="T_Citrix_SDK_AppDNA_Report">Report</a> objects that contain the results of analysis (see <a href="M_Citrix_SDK_AppDNA_ReportConfiguration_GetReport">GetReport</a> or one of its overloads).


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.ReportConfiguration<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ReportConfiguration : INotifyPropertyChanged
```

###VB
```vbnet
Public Class ReportConfiguration
	Implements INotifyPropertyChanged
```

The ReportConfiguration type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Algorithms">Algorithms</a></td><td>
Returns a collection of the ResultsByAlgorithm in this report configuration. This is all the ResultsByAlgorithm from each AlgorithmGroup flattened into a single collection.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Customizations">Customizations</a></td><td>
Gets a read only collection of the AlgorithmCustomization objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Description">Description</a></td><td>
The description of the reporting module</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Enabled">Enabled</a></td><td>
Gets a value that is true if the reporting module should be used in analysis.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Groups">Groups</a></td><td>
Gets a read only collection of the AlgorithmGroup objects in this report configuration.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Icon">Icon</a></td><td>
The icon of the reporting module</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Identifier">Identifier</a></td><td>
A unique identifier for the reporting module</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Image">Image</a></td><td>
The image of the reporting module</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_IsCustomReport">IsCustomReport</a></td><td>
Returns true if the ReportConfiguration is a user defined report.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_IsInternal">IsInternal</a></td><td>
Returns true if the ReportConfiguration is for internal needs, quite often for a solutions.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Licensed">Licensed</a></td><td>
Gets a value specifying if the reporting module is currently licensed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_Name">Name</a></td><td>
The name of the reporting module</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_ProductName">ProductName</a></td><td>
The product name of the reporting module</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ReportConfiguration_ReleaseNotes">ReleaseNotes</a></td><td>
The release notes of the reporting module</td></tr></table>&nbsp;
<a href="#reportconfiguration-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportConfiguration_Analyze">Analyze(IEnumerable(Application))</a></td><td>
Triggers an analysis of the specified applications against this ReportConfiguration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportConfiguration_Analyze_1">Analyze(IEnumerable(Application), PropertyChangedEventHandler)</a></td><td>
Triggers an analysis of the specified applications against this ReportConfiguration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportConfiguration_Analyze_2">Analyze(IEnumerable(Application), PropertyChangedEventHandler, SynchronizationContext)</a></td><td>
Triggers an analysis of the specified applications against this ReportConfiguration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportConfiguration_Enable">Enable</a></td><td>
If set *state* to `true` enables the specified report configurations, algorithm groups and algorithms. Otherwise disables all above.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportConfiguration_GetReport">GetReport()</a></td><td>
Retrieves the Report object of this ReportConfiguration for all applications.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportConfiguration_GetReport_1">GetReport(IEnumerable(Application))</a></td><td>
Retrieves the Report object of this ReportConfiguration for the specified applications.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportConfiguration_GetReport_2">GetReport(IEnumerable(Application), IEnumerable(Algorithm))</a></td><td>
Retrieves the Report object of this ReportConfiguration for the specified applications.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#reportconfiguration-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_ReportConfiguration_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#reportconfiguration-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />