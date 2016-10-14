# PatchImpactAnalysisSolution Class
 

Represents a solution instance.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis.PatchImpactAnalysisSolution<br />
**Namespace:**&nbsp;<a href="871ad9a2-386c-600b-6667-036c2dd65206">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis (in Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**
```csharp
public class PatchImpactAnalysisSolution : INotifyPropertyChanged, 
	ISolution
```

**VB**
```vbnet
Public Class PatchImpactAnalysisSolution
	Implements INotifyPropertyChanged, ISolution
```

The PatchImpactAnalysisSolution type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="72de491f-e540-896a-0d6d-0e8afea3aa43">AnalysisData</a></td><td>
Gets the analysis data.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="ebe58a54-aa11-3699-98e8-d09345520dcb">Description</a></td><td>
Gets the description.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="560827f0-a533-4e0c-f72e-405429eaf9bd">Identifier</a></td><td>
Gets the identifier.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="406ca0b6-7786-d2fd-62e4-5aacede98d29">LatestAnalyzedState</a></td><td>
Gets a value indicating whether the solution is analyzed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="d725e4b6-27de-b9a2-5f25-42fc2aa39886">Name</a></td><td>
Gets the name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="c2fb5adf-7ead-7cad-ca73-df0383b8c3be">OsBuild</a></td><td>
Gets the os build.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="1ce86a7c-0f89-b7b8-c44d-55d4dfc1277f">ReportingRequirements</a></td><td>
Gets the reporting requirements for the solution.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="042f976a-5d1c-39a1-e6b3-22a6e3324e13">Reports</a></td><td>
Gets the available reports for this solution.</td></tr></table>&nbsp;
<a href="#patchimpactanalysissolution-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="58b1684a-789e-eafd-0b48-9be06b73075c">Analyze()</a></td><td>
Starts the solution analysis.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="17a486c2-9ccf-5bdf-0a5e-e4fb4f9e566b">Analyze(Boolean)</a></td><td>
Analyzes this solution.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="5115df07-d139-fdf3-f638-4f6df4f7660e">ApplicationSelectionScope</a></td><td>
Gets a collection of applications that will be used to generate the solution's report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="c1ae4048-3a49-e0e1-68c2-8735d2fb2def">Delete</a></td><td>
Deletes this solution.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="7867beca-d31c-f451-abf3-f971b69bd951">ExportReport</a></td><td>
Exports the report.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="f71424fd-bf3c-cffa-9372-08a580ac6269">GetSelectionScope</a></td><td> **Obsolete. **
Gets a collection of application ids that will be used to generate the solution's report.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#patchimpactanalysissolution-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="457ac64a-fdef-2dc0-fe47-ed1aca7ca7e6">Deleted</a></td><td>
Occurs when the solution is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="a22d4f58-e637-2838-f2ab-a931e1c56837">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#patchimpactanalysissolution-class">Back to Top</a>

## Remarks
A solution instance is a stored configuration for a solution template

## See Also


#### Reference
<a href="871ad9a2-386c-600b-6667-036c2dd65206">Citrix.SDK.AppDNA.Solutions.PatchImpactAnalysis Namespace</a><br /><a href="http://msdn2.microsoft.com/en-us/library/ms133020" target="_blank">System.ComponentModel.INotifyPropertyChanged</a><br /><a href="542a63db-c984-0d48-7ab7-056c266ebdc1">Citrix.SDK.AppDNA.Interfaces.ISolution</a><br />