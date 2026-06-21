# UserApi

All URIs are relative to *https://localhost/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**createCurrentUserRepo**](UserApi.md#createCurrentUserRepo) | **POST** /user/repos | Create a repository
[**createUserVariable**](UserApi.md#createUserVariable) | **POST** /user/actions/variables/{variablename} | Create a user-level variable
[**deleteUserRunner**](UserApi.md#deleteUserRunner) | **DELETE** /user/actions/runners/{runner_id} | Delete a user-level runner
[**deleteUserSecret**](UserApi.md#deleteUserSecret) | **DELETE** /user/actions/secrets/{secretname} | Delete a secret in a user scope
[**deleteUserVariable**](UserApi.md#deleteUserVariable) | **DELETE** /user/actions/variables/{variablename} | Delete a user-level variable which is created by current doer
[**getUserRunner**](UserApi.md#getUserRunner) | **GET** /user/actions/runners/{runner_id} | Get a user-level runner
[**getUserRunners**](UserApi.md#getUserRunners) | **GET** /user/actions/runners | Get user-level runners
[**getUserSettings**](UserApi.md#getUserSettings) | **GET** /user/settings | Get user settings
[**getUserVariable**](UserApi.md#getUserVariable) | **GET** /user/actions/variables/{variablename} | Get a user-level variable which is created by current doer
[**getUserVariablesList**](UserApi.md#getUserVariablesList) | **GET** /user/actions/variables | Get the user-level list of variables which is created by current doer
[**getUserWorkflowJobs**](UserApi.md#getUserWorkflowJobs) | **GET** /user/actions/jobs | Get workflow jobs
[**getUserWorkflowRuns**](UserApi.md#getUserWorkflowRuns) | **GET** /user/actions/runs | Get workflow runs
[**getVerificationToken**](UserApi.md#getVerificationToken) | **GET** /user/gpg_key_token | Get a Token to verify
[**updateUserRunner**](UserApi.md#updateUserRunner) | **PATCH** /user/actions/runners/{runner_id} | Update a user-level runner
[**updateUserSecret**](UserApi.md#updateUserSecret) | **PUT** /user/actions/secrets/{secretname} | Create or Update a secret value in a user scope
[**updateUserSettings**](UserApi.md#updateUserSettings) | **PATCH** /user/settings | Update user settings
[**updateUserVariable**](UserApi.md#updateUserVariable) | **PUT** /user/actions/variables/{variablename} | Update a user-level variable which is created by current doer
[**userAddEmail**](UserApi.md#userAddEmail) | **POST** /user/emails | Add email addresses
[**userBlockUser**](UserApi.md#userBlockUser) | **PUT** /user/blocks/{username} | Block a user
[**userCheckFollowing**](UserApi.md#userCheckFollowing) | **GET** /users/{username}/following/{target} | Check if one user is following another user
[**userCheckUserBlock**](UserApi.md#userCheckUserBlock) | **GET** /user/blocks/{username} | Check if a user is blocked by the authenticated user
[**userCreateHook**](UserApi.md#userCreateHook) | **POST** /user/hooks | Create a hook
[**userCreateOAuth2Application**](UserApi.md#userCreateOAuth2Application) | **POST** /user/applications/oauth2 | creates a new OAuth2 application
[**userCreateRunnerRegistrationToken**](UserApi.md#userCreateRunnerRegistrationToken) | **POST** /user/actions/runners/registration-token | Get an user&#39;s actions runner registration token
[**userCreateToken**](UserApi.md#userCreateToken) | **POST** /users/{username}/tokens | Create an access token
[**userCurrentCheckFollowing**](UserApi.md#userCurrentCheckFollowing) | **GET** /user/following/{username} | Check whether a user is followed by the authenticated user
[**userCurrentCheckStarring**](UserApi.md#userCurrentCheckStarring) | **GET** /user/starred/{owner}/{repo} | Whether the authenticated is starring the repo
[**userCurrentDeleteFollow**](UserApi.md#userCurrentDeleteFollow) | **DELETE** /user/following/{username} | Unfollow a user
[**userCurrentDeleteGPGKey**](UserApi.md#userCurrentDeleteGPGKey) | **DELETE** /user/gpg_keys/{id} | Remove a GPG key
[**userCurrentDeleteKey**](UserApi.md#userCurrentDeleteKey) | **DELETE** /user/keys/{id} | Delete a public key
[**userCurrentDeleteStar**](UserApi.md#userCurrentDeleteStar) | **DELETE** /user/starred/{owner}/{repo} | Unstar the given repo
[**userCurrentGetGPGKey**](UserApi.md#userCurrentGetGPGKey) | **GET** /user/gpg_keys/{id} | Get a GPG key
[**userCurrentGetKey**](UserApi.md#userCurrentGetKey) | **GET** /user/keys/{id} | Get a public key
[**userCurrentListFollowers**](UserApi.md#userCurrentListFollowers) | **GET** /user/followers | List the authenticated user&#39;s followers
[**userCurrentListFollowing**](UserApi.md#userCurrentListFollowing) | **GET** /user/following | List the users that the authenticated user is following
[**userCurrentListGPGKeys**](UserApi.md#userCurrentListGPGKeys) | **GET** /user/gpg_keys | List the authenticated user&#39;s GPG keys
[**userCurrentListKeys**](UserApi.md#userCurrentListKeys) | **GET** /user/keys | List the authenticated user&#39;s public keys
[**userCurrentListRepos**](UserApi.md#userCurrentListRepos) | **GET** /user/repos | List the repos that the authenticated user owns
[**userCurrentListStarred**](UserApi.md#userCurrentListStarred) | **GET** /user/starred | The repos that the authenticated user has starred
[**userCurrentListSubscriptions**](UserApi.md#userCurrentListSubscriptions) | **GET** /user/subscriptions | List repositories watched by the authenticated user
[**userCurrentPostGPGKey**](UserApi.md#userCurrentPostGPGKey) | **POST** /user/gpg_keys | Create a GPG key
[**userCurrentPostKey**](UserApi.md#userCurrentPostKey) | **POST** /user/keys | Create a public key
[**userCurrentPutFollow**](UserApi.md#userCurrentPutFollow) | **PUT** /user/following/{username} | Follow a user
[**userCurrentPutStar**](UserApi.md#userCurrentPutStar) | **PUT** /user/starred/{owner}/{repo} | Star the given repo
[**userCurrentTrackedTimes**](UserApi.md#userCurrentTrackedTimes) | **GET** /user/times | List the current user&#39;s tracked times
[**userDeleteAccessToken**](UserApi.md#userDeleteAccessToken) | **DELETE** /users/{username}/tokens/{token} | delete an access token
[**userDeleteAvatar**](UserApi.md#userDeleteAvatar) | **DELETE** /user/avatar | Delete Avatar
[**userDeleteEmail**](UserApi.md#userDeleteEmail) | **DELETE** /user/emails | Delete email addresses
[**userDeleteHook**](UserApi.md#userDeleteHook) | **DELETE** /user/hooks/{id} | Delete a hook
[**userDeleteOAuth2Application**](UserApi.md#userDeleteOAuth2Application) | **DELETE** /user/applications/oauth2/{id} | delete an OAuth2 Application
[**userEditHook**](UserApi.md#userEditHook) | **PATCH** /user/hooks/{id} | Update a hook
[**userGet**](UserApi.md#userGet) | **GET** /users/{username} | Get a user
[**userGetCurrent**](UserApi.md#userGetCurrent) | **GET** /user | Get the authenticated user
[**userGetHeatmapData**](UserApi.md#userGetHeatmapData) | **GET** /users/{username}/heatmap | Get a user&#39;s heatmap
[**userGetHook**](UserApi.md#userGetHook) | **GET** /user/hooks/{id} | Get a hook
[**userGetOAuth2Application**](UserApi.md#userGetOAuth2Application) | **GET** /user/applications/oauth2/{id} | get an OAuth2 Application
[**userGetOauth2Application**](UserApi.md#userGetOauth2Application) | **GET** /user/applications/oauth2 | List the authenticated user&#39;s oauth2 applications
[**userGetStopWatches**](UserApi.md#userGetStopWatches) | **GET** /user/stopwatches | Get list of all existing stopwatches
[**userGetTokens**](UserApi.md#userGetTokens) | **GET** /users/{username}/tokens | List the authenticated user&#39;s access tokens
[**userListActivityFeeds**](UserApi.md#userListActivityFeeds) | **GET** /users/{username}/activities/feeds | List a user&#39;s activity feeds
[**userListBlocks**](UserApi.md#userListBlocks) | **GET** /user/blocks | List users blocked by the authenticated user
[**userListEmails**](UserApi.md#userListEmails) | **GET** /user/emails | List the authenticated user&#39;s email addresses
[**userListFollowers**](UserApi.md#userListFollowers) | **GET** /users/{username}/followers | List the given user&#39;s followers
[**userListFollowing**](UserApi.md#userListFollowing) | **GET** /users/{username}/following | List the users that the given user is following
[**userListGPGKeys**](UserApi.md#userListGPGKeys) | **GET** /users/{username}/gpg_keys | List the given user&#39;s GPG keys
[**userListHooks**](UserApi.md#userListHooks) | **GET** /user/hooks | List the authenticated user&#39;s webhooks
[**userListKeys**](UserApi.md#userListKeys) | **GET** /users/{username}/keys | List the given user&#39;s public keys
[**userListRepos**](UserApi.md#userListRepos) | **GET** /users/{username}/repos | List the repos owned by the given user
[**userListStarred**](UserApi.md#userListStarred) | **GET** /users/{username}/starred | The repos that the given user has starred
[**userListSubscriptions**](UserApi.md#userListSubscriptions) | **GET** /users/{username}/subscriptions | List the repositories watched by a user
[**userListTeams**](UserApi.md#userListTeams) | **GET** /user/teams | List all the teams a user belongs to
[**userSearch**](UserApi.md#userSearch) | **GET** /users/search | Search for users
[**userUnblockUser**](UserApi.md#userUnblockUser) | **DELETE** /user/blocks/{username} | Unblock a user
[**userUpdateAvatar**](UserApi.md#userUpdateAvatar) | **POST** /user/avatar | Update Avatar
[**userUpdateOAuth2Application**](UserApi.md#userUpdateOAuth2Application) | **PATCH** /user/applications/oauth2/{id} | update an OAuth2 Application, this includes regenerating the client secret
[**userVerifyGPGKey**](UserApi.md#userVerifyGPGKey) | **POST** /user/gpg_key_verify | Verify a GPG key


<a name="createCurrentUserRepo"></a>
# **createCurrentUserRepo**
> Repository createCurrentUserRepo(body)

Create a repository

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
CreateRepoOption body = new CreateRepoOption(); // CreateRepoOption | 
try {
    Repository result = apiInstance.createCurrentUserRepo(body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#createCurrentUserRepo");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CreateRepoOption**](CreateRepoOption.md)|  | [optional]

### Return type

[**Repository**](Repository.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="createUserVariable"></a>
# **createUserVariable**
> createUserVariable(variablename, body)

Create a user-level variable

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String variablename = "variablename_example"; // String | name of the variable
CreateVariableOption body = new CreateVariableOption(); // CreateVariableOption | 
try {
    apiInstance.createUserVariable(variablename, body);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#createUserVariable");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **variablename** | **String**| name of the variable |
 **body** | [**CreateVariableOption**](CreateVariableOption.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="deleteUserRunner"></a>
# **deleteUserRunner**
> deleteUserRunner(runnerId)

Delete a user-level runner

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String runnerId = "runnerId_example"; // String | id of the runner
try {
    apiInstance.deleteUserRunner(runnerId);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#deleteUserRunner");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **runnerId** | **String**| id of the runner |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="deleteUserSecret"></a>
# **deleteUserSecret**
> deleteUserSecret(secretname)

Delete a secret in a user scope

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String secretname = "secretname_example"; // String | name of the secret
try {
    apiInstance.deleteUserSecret(secretname);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#deleteUserSecret");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secretname** | **String**| name of the secret |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="deleteUserVariable"></a>
# **deleteUserVariable**
> deleteUserVariable(variablename)

Delete a user-level variable which is created by current doer

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String variablename = "variablename_example"; // String | name of the variable
try {
    apiInstance.deleteUserVariable(variablename);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#deleteUserVariable");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **variablename** | **String**| name of the variable |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserRunner"></a>
# **getUserRunner**
> ActionRunner getUserRunner(runnerId)

Get a user-level runner

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String runnerId = "runnerId_example"; // String | id of the runner
try {
    ActionRunner result = apiInstance.getUserRunner(runnerId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getUserRunner");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **runnerId** | **String**| id of the runner |

### Return type

[**ActionRunner**](ActionRunner.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserRunners"></a>
# **getUserRunners**
> ActionRunnersResponse getUserRunners(disabled)

Get user-level runners

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Boolean disabled = true; // Boolean | filter by disabled status (true or false)
try {
    ActionRunnersResponse result = apiInstance.getUserRunners(disabled);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getUserRunners");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **disabled** | **Boolean**| filter by disabled status (true or false) | [optional]

### Return type

[**ActionRunnersResponse**](ActionRunnersResponse.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserSettings"></a>
# **getUserSettings**
> List&lt;UserSettings&gt; getUserSettings()

Get user settings

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
try {
    List<UserSettings> result = apiInstance.getUserSettings();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getUserSettings");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List&lt;UserSettings&gt;**](UserSettings.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserVariable"></a>
# **getUserVariable**
> ActionVariable getUserVariable(variablename)

Get a user-level variable which is created by current doer

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String variablename = "variablename_example"; // String | name of the variable
try {
    ActionVariable result = apiInstance.getUserVariable(variablename);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getUserVariable");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **variablename** | **String**| name of the variable |

### Return type

[**ActionVariable**](ActionVariable.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserVariablesList"></a>
# **getUserVariablesList**
> List&lt;ActionVariable&gt; getUserVariablesList(page, limit)

Get the user-level list of variables which is created by current doer

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<ActionVariable> result = apiInstance.getUserVariablesList(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getUserVariablesList");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;ActionVariable&gt;**](ActionVariable.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserWorkflowJobs"></a>
# **getUserWorkflowJobs**
> ActionWorkflowJobsResponse getUserWorkflowJobs(status, page, limit)

Get workflow jobs

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String status = "status_example"; // String | workflow status (pending, queued, in_progress, failure, success, skipped)
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    ActionWorkflowJobsResponse result = apiInstance.getUserWorkflowJobs(status, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getUserWorkflowJobs");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **String**| workflow status (pending, queued, in_progress, failure, success, skipped) | [optional]
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**ActionWorkflowJobsResponse**](ActionWorkflowJobsResponse.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserWorkflowRuns"></a>
# **getUserWorkflowRuns**
> ActionWorkflowRunsResponse getUserWorkflowRuns(event, branch, status, actor, headSha, page, limit)

Get workflow runs

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String event = "event_example"; // String | workflow event name
String branch = "branch_example"; // String | workflow branch
String status = "status_example"; // String | workflow status (pending, queued, in_progress, failure, success, skipped)
String actor = "actor_example"; // String | triggered by user
String headSha = "headSha_example"; // String | triggering sha of the workflow run
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    ActionWorkflowRunsResponse result = apiInstance.getUserWorkflowRuns(event, branch, status, actor, headSha, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getUserWorkflowRuns");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **event** | **String**| workflow event name | [optional]
 **branch** | **String**| workflow branch | [optional]
 **status** | **String**| workflow status (pending, queued, in_progress, failure, success, skipped) | [optional]
 **actor** | **String**| triggered by user | [optional]
 **headSha** | **String**| triggering sha of the workflow run | [optional]
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**ActionWorkflowRunsResponse**](ActionWorkflowRunsResponse.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getVerificationToken"></a>
# **getVerificationToken**
> String getVerificationToken()

Get a Token to verify

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
try {
    String result = apiInstance.getVerificationToken();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#getVerificationToken");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

**String**

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: text/plain

<a name="updateUserRunner"></a>
# **updateUserRunner**
> ActionRunner updateUserRunner(runnerId, body)

Update a user-level runner

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String runnerId = "runnerId_example"; // String | id of the runner
EditActionRunnerOption body = new EditActionRunnerOption(); // EditActionRunnerOption | 
try {
    ActionRunner result = apiInstance.updateUserRunner(runnerId, body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#updateUserRunner");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **runnerId** | **String**| id of the runner |
 **body** | [**EditActionRunnerOption**](EditActionRunnerOption.md)|  | [optional]

### Return type

[**ActionRunner**](ActionRunner.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="updateUserSecret"></a>
# **updateUserSecret**
> updateUserSecret(secretname, body)

Create or Update a secret value in a user scope

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String secretname = "secretname_example"; // String | name of the secret
CreateOrUpdateSecretOption body = new CreateOrUpdateSecretOption(); // CreateOrUpdateSecretOption | 
try {
    apiInstance.updateUserSecret(secretname, body);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#updateUserSecret");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secretname** | **String**| name of the secret |
 **body** | [**CreateOrUpdateSecretOption**](CreateOrUpdateSecretOption.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="updateUserSettings"></a>
# **updateUserSettings**
> List&lt;UserSettings&gt; updateUserSettings(body)

Update user settings

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
UserSettingsOptions body = new UserSettingsOptions(); // UserSettingsOptions | 
try {
    List<UserSettings> result = apiInstance.updateUserSettings(body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#updateUserSettings");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**UserSettingsOptions**](UserSettingsOptions.md)|  | [optional]

### Return type

[**List&lt;UserSettings&gt;**](UserSettings.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="updateUserVariable"></a>
# **updateUserVariable**
> updateUserVariable(variablename, body)

Update a user-level variable which is created by current doer

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String variablename = "variablename_example"; // String | name of the variable
UpdateVariableOption body = new UpdateVariableOption(); // UpdateVariableOption | 
try {
    apiInstance.updateUserVariable(variablename, body);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#updateUserVariable");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **variablename** | **String**| name of the variable |
 **body** | [**UpdateVariableOption**](UpdateVariableOption.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userAddEmail"></a>
# **userAddEmail**
> List&lt;Email&gt; userAddEmail(body)

Add email addresses

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
CreateEmailOption body = new CreateEmailOption(); // CreateEmailOption | 
try {
    List<Email> result = apiInstance.userAddEmail(body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userAddEmail");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CreateEmailOption**](CreateEmailOption.md)|  | [optional]

### Return type

[**List&lt;Email&gt;**](Email.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userBlockUser"></a>
# **userBlockUser**
> userBlockUser(username, note)

Block a user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user to block
String note = "note_example"; // String | optional note for the block
try {
    apiInstance.userBlockUser(username, note);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userBlockUser");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user to block |
 **note** | **String**| optional note for the block | [optional]

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCheckFollowing"></a>
# **userCheckFollowing**
> userCheckFollowing(username, target)

Check if one user is following another user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the following user
String target = "target_example"; // String | username of the followed user
try {
    apiInstance.userCheckFollowing(username, target);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCheckFollowing");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the following user |
 **target** | **String**| username of the followed user |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCheckUserBlock"></a>
# **userCheckUserBlock**
> userCheckUserBlock(username)

Check if a user is blocked by the authenticated user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user to check
try {
    apiInstance.userCheckUserBlock(username);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCheckUserBlock");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user to check |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCreateHook"></a>
# **userCreateHook**
> Hook userCreateHook(body)

Create a hook

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
CreateHookOption body = new CreateHookOption(); // CreateHookOption | 
try {
    Hook result = apiInstance.userCreateHook(body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCreateHook");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CreateHookOption**](CreateHookOption.md)|  |

### Return type

[**Hook**](Hook.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCreateOAuth2Application"></a>
# **userCreateOAuth2Application**
> OAuth2Application userCreateOAuth2Application(body)

creates a new OAuth2 application

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
CreateOAuth2ApplicationOptions body = new CreateOAuth2ApplicationOptions(); // CreateOAuth2ApplicationOptions | 
try {
    OAuth2Application result = apiInstance.userCreateOAuth2Application(body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCreateOAuth2Application");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CreateOAuth2ApplicationOptions**](CreateOAuth2ApplicationOptions.md)|  |

### Return type

[**OAuth2Application**](OAuth2Application.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCreateRunnerRegistrationToken"></a>
# **userCreateRunnerRegistrationToken**
> userCreateRunnerRegistrationToken()

Get an user&#39;s actions runner registration token

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
try {
    apiInstance.userCreateRunnerRegistrationToken();
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCreateRunnerRegistrationToken");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCreateToken"></a>
# **userCreateToken**
> AccessToken userCreateToken(username, body)

Create an access token

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose token is to be created
CreateAccessTokenOption body = new CreateAccessTokenOption(); // CreateAccessTokenOption | 
try {
    AccessToken result = apiInstance.userCreateToken(username, body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCreateToken");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose token is to be created |
 **body** | [**CreateAccessTokenOption**](CreateAccessTokenOption.md)|  | [optional]

### Return type

[**AccessToken**](AccessToken.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentCheckFollowing"></a>
# **userCurrentCheckFollowing**
> userCurrentCheckFollowing(username)

Check whether a user is followed by the authenticated user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user to check for authenticated followers
try {
    apiInstance.userCurrentCheckFollowing(username);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentCheckFollowing");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user to check for authenticated followers |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentCheckStarring"></a>
# **userCurrentCheckStarring**
> userCurrentCheckStarring(owner, repo)

Whether the authenticated is starring the repo

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String owner = "owner_example"; // String | owner of the repo
String repo = "repo_example"; // String | name of the repo
try {
    apiInstance.userCurrentCheckStarring(owner, repo);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentCheckStarring");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **owner** | **String**| owner of the repo |
 **repo** | **String**| name of the repo |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentDeleteFollow"></a>
# **userCurrentDeleteFollow**
> userCurrentDeleteFollow(username)

Unfollow a user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user to unfollow
try {
    apiInstance.userCurrentDeleteFollow(username);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentDeleteFollow");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user to unfollow |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentDeleteGPGKey"></a>
# **userCurrentDeleteGPGKey**
> userCurrentDeleteGPGKey(id)

Remove a GPG key

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | id of key to delete
try {
    apiInstance.userCurrentDeleteGPGKey(id);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentDeleteGPGKey");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id of key to delete |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentDeleteKey"></a>
# **userCurrentDeleteKey**
> userCurrentDeleteKey(id)

Delete a public key

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | id of key to delete
try {
    apiInstance.userCurrentDeleteKey(id);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentDeleteKey");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id of key to delete |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentDeleteStar"></a>
# **userCurrentDeleteStar**
> userCurrentDeleteStar(owner, repo)

Unstar the given repo

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String owner = "owner_example"; // String | owner of the repo to unstar
String repo = "repo_example"; // String | name of the repo to unstar
try {
    apiInstance.userCurrentDeleteStar(owner, repo);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentDeleteStar");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **owner** | **String**| owner of the repo to unstar |
 **repo** | **String**| name of the repo to unstar |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentGetGPGKey"></a>
# **userCurrentGetGPGKey**
> GPGKey userCurrentGetGPGKey(id)

Get a GPG key

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | id of key to get
try {
    GPGKey result = apiInstance.userCurrentGetGPGKey(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentGetGPGKey");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id of key to get |

### Return type

[**GPGKey**](GPGKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentGetKey"></a>
# **userCurrentGetKey**
> PublicKey userCurrentGetKey(id)

Get a public key

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | id of key to get
try {
    PublicKey result = apiInstance.userCurrentGetKey(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentGetKey");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id of key to get |

### Return type

[**PublicKey**](PublicKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentListFollowers"></a>
# **userCurrentListFollowers**
> List&lt;User&gt; userCurrentListFollowers(page, limit)

List the authenticated user&#39;s followers

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<User> result = apiInstance.userCurrentListFollowers(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentListFollowers");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;User&gt;**](User.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentListFollowing"></a>
# **userCurrentListFollowing**
> List&lt;User&gt; userCurrentListFollowing(page, limit)

List the users that the authenticated user is following

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<User> result = apiInstance.userCurrentListFollowing(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentListFollowing");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;User&gt;**](User.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentListGPGKeys"></a>
# **userCurrentListGPGKeys**
> List&lt;GPGKey&gt; userCurrentListGPGKeys(page, limit)

List the authenticated user&#39;s GPG keys

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<GPGKey> result = apiInstance.userCurrentListGPGKeys(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentListGPGKeys");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;GPGKey&gt;**](GPGKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentListKeys"></a>
# **userCurrentListKeys**
> List&lt;PublicKey&gt; userCurrentListKeys(fingerprint, page, limit)

List the authenticated user&#39;s public keys

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String fingerprint = "fingerprint_example"; // String | fingerprint of the key
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<PublicKey> result = apiInstance.userCurrentListKeys(fingerprint, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentListKeys");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fingerprint** | **String**| fingerprint of the key | [optional]
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;PublicKey&gt;**](PublicKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentListRepos"></a>
# **userCurrentListRepos**
> List&lt;Repository&gt; userCurrentListRepos(page, limit)

List the repos that the authenticated user owns

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Repository> result = apiInstance.userCurrentListRepos(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentListRepos");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Repository&gt;**](Repository.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentListStarred"></a>
# **userCurrentListStarred**
> List&lt;Repository&gt; userCurrentListStarred(page, limit)

The repos that the authenticated user has starred

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Repository> result = apiInstance.userCurrentListStarred(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentListStarred");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Repository&gt;**](Repository.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentListSubscriptions"></a>
# **userCurrentListSubscriptions**
> List&lt;Repository&gt; userCurrentListSubscriptions(page, limit)

List repositories watched by the authenticated user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Repository> result = apiInstance.userCurrentListSubscriptions(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentListSubscriptions");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Repository&gt;**](Repository.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentPostGPGKey"></a>
# **userCurrentPostGPGKey**
> GPGKey userCurrentPostGPGKey(form)

Create a GPG key

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
CreateGPGKeyOption form = new CreateGPGKeyOption(); // CreateGPGKeyOption | 
try {
    GPGKey result = apiInstance.userCurrentPostGPGKey(form);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentPostGPGKey");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **form** | [**CreateGPGKeyOption**](CreateGPGKeyOption.md)|  | [optional]

### Return type

[**GPGKey**](GPGKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentPostKey"></a>
# **userCurrentPostKey**
> PublicKey userCurrentPostKey(body)

Create a public key

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
CreateKeyOption body = new CreateKeyOption(); // CreateKeyOption | 
try {
    PublicKey result = apiInstance.userCurrentPostKey(body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentPostKey");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CreateKeyOption**](CreateKeyOption.md)|  | [optional]

### Return type

[**PublicKey**](PublicKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentPutFollow"></a>
# **userCurrentPutFollow**
> userCurrentPutFollow(username)

Follow a user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user to follow
try {
    apiInstance.userCurrentPutFollow(username);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentPutFollow");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user to follow |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentPutStar"></a>
# **userCurrentPutStar**
> userCurrentPutStar(owner, repo)

Star the given repo

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String owner = "owner_example"; // String | owner of the repo to star
String repo = "repo_example"; // String | name of the repo to star
try {
    apiInstance.userCurrentPutStar(owner, repo);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentPutStar");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **owner** | **String**| owner of the repo to star |
 **repo** | **String**| name of the repo to star |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userCurrentTrackedTimes"></a>
# **userCurrentTrackedTimes**
> List&lt;TrackedTime&gt; userCurrentTrackedTimes(page, limit, since, before)

List the current user&#39;s tracked times

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
OffsetDateTime since = OffsetDateTime.now(); // OffsetDateTime | Only show times updated after the given time. This is a timestamp in RFC 3339 format
OffsetDateTime before = OffsetDateTime.now(); // OffsetDateTime | Only show times updated before the given time. This is a timestamp in RFC 3339 format
try {
    List<TrackedTime> result = apiInstance.userCurrentTrackedTimes(page, limit, since, before);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userCurrentTrackedTimes");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]
 **since** | **OffsetDateTime**| Only show times updated after the given time. This is a timestamp in RFC 3339 format | [optional]
 **before** | **OffsetDateTime**| Only show times updated before the given time. This is a timestamp in RFC 3339 format | [optional]

### Return type

[**List&lt;TrackedTime&gt;**](TrackedTime.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userDeleteAccessToken"></a>
# **userDeleteAccessToken**
> userDeleteAccessToken(username, token)

delete an access token

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose token is to be deleted
String token = "token_example"; // String | token to be deleted, identified by ID and if not available by name
try {
    apiInstance.userDeleteAccessToken(username, token);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userDeleteAccessToken");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose token is to be deleted |
 **token** | **String**| token to be deleted, identified by ID and if not available by name |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userDeleteAvatar"></a>
# **userDeleteAvatar**
> userDeleteAvatar()

Delete Avatar

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
try {
    apiInstance.userDeleteAvatar();
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userDeleteAvatar");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userDeleteEmail"></a>
# **userDeleteEmail**
> userDeleteEmail(body)

Delete email addresses

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
DeleteEmailOption body = new DeleteEmailOption(); // DeleteEmailOption | 
try {
    apiInstance.userDeleteEmail(body);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userDeleteEmail");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**DeleteEmailOption**](DeleteEmailOption.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userDeleteHook"></a>
# **userDeleteHook**
> userDeleteHook(id)

Delete a hook

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | id of the hook to delete
try {
    apiInstance.userDeleteHook(id);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userDeleteHook");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id of the hook to delete |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userDeleteOAuth2Application"></a>
# **userDeleteOAuth2Application**
> userDeleteOAuth2Application(id)

delete an OAuth2 Application

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | token to be deleted
try {
    apiInstance.userDeleteOAuth2Application(id);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userDeleteOAuth2Application");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| token to be deleted |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userEditHook"></a>
# **userEditHook**
> Hook userEditHook(id, body)

Update a hook

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | id of the hook to update
EditHookOption body = new EditHookOption(); // EditHookOption | 
try {
    Hook result = apiInstance.userEditHook(id, body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userEditHook");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id of the hook to update |
 **body** | [**EditHookOption**](EditHookOption.md)|  | [optional]

### Return type

[**Hook**](Hook.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGet"></a>
# **userGet**
> User userGet(username)

Get a user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose data is to be listed
try {
    User result = apiInstance.userGet(username);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose data is to be listed |

### Return type

[**User**](User.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGetCurrent"></a>
# **userGetCurrent**
> User userGetCurrent()

Get the authenticated user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
try {
    User result = apiInstance.userGetCurrent();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGetCurrent");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**User**](User.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGetHeatmapData"></a>
# **userGetHeatmapData**
> List&lt;UserHeatmapData&gt; userGetHeatmapData(username)

Get a user&#39;s heatmap

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose heatmap is to be obtained
try {
    List<UserHeatmapData> result = apiInstance.userGetHeatmapData(username);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGetHeatmapData");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose heatmap is to be obtained |

### Return type

[**List&lt;UserHeatmapData&gt;**](UserHeatmapData.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGetHook"></a>
# **userGetHook**
> Hook userGetHook(id)

Get a hook

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | id of the hook to get
try {
    Hook result = apiInstance.userGetHook(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGetHook");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id of the hook to get |

### Return type

[**Hook**](Hook.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGetOAuth2Application"></a>
# **userGetOAuth2Application**
> OAuth2Application userGetOAuth2Application(id)

get an OAuth2 Application

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | Application ID to be found
try {
    OAuth2Application result = apiInstance.userGetOAuth2Application(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGetOAuth2Application");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| Application ID to be found |

### Return type

[**OAuth2Application**](OAuth2Application.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGetOauth2Application"></a>
# **userGetOauth2Application**
> List&lt;OAuth2Application&gt; userGetOauth2Application(page, limit)

List the authenticated user&#39;s oauth2 applications

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<OAuth2Application> result = apiInstance.userGetOauth2Application(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGetOauth2Application");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;OAuth2Application&gt;**](OAuth2Application.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGetStopWatches"></a>
# **userGetStopWatches**
> List&lt;StopWatch&gt; userGetStopWatches(page, limit)

Get list of all existing stopwatches

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<StopWatch> result = apiInstance.userGetStopWatches(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGetStopWatches");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;StopWatch&gt;**](StopWatch.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userGetTokens"></a>
# **userGetTokens**
> List&lt;AccessToken&gt; userGetTokens(username, page, limit)

List the authenticated user&#39;s access tokens

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of to user whose access tokens are to be listed
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<AccessToken> result = apiInstance.userGetTokens(username, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userGetTokens");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of to user whose access tokens are to be listed |
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;AccessToken&gt;**](AccessToken.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListActivityFeeds"></a>
# **userListActivityFeeds**
> List&lt;Activity&gt; userListActivityFeeds(username, onlyPerformedBy, date, page, limit)

List a user&#39;s activity feeds

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose activity feeds are to be listed
Boolean onlyPerformedBy = true; // Boolean | if true, only show actions performed by the requested user
LocalDate date = LocalDate.now(); // LocalDate | the date of the activities to be found
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Activity> result = apiInstance.userListActivityFeeds(username, onlyPerformedBy, date, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListActivityFeeds");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose activity feeds are to be listed |
 **onlyPerformedBy** | **Boolean**| if true, only show actions performed by the requested user | [optional]
 **date** | **LocalDate**| the date of the activities to be found | [optional]
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Activity&gt;**](Activity.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListBlocks"></a>
# **userListBlocks**
> List&lt;User&gt; userListBlocks(page, limit)

List users blocked by the authenticated user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<User> result = apiInstance.userListBlocks(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListBlocks");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;User&gt;**](User.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListEmails"></a>
# **userListEmails**
> List&lt;Email&gt; userListEmails()

List the authenticated user&#39;s email addresses

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
try {
    List<Email> result = apiInstance.userListEmails();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListEmails");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List&lt;Email&gt;**](Email.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListFollowers"></a>
# **userListFollowers**
> List&lt;User&gt; userListFollowers(username, page, limit)

List the given user&#39;s followers

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose followers are to be listed
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<User> result = apiInstance.userListFollowers(username, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListFollowers");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose followers are to be listed |
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;User&gt;**](User.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListFollowing"></a>
# **userListFollowing**
> List&lt;User&gt; userListFollowing(username, page, limit)

List the users that the given user is following

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose followed users are to be listed
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<User> result = apiInstance.userListFollowing(username, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListFollowing");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose followed users are to be listed |
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;User&gt;**](User.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListGPGKeys"></a>
# **userListGPGKeys**
> List&lt;GPGKey&gt; userListGPGKeys(username, page, limit)

List the given user&#39;s GPG keys

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose GPG key list is to be obtained
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<GPGKey> result = apiInstance.userListGPGKeys(username, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListGPGKeys");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose GPG key list is to be obtained |
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;GPGKey&gt;**](GPGKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListHooks"></a>
# **userListHooks**
> List&lt;Hook&gt; userListHooks(page, limit)

List the authenticated user&#39;s webhooks

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Hook> result = apiInstance.userListHooks(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListHooks");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Hook&gt;**](Hook.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListKeys"></a>
# **userListKeys**
> List&lt;PublicKey&gt; userListKeys(username, fingerprint, page, limit)

List the given user&#39;s public keys

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose public keys are to be listed
String fingerprint = "fingerprint_example"; // String | fingerprint of the key
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<PublicKey> result = apiInstance.userListKeys(username, fingerprint, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListKeys");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose public keys are to be listed |
 **fingerprint** | **String**| fingerprint of the key | [optional]
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;PublicKey&gt;**](PublicKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListRepos"></a>
# **userListRepos**
> List&lt;Repository&gt; userListRepos(username, page, limit)

List the repos owned by the given user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose owned repos are to be listed
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Repository> result = apiInstance.userListRepos(username, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListRepos");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose owned repos are to be listed |
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Repository&gt;**](Repository.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListStarred"></a>
# **userListStarred**
> List&lt;Repository&gt; userListStarred(username, page, limit)

The repos that the given user has starred

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose starred repos are to be listed
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Repository> result = apiInstance.userListStarred(username, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListStarred");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose starred repos are to be listed |
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Repository&gt;**](Repository.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListSubscriptions"></a>
# **userListSubscriptions**
> List&lt;Repository&gt; userListSubscriptions(username, page, limit)

List the repositories watched by a user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user whose watched repos are to be listed
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Repository> result = apiInstance.userListSubscriptions(username, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListSubscriptions");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user whose watched repos are to be listed |
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Repository&gt;**](Repository.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userListTeams"></a>
# **userListTeams**
> List&lt;Team&gt; userListTeams(page, limit)

List all the teams a user belongs to

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    List<Team> result = apiInstance.userListTeams(page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userListTeams");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**List&lt;Team&gt;**](Team.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userSearch"></a>
# **userSearch**
> InlineResponse2001 userSearch(q, uid, page, limit)

Search for users

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String q = "q_example"; // String | keyword
Long uid = 789L; // Long | ID of the user to search for
Integer page = 56; // Integer | page number of results to return (1-based)
Integer limit = 56; // Integer | page size of results
try {
    InlineResponse2001 result = apiInstance.userSearch(q, uid, page, limit);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userSearch");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **q** | **String**| keyword | [optional]
 **uid** | **Long**| ID of the user to search for | [optional]
 **page** | **Integer**| page number of results to return (1-based) | [optional]
 **limit** | **Integer**| page size of results | [optional]

### Return type

[**InlineResponse2001**](InlineResponse2001.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userUnblockUser"></a>
# **userUnblockUser**
> userUnblockUser(username)

Unblock a user

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
String username = "username_example"; // String | username of the user to unblock
try {
    apiInstance.userUnblockUser(username);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userUnblockUser");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **String**| username of the user to unblock |

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userUpdateAvatar"></a>
# **userUpdateAvatar**
> userUpdateAvatar(body)

Update Avatar

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
UpdateUserAvatarOption body = new UpdateUserAvatarOption(); // UpdateUserAvatarOption | 
try {
    apiInstance.userUpdateAvatar(body);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userUpdateAvatar");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**UpdateUserAvatarOption**](UpdateUserAvatarOption.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userUpdateOAuth2Application"></a>
# **userUpdateOAuth2Application**
> OAuth2Application userUpdateOAuth2Application(id, body)

update an OAuth2 Application, this includes regenerating the client secret

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
Long id = 789L; // Long | application to be updated
CreateOAuth2ApplicationOptions body = new CreateOAuth2ApplicationOptions(); // CreateOAuth2ApplicationOptions | 
try {
    OAuth2Application result = apiInstance.userUpdateOAuth2Application(id, body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userUpdateOAuth2Application");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| application to be updated |
 **body** | [**CreateOAuth2ApplicationOptions**](CreateOAuth2ApplicationOptions.md)|  |

### Return type

[**OAuth2Application**](OAuth2Application.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="userVerifyGPGKey"></a>
# **userVerifyGPGKey**
> GPGKey userVerifyGPGKey()

Verify a GPG key

### Example
```java
// Import classes:
//import io.gitea.ApiClient;
//import io.gitea.ApiException;
//import io.gitea.Configuration;
//import io.gitea.auth.*;
//import io.gitea.api.UserApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: AccessToken
ApiKeyAuth AccessToken = (ApiKeyAuth) defaultClient.getAuthentication("AccessToken");
AccessToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AccessToken.setApiKeyPrefix("Token");

// Configure API key authorization: AuthorizationHeaderToken
ApiKeyAuth AuthorizationHeaderToken = (ApiKeyAuth) defaultClient.getAuthentication("AuthorizationHeaderToken");
AuthorizationHeaderToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//AuthorizationHeaderToken.setApiKeyPrefix("Token");

// Configure HTTP basic authorization: BasicAuth
HttpBasicAuth BasicAuth = (HttpBasicAuth) defaultClient.getAuthentication("BasicAuth");
BasicAuth.setUsername("YOUR USERNAME");
BasicAuth.setPassword("YOUR PASSWORD");

// Configure API key authorization: SudoHeader
ApiKeyAuth SudoHeader = (ApiKeyAuth) defaultClient.getAuthentication("SudoHeader");
SudoHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoHeader.setApiKeyPrefix("Token");

// Configure API key authorization: SudoParam
ApiKeyAuth SudoParam = (ApiKeyAuth) defaultClient.getAuthentication("SudoParam");
SudoParam.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//SudoParam.setApiKeyPrefix("Token");

// Configure API key authorization: TOTPHeader
ApiKeyAuth TOTPHeader = (ApiKeyAuth) defaultClient.getAuthentication("TOTPHeader");
TOTPHeader.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//TOTPHeader.setApiKeyPrefix("Token");

// Configure API key authorization: Token
ApiKeyAuth Token = (ApiKeyAuth) defaultClient.getAuthentication("Token");
Token.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//Token.setApiKeyPrefix("Token");

UserApi apiInstance = new UserApi();
try {
    GPGKey result = apiInstance.userVerifyGPGKey();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling UserApi#userVerifyGPGKey");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**GPGKey**](GPGKey.md)

### Authorization

[AccessToken](../README.md#AccessToken), [AuthorizationHeaderToken](../README.md#AuthorizationHeaderToken), [BasicAuth](../README.md#BasicAuth), [SudoHeader](../README.md#SudoHeader), [SudoParam](../README.md#SudoParam), [TOTPHeader](../README.md#TOTPHeader), [Token](../README.md#Token)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

