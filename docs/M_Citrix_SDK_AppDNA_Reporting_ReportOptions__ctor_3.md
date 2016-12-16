# ReportOptions Constructor (ReportType, String, String, String, Boolean, Boolean, IEnumerable(ReportDescription))
 

Initializes a new instance of the <a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">ReportOptions</a> class.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Reporting">Citrix.SDK.AppDNA.Reporting</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public ReportOptions(
	ReportType reportType,
	string moduleIdentifier,
	string title,
	string pageUrlName,
	bool changeSelectionAllowed,
	bool isTopLevel,
	IEnumerable<ReportDescription> reportViews
)
```

###VB
```vbnet
Public Sub New ( 
	reportType As ReportType,
	moduleIdentifier As String,
	title As String,
	pageUrlName As String,
	changeSelectionAllowed As Boolean,
	isTopLevel As Boolean,
	reportViews As IEnumerable(Of ReportDescription)
)
```


#### Parameters
&nbsp;<dl><dt>reportType</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportType">Citrix.SDK.AppDNA.ReportType</a><br />Type of the report.</dd><dt>moduleIdentifier</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The module identifier.</dd><dt>title</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The report title.</dd><dt>pageUrlName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Name of the report page.</dd><dt>changeSelectionAllowed</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />if set to `true` [change selection allowed].</dd><dt>isTopLevel</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />if set to `true` [is top level].</dd><dt>reportViews</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Reporting_ReportDescription">ReportDescription</a>)<br />The report views.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Reporting_ReportOptions">ReportOptions Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Reporting_ReportOptions__ctor">ReportOptions Overload</a><br /><a href="N_Citrix_SDK_AppDNA_Reporting">Citrix.SDK.AppDNA.Reporting Namespace</a><br />