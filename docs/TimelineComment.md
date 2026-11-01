
# TimelineComment

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**assignee** | [**User**](User.md) |  |  [optional]
**assigneeTeam** | [**Team**](Team.md) |  |  [optional]
**body** | **String** | Body contains the timeline event content |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**dependentIssue** | [**Issue**](Issue.md) |  |  [optional]
**htmlUrl** | **String** | HTMLURL is the web URL for viewing the comment |  [optional]
**id** | **Long** | ID is the unique identifier for the timeline comment |  [optional]
**issueUrl** | **String** | IssueURL is the API URL for the issue |  [optional]
**label** | [**Label**](Label.md) |  |  [optional]
**milestone** | [**Milestone**](Milestone.md) |  |  [optional]
**newRef** | **String** |  |  [optional]
**newTitle** | **String** |  |  [optional]
**oldMilestone** | [**Milestone**](Milestone.md) |  |  [optional]
**oldProjectId** | **Long** |  |  [optional]
**oldRef** | **String** |  |  [optional]
**oldTitle** | **String** |  |  [optional]
**projectId** | **Long** |  |  [optional]
**pullRequestUrl** | **String** | PRURL is the API URL for the pull request (if applicable) |  [optional]
**refAction** | **String** |  |  [optional]
**refComment** | [**Comment**](Comment.md) |  |  [optional]
**refCommitSha** | **String** | commit SHA where issue/PR was referenced |  [optional]
**refIssue** | [**Issue**](Issue.md) |  |  [optional]
**removedAssignee** | **Boolean** | whether the assignees were removed or added |  [optional]
**resolveDoer** | [**User**](User.md) |  |  [optional]
**reviewId** | **Long** |  |  [optional]
**trackedTime** | [**TrackedTime**](TrackedTime.md) |  |  [optional]
**type** | **String** | Type indicates the type of timeline event |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**user** | [**User**](User.md) |  |  [optional]



