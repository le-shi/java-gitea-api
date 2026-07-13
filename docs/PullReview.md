
# PullReview

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**body** | **String** |  |  [optional]
**commentsCount** | **Long** |  |  [optional]
**commitId** | **String** |  |  [optional]
**dismissed** | **Boolean** |  |  [optional]
**htmlUrl** | **String** | HTMLURL is the web URL for viewing the review |  [optional]
**id** | **Long** |  |  [optional]
**official** | **Boolean** |  |  [optional]
**pullRequestUrl** | **String** | HTMLPullURL is the web URL for the pull request |  [optional]
**stale** | **Boolean** |  |  [optional]
**state** | [**StateEnum**](#StateEnum) |  |  [optional]
**submittedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**team** | [**Team**](Team.md) |  |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**user** | [**User**](User.md) |  |  [optional]


<a name="StateEnum"></a>
## Enum: StateEnum
Name | Value
---- | -----
APPROVED | &quot;APPROVED&quot;
PENDING | &quot;PENDING&quot;
COMMENT | &quot;COMMENT&quot;
REQUEST_CHANGES | &quot;REQUEST_CHANGES&quot;
REQUEST_REVIEW | &quot;REQUEST_REVIEW&quot;



