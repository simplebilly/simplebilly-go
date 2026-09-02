# \ShippingThresholdAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateShippingThreshold**](ShippingThresholdAPI.md#CreateShippingThreshold) | **Post** /api/v1/shipping-thresholds | 
[**DeleteShippingThreshold**](ShippingThresholdAPI.md#DeleteShippingThreshold) | **Delete** /api/v1/shipping-thresholds/{threshold_id} | 
[**GetDeliverable**](ShippingThresholdAPI.md#GetDeliverable) | **Get** /api/v1/shipping-thresholds/deliverable | 
[**GetShippingThreshold**](ShippingThresholdAPI.md#GetShippingThreshold) | **Get** /api/v1/shipping-thresholds/{threshold_id} | 
[**ListShippingThresholds**](ShippingThresholdAPI.md#ListShippingThresholds) | **Get** /api/v1/shipping-thresholds/ | 
[**UpdateShippingThreshold**](ShippingThresholdAPI.md#UpdateShippingThreshold) | **Put** /api/v1/shipping-thresholds/{threshold_id} | 



## CreateShippingThreshold

> ShippingThreshold CreateShippingThreshold(ctx).ShippingThresholdCreate(shippingThresholdCreate).Execute()



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
	shippingThresholdCreate := *openapiclient.NewShippingThresholdCreate("Name_example") // ShippingThresholdCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingThresholdAPI.CreateShippingThreshold(context.Background()).ShippingThresholdCreate(shippingThresholdCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingThresholdAPI.CreateShippingThreshold``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateShippingThreshold`: ShippingThreshold
	fmt.Fprintf(os.Stdout, "Response from `ShippingThresholdAPI.CreateShippingThreshold`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateShippingThresholdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **shippingThresholdCreate** | [**ShippingThresholdCreate**](ShippingThresholdCreate.md) |  | 

### Return type

[**ShippingThreshold**](ShippingThreshold.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteShippingThreshold

> DeleteShippingThreshold(ctx, thresholdId).Execute()



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
	thresholdId := "thresholdId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ShippingThresholdAPI.DeleteShippingThreshold(context.Background(), thresholdId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingThresholdAPI.DeleteShippingThreshold``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**thresholdId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteShippingThresholdRequest struct via the builder pattern


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


## GetDeliverable

> DeliverableResponse GetDeliverable(ctx).ProductId(productId).WarehouseId(warehouseId).Execute()



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
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	warehouseId := "warehouseId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingThresholdAPI.GetDeliverable(context.Background()).ProductId(productId).WarehouseId(warehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingThresholdAPI.GetDeliverable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliverable`: DeliverableResponse
	fmt.Fprintf(os.Stdout, "Response from `ShippingThresholdAPI.GetDeliverable`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliverableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productId** | **string** |  | 
 **warehouseId** | **string** |  | 

### Return type

[**DeliverableResponse**](DeliverableResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetShippingThreshold

> ShippingThreshold GetShippingThreshold(ctx, thresholdId).Execute()



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
	thresholdId := "thresholdId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingThresholdAPI.GetShippingThreshold(context.Background(), thresholdId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingThresholdAPI.GetShippingThreshold``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetShippingThreshold`: ShippingThreshold
	fmt.Fprintf(os.Stdout, "Response from `ShippingThresholdAPI.GetShippingThreshold`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**thresholdId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetShippingThresholdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ShippingThreshold**](ShippingThreshold.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListShippingThresholds

> []ShippingThreshold ListShippingThresholds(ctx).Page(page).PageSize(pageSize).ProductId(productId).WarehouseId(warehouseId).IsActive(isActive).Execute()



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
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	warehouseId := "warehouseId_example" // string |  (optional)
	isActive := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingThresholdAPI.ListShippingThresholds(context.Background()).Page(page).PageSize(pageSize).ProductId(productId).WarehouseId(warehouseId).IsActive(isActive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingThresholdAPI.ListShippingThresholds``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListShippingThresholds`: []ShippingThreshold
	fmt.Fprintf(os.Stdout, "Response from `ShippingThresholdAPI.ListShippingThresholds`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListShippingThresholdsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **productId** | **string** |  | 
 **warehouseId** | **string** |  | 
 **isActive** | **bool** |  | 

### Return type

[**[]ShippingThreshold**](ShippingThreshold.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateShippingThreshold

> ShippingThreshold UpdateShippingThreshold(ctx, thresholdId).ShippingThresholdUpdate(shippingThresholdUpdate).Execute()



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
	thresholdId := "thresholdId_example" // string | 
	shippingThresholdUpdate := *openapiclient.NewShippingThresholdUpdate() // ShippingThresholdUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingThresholdAPI.UpdateShippingThreshold(context.Background(), thresholdId).ShippingThresholdUpdate(shippingThresholdUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingThresholdAPI.UpdateShippingThreshold``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateShippingThreshold`: ShippingThreshold
	fmt.Fprintf(os.Stdout, "Response from `ShippingThresholdAPI.UpdateShippingThreshold`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**thresholdId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateShippingThresholdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **shippingThresholdUpdate** | [**ShippingThresholdUpdate**](ShippingThresholdUpdate.md) |  | 

### Return type

[**ShippingThreshold**](ShippingThreshold.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

