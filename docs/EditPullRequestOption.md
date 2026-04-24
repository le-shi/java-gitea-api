
# EditPullRequestOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowMaintainerEdit** | **Boolean** | Whether to allow maintainer edits |  [optional]
**assignee** | **String** | The new primary assignee username |  [optional]
**assignees** | **List&lt;String&gt;** | The new list of assignee usernames |  [optional]
**base** | **String** | The new base branch for the pull request |  [optional]
**body** | **String** | The new description body for the pull request |  [optional]
**dueDate** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**labels** | **List&lt;Long&gt;** | The new list of label IDs for the pull request |  [optional]
**milestone** | **Long** | The new milestone ID for the pull request |  [optional]
**state** | **String** | The new state for the pull request |  [optional]
**title** | **String** | The new title for the pull request |  [optional]
**unsetDueDate** | **Boolean** | Whether to remove the current deadline |  [optional]



