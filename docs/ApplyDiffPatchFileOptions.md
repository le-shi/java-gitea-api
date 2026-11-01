
# ApplyDiffPatchFileOptions

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**author** | [**Identity**](Identity.md) |  |  [optional]
**branch** | **String** | branch (optional) is the base branch for the changes. If not supplied, the default branch is used |  [optional]
**committer** | [**Identity**](Identity.md) |  |  [optional]
**content** | **String** |  | 
**dates** | [**CommitDateOptions**](CommitDateOptions.md) |  |  [optional]
**forcePush** | **Boolean** | force_push (optional) will do a force-push if the new branch already exists |  [optional]
**message** | **String** | message (optional) is the commit message of the changes. If not supplied, a default message will be used |  [optional]
**newBranch** | **String** | new_branch (optional) will make a new branch from base branch for the changes. If not supplied, the changes will be committed to the base branch |  [optional]
**signoff** | **Boolean** | Add a Signed-off-by trailer by the committer at the end of the commit log message. |  [optional]



