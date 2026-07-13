
# ActionWorkflowRun

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**actor** | [**User**](User.md) |  |  [optional]
**completedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**conclusion** | **String** |  |  [optional]
**displayTitle** | **String** |  |  [optional]
**event** | **String** |  |  [optional]
**headBranch** | **String** |  |  [optional]
**headRepository** | [**Repository**](Repository.md) |  |  [optional]
**headSha** | **String** |  |  [optional]
**htmlUrl** | **String** |  |  [optional]
**id** | **Long** |  |  [optional]
**path** | **String** |  |  [optional]
**previousAttemptUrl** | **String** | PreviousAttemptURL is the API URL of the previous attempt of this run, e.g. \&quot;.../actions/runs/{run_id}/attempts/{attempt-1}\&quot;. It is set only when the current attempt is &gt; 1 (i.e. a rerun). For the first attempt, or for legacy runs that pre-date ActionRunAttempt, it is null. |  [optional]
**pullRequests** | [**List&lt;PullRequestMinimal&gt;**](PullRequestMinimal.md) |  |  [optional]
**repository** | [**Repository**](Repository.md) |  |  [optional]
**repositoryId** | **Long** |  |  [optional]
**runAttempt** | **Long** | RunAttempt is 1-based for runs created after ActionRunAttempt was introduced. A value of 0 is a legacy-only sentinel for runs created before attempts existed and indicates no corresponding /attempts/{n} resource is available. |  [optional]
**runNumber** | **Long** |  |  [optional]
**startedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**status** | **String** |  |  [optional]
**triggerActor** | [**User**](User.md) |  |  [optional]
**url** | **String** |  |  [optional]



