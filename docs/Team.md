
# Team

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**canCreateOrgRepo** | **Boolean** | Whether the team can create repositories in the organization |  [optional]
**description** | **String** | The description of the team |  [optional]
**id** | **Long** | The unique identifier of the team |  [optional]
**includesAllRepositories** | **Boolean** | Whether the team has access to all repositories in the organization |  [optional]
**name** | **String** | The name of the team |  [optional]
**organization** | [**Organization**](Organization.md) |  |  [optional]
**permission** | [**PermissionEnum**](#PermissionEnum) |  |  [optional]
**units** | **List&lt;String&gt;** |  |  [optional]
**unitsMap** | **Map&lt;String, String&gt;** |  |  [optional]


<a name="PermissionEnum"></a>
## Enum: PermissionEnum
Name | Value
---- | -----
NONE | &quot;none&quot;
READ | &quot;read&quot;
WRITE | &quot;write&quot;
ADMIN | &quot;admin&quot;
OWNER | &quot;owner&quot;



