
# CreateHookOption

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | **Boolean** |  |  [optional]
**authorizationHeader** | **String** | Authorization header to include in webhook requests |  [optional]
**branchFilter** | **String** | Branch filter pattern to determine which branches trigger the webhook |  [optional]
**config** | [**CreateHookOptionConfig**](CreateHookOptionConfig.md) |  | 
**events** | **List&lt;String&gt;** | List of events that will trigger this webhook |  [optional]
**name** | **String** | Optional human-readable name for the webhook |  [optional]
**type** | [**TypeEnum**](#TypeEnum) |  | 


<a name="TypeEnum"></a>
## Enum: TypeEnum
Name | Value
---- | -----
DINGTALK | &quot;dingtalk&quot;
DISCORD | &quot;discord&quot;
GITEA | &quot;gitea&quot;
GOGS | &quot;gogs&quot;
MSTEAMS | &quot;msteams&quot;
SLACK | &quot;slack&quot;
TELEGRAM | &quot;telegram&quot;
FEISHU | &quot;feishu&quot;
WECHATWORK | &quot;wechatwork&quot;
PACKAGIST | &quot;packagist&quot;



