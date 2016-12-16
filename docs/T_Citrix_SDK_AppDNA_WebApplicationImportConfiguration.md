# WebApplicationImportConfiguration Class
 

Holds configuration datails for a web application import


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">Citrix.SDK.AppDNA.ApplicationImportConfiguration</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.WebApplicationImportConfiguration<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class WebApplicationImportConfiguration : ApplicationImportConfiguration
```

###VB
```vbnet
Public Class WebApplicationImportConfiguration
	Inherits ApplicationImportConfiguration
```

The WebApplicationImportConfiguration type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_WebApplicationImportConfiguration__ctor">WebApplicationImportConfiguration</a></td><td>
An instance constructor.</td></tr></table>&nbsp;
<a href="#webapplicationimportconfiguration-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_AutoAnalyseAllModules">AutoAnalyseAllModules</a></td><td>
Specify true to start the analysis automatically after the import is finished.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_GeneratedMsiFolder">GeneratedMsiFolder</a></td><td>
If the import needs to generate an msi during the import process, such as when importing an SFT or App-V file, the intermediate msi files will be saved to this location. If this is null, then no files are saved.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_IceValidationConfig">IceValidationConfig</a></td><td>
An optional configuration for ICE validation. Can be null.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebApplicationImportConfiguration_Mode">Mode</a></td><td>
Indicates in which way web applications are imported.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_ModulesToAnalyse">ModulesToAnalyse</a></td><td>
A list of modules to automatically analyse
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_OutputFolder">OutputFolder</a></td><td>
The full path to the folder into which the output of the import process is to be placed.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_SaveDetailedLogs">SaveDetailedLogs</a></td><td>
Specify true to save intermediate files. Useful for troubleshooting.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebApplicationImportConfiguration_SpiderSettings">SpiderSettings</a></td><td>
Contains Spider settings used to capture web applications from URLs</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_SynchronizationContext">SynchronizationContext</a></td><td>
A SynchronizationContext used to control the thread on which notifications are raised.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr></table>&nbsp;
<a href="#webapplicationimportconfiguration-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#webapplicationimportconfiguration-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />