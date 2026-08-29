
# MergePullRequestOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**deleteBranchAfterMerge** | **Boolean** |  |  [optional]
**_do** | [**DoEnum**](#DoEnum) |  | 
**forceMerge** | **Boolean** |  |  [optional]
**headCommitId** | **String** |  |  [optional]
**mergeCommitId** | **String** |  |  [optional]
**mergeMessageField** | **String** |  |  [optional]
**mergeTitleField** | **String** |  |  [optional]
**mergeWhenChecksSucceed** | **Boolean** |  |  [optional]


<a name="DoEnum"></a>
## Enum: DoEnum
Name | Value
---- | -----
MERGE | &quot;merge&quot;
REBASE | &quot;rebase&quot;
REBASE_MERGE | &quot;rebase-merge&quot;
SQUASH | &quot;squash&quot;
FAST_FORWARD_ONLY | &quot;fast-forward-only&quot;
MANUALLY_MERGED | &quot;manually-merged&quot;



