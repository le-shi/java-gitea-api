
# CreateTeamOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**canCreateOrgRepo** | **Boolean** | Whether the team can create repositories in the organization |  [optional]
**description** | **String** | The description of the team |  [optional]
**includesAllRepositories** | **Boolean** | Whether the team has access to all repositories in the organization |  [optional]
**name** | **String** |  | 
**permission** | [**PermissionEnum**](#PermissionEnum) | All units have this permission (read/write/admin) |  [optional]
**units** | **List&lt;String&gt;** | Deprecated: This variable should be replaced by UnitsMap and will be dropped in later versions. |  [optional]
**unitsMap** | **Map&lt;String, String&gt;** |  |  [optional]
**visibility** | [**VisibilityEnum**](#VisibilityEnum) | Team visibility within the organization. Defaults to \&quot;private\&quot;. |  [optional]


<a name="PermissionEnum"></a>
## Enum: PermissionEnum
Name | Value
---- | -----
READ | &quot;read&quot;
WRITE | &quot;write&quot;
ADMIN | &quot;admin&quot;


<a name="VisibilityEnum"></a>
## Enum: VisibilityEnum
Name | Value
---- | -----
PUBLIC | &quot;public&quot;
LIMITED | &quot;limited&quot;
PRIVATE | &quot;private&quot;



