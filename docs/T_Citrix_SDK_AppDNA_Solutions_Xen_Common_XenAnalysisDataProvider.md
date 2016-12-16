# XenAnalysisDataProvider Class
 

Contains logic to retrieve analysis data and solution report, group and algorithm requirements specific for a Xen Solutions


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common.XenAnalysisDataProvider<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_Solutions_XenUpgrade_XenUpgradeAnalysisDataProvider">Citrix.SDK.AppDNA.Solutions.XenUpgrade.XenUpgradeAnalysisDataProvider</a><br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public abstract class XenAnalysisDataProvider : IAnalysisDataProvider
```

###VB
```vbnet
Public MustInherit Class XenAnalysisDataProvider
	Implements IAnalysisDataProvider
```

The XenAnalysisDataProvider type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider__ctor">XenAnalysisDataProvider</a></td><td>
Initializes a new instance of the XenAnalysisDataProvider class.</td></tr></table>&nbsp;
<a href="#xenanalysisdataprovider-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_AdditionalModuleTargets">AdditionalModuleTargets</a></td><td>
Returns additional analysis targets for solution.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_AdditionalReportingRequirements">AdditionalReportingRequirements</a></td><td>
Gets an additional <a href="T_Citrix_SDK_AppDNA_Reporting_ReportingRequirementsInfo">ReportingRequirementsInfo</a>.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_AlgorithmGroupInfos">AlgorithmGroupInfos</a></td><td>
Constructs <a href="T_Citrix_SDK_AppDNA_Reporting_AlgorithmGroupInfo">AlgorithmGroupInfo</a> based in the *reportingRequirements* and *algorithms*</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_GetApplicationStates">GetApplicationStates</a></td><td>
Gets the application states for specified report configurations.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_GetFamilyIdentifier">GetFamilyIdentifier</a></td><td>
Gets the family identifier for the *osName*.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")![Static member](media/static.gif "Static member")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_GetSelectedApplicationsForPlatforms">GetSelectedApplicationsForPlatforms</a></td><td>
Gets the selected applications for platforms.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_GetTargetModuleIds">GetTargetModuleIds</a></td><td>
Gets the target module ids.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_IsRedOrAmber">IsRedOrAmber</a></td><td>
Determines whether algorithm has red or amber rag.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider_LoadTargetModuleIds">LoadTargetModuleIds</a></td><td>
Loads the target module ids.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#xenanalysisdataprovider-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected field](media/protfield.gif "Protected field")</td><td><a href="F_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenAnalysisDataProvider__targetModuleIds">_targetModuleIds</a></td><td>
Modules required for a target platform analysis</td></tr></table>&nbsp;
<a href="#xenanalysisdataprovider-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br /><a href="T_Citrix_SDK_AppDNA_Interfaces_IAnalysisDataProvider">Citrix.SDK.AppDNA.Interfaces.IAnalysisDataProvider</a><br />