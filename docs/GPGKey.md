
# GPGKey

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**canCertify** | **Boolean** | Whether the key can be used for certification |  [optional]
**canEncryptComms** | **Boolean** | Whether the key can be used for encrypting communications |  [optional]
**canEncryptStorage** | **Boolean** | Whether the key can be used for encrypting storage |  [optional]
**canSign** | **Boolean** | Whether the key can be used for signing |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**emails** | [**List&lt;GPGKeyEmail&gt;**](GPGKeyEmail.md) | List of email addresses associated with this GPG key |  [optional]
**expiresAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**id** | **Long** | The unique identifier of the GPG key |  [optional]
**keyId** | **String** | The key ID of the GPG key |  [optional]
**primaryKeyId** | **String** | The primary key ID of the GPG key |  [optional]
**publicKey** | **String** | The public key content in armored format |  [optional]
**subkeys** | [**List&lt;GPGKey&gt;**](GPGKey.md) | List of subkeys of this GPG key |  [optional]
**verified** | **Boolean** | Whether the GPG key has been verified |  [optional]



