
# PullRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**additions** | **Long** | The number of lines added in the pull request |  [optional]
**allowMaintainerEdit** | **Boolean** | Whether maintainers can edit the pull request |  [optional]
**assignee** | [**User**](User.md) |  |  [optional]
**assignees** | [**List&lt;User&gt;**](User.md) | The list of users assigned to the pull request |  [optional]
**base** | [**PRBranchInfo**](PRBranchInfo.md) |  |  [optional]
**body** | **String** | The description body of the pull request |  [optional]
**changedFiles** | **Long** | The number of files changed in the pull request |  [optional]
**closedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**comments** | **Long** | The number of comments on the pull request |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**deletions** | **Long** | The number of lines deleted in the pull request |  [optional]
**diffUrl** | **String** | The URL to download the diff patch |  [optional]
**draft** | **Boolean** | Whether the pull request is a draft |  [optional]
**dueDate** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**head** | [**PRBranchInfo**](PRBranchInfo.md) |  |  [optional]
**htmlUrl** | **String** | The HTML URL to view the pull request |  [optional]
**id** | **Long** | The unique identifier of the pull request |  [optional]
**isLocked** | **Boolean** | Whether the pull request conversation is locked |  [optional]
**labels** | [**List&lt;Label&gt;**](Label.md) | The labels attached to the pull request |  [optional]
**mergeBase** | **String** | The merge base commit SHA |  [optional]
**mergeCommitSha** | **String** | The SHA of the merge commit |  [optional]
**mergeable** | **Boolean** | Whether the pull request can be merged |  [optional]
**merged** | **Boolean** | Whether the pull request has been merged |  [optional]
**mergedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**mergedBy** | [**User**](User.md) |  |  [optional]
**milestone** | [**Milestone**](Milestone.md) |  |  [optional]
**number** | **Long** | The pull request number |  [optional]
**patchUrl** | **String** | The URL to download the patch file |  [optional]
**pinOrder** | **Long** | The pin order for the pull request |  [optional]
**requestedReviewers** | [**List&lt;User&gt;**](User.md) | The users requested to review the pull request |  [optional]
**requestedReviewersTeams** | [**List&lt;Team&gt;**](Team.md) | The teams requested to review the pull request |  [optional]
**reviewComments** | **Long** | number of review comments made on the diff of a PR review (not including comments on commits or issues in a PR) |  [optional]
**state** | **String** |  |  [optional]
**title** | **String** | The title of the pull request |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**url** | **String** | The API URL of the pull request |  [optional]
**user** | [**User**](User.md) |  |  [optional]



