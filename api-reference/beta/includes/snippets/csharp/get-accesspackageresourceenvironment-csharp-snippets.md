---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var accessPackageResourceEnvironment = await graphClient.IdentityGovernance.EntitlementManagement.AccessPackageResourceEnvironments["{accessPackageResourceEnvironmentId}"]
	.Request()
	.GetAsync();

```