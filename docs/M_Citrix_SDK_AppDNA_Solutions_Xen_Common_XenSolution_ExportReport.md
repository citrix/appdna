# XenSolution.ExportReport Method 
 

Exports the report.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.Xen.Common (in Citrix.SDK.AppDNA.Solutions.Xen.Common.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public abstract void ExportReport(
	string fileName,
	ReportExportFormat format,
	TimeSpan timeout
)
```

###VB
```vbnet
Public MustOverride Sub ExportReport ( 
	fileName As String,
	format As ReportExportFormat,
	timeout As TimeSpan
)
```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Name of the file.</dd><dt>format</dt><dd>Type: <a href="T_Citrix_SDK_AppDNA_ReportExportFormat">Citrix.SDK.AppDNA.ReportExportFormat</a><br />The format of the report.</dd><dt>timeout</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The timeout.</dd></dl>

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_Xen_Common_XenSolution">XenSolution Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_Xen_Common">Citrix.SDK.AppDNA.Solutions.Xen.Common Namespace</a><br />