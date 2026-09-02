# \PaymentGatewayAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePaymentGatewayApi**](PaymentGatewayAPI.md#CreatePaymentGatewayApi) | **Post** /api/v1/payment-gateways | 
[**DeletePaymentGatewayApi**](PaymentGatewayAPI.md#DeletePaymentGatewayApi) | **Delete** /api/v1/payment-gateways/{gateway_id} | 
[**ListPaymentGatewaysApi**](PaymentGatewayAPI.md#ListPaymentGatewaysApi) | **Get** /api/v1/payment-gateways/ | 
[**OauthAuthorizeApi**](PaymentGatewayAPI.md#OauthAuthorizeApi) | **Post** /api/v1/payment-gateways/oauth/authorize | 
[**OauthCallbackApi**](PaymentGatewayAPI.md#OauthCallbackApi) | **Post** /api/v1/payment-gateways/oauth/callback | 
[**UpdatePaymentGatewayApi**](PaymentGatewayAPI.md#UpdatePaymentGatewayApi) | **Put** /api/v1/payment-gateways/{gateway_id} | 



## CreatePaymentGatewayApi

> PaymentGateway CreatePaymentGatewayApi(ctx).Body(body).Execute()



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
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewayAPI.CreatePaymentGatewayApi(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewayAPI.CreatePaymentGatewayApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePaymentGatewayApi`: PaymentGateway
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewayAPI.CreatePaymentGatewayApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePaymentGatewayApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **interface{}** |  | 

### Return type

[**PaymentGateway**](PaymentGateway.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePaymentGatewayApi

> DeletePaymentGatewayApi(ctx, gatewayId).Execute()



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
	gatewayId := "gatewayId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PaymentGatewayAPI.DeletePaymentGatewayApi(context.Background(), gatewayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewayAPI.DeletePaymentGatewayApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**gatewayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePaymentGatewayApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPaymentGatewaysApi

> []PaymentGateway ListPaymentGatewaysApi(ctx).Execute()



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
	resp, r, err := apiClient.PaymentGatewayAPI.ListPaymentGatewaysApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewayAPI.ListPaymentGatewaysApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPaymentGatewaysApi`: []PaymentGateway
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewayAPI.ListPaymentGatewaysApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPaymentGatewaysApiRequest struct via the builder pattern


### Return type

[**[]PaymentGateway**](PaymentGateway.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OauthAuthorizeApi

> GatewayOAuthAuthorizeResponse OauthAuthorizeApi(ctx).GatewayOAuthAuthorizeRequest(gatewayOAuthAuthorizeRequest).Execute()



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
	gatewayOAuthAuthorizeRequest := *openapiclient.NewGatewayOAuthAuthorizeRequest("GatewayType_example", "RedirectUri_example") // GatewayOAuthAuthorizeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewayAPI.OauthAuthorizeApi(context.Background()).GatewayOAuthAuthorizeRequest(gatewayOAuthAuthorizeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewayAPI.OauthAuthorizeApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OauthAuthorizeApi`: GatewayOAuthAuthorizeResponse
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewayAPI.OauthAuthorizeApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOauthAuthorizeApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **gatewayOAuthAuthorizeRequest** | [**GatewayOAuthAuthorizeRequest**](GatewayOAuthAuthorizeRequest.md) |  | 

### Return type

[**GatewayOAuthAuthorizeResponse**](GatewayOAuthAuthorizeResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OauthCallbackApi

> PaymentGateway OauthCallbackApi(ctx).GatewayOAuthCallbackRequest(gatewayOAuthCallbackRequest).Execute()



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
	gatewayOAuthCallbackRequest := *openapiclient.NewGatewayOAuthCallbackRequest("Code_example", "GatewayType_example", "RedirectUri_example", "State_example") // GatewayOAuthCallbackRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewayAPI.OauthCallbackApi(context.Background()).GatewayOAuthCallbackRequest(gatewayOAuthCallbackRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewayAPI.OauthCallbackApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OauthCallbackApi`: PaymentGateway
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewayAPI.OauthCallbackApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOauthCallbackApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **gatewayOAuthCallbackRequest** | [**GatewayOAuthCallbackRequest**](GatewayOAuthCallbackRequest.md) |  | 

### Return type

[**PaymentGateway**](PaymentGateway.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePaymentGatewayApi

> PaymentGateway UpdatePaymentGatewayApi(ctx, gatewayId).Body(body).Execute()



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
	gatewayId := "gatewayId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewayAPI.UpdatePaymentGatewayApi(context.Background(), gatewayId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewayAPI.UpdatePaymentGatewayApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePaymentGatewayApi`: PaymentGateway
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewayAPI.UpdatePaymentGatewayApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**gatewayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePaymentGatewayApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**PaymentGateway**](PaymentGateway.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

