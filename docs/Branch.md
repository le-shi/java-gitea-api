
# Branch

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**commit** | [**PayloadCommit**](PayloadCommit.md) |  |  [optional]
**effectiveBranchProtectionName** | **String** | EffectiveBranchProtectionName is the name of the effective branch protection rule |  [optional]
**enableStatusCheck** | **Boolean** | EnableStatusCheck indicates if status checks are enabled |  [optional]
**name** | **String** | Name is the branch name |  [optional]
**_protected** | **Boolean** | Protected indicates if the branch is protected |  [optional]
**requiredApprovals** | **Long** | RequiredApprovals is the number of required approvals for pull requests |  [optional]
**statusCheckContexts** | **List&lt;String&gt;** | StatusCheckContexts contains the list of required status check contexts |  [optional]
**userCanMerge** | **Boolean** | UserCanMerge indicates if the current user can merge to this branch |  [optional]
**userCanPush** | **Boolean** | UserCanPush indicates if the current user can push to this branch |  [optional]



