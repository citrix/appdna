#Use application attributesUse application attributes to assign user-defined values to applications in AppDNA. This is useful when using AppDNA as a decision-making tool. For example, an application may have an attribute that defines its owner and their email address. After importing and analyzing the application, you can use the report value to generate an email to send to the application owner for the next action.Application attributes have two important parts:1.	**An ApplicationAttributeDefinition**. This defines what type of values can be assigned to an application, including a name, description and other properties.2.	The **value** assigned to each application for a given attribute definition.Therefore, an application attribute links an application and an ApplicationAttributeDefinition together with a value.##Create an ApplicationAttributeDefinitionYou create an ApplicationAttributeDefinition using the object returned from the Server.ApplicationAttributeDefinition. For example:
```using AppDNA = Citrix.SDK.AppDNA;
AppDNA.Server appdna;
appdna = login.AppDNAServer;var definition =
appdna.ApplicationAttributeDefinition.CreateStringDefinition("ApplicationOwner", "Application Owner",
	false,
	AppDNA.AttributeDefinitionVisibilities.ShowInAppList,
	0);```
Similarly, you retrieve an existing definition as follows:
```
definition = appdna.ApplicationAttributeDefinition.Get("ApplicationOwner");
```
##Set and retrieve valuesUse an Application object to assign a value for a given ApplicationAttributeDefinition. For example:
```
AppDNA.ApplicationAttribute SetAttributeValue(AppDNA.Application app, AppDNA.ApplicationAttrributeDefinition definition, string value)
{
	return app.SetAttribute(definition.Identifier, value);
}
```Use a property of the Application class to retrieve a collection of application attributes set for that application.Note: the Application.Attributes property includes only application attribute objects for definitions used to set a value on the application; unused objects are not included.From the ApplicationAttribute, you can retrieve the value and the ApplicationAttributeDefinition. For example:
```void PrintApplicationAttributes(AppDNA.Application app)
{
	foreach (var attribute in app.Attributes)
	{
		string valueString = string.Empty;
		if (attribute.IsNull)
			valueString = "<null>";
		else
		{
			switch (attribute.Definition.DataType)
			{
				case AppDNA.AttributeDefinitionDataType.Boolean:
					valueString = attribute.BooleanValue.ToString();
					break;
				case AppDNA.AttributeDefinitionDataType.DateTime:
					valueString = attribute.DateTimeValue.ToString();
					break;
				case AppDNA.AttributeDefinitionDataType.Numeric:
						valueString =attribute.NumericValue.ToString();
						break;
				case AppDNA.AttributeDefinitionDataType.Rag:
						valueString = attribute.RagValue.ToString();
						break;
				case AppDNA.AttributeDefinitionDataType.String:
				case AppDNA.AttributeDefinitionDataType.StringList:
						valueString = attribute.StringValue;
						break;
			}
		}
		Console.WriteLine(attribute.Definition.Name + " : " + valueString);
	}
}
```