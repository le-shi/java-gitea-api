
# CreateStatusOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**context** | **String** | Context is the unique context identifier for the status |  [optional]
**description** | **String** | Description provides a brief description of the status |  [optional]
**state** | [**StateEnum**](#StateEnum) | State represents the status state to set (pending, success, error, failure) pending CommitStatusPending  CommitStatusPending is for when the CommitStatus is Pending success CommitStatusSuccess  CommitStatusSuccess is for when the CommitStatus is Success error CommitStatusError  CommitStatusError is for when the CommitStatus is Error failure CommitStatusFailure  CommitStatusFailure is for when the CommitStatus is Failure warning CommitStatusWarning  CommitStatusWarning is for when the CommitStatus is Warning skipped CommitStatusSkipped  CommitStatusSkipped is for when CommitStatus is Skipped |  [optional]
**targetUrl** | **String** | TargetURL is the URL to link to for more details |  [optional]


<a name="StateEnum"></a>
## Enum: StateEnum
Name | Value
---- | -----
PENDING | &quot;pending&quot;
SUCCESS | &quot;success&quot;
ERROR | &quot;error&quot;
FAILURE | &quot;failure&quot;
WARNING | &quot;warning&quot;
SKIPPED | &quot;skipped&quot;



