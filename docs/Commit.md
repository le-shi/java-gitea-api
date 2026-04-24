
# Commit

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**author** | [**User**](User.md) |  |  [optional]
**commit** | [**RepoCommit**](RepoCommit.md) |  |  [optional]
**committer** | [**User**](User.md) |  |  [optional]
**created** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**files** | [**List&lt;CommitAffectedFiles&gt;**](CommitAffectedFiles.md) | Files contains information about files affected by the commit |  [optional]
**htmlUrl** | **String** | HTMLURL is the web URL for viewing the commit |  [optional]
**parents** | [**List&lt;CommitMeta&gt;**](CommitMeta.md) | Parents contains the parent commit information |  [optional]
**sha** | **String** | SHA is the commit SHA hash |  [optional]
**stats** | [**CommitStats**](CommitStats.md) |  |  [optional]
**url** | **String** | URL is the API URL for the commit |  [optional]



