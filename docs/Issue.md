
# Issue

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**assets** | [**List&lt;Attachment&gt;**](Attachment.md) |  |  [optional]
**assignee** | [**User**](User.md) |  |  [optional]
**assignees** | [**List&lt;User&gt;**](User.md) |  |  [optional]
**body** | **String** |  |  [optional]
**closedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**comments** | **Long** |  |  [optional]
**contentVersion** | **Long** | The version of the issue content for optimistic locking |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**dueDate** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**htmlUrl** | **String** |  |  [optional]
**id** | **Long** |  |  [optional]
**isLocked** | **Boolean** |  |  [optional]
**labels** | [**List&lt;Label&gt;**](Label.md) |  |  [optional]
**milestone** | [**Milestone**](Milestone.md) |  |  [optional]
**number** | **Long** |  |  [optional]
**originalAuthor** | **String** |  |  [optional]
**originalAuthorId** | **Long** |  |  [optional]
**pinOrder** | **Long** |  |  [optional]
**pullRequest** | [**PullRequestMeta**](PullRequestMeta.md) |  |  [optional]
**ref** | **String** |  |  [optional]
**repository** | [**RepositoryMeta**](RepositoryMeta.md) |  |  [optional]
**state** | [**StateEnum**](#StateEnum) |  |  [optional]
**timeEstimate** | **Long** |  |  [optional]
**title** | **String** |  |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**url** | **String** |  |  [optional]
**user** | [**User**](User.md) |  |  [optional]


<a name="StateEnum"></a>
## Enum: StateEnum
Name | Value
---- | -----
OPEN | &quot;open&quot;
CLOSED | &quot;closed&quot;



