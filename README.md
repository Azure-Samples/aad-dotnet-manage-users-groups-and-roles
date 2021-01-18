---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
  services: Graph-Rbac
  platforms: dotnet
---

# Getting started on managing users and groups using C# #

 Azure Users, Groups and Roles sample.
 - Create a user
 - Assign role to AD user
 - Revoke role from AD user
 - Get role by scope and role name
 - Create service principal
 - Assign role to service principal
 - Create 2 Active Directory groups
 - Add the user, the service principal, and the 1st group as members of the 2nd group


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/aad-dotnet-manage-users-groups-and-roles.git

    cd aad-dotnet-manage-users-groups-and-roles

    dotnet build

    bin\Debug\net452\ManageUsersGroupsAndRoles.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.