
# DeployKey

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) | Created is the time when the deploy-key was added |  [optional]
**fingerprint** | **String** | Fingerprint is the key&#39;s fingerprint |  [optional]
**id** | **Long** | ID is the unique identifier for the deploy-key |  [optional]
**key** | **String** | Key contains the actual SSH key content |  [optional]
**keyId** | **Long** | KeyID is the associated public key ID |  [optional]
**keyType** | [**KeyTypeEnum**](#KeyTypeEnum) | Type tells whether the key authenticates over SSH or with a token over HTTPS |  [optional]
**readOnly** | **Boolean** | ReadOnly indicates if the key has read-only access |  [optional]
**repository** | [**Repository**](Repository.md) |  |  [optional]
**title** | **String** | Title is the human-readable name for the key |  [optional]
**token** | **String** | Token is the plaintext token of an HTTPS key, only returned when it is created |  [optional]
**url** | **String** | URL is the API URL for this deploy-key |  [optional]


<a name="KeyTypeEnum"></a>
## Enum: KeyTypeEnum
Name | Value
---- | -----
SSH | &quot;ssh&quot;
TOKEN | &quot;token&quot;



