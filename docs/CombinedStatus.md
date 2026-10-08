
# CombinedStatus

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**commitUrl** | **String** | CommitURL is the API URL for the commit |  [optional]
**repository** | [**Repository**](Repository.md) |  |  [optional]
**sha** | **String** | SHA is the commit SHA this status applies to |  [optional]
**state** | [**StateEnum**](#StateEnum) | State is the overall combined status state |  [optional]
**statuses** | [**List&lt;CommitStatus&gt;**](CommitStatus.md) | Statuses contains all individual commit statuses |  [optional]
**totalCount** | **Long** | TotalCount is the total number of statuses |  [optional]
**url** | **String** | URL is the API URL for this combined status |  [optional]


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



