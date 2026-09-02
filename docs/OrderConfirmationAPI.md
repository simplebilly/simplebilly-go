# \OrderConfirmationAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateConfirmation**](OrderConfirmationAPI.md#CreateConfirmation) | **Post** /api/v1/order-confirmations | 
[**DeleteConfirmation**](OrderConfirmationAPI.md#DeleteConfirmation) | **Delete** /api/v1/order-confirmations/{confirmation_id} | 
[**DownloadConfirmationPdf**](OrderConfirmationAPI.md#DownloadConfirmationPdf) | **Get** /api/v1/order-confirmations/{confirmation_id}/pdf | 
[**GetConfirmation**](OrderConfirmationAPI.md#GetConfirmation) | **Get** /api/v1/order-confirmations/{confirmation_id} | 
[**ListConfirmations**](OrderConfirmationAPI.md#ListConfirmations) | **Get** /api/v1/order-confirmations/ | 
[**OrderconfirmationRestore**](OrderConfirmationAPI.md#OrderconfirmationRestore) | **Post** /api/v1/order-confirmations/{confirmation_id}/restore | 
[**PursueConfirmation**](OrderConfirmationAPI.md#PursueConfirmation) | **Post** /api/v1/order-confirmations/{confirmation_id}/pursue | 



## CreateConfirmation

> OrderConfirmation CreateConfirmation(ctx).OrderConfirmationCreate(orderConfirmationCreate).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	orderConfirmationCreate := *openapiclient.NewOrderConfirmationCreate("Currency_example", time.Now(), openapiclient.VoucherStatus("open")) // OrderConfirmationCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderConfirmationAPI.CreateConfirmation(context.Background()).OrderConfirmationCreate(orderConfirmationCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderConfirmationAPI.CreateConfirmation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateConfirmation`: OrderConfirmation
	fmt.Fprintf(os.Stdout, "Response from `OrderConfirmationAPI.CreateConfirmation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateConfirmationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderConfirmationCreate** | [**OrderConfirmationCreate**](OrderConfirmationCreate.md) |  | 

### Return type

[**OrderConfirmation**](OrderConfirmation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteConfirmation

> DeleteConfirmation(ctx, confirmationId).Execute()



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
	confirmationId := "confirmationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OrderConfirmationAPI.DeleteConfirmation(context.Background(), confirmationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderConfirmationAPI.DeleteConfirmation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**confirmationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteConfirmationRequest struct via the builder pattern


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


## DownloadConfirmationPdf

> DownloadConfirmationPdf(ctx, confirmationId).Execute()



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
	confirmationId := "confirmationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OrderConfirmationAPI.DownloadConfirmationPdf(context.Background(), confirmationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderConfirmationAPI.DownloadConfirmationPdf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**confirmationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadConfirmationPdfRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConfirmation

> OrderConfirmation GetConfirmation(ctx, confirmationId).Execute()



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
	confirmationId := "confirmationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderConfirmationAPI.GetConfirmation(context.Background(), confirmationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderConfirmationAPI.GetConfirmation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConfirmation`: OrderConfirmation
	fmt.Fprintf(os.Stdout, "Response from `OrderConfirmationAPI.GetConfirmation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**confirmationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConfirmationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderConfirmation**](OrderConfirmation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListConfirmations

> []OrderConfirmation ListConfirmations(ctx).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()



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
	page := int32(1) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	search := "search_example" // string |  (optional)
	includeDeleted := true // bool | Soft-delete entities: set true to include rows with `deleted_at` set. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderConfirmationAPI.ListConfirmations(context.Background()).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderConfirmationAPI.ListConfirmations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListConfirmations`: []OrderConfirmation
	fmt.Fprintf(os.Stdout, "Response from `OrderConfirmationAPI.ListConfirmations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListConfirmationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 
 **includeDeleted** | **bool** | Soft-delete entities: set true to include rows with &#x60;deleted_at&#x60; set. | 

### Return type

[**[]OrderConfirmation**](OrderConfirmation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrderconfirmationRestore

> OrderConfirmation OrderconfirmationRestore(ctx, confirmationId).Execute()



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
	confirmationId := "confirmationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderConfirmationAPI.OrderconfirmationRestore(context.Background(), confirmationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderConfirmationAPI.OrderconfirmationRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrderconfirmationRestore`: OrderConfirmation
	fmt.Fprintf(os.Stdout, "Response from `OrderConfirmationAPI.OrderconfirmationRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**confirmationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrderconfirmationRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderConfirmation**](OrderConfirmation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PursueConfirmation

> DeliveryNote PursueConfirmation(ctx, confirmationId).Execute()



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
	confirmationId := "confirmationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderConfirmationAPI.PursueConfirmation(context.Background(), confirmationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderConfirmationAPI.PursueConfirmation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PursueConfirmation`: DeliveryNote
	fmt.Fprintf(os.Stdout, "Response from `OrderConfirmationAPI.PursueConfirmation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**confirmationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPursueConfirmationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeliveryNote**](DeliveryNote.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

