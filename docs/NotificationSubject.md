
# NotificationSubject

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**htmlUrl** | **String** | HTMLURL is the web URL for the notification subject |  [optional]
**latestCommentHtmlUrl** | **String** | LatestCommentHTMLURL is the web URL for the latest comment |  [optional]
**latestCommentUrl** | **String** | LatestCommentURL is the API URL for the latest comment |  [optional]
**state** | [**StateEnum**](#StateEnum) | State indicates the current state of the notification subject open NotifySubjectStateOpen is an open subject closed NotifySubjectStateClosed is a closed subject merged NotifySubjectStateMerged is a merged pull request |  [optional]
**title** | **String** | Title is the title of the notification subject |  [optional]
**type** | [**TypeEnum**](#TypeEnum) | Type indicates the type of the notification subject Issue NotifySubjectIssue a issue is subject of an notification Pull NotifySubjectPull a pull is subject of an notification Commit NotifySubjectCommit a commit is subject of an notification Repository NotifySubjectRepository a repository is subject of an notification |  [optional]
**url** | **String** | URL is the API URL for the notification subject |  [optional]


<a name="StateEnum"></a>
## Enum: StateEnum
Name | Value
---- | -----
OPEN | &quot;open&quot;
CLOSED | &quot;closed&quot;
MERGED | &quot;merged&quot;


<a name="TypeEnum"></a>
## Enum: TypeEnum
Name | Value
---- | -----
ISSUE | &quot;Issue&quot;
PULL | &quot;Pull&quot;
COMMIT | &quot;Commit&quot;
REPOSITORY | &quot;Repository&quot;



