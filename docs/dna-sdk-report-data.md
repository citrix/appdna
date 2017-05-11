#Use report data

	AppDNA.Server appdna;













report.Export( targetFilename, AppDNA.ReportType.EstateView, AppDNA.ReportExportFormat.MimeHMimeHtml, TimeSpan.FromMinutes(5) );

AppDNA.Server appdna;

In addition to exporting pre-defined report views, the Report object provides access to detailed information about each application and algorithm combination, as well as aggregated information for each application over all enabled algorithms in the ReportConfiguration.

To access the aggregated information for a given application, use the object stored in the ByApplication property.

```
public void Report(AppDNA.Application app)












Detailed results for each Application and Algorithm combination are available using the ByApplication collection or its equivalent ByAlgorithm collection. The ByAlgorithm collection contains ReportedAlgorithm objects; for example:

```
AppDNA.ReportedAlgorithm algResult = report.ByAlgorithm["x32_001"];

```
- A ReportedAlgorithm object has a ResultsByApplication property. This returns a collection that can be enumerated or indexed by Application.

AppDNA.ApplicationAlgorithmResult appAndAlg = report.ByApplication[app].ResultsByAlgorithm["x32_001"]

If the parent ReportedApplication.RAG property is Unanalyzed or Locked, the ApplicationAlgorithmResult will have no useful data and its RAG property will be green. For example:

```
foreach (var reportedApp in report.ByApplication)

















