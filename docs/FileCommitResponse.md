
# FileCommitResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**author** | [**CommitUser**](CommitUser.md) |  |  [optional]
**committer** | [**CommitUser**](CommitUser.md) |  |  [optional]
**created** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**htmlUrl** | **String** | HTMLURL is the web URL for viewing this commit |  [optional]
**message** | **String** | Message is the commit message |  [optional]
**parents** | [**List&lt;CommitMeta&gt;**](CommitMeta.md) | Parents contains parent commit metadata |  [optional]
**sha** | **String** | SHA is the commit SHA hash |  [optional]
**tree** | [**CommitMeta**](CommitMeta.md) |  |  [optional]
**url** | **String** | URL is the API URL for the commit |  [optional]



