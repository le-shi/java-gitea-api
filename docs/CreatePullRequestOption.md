
# CreatePullRequestOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**assignee** | **String** | The primary assignee username |  [optional]
**assignees** | **List&lt;String&gt;** | The list of assignee usernames |  [optional]
**base** | **String** | The base branch for the pull request |  [optional]
**body** | **String** | The description body of the pull request |  [optional]
**dueDate** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**head** | **String** | The head branch for the pull request, it could be a branch name on the base repository or a form like &#x60;&lt;username&gt;:&lt;branch&gt;&#x60; which refers to the user&#39;s fork repository&#39;s branch. |  [optional]
**labels** | **List&lt;Long&gt;** | The list of label IDs to assign to the pull request |  [optional]
**milestone** | **Long** | The milestone ID to assign to the pull request |  [optional]
**reviewers** | **List&lt;String&gt;** | The list of reviewer usernames |  [optional]
**teamReviewers** | **List&lt;String&gt;** | The list of team reviewer names |  [optional]
**title** | **String** | The title of the pull request |  [optional]



