# ReportRag Enumeration
 

Contains values that represent the state of an analyzed application.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public enum ReportRag
```

###VB
```vbnet
Public Enumeration ReportRag
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ReportRag.NonApplicable">**NonApplicable**</td><td>-2</td><td>Application result is not applicable in this case for a some external reason.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ReportRag.Unanalyzed">**Unanalyzed**</td><td>-1</td><td>Unanalyzed, indicating that the application has not been analyzed for the report.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ReportRag.Red">**Red**</td><td>10</td><td>Red, indicating a serious problem.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ReportRag.Amber">**Amber**</td><td>5</td><td>Amber, indicating a possible problem.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ReportRag.Green">**Green**</td><td>0</td><td>Green, indicating no problem or a minor problem.</td></tr><tr><td /><td target="F:Citrix.SDK.AppDNA.ReportRag.Locked">**Locked**</td><td>99</td><td>Locked, indicating that the application has not been licensed for the report.</td></tr></table>

## See Also


#### Reference
<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />