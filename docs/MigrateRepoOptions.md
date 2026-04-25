
# MigrateRepoOptions

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**authPassword** | **String** |  |  [optional]
**authToken** | **String** |  |  [optional]
**authUsername** | **String** |  |  [optional]
**awsAccessKeyId** | **String** |  |  [optional]
**awsSecretAccessKey** | **String** |  |  [optional]
**cloneAddr** | **String** |  | 
**description** | **String** |  |  [optional]
**issues** | **Boolean** |  |  [optional]
**labels** | **Boolean** |  |  [optional]
**lfs** | **Boolean** |  |  [optional]
**lfsEndpoint** | **String** |  |  [optional]
**milestones** | **Boolean** |  |  [optional]
**mirror** | **Boolean** |  |  [optional]
**mirrorInterval** | **String** |  |  [optional]
**_private** | **Boolean** |  |  [optional]
**pullRequests** | **Boolean** |  |  [optional]
**releases** | **Boolean** |  |  [optional]
**repoName** | **String** |  | 
**repoOwner** | **String** | the organization&#39;s name or individual user&#39;s name who will own the migrated repository |  [optional]
**service** | [**ServiceEnum**](#ServiceEnum) |  |  [optional]
**uid** | **Long** | deprecated (only for backwards compatibility, use repo_owner instead) |  [optional]
**wiki** | **Boolean** |  |  [optional]


<a name="ServiceEnum"></a>
## Enum: ServiceEnum
Name | Value
---- | -----
GIT | &quot;git&quot;
GITHUB | &quot;github&quot;
GITEA | &quot;gitea&quot;
GITLAB | &quot;gitlab&quot;
GOGS | &quot;gogs&quot;
ONEDEV | &quot;onedev&quot;
GITBUCKET | &quot;gitbucket&quot;
CODEBASE | &quot;codebase&quot;
CODECOMMIT | &quot;codecommit&quot;



