# BuildAssessmentSolution Class
 

Represents a Build Assessment solution instance.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.BuildAssessment.BuildAssessmentSolution<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.BuildAssessment (in Citrix.SDK.AppDNA.Solutions.BuildAssessment.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class BuildAssessmentSolution : INotifyPropertyChanged, 
	ISolution, IEquatable<BuildAssessmentSolution>
```

###VB
```vbnet
Public Class BuildAssessmentSolution
	Implements INotifyPropertyChanged, ISolution, IEquatable(Of BuildAssessmentSolution)
```

The BuildAssessmentSolution type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_AnalysisData">AnalysisData</a></td><td>
Gets the analysis data for this instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Applications">Applications</a></td><td>
Gets the collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects associated with the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_CertifiedApplications">CertifiedApplications</a></td><td>
Gets a collection of <a href="T_Citrix_SDK_AppDNA_Application">Application</a> objects that are certified on the reference build.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Description">Description</a></td><td>
Gets the description of the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Identifier">Identifier</a></td><td>
Gets the identifier of the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_LatestAnalyzedState">LatestAnalyzedState</a></td><td>
Gets a value indicating whether the solution is analyzed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Name">Name</a></td><td>
Gets the name of the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ReferenceBuild">ReferenceBuild</a></td><td>
Gets the reference build.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ReferenceBuildAppMode">ReferenceBuildAppMode</a></td><td>
Gets the reference build application mode.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ReportingRequirements">ReportingRequirements</a></td><td>
Gets the report, group and algorithm requirements for this instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Reports">Reports</a></td><td>
Gets the available reports for this solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_TargetBuilds">TargetBuilds</a></td><td>
Gets a collection of target builds.</td></tr></table>&nbsp;
<a href="#buildassessmentsolution-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Analyze">Analyze()</a></td><td>
Starts the solution analysis.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Analyze_1">Analyze(Boolean)</a></td><td>
Starts the solution analysis.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ApplicationSelectionScope">ApplicationSelectionScope</a></td><td>
Gets a collection of applications that will be used to generate the solution's report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Delete">Delete</a></td><td>
Deletes this solution.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Equals">Equals(BuildAssessmentSolution)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ExportReport">ExportReport(String, ReportOptions, ReportExportFormat, TimeSpan)</a></td><td>
Exports the report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ExportReport_1">ExportReport(String, ReportOptions, ReportExportFormat, TimeSpan, OSImage)</a></td><td>
Exports the report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_ExportReport_2">ExportReport(String, ReportOptions, ReportExportFormat, TimeSpan, OSImage, Application)</a></td><td>
Exports the report.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_GetHashCode">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_GetReport">GetReport</a></td><td>
Gets the report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_GetSelectionScope">GetSelectionScope</a></td><td> **Obsolete. **
Gets a collection of application ids that will be used to generate the solution's report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#buildassessmentsolution-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_Deleted">Deleted</a></td><td>
Occurs when the solution is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Citrix_SDK_AppDNA_Solutions_BuildAssessment_BuildAssessmentSolution_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#buildassessmentsolution-class">Back to Top</a>

## Remarks
The solution instance is the stored configuration of a solution template

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_BuildAssessment">Citrix.SDK.AppDNA.Solutions.BuildAssessment Namespace</a><br />