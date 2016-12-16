# AppVPackageManager.Validate Method 
 

Determines whether an App-V package has errors

**Namespace:**&nbsp;<a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Sequence">Citrix.SDK.AppDNA.Solutions.AppV.Sequence</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.AppV (in Citrix.SDK.AppDNA.Solutions.AppV.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

###C#
```csharp
public List<SequenceIssue> Validate(
	string log
)
```

###VB
```vbnet
Public Function Validate ( 
	log As String
) As List(Of SequenceIssue)
```


#### Parameters
&nbsp;<dl><dt>log</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />App-V package's log as list of <a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Sequence_SequenceIssue">SequenceIssue</a></dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/6sh2ey19" target="_blank">List</a>(<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Sequence_SequenceIssue">SequenceIssue</a>)<br />list of errors

## See Also


#### Reference
<a href="T_Citrix_SDK_AppDNA_Solutions_AppV_Sequence_AppVPackageManager">AppVPackageManager Class</a><br /><a href="N_Citrix_SDK_AppDNA_Solutions_AppV_Sequence">Citrix.SDK.AppDNA.Solutions.AppV.Sequence Namespace</a><br />