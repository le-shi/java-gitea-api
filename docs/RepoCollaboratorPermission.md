
# RepoCollaboratorPermission

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**permission** | [**PermissionEnum**](#PermissionEnum) | Permission level of the collaborator none AccessLevelNameNone read AccessLevelNameRead write AccessLevelNameWrite admin AccessLevelNameAdmin owner AccessLevelNameOwner |  [optional]
**roleName** | **String** | RoleName is the name of the permission role |  [optional]
**user** | [**User**](User.md) |  |  [optional]


<a name="PermissionEnum"></a>
## Enum: PermissionEnum
Name | Value
---- | -----
NONE | &quot;none&quot;
READ | &quot;read&quot;
WRITE | &quot;write&quot;
ADMIN | &quot;admin&quot;
OWNER | &quot;owner&quot;



