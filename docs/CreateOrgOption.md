
# CreateOrgOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **String** | The description of the organization |  [optional]
**email** | **String** | The email address of the organization |  [optional]
**fullName** | **String** | The full display name of the organization |  [optional]
**location** | **String** | The location of the organization |  [optional]
**repoAdminChangeTeamAccess** | **Boolean** | Whether repository administrators can change team access |  [optional]
**username** | **String** | username of the organization | 
**visibility** | [**VisibilityEnum**](#VisibilityEnum) | possible values are &#x60;public&#x60; (default), &#x60;limited&#x60; or &#x60;private&#x60; |  [optional]
**website** | **String** | The website URL of the organization |  [optional]


<a name="VisibilityEnum"></a>
## Enum: VisibilityEnum
Name | Value
---- | -----
PUBLIC | &quot;public&quot;
LIMITED | &quot;limited&quot;
PRIVATE | &quot;private&quot;



