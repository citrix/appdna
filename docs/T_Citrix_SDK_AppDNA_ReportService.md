# ReportService Class
 

This class is accessible from <a href="P_Citrix_SDK_AppDNA_Server_Report">Report</a> property and provides access to report-related functionality.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.ReportService<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class ReportService
```

###VB
```vbnet
Public Class ReportService
```

The ReportService type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediation">ExportApplicationRemediation(String, ReportExportFormat, Application, IEnumerable(ReportConfiguration))</a></td><td>
Exports the Application Remediation report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediation_2">ExportApplicationRemediation(String, ReportExportFormat, Application, IEnumerable(String))</a></td><td>
Exports the Application Remediation report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediation_1">ExportApplicationRemediation(String, ReportExportFormat, Application, IEnumerable(ReportConfiguration), OSImage, OSImage, TimeSpan)</a></td><td>
Exports the Application Remediation report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediation_3">ExportApplicationRemediation(String, ReportExportFormat, Application, IEnumerable(String), OSImage, OSImage, TimeSpan)</a></td><td>
Exports the Application Remediation report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediationActions">ExportApplicationRemediationActions(String, ReportExportFormat, Application, IEnumerable(ReportConfiguration))</a></td><td>
Exports the Application Remediation Actions report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediationActions_2">ExportApplicationRemediationActions(String, ReportExportFormat, Application, IEnumerable(String))</a></td><td>
Exports the Application Remediation Actions report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediationActions_1">ExportApplicationRemediationActions(String, ReportExportFormat, Application, IEnumerable(ReportConfiguration), OSImage, OSImage, TimeSpan)</a></td><td>
Exports the Application Remediation Actions report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_ExportApplicationRemediationActions_3">ExportApplicationRemediationActions(String, ReportExportFormat, Application, IEnumerable(String), OSImage, OSImage, TimeSpan)</a></td><td>
Exports the Application Remediation Actions report for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_6">Get(String)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all analyzed application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get">Get(ReportConfiguration)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_8">Get(String, IEnumerable(Application))</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_2">Get(ReportConfiguration, IEnumerable(Application))</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_7">Get(String, OSImage, OSImage)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all analyzed application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_10">Get(String, IEnumerable(Application), IEnumerable(Algorithm))</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results against a specific set of algorithms for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_1">Get(ReportConfiguration, OSImage, OSImage)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to all application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_4">Get(ReportConfiguration, IEnumerable(Application), IEnumerable(Algorithm))</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results against a specific set of algorithms for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_9">Get(String, IEnumerable(Application), OSImage, OSImage)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_3">Get(ReportConfiguration, IEnumerable(Application), OSImage, OSImage)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_11">Get(String, IEnumerable(Application), IEnumerable(Algorithm), OSImage, OSImage)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results against a specific set of algorithms for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_Get_5">Get(ReportConfiguration, IEnumerable(Application), IEnumerable(Algorithm), OSImage, OSImage)</a></td><td>
Return a <a href="T_Citrix_SDK_AppDNA_Report">Report</a> for a given <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>, providing access to a specific set of application results against a specific set of algorithms for that <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_GetApplicationRemediationIssuesUrl">GetApplicationRemediationIssuesUrl</a></td><td>
Gets the Application Remediation report Url for the specified application, optionally combining the results from multiple report configurations.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_ReportService_RegenerateRepository">RegenerateRepository</a></td><td>
Regenerates the repository.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#reportservice-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />