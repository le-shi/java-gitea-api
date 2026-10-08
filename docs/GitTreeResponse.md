
# GitTreeResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page** | **Long** | Page is the current page number for pagination |  [optional]
**sha** | **String** | SHA is the tree object SHA |  [optional]
**totalCount** | **Long** | TotalCount is the total number of entries in the tree |  [optional]
**tree** | [**List&lt;GitEntry&gt;**](GitEntry.md) | Entries contains the tree entries (files and directories) |  [optional]
**truncated** | **Boolean** | Truncated indicates if the response was truncated due to size |  [optional]
**url** | **String** | URL is the API URL for this tree |  [optional]



