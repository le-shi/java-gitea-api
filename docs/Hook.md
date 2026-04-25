
# Hook

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | **Boolean** | Whether the webhook is active and will be triggered |  [optional]
**authorizationHeader** | **String** | Authorization header to include in webhook requests |  [optional]
**branchFilter** | **String** | Branch filter pattern to determine which branches trigger the webhook |  [optional]
**config** | **Map&lt;String, String&gt;** | Configuration settings for the webhook |  [optional]
**createdAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]
**events** | **List&lt;String&gt;** | List of events that trigger this webhook |  [optional]
**id** | **Long** | The unique identifier of the webhook |  [optional]
**type** | **String** | The type of the webhook (e.g., gitea, slack, discord) |  [optional]
**updatedAt** | [**OffsetDateTime**](OffsetDateTime.md) |  |  [optional]



