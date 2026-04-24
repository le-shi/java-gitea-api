
# PublicKey

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**fingerprint** | **String** | Fingerprint is the key&#39;s fingerprint |  [optional]
**id** | **Long** | ID is the unique identifier for the public key |  [optional]
**key** | **String** | Key contains the actual SSH public key content |  [optional]
**keyType** | **String** | KeyType indicates the type of the SSH key |  [optional]
**lastUsedAt** | [**OffsetDateTime**](OffsetDateTime.md) | Updated is the time when the key was last used |  [optional]
**readOnly** | **Boolean** | ReadOnly indicates if the key has read-only access |  [optional]
**title** | **String** | Title is the human-readable name for the key |  [optional]
**url** | **String** | URL is the API URL for this key |  [optional]
**user** | [**User**](User.md) |  |  [optional]



