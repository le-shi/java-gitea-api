
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
**units** | **List&lt;String&gt;** | Deprecated: This variable should be replaced by UnitsMap and will be dropped in later versions. |  [optional]
**unitsMap** | **Map&lt;String, String&gt;** |  |  [optional]
**visibility** | [**VisibilityEnum**](#VisibilityEnum) | Team visibility within the organization. \&quot;private\&quot; teams are only listable by members and org owners; \&quot;limited\&quot; teams are listable by any organization member; \&quot;public\&quot; teams are listable by any signed-in user. |  [optional]


<a name="PermissionEnum"></a>
## Enum: PermissionEnum
Name | Value
---- | -----
NONE | &quot;none&quot;
READ | &quot;read&quot;
WRITE | &quot;write&quot;
ADMIN | &quot;admin&quot;
OWNER | &quot;owner&quot;


<a name="VisibilityEnum"></a>
## Enum: VisibilityEnum
Name | Value
---- | -----
PUBLIC | &quot;public&quot;
LIMITED | &quot;limited&quot;
PRIVATE | &quot;private&quot;



