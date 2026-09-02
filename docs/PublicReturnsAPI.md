# \PublicReturnsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPublicReturnStatus**](PublicReturnsAPI.md#GetPublicReturnStatus) | **Get** /api/v1/public/returns/status | Customer checks the status of a return (public, no auth). The return is only revealed when its linked order&#39;s email matches.
[**ListPublicReturns**](PublicReturnsAPI.md#ListPublicReturns) | **Get** /api/v1/public/returns/list | List all returns for an order (public, no auth).
[**RequestPublicReturn**](PublicReturnsAPI.md#RequestPublicReturn) | **Post** /api/v1/public/returns/request | Customer requests a return for an order (public, no auth).



## GetPublicReturnStatus

> PublicReturnStatusResponse GetPublicReturnStatus(ctx).Email(email).ReturnNumber(returnNumber).ReturnOrderId(returnOrderId).OrderNumber(orderNumber).Execute()

Customer checks the status of a return (public, no auth). The return is only revealed when its linked order's email matches.

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
	email := "email_example" // string | 
	returnNumber := "returnNumber_example" // string | Either return_number or return_order_id must be provided. (optional)
	returnOrderId := "returnOrderId_example" // string |  (optional)
	orderNumber := "orderNumber_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicReturnsAPI.GetPublicReturnStatus(context.Background()).Email(email).ReturnNumber(returnNumber).ReturnOrderId(returnOrderId).OrderNumber(orderNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicReturnsAPI.GetPublicReturnStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicReturnStatus`: PublicReturnStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `PublicReturnsAPI.GetPublicReturnStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicReturnStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email** | **string** |  | 
 **returnNumber** | **string** | Either return_number or return_order_id must be provided. | 
 **returnOrderId** | **string** |  | 
 **orderNumber** | **string** |  | 

### Return type

[**PublicReturnStatusResponse**](PublicReturnStatusResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPublicReturns

> []PublicReturnStatusResponse ListPublicReturns(ctx).OrderNumber(orderNumber).Email(email).Execute()

List all returns for an order (public, no auth).

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
	orderNumber := "orderNumber_example" // string | 
	email := "email_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicReturnsAPI.ListPublicReturns(context.Background()).OrderNumber(orderNumber).Email(email).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicReturnsAPI.ListPublicReturns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPublicReturns`: []PublicReturnStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `PublicReturnsAPI.ListPublicReturns`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPublicReturnsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderNumber** | **string** |  | 
 **email** | **string** |  | 

### Return type

[**[]PublicReturnStatusResponse**](PublicReturnStatusResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestPublicReturn

> PublicReturnResponse RequestPublicReturn(ctx).PublicReturnRequest(publicReturnRequest).Execute()

Customer requests a return for an order (public, no auth).

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
	publicReturnRequest := *openapiclient.NewPublicReturnRequest("Email_example", []openapiclient.PublicReturnItem{*openapiclient.NewPublicReturnItem("ProductId_example", int64(123))}, "OrderNumber_example") // PublicReturnRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicReturnsAPI.RequestPublicReturn(context.Background()).PublicReturnRequest(publicReturnRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicReturnsAPI.RequestPublicReturn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RequestPublicReturn`: PublicReturnResponse
	fmt.Fprintf(os.Stdout, "Response from `PublicReturnsAPI.RequestPublicReturn`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRequestPublicReturnRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **publicReturnRequest** | [**PublicReturnRequest**](PublicReturnRequest.md) |  | 

### Return type

[**PublicReturnResponse**](PublicReturnResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

