---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

var graphClient = new GraphServiceClient(requestAdapter);

var result = await graphClient.Users["{user-id}"].GetAsync((requestConfiguration) =>
{
	requestConfiguration.QueryParameters.Select = new string []{ "ext55gb1l09_msLearnCourses" };
});


```