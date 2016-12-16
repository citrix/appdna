# XenUpgradeSolution Class
 

Represents a solution instance.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolution</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade.XenUpgradeSolution<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade (in Citrix.SDK.AppDNA.Solutions.XenUpgrade.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class XenUpgradeSolution : XenSolution, 
	INotifyPropertyChanged, IEquatable<XenUpgradeSolution>
```

###VB
```vbnet
Public Class XenUpgradeSolution
	Inherits XenSolution
	Implements INotifyPropertyChanged, IEquatable(Of XenUpgradeSolution)
```

The XenUpgradeSolution type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_AnalysisData">AnalysisData</a></td><td>
Gets the data required to perform the analysis.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_AnalysisData">XenSolution.AnalysisData</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_CurrentPlatforms">CurrentPlatforms</a></td><td>
Gets or sets the current platforms.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_CurrentPlatforms">XenSolution.CurrentPlatforms</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Description">Description</a></td><td>
Gets or sets the description.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_Description">XenSolution.Description</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Enabled">Enabled</a></td><td>
Gets a value indicating whether the solution is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Identifier">Identifier</a></td><td>
Gets the identifier.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_Identifier">XenSolution.Identifier</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_IsValid">IsValid</a></td><td>
Gets a value indicating whether the solution is valid.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_IsValid">XenSolution.IsValid</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_LatestAnalyzedState">LatestAnalyzedState</a></td><td>
Gets or sets a value indicating whether solution is analyzed. Is updated when use <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_AnalysisData">AnalysisData</a>
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Name">Name</a></td><td>
Gets or sets the name.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_Name">XenSolution.Name</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Report">Report</a></td><td>
Gets the core data for soluton report.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_Report">XenSolution.Report</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_ReportingRequirements">ReportingRequirements</a></td><td>
Gets the reporting requirements for the solution.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_ReportingRequirements">XenSolution.ReportingRequirements</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_TargetPlatform">TargetPlatform</a></td><td>
Gets or sets the target platform.
 (Overrides <a href="P_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_TargetPlatform">XenSolution.TargetPlatform</a>.)</td></tr></table>&nbsp;
<a href="#xenupgradesolution-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Analyze">Analyze()</a></td><td>
Analyzes this solution.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Analyze_1">Analyze(Boolean)</a></td><td>
Analyzes this solution.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_ApplicationSelectionScope">ApplicationSelectionScope</a></td><td>
Gets the applications collection which can be selected for solution report.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Delete">Delete</a></td><td>
Deletes this solution.
 (Overrides <a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_Delete">XenSolution.Delete()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Equals_2">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Equals">Equals(XenSolution)</a></td><td>
Indicates whether the current object is equal to another object of the same type.
 (Overrides <a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_Equals">XenSolution.Equals(XenSolution)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Equals_1">Equals(XenUpgradeSolution)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_ExportReport">ExportReport</a></td><td>
Exports the report.
 (Overrides <a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_ExportReport">XenSolution.ExportReport(String, ReportExportFormat, TimeSpan)</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_GetHashCode">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_GetReport">GetReport</a></td><td>
Gets the report data for this solution.
 (Overrides <a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_GetReport">XenSolution.GetReport()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_GetSelection">GetSelection</a></td><td>
Gets the application selection for the solution. It is used to filter the applciations for the report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution_GetSelectionScope">GetSelectionScope</a></td><td> **Obsolete. **
Gets the selection scope.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_SetSelection">SetSelection</a></td><td>
Save the application selection for the solution. It is used to filter the applications for the report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#xenupgradesolution-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_Deleted">Deleted</a></td><td>
Raised when the solution is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeSolution_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#xenupgradesolution-class">Back to Top</a>

## Remarks
A solution instance is a stored configuration for the solution template

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_XenUpgrade">Citrix.SDK.AppDNA.Solutions.XenUpgrade Namespace</a><br />