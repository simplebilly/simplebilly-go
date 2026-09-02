# \MarketplaceApiAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateConnectionApi**](MarketplaceApiAPI.md#CreateConnectionApi) | **Post** /api/v1/marketplace/connections | Create a new connection (for API-key based platforms)
[**DeleteConnectionApi**](MarketplaceApiAPI.md#DeleteConnectionApi) | **Delete** /api/v1/marketplace/connections/{connection_id} | Soft-delete a connection
[**GetConnectionApi**](MarketplaceApiAPI.md#GetConnectionApi) | **Get** /api/v1/marketplace/connections/{connection_id} | Get a single connection
[**GetSyncDirectionApi**](MarketplaceApiAPI.md#GetSyncDirectionApi) | **Get** /api/v1/marketplace/connections/{connection_id}/directions | Get current sync direction configuration for a connection
[**GetSyncLogsApi**](MarketplaceApiAPI.md#GetSyncLogsApi) | **Get** /api/v1/marketplace/connections/{connection_id}/logs | Get sync logs for a connection
[**ListConnectionsApi**](MarketplaceApiAPI.md#ListConnectionsApi) | **Get** /api/v1/marketplace/connections | List connections for the current tenant
[**ListPlatformsApi**](MarketplaceApiAPI.md#ListPlatformsApi) | **Get** /api/v1/marketplace/platforms | List all supported platforms
[**OauthAuthorizeApi**](MarketplaceApiAPI.md#OauthAuthorizeApi) | **Post** /api/v1/marketplace/oauth/authorize | OAuth: initiate authorization flow
[**OauthCallbackApi**](MarketplaceApiAPI.md#OauthCallbackApi) | **Post** /api/v1/marketplace/oauth/callback | OAuth: handle callback after authorization
[**TriggerSyncApi**](MarketplaceApiAPI.md#TriggerSyncApi) | **Post** /api/v1/marketplace/connections/{connection_id}/sync | Trigger sync for a connection
[**UpdateConnectionApi**](MarketplaceApiAPI.md#UpdateConnectionApi) | **Put** /api/v1/marketplace/connections/{connection_id} | Update a connection
[**UpdateSyncDirectionApi**](MarketplaceApiAPI.md#UpdateSyncDirectionApi) | **Put** /api/v1/marketplace/connections/{connection_id}/directions | Update per-entity sync direction configuration for a connection
[**WebhookReceiverApi**](MarketplaceApiAPI.md#WebhookReceiverApi) | **Post** /api/v1/marketplace/webhook/{platform}/{connection_id} | Webhook receiver



## CreateConnectionApi

> MarketplaceConnection CreateConnectionApi(ctx).CreateConnectionRequest(createConnectionRequest).Execute()

Create a new connection (for API-key based platforms)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	createConnectionRequest := *openapiclient.NewCreateConnectionRequest("Label_example", "Platform_example") // CreateConnectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.CreateConnectionApi(context.Background()).CreateConnectionRequest(createConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.CreateConnectionApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateConnectionApi`: MarketplaceConnection
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.CreateConnectionApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateConnectionApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createConnectionRequest** | [**CreateConnectionRequest**](CreateConnectionRequest.md) |  | 

### Return type

[**MarketplaceConnection**](MarketplaceConnection.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteConnectionApi

> DeleteConnectionApi(ctx, connectionId).Execute()

Soft-delete a connection

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionId := "connectionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MarketplaceApiAPI.DeleteConnectionApi(context.Background(), connectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.DeleteConnectionApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteConnectionApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConnectionApi

> MarketplaceConnection GetConnectionApi(ctx, connectionId).Execute()

Get a single connection

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionId := "connectionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.GetConnectionApi(context.Background(), connectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.GetConnectionApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnectionApi`: MarketplaceConnection
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.GetConnectionApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MarketplaceConnection**](MarketplaceConnection.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSyncDirectionApi

> GetSyncDirectionApi(ctx, connectionId).Execute()

Get current sync direction configuration for a connection

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionId := "connectionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MarketplaceApiAPI.GetSyncDirectionApi(context.Background(), connectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.GetSyncDirectionApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSyncDirectionApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSyncLogsApi

> []SyncLog GetSyncLogsApi(ctx, connectionId).Execute()

Get sync logs for a connection

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionId := "connectionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.GetSyncLogsApi(context.Background(), connectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.GetSyncLogsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSyncLogsApi`: []SyncLog
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.GetSyncLogsApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSyncLogsApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]SyncLog**](SyncLog.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListConnectionsApi

> []MarketplaceConnection ListConnectionsApi(ctx).Execute()

List connections for the current tenant

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.ListConnectionsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.ListConnectionsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListConnectionsApi`: []MarketplaceConnection
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.ListConnectionsApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListConnectionsApiRequest struct via the builder pattern


### Return type

[**[]MarketplaceConnection**](MarketplaceConnection.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPlatformsApi

> []PlatformInfo ListPlatformsApi(ctx).Execute()

List all supported platforms

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.ListPlatformsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.ListPlatformsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPlatformsApi`: []PlatformInfo
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.ListPlatformsApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPlatformsApiRequest struct via the builder pattern


### Return type

[**[]PlatformInfo**](PlatformInfo.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OauthAuthorizeApi

> OAuthAuthorizeResponse OauthAuthorizeApi(ctx).OAuthAuthorizeRequest(oAuthAuthorizeRequest).Execute()

OAuth: initiate authorization flow

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	oAuthAuthorizeRequest := *openapiclient.NewOAuthAuthorizeRequest("Platform_example", "RedirectUri_example") // OAuthAuthorizeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.OauthAuthorizeApi(context.Background()).OAuthAuthorizeRequest(oAuthAuthorizeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.OauthAuthorizeApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OauthAuthorizeApi`: OAuthAuthorizeResponse
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.OauthAuthorizeApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOauthAuthorizeApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oAuthAuthorizeRequest** | [**OAuthAuthorizeRequest**](OAuthAuthorizeRequest.md) |  | 

### Return type

[**OAuthAuthorizeResponse**](OAuthAuthorizeResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OauthCallbackApi

> MarketplaceConnection OauthCallbackApi(ctx).OAuthCallbackRequest(oAuthCallbackRequest).Execute()

OAuth: handle callback after authorization

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	oAuthCallbackRequest := *openapiclient.NewOAuthCallbackRequest("Code_example", "Platform_example", "State_example") // OAuthCallbackRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.OauthCallbackApi(context.Background()).OAuthCallbackRequest(oAuthCallbackRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.OauthCallbackApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OauthCallbackApi`: MarketplaceConnection
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.OauthCallbackApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOauthCallbackApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oAuthCallbackRequest** | [**OAuthCallbackRequest**](OAuthCallbackRequest.md) |  | 

### Return type

[**MarketplaceConnection**](MarketplaceConnection.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TriggerSyncApi

> SyncSummary TriggerSyncApi(ctx, connectionId).SyncType(syncType).Direction(direction).Execute()

Trigger sync for a connection

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionId := "connectionId_example" // string | 
	syncType := "syncType_example" // string |  (optional)
	direction := "direction_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.TriggerSyncApi(context.Background(), connectionId).SyncType(syncType).Direction(direction).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.TriggerSyncApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TriggerSyncApi`: SyncSummary
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.TriggerSyncApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTriggerSyncApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **syncType** | **string** |  | 
 **direction** | **string** |  | 

### Return type

[**SyncSummary**](SyncSummary.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateConnectionApi

> MarketplaceConnection UpdateConnectionApi(ctx, connectionId).UpdateConnectionRequest(updateConnectionRequest).Execute()

Update a connection

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionId := "connectionId_example" // string | 
	updateConnectionRequest := *openapiclient.NewUpdateConnectionRequest() // UpdateConnectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceApiAPI.UpdateConnectionApi(context.Background(), connectionId).UpdateConnectionRequest(updateConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.UpdateConnectionApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateConnectionApi`: MarketplaceConnection
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceApiAPI.UpdateConnectionApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateConnectionApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateConnectionRequest** | [**UpdateConnectionRequest**](UpdateConnectionRequest.md) |  | 

### Return type

[**MarketplaceConnection**](MarketplaceConnection.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSyncDirectionApi

> UpdateSyncDirectionApi(ctx, connectionId).UpdateSyncDirectionRequest(updateSyncDirectionRequest).Execute()

Update per-entity sync direction configuration for a connection

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionId := "connectionId_example" // string | 
	updateSyncDirectionRequest := *openapiclient.NewUpdateSyncDirectionRequest(map[string]string{"key": "Inner_example"}) // UpdateSyncDirectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MarketplaceApiAPI.UpdateSyncDirectionApi(context.Background(), connectionId).UpdateSyncDirectionRequest(updateSyncDirectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.UpdateSyncDirectionApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSyncDirectionApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateSyncDirectionRequest** | [**UpdateSyncDirectionRequest**](UpdateSyncDirectionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WebhookReceiverApi

> WebhookReceiverApi(ctx, platform, connectionId).Execute()

Webhook receiver

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	platform := "platform_example" // string | 
	connectionId := "connectionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MarketplaceApiAPI.WebhookReceiverApi(context.Background(), platform, connectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceApiAPI.WebhookReceiverApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**platform** | **string** |  | 
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiWebhookReceiverApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

