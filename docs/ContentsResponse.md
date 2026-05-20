
# ContentsResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**FileLinksResponse**](FileLinksResponse.md) |  |  [optional]
**content** | **String** | &#x60;content&#x60; is populated when &#x60;type&#x60; is &#x60;file&#x60;, otherwise null |  [optional]
**downloadUrl** | **String** | DownloadURL is the direct download URL for this file |  [optional]
**encoding** | **String** | &#x60;encoding&#x60; is populated when &#x60;type&#x60; is &#x60;file&#x60;, otherwise null |  [optional]
**gitUrl** | **String** | GitURL is the Git API URL for this blob or tree |  [optional]
**htmlUrl** | **String** | HTMLURL is the web URL for this file or directory |  [optional]
**lastAuthorDate** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**lastCommitMessage** | **String** | LastCommitMessage is the message of the last commit that affected this file |  [optional]
**lastCommitSha** | **String** | LastCommitSHA is the SHA of the last commit that affected this file |  [optional]
**lastCommitterDate** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**lfsOid** | **String** | LfsOid is the Git LFS object ID if this file is stored in LFS |  [optional]
**lfsSize** | **Long** | LfsSize is the file size if this file is stored in LFS |  [optional]
**name** | **String** | Name is the file or directory name |  [optional]
**path** | **String** | Path is the full path to the file or directory |  [optional]
**sha** | **String** | SHA is the Git blob or tree SHA |  [optional]
**size** | **Long** | Size is the file size in bytes |  [optional]
**submoduleGitUrl** | **String** | &#x60;submodule_git_url&#x60; is populated when &#x60;type&#x60; is &#x60;submodule&#x60;, otherwise null |  [optional]
**target** | **String** | &#x60;target&#x60; is populated when &#x60;type&#x60; is &#x60;symlink&#x60;, otherwise null |  [optional]
**type** | **String** | &#x60;type&#x60; will be &#x60;file&#x60;, &#x60;dir&#x60;, &#x60;symlink&#x60;, or &#x60;submodule&#x60; |  [optional]
**url** | **String** | URL is the API URL for this file or directory |  [optional]



