# WebCaptureSettings Class
 

Represents settings for capturing web applications via Directed Spider


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Citrix.SDK.AppDNA.WebCaptureSettings<br />
**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public class WebCaptureSettings
```

###VB
```vbnet
Public Class WebCaptureSettings
```

The WebCaptureSettings type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Citrix_SDK_AppDNA_WebCaptureSettings__ctor">WebCaptureSettings</a></td><td>
Initializes a new instance of the WebCaptureSettings class</td></tr></table>&nbsp;
<a href="#webcapturesettings-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_AcceptCertificateWhenWarned">AcceptCertificateWhenWarned</a></td><td>
Indication that the spider should tell IE to always accept certificate when the IE comes accross one</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_AllowDuplicates">AllowDuplicates</a></td><td>
Indicates whether spider captures pages with the same Url</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_AllowProxyPopup">AllowProxyPopup</a></td><td>
Indicates that even though autoCloseDialogsAndPopups is set, the proxy dialog should not be restricted</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_AutoClose">AutoClose</a></td><td>
Auto close the spider when launched in gui mode</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_AutoCloseDialogsAndPopups">AutoCloseDialogsAndPopups</a></td><td>
Indication that the spider should attempt to detect and close browser popup dialogs</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_AutoStart">AutoStart</a></td><td>
Automatically press the start button when spider launched in gui mode</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_BrowserTimout">BrowserTimout</a></td><td>
Default timeout for watin</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_CaptureDelaySize">CaptureDelaySize</a></td><td>
Gets size of hte delay between capture next page in miliseconds</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_CaptureOutputDirectory">CaptureOutputDirectory</a></td><td>
This sets the default place to move the data to</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_ContentStorePageDirectory">ContentStorePageDirectory</a></td><td>
The folder name within the content store root directory that contains the saved pages</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_ContentStoreRoot">ContentStoreRoot</a></td><td>
The root directory prefix that the content store is located at</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_DelayCapturing">DelayCapturing</a></td><td>
Indicates whether allows delay between navigation to the next page, uses for prevent blocking Spider by firewalls</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_DelayPageCompletionCheckBy">DelayPageCompletionCheckBy</a></td><td>
Indicates how long the spider should delay before wiating for the page to load.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_Depth">Depth</a></td><td>
This sets the default depth to which to spider down to</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_DetectForms">DetectForms</a></td><td>
Determines wheather the spider is interrupted, to ask the user to fill forms in</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_DuplicatesCountForUrl">DuplicatesCountForUrl</a></td><td>
Gets or sets allowed number of duplicates for each url</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_DuplicatesDifference">DuplicatesDifference</a></td><td>
Gets or sets level of the differnce to determine page as duplicated (0 is minimum - spider will capture even the same pages, 100 is maximum - pages should be fully different to capture it)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_IncludeSubdomains">IncludeSubdomains</a></td><td>
User setting that indicates to the spider that provided domains in the inclusion domain section of the settings should be used</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_InclusionDomains">InclusionDomains</a></td><td>
list of URLs that the user has specified that are domains that will be visited, even though out of the current domain</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_MustGenerateMSI">MustGenerateMSI</a></td><td>
Flag that indicates that the spider should generate an MSI of the web capture content. This is based on a user setting</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_RestrictToLastVirtualDirectory">RestrictToLastVirtualDirectory</a></td><td>
Setting that indicates that only the last vistual directory in the provided URL should be spidered. ie only the folder that the webapp is in</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_ShowPageCaptureErrorsInManualMode">ShowPageCaptureErrorsInManualMode</a></td><td>
Defines whether page capture errors will be shown in manual mode, in automatic mode the setting is ignored</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_Urls">Urls</a></td><td>
List of Urls that the spider has been asked to traverse</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_UseGui">UseGui</a></td><td>
When run in cmd line mode, this setting can cuase the GUI frontend to be used</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Citrix_SDK_AppDNA_WebCaptureSettings_UseManual">UseManual</a></td><td>
This disables the spider.</td></tr></table>&nbsp;
<a href="#webcapturesettings-class">Back to Top</a>

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
<a href="#webcapturesettings-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />