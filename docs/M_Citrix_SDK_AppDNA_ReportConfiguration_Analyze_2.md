# ReportConfiguration.Analyze Method (IEnumerable(Application), PropertyChangedEventHandler, SynchronizationContext)
 

Triggers an analysis of the specified applications against this <a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration</a>.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Analysis Analyze(
	IEnumerable<Application> applications,
	PropertyChangedEventHandler propertyChangedHandler,
	SynchronizationContext context
)
```

###VB
```vbnet
Public Function Analyze ( 
	applications As IEnumerable(Of Application),
	propertyChangedHandler As PropertyChangedEventHandler,
	context As SynchronizationContext
) As Analysis
```


#### Parameters
&nbsp;<dl><dt>applications</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="T_Citrix_SDK_AppDNA_Application">Application</a>)<br />The collection applications to analyze.</dd><dt>propertyChangedHandler</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/hyza7z75" target="_blank">System.ComponentModel.PropertyChangedEventHandler</a><br />The event handler to be called when the state of the analysis changes.</dd><dt>context</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/wx31754f" target="_blank">System.Threading.SynchronizationContext</a><br />A SynchronizationContext that governs which thread any notification events are raised on. See the remarks of Application.Import for more details.</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Analysis">Analysis</a><br />An Analysis object which can be used to track the progress of the analysis.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ReportConfiguration">ReportConfiguration Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_ReportConfiguration_Analyze">Analyze Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />