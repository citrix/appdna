# Application.Import Method (String, Boolean)
 

Imports an <a href="T_Citrix_SDK_AppDNA_Application">Application</a> object directly from the source file into previously created application.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public Application Import(
	string applicationPath,
	bool overwrite
)
```

###VB
```vbnet
Public Function Import ( 
	applicationPath As String,
	overwrite As Boolean
) As Application
```


#### Parameters
&nbsp;<dl><dt>applicationPath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The full path to the file to import.</dd><dt>overwrite</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />If set to true, the application information (Name, Manufacturer, Version) will replace the current application (false by default).</dd></dl>

#### Return Value
Type: <a href="T_Citrix_SDK_AppDNA_Application">Application</a><br />The imported application.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Application">Application Class</a><br /><a href="Overload_Citrix_SDK_AppDNA_Application_Import">Import Overload</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />