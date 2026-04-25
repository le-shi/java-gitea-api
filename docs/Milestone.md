
# Milestone

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**closedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**closedIssues** | **Long** | ClosedIssues is the number of closed issues in this milestone |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**description** | **String** | Description provides details about the milestone |  [optional]
**dueOn** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**id** | **Long** | ID is the unique identifier for the milestone |  [optional]
**openIssues** | **Long** | OpenIssues is the number of open issues in this milestone |  [optional]
**state** | [**StateEnum**](#StateEnum) | State indicates if the milestone is open or closed open StateOpen  StateOpen pr is opened closed StateClosed  StateClosed pr is closed |  [optional]
**title** | **String** | Title is the title of the milestone |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]


<a name="StateEnum"></a>
## Enum: StateEnum
Name | Value
---- | -----
OPEN | &quot;open&quot;
CLOSED | &quot;closed&quot;



