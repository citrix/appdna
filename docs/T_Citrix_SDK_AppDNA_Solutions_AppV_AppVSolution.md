# AppVSolution Class
 

Represents an App-V solution instance.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.AppV.AppVSolution<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class AppVSolution : INotifyPropertyChanged, 
	ISolution, IEquatable<AppVSolution>
```

###VB
```vbnet
Public Class AppVSolution
	Implements INotifyPropertyChanged, ISolution, IEquatable(Of AppVSolution)
```

The AppVSolution type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_AnalysisData">AnalysisData</a></td><td>
Gets the analysis data for this instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Applications">Applications</a></td><td>
Gets the collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects associated with the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_DeployOnManagementServer">DeployOnManagementServer</a></td><td>
Gets a value indicating whether to deploy the package on the management server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_DeployOnPublishingServer">DeployOnPublishingServer</a></td><td>
Gets a value indicating whether the package will tested by deploying it to the publishing server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Description">Description</a></td><td>
Gets the description of the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Identifier">Identifier</a></td><td>
Gets the identifier of the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_IPNameManagementServer">IPNameManagementServer</a></td><td>
Gets the IP address or machine name of the management server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_IPNamePublishingServer">IPNamePublishingServer</a></td><td>
Gets the IP address or machine name of the publishing server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_LatestAnalyzedState">LatestAnalyzedState</a></td><td>
Gets a value indicating whether the solution is analyzed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_LoginManagementServer">LoginManagementServer</a></td><td>
Gets the login used to connect to the management server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_LoginPublishingServer">LoginPublishingServer</a></td><td>
Gets the login used to connect to the publishing server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_ManualMode">ManualMode</a></td><td>
Gets a value indicating whether the solution's applications will be install captured/sequenced in manual mode (i.e. autoclick feature is disabled).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Name">Name</a></td><td>
Gets the name of the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_NotImportedApplicationLocations">NotImportedApplicationLocations</a></td><td>
Gets the collection of <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> objects associated with the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_OutPackageDirectory">OutPackageDirectory</a></td><td>
Gets the path to the out package directory.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_PasswordManagementServer">PasswordManagementServer</a></td><td>
Gets the password used to connect to the management server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_PasswordPublishingServer">PasswordPublishingServer</a></td><td>
Gets the password used to connect to the publishing server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_PrerequisitesFolder">PrerequisitesFolder</a></td><td>
Gets App-V prerequisites folder.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_ReportingRequirements">ReportingRequirements</a></td><td>
Gets the report, group and algorithm requirements for this instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Reports">Reports</a></td><td>
Gets the available reports for this solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_SequenceDependenciesWithinOnePackage">SequenceDependenciesWithinOnePackage</a></td><td>
Gets a value indicating whether an application with dependencies will be sequenced within one App-V package.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_VmConfigs">VmConfigs</a></td><td>
Gets virtual machine configurations for the solutions</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Workflow">Workflow</a></td><td>
Gets the solution workflow.</td></tr></table>&nbsp;
<a href="#appvsolution-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Analyze">Analyze()</a></td><td>
Analyzes this solution.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Analyze_1">Analyze(Boolean)</a></td><td>
Starts the solution analysis.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_AnalyzeInBackground">AnalyzeInBackground()</a></td><td>
Analyzes this solution in background.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_AnalyzeInBackground_1">AnalyzeInBackground(Boolean)</a></td><td>
Analyzes this solution in background.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_ApplicationSelectionScope">ApplicationSelectionScope</a></td><td>
Gets a collection of applications that will be used to generate the solution's report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Delete">Delete</a></td><td>
Deletes this solution.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>, is equal to this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Equals">Equals(AppVSolution)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_GetSelectionScope">GetSelectionScope</a></td><td> **Obsolete. **
Gets a collection of application ids that will be used to generate the solution's report</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Processing">Processing</a></td><td>
Gets a processing.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#appvsolution-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_Deleted">Deleted</a></td><td>
Occures when the solution is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_AppV_AppVSolution_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#appvsolution-class">Back to Top</a>

## Remarks
The solution instance is the stored configuration of a solution template.

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_AppV">Citrix.SDK.AppDNA.Solutions.AppV Namespace</a><br />