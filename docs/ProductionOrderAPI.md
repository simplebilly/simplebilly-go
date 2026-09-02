# \ProductionOrderAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProductionOrder**](ProductionOrderAPI.md#CreateProductionOrder) | **Post** /api/v1/production-orders | 
[**DeleteProductionOrder**](ProductionOrderAPI.md#DeleteProductionOrder) | **Delete** /api/v1/production-orders/{production_order_id} | 
[**GetProductionOrder**](ProductionOrderAPI.md#GetProductionOrder) | **Get** /api/v1/production-orders/{production_order_id} | 
[**ListProductionOrders**](ProductionOrderAPI.md#ListProductionOrders) | **Get** /api/v1/production-orders/ | 
[**ProductionOrderCosting**](ProductionOrderAPI.md#ProductionOrderCosting) | **Get** /api/v1/production-orders/{production_order_id}/costing | Actual-costing report (Nachkalkulation) — material costs from BOM components at their purchase price plus the resulting per-unit cost and margin against the finished product&#39;s sale price.
[**UpdateProductionOrder**](ProductionOrderAPI.md#UpdateProductionOrder) | **Put** /api/v1/production-orders/{production_order_id} | 
[**UpdateProductionOrderStatus**](ProductionOrderAPI.md#UpdateProductionOrderStatus) | **Put** /api/v1/production-orders/{production_order_id}/status | 



## CreateProductionOrder

> ProductionOrder CreateProductionOrder(ctx).ProductionOrder(productionOrder).Execute()



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
	productionOrder := *openapiclient.NewProductionOrder("OrderNumber_example", "ProductId_example", int64(123)) // ProductionOrder | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOrderAPI.CreateProductionOrder(context.Background()).ProductionOrder(productionOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOrderAPI.CreateProductionOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProductionOrder`: ProductionOrder
	fmt.Fprintf(os.Stdout, "Response from `ProductionOrderAPI.CreateProductionOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProductionOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productionOrder** | [**ProductionOrder**](ProductionOrder.md) |  | 

### Return type

[**ProductionOrder**](ProductionOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProductionOrder

> DeleteProductionOrder(ctx, productionOrderId).Execute()



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
	productionOrderId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProductionOrderAPI.DeleteProductionOrder(context.Background(), productionOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOrderAPI.DeleteProductionOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**productionOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProductionOrderRequest struct via the builder pattern


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


## GetProductionOrder

> ProductionOrder GetProductionOrder(ctx, productionOrderId).Execute()



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
	productionOrderId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOrderAPI.GetProductionOrder(context.Background(), productionOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOrderAPI.GetProductionOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProductionOrder`: ProductionOrder
	fmt.Fprintf(os.Stdout, "Response from `ProductionOrderAPI.GetProductionOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**productionOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProductionOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOrder**](ProductionOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProductionOrders

> []ProductionOrder ListProductionOrders(ctx).Page(page).PageSize(pageSize).Search(search).Status(status).Execute()



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
	search := "search_example" // string |  (optional)
	status := "status_example" // string | Filter by status. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOrderAPI.ListProductionOrders(context.Background()).Page(page).PageSize(pageSize).Search(search).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOrderAPI.ListProductionOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProductionOrders`: []ProductionOrder
	fmt.Fprintf(os.Stdout, "Response from `ProductionOrderAPI.ListProductionOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListProductionOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 
 **status** | **string** | Filter by status. | 

### Return type

[**[]ProductionOrder**](ProductionOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductionOrderCosting

> ProductionOrderCosting ProductionOrderCosting(ctx, productionOrderId).Execute()

Actual-costing report (Nachkalkulation) — material costs from BOM components at their purchase price plus the resulting per-unit cost and margin against the finished product's sale price.

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
	productionOrderId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOrderAPI.ProductionOrderCosting(context.Background(), productionOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOrderAPI.ProductionOrderCosting``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductionOrderCosting`: ProductionOrderCosting
	fmt.Fprintf(os.Stdout, "Response from `ProductionOrderAPI.ProductionOrderCosting`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**productionOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductionOrderCostingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductionOrderCosting**](ProductionOrderCosting.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProductionOrder

> ProductionOrder UpdateProductionOrder(ctx, productionOrderId).ProductionOrder(productionOrder).Execute()



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
	productionOrderId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	productionOrder := *openapiclient.NewProductionOrder("OrderNumber_example", "ProductId_example", int64(123)) // ProductionOrder | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOrderAPI.UpdateProductionOrder(context.Background(), productionOrderId).ProductionOrder(productionOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOrderAPI.UpdateProductionOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProductionOrder`: ProductionOrder
	fmt.Fprintf(os.Stdout, "Response from `ProductionOrderAPI.UpdateProductionOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**productionOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProductionOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOrder** | [**ProductionOrder**](ProductionOrder.md) |  | 

### Return type

[**ProductionOrder**](ProductionOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProductionOrderStatus

> ProductionOrder UpdateProductionOrderStatus(ctx, productionOrderId).ProductionOrderStatusUpdate(productionOrderStatusUpdate).Execute()



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
	productionOrderId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	productionOrderStatusUpdate := *openapiclient.NewProductionOrderStatusUpdate("Status_example") // ProductionOrderStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductionOrderAPI.UpdateProductionOrderStatus(context.Background(), productionOrderId).ProductionOrderStatusUpdate(productionOrderStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductionOrderAPI.UpdateProductionOrderStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProductionOrderStatus`: ProductionOrder
	fmt.Fprintf(os.Stdout, "Response from `ProductionOrderAPI.UpdateProductionOrderStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**productionOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProductionOrderStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productionOrderStatusUpdate** | [**ProductionOrderStatusUpdate**](ProductionOrderStatusUpdate.md) |  | 

### Return type

[**ProductionOrder**](ProductionOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

