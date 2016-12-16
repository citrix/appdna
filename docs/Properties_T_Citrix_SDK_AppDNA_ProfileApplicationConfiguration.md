# ProfileApplicationConfiguration Properties
 

The <a href="T_Citrix_SDK_AppDNA_ProfileApplicationConfiguration">ProfileApplicationConfiguration</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_AutoAnalyseAllModules">AutoAnalyseAllModules</a></td><td>
Specify true to start the analysis automatically after the import is finished.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureConfiguration_ExecutionProfileName">ExecutionProfileName</a></td><td>
The name of an already configured VM Execution Profile.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">InstallCaptureConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_GeneratedMsiFolder">GeneratedMsiFolder</a></td><td>
If the import needs to generate an msi during the import process, such as when importing an SFT or App-V file, the intermediate msi files will be saved to this location. If this is null, then no files are saved.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureConfiguration_HideUserInterface">HideUserInterface</a></td><td>
Set this to true to hide the controls for the execution profile and the VM console. IMPORTANT: The <a href="P_Citrix_SDK_AppDNA_InstallCaptureSourceDetails_InstallCommand">InstallCommand</a> property of each <a href="T_Citrix_SDK_AppDNA_InstallCaptureSourceDetails">InstallCaptureSourceDetails</a> must be set to do an unattended installation of the software. If necessary, you can use the VM provider's software to access the VM console independently of AppDNA to troubleshoot when the Install Capture has stalled.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">InstallCaptureConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_IceValidationConfig">IceValidationConfig</a></td><td>
An optional configuration for ICE validation. Can be null.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_ModulesToAnalyse">ModulesToAnalyse</a></td><td>
A list of modules to automatically analyse
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_OutputFolder">OutputFolder</a></td><td>
The full path to the folder into which the output of the import process is to be placed.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureConfiguration_Replaceables">Replaceables</a></td><td>
A Dictionary of replaceable names to values, which can be used to override the execution profile replaceables.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">InstallCaptureConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_SaveDetailedLogs">SaveDetailedLogs</a></td><td>
Specify true to save intermediate files. Useful for troubleshooting.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ApplicationImportConfiguration_SynchronizationContext">SynchronizationContext</a></td><td>
A SynchronizationContext used to control the thread on which notifications are raised.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_ApplicationImportConfiguration">ApplicationImportConfiguration</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_ProfileApplicationConfiguration_VM">VM</a></td><td>
VM configuration used to profile an application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_InstallCaptureConfiguration_VMConfigurationName">VMConfigurationName</a></td><td>
The name of an already configured VM Configuration.
 (Inherited from <a href="T_Citrix_SDK_AppDNA_InstallCaptureConfiguration">InstallCaptureConfiguration</a>.)</td></tr></table>&nbsp;
<a href="#profileapplicationconfiguration-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ProfileApplicationConfiguration">ProfileApplicationConfiguration Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />