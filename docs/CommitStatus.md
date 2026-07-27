
# CommitStatus

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**context** | **String** | Context is the unique context identifier for the status |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**creator** | [**User**](User.md) |  |  [optional]
**description** | **String** | Description provides a brief description of the status |  [optional]
**id** | **Long** | ID is the unique identifier for the commit status |  [optional]
**status** | [**StatusEnum**](#StatusEnum) | State represents the status state (pending, success, error, failure) pending CommitStatusPending is for when the CommitStatus is Pending success CommitStatusSuccess is for when the CommitStatus is Success error CommitStatusError is for when the CommitStatus is Error failure CommitStatusFailure is for when the CommitStatus is Failure warning CommitStatusWarning is for when the CommitStatus is Warning skipped CommitStatusSkipped is for when CommitStatus is Skipped |  [optional]
**targetUrl** | **String** | TargetURL is the URL to link to for more details |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**url** | **String** | URL is the API URL for this status |  [optional]


<a name="StatusEnum"></a>
## Enum: StatusEnum
Name | Value
---- | -----
PENDING | &quot;pending&quot;
SUCCESS | &quot;success&quot;
ERROR | &quot;error&quot;
FAILURE | &quot;failure&quot;
WARNING | &quot;warning&quot;
SKIPPED | &quot;skipped&quot;



