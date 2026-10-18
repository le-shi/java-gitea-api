
# Project

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cardType** | **String** | Card type: \&quot;text_only\&quot; or \&quot;images_and_text\&quot; |  [optional]
**closedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**creator** | [**User**](User.md) |  |  [optional]
**creatorId** | **Long** | Deprecated: use Creator instead |  [optional]
**description** | **String** |  |  [optional]
**htmlUrl** | **String** |  |  [optional]
**id** | **Long** |  |  [optional]
**isClosed** | **Boolean** | Deprecated: use State instead |  [optional]
**numClosedIssues** | **Long** |  |  [optional]
**numIssues** | **Long** |  |  [optional]
**numOpenIssues** | **Long** |  |  [optional]
**ownerId** | **Long** |  |  [optional]
**repoId** | **Long** |  |  [optional]
**state** | [**StateEnum**](#StateEnum) |  |  [optional]
**templateType** | **String** | Template type: \&quot;none\&quot;, \&quot;basic_kanban\&quot; or \&quot;bug_triage\&quot; |  [optional]
**title** | **String** |  |  [optional]
**type** | **String** | Project type: \&quot;individual\&quot;, \&quot;repository\&quot; or \&quot;organization\&quot; |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) | null only for legacy rows that carry no update timestamp |  [optional]


<a name="StateEnum"></a>
## Enum: StateEnum
Name | Value
---- | -----
OPEN | &quot;open&quot;
CLOSED | &quot;closed&quot;



