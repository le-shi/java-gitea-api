
# CreateUserOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) | For explicitly setting the user creation timestamp. Useful when users are migrated from other systems. When omitted, the user&#39;s creation timestamp will be set to \&quot;now\&quot;. |  [optional]
**email** | **String** |  | 
**fullName** | **String** | The full display name of the user |  [optional]
**loginName** | **String** | identifier of the user, provided by the external authenticator (if configured) |  [optional]
**mustChangePassword** | **Boolean** | Whether the user must change password on first login |  [optional]
**password** | **String** | The plain text password for the user |  [optional]
**restricted** | **Boolean** | Whether the user has restricted access privileges |  [optional]
**sendNotify** | **Boolean** | Whether to send welcome notification email to the user |  [optional]
**sourceId** | **Long** | The authentication source ID to associate with the user |  [optional]
**username** | **String** | username of the user | 
**visibility** | **String** | User visibility level: public, limited, or private |  [optional]



