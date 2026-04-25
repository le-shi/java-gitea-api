
# Repository

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowFastForwardOnlyMerge** | **Boolean** |  |  [optional]
**allowManualMerge** | **Boolean** |  |  [optional]
**allowMergeCommits** | **Boolean** |  |  [optional]
**allowRebase** | **Boolean** |  |  [optional]
**allowRebaseExplicit** | **Boolean** |  |  [optional]
**allowRebaseUpdate** | **Boolean** |  |  [optional]
**allowSquashMerge** | **Boolean** |  |  [optional]
**archived** | **Boolean** |  |  [optional]
**archivedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**autodetectManualMerge** | **Boolean** |  |  [optional]
**avatarUrl** | **String** |  |  [optional]
**cloneUrl** | **String** |  |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**defaultAllowMaintainerEdit** | **Boolean** |  |  [optional]
**defaultBranch** | **String** |  |  [optional]
**defaultDeleteBranchAfterMerge** | **Boolean** |  |  [optional]
**defaultMergeStyle** | **String** |  |  [optional]
**description** | **String** |  |  [optional]
**empty** | **Boolean** |  |  [optional]
**externalTracker** | [**ExternalTracker**](ExternalTracker.md) |  |  [optional]
**externalWiki** | [**ExternalWiki**](ExternalWiki.md) |  |  [optional]
**fork** | **Boolean** |  |  [optional]
**forksCount** | **Long** |  |  [optional]
**fullName** | **String** |  |  [optional]
**hasActions** | **Boolean** |  |  [optional]
**hasCode** | **Boolean** |  |  [optional]
**hasIssues** | **Boolean** |  |  [optional]
**hasPackages** | **Boolean** |  |  [optional]
**hasProjects** | **Boolean** |  |  [optional]
**hasPullRequests** | **Boolean** |  |  [optional]
**hasReleases** | **Boolean** |  |  [optional]
**hasWiki** | **Boolean** |  |  [optional]
**htmlUrl** | **String** |  |  [optional]
**id** | **Long** |  |  [optional]
**ignoreWhitespaceConflicts** | **Boolean** |  |  [optional]
**internal** | **Boolean** |  |  [optional]
**internalTracker** | [**InternalTracker**](InternalTracker.md) |  |  [optional]
**language** | **String** |  |  [optional]
**languagesUrl** | **String** |  |  [optional]
**licenses** | **List&lt;String&gt;** |  |  [optional]
**link** | **String** |  |  [optional]
**mirror** | **Boolean** |  |  [optional]
**mirrorInterval** | **String** |  |  [optional]
**mirrorUpdated** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**name** | **String** |  |  [optional]
**objectFormatName** | [**ObjectFormatNameEnum**](#ObjectFormatNameEnum) | ObjectFormatName of the underlying git repository |  [optional]
**openIssuesCount** | **Long** |  |  [optional]
**openPrCounter** | **Long** |  |  [optional]
**originalUrl** | **String** |  |  [optional]
**owner** | [**User**](User.md) |  |  [optional]
**parent** | [**Repository**](Repository.md) |  |  [optional]
**permissions** | [**Permission**](Permission.md) |  |  [optional]
**_private** | **Boolean** |  |  [optional]
**projectsMode** | **String** |  |  [optional]
**releaseCounter** | **Long** |  |  [optional]
**repoTransfer** | [**RepoTransfer**](RepoTransfer.md) |  |  [optional]
**size** | **Long** |  |  [optional]
**sshUrl** | **String** |  |  [optional]
**starsCount** | **Long** |  |  [optional]
**template** | **Boolean** |  |  [optional]
**topics** | **List&lt;String&gt;** |  |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**url** | **String** |  |  [optional]
**watchersCount** | **Long** |  |  [optional]
**website** | **String** |  |  [optional]


<a name="ObjectFormatNameEnum"></a>
## Enum: ObjectFormatNameEnum
Name | Value
---- | -----
SHA1 | &quot;sha1&quot;
SHA256 | &quot;sha256&quot;



