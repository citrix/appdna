# ApplicationAlgorithmResult.Results Property 
 

Gets a <a href="http://msdn2.microsoft.com/en-us/library/9186hy08" target="_blank">DataTable</a> that holds the details of the application data that triggered the algorithm. `null` if the algorithm did not trigger or the results are not available.

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA (in Citrix.SDK.AppDNA.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public DataTable Results { get; }
```

###VB
```vbnet
Public ReadOnly Property Results As DataTable
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/9186hy08" target="_blank">DataTable</a>

## Remarks
There will be a column for each relevant field and one row for each trigger of the algorithm.

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_ApplicationAlgorithmResult">ApplicationAlgorithmResult Class</a><br /><a href="N_Citrix_SDK_AppDNA">Citrix.SDK.AppDNA Namespace</a><br />