# \WarehouseStockAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateWarehouseStock**](WarehouseStockAPI.md#CreateWarehouseStock) | **Post** /api/v1/warehouses/{warehouse_id}/stock | 
[**DeleteWarehouseStock**](WarehouseStockAPI.md#DeleteWarehouseStock) | **Delete** /api/v1/warehouses/{warehouse_id}/stock/{product_id} | 
[**ListWarehouseStock**](WarehouseStockAPI.md#ListWarehouseStock) | **Get** /api/v1/warehouses/{warehouse_id}/stock | 
[**UpdateWarehouseStock**](WarehouseStockAPI.md#UpdateWarehouseStock) | **Put** /api/v1/warehouses/{warehouse_id}/stock/{product_id} | 



## CreateWarehouseStock

> WarehouseStock CreateWarehouseStock(ctx, warehouseId).StockAdjustment(stockAdjustment).Execute()



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
	warehouseId := "warehouseId_example" // string | 
	stockAdjustment := *openapiclient.NewStockAdjustment(int64(123)) // StockAdjustment | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WarehouseStockAPI.CreateWarehouseStock(context.Background(), warehouseId).StockAdjustment(stockAdjustment).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WarehouseStockAPI.CreateWarehouseStock``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWarehouseStock`: WarehouseStock
	fmt.Fprintf(os.Stdout, "Response from `WarehouseStockAPI.CreateWarehouseStock`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**warehouseId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateWarehouseStockRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **stockAdjustment** | [**StockAdjustment**](StockAdjustment.md) |  | 

### Return type

[**WarehouseStock**](WarehouseStock.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteWarehouseStock

> DeleteWarehouseStock(ctx, warehouseId, productId).Execute()



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
	warehouseId := "warehouseId_example" // string | 
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WarehouseStockAPI.DeleteWarehouseStock(context.Background(), warehouseId, productId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WarehouseStockAPI.DeleteWarehouseStock``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**warehouseId** | **string** |  | 
**productId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWarehouseStockRequest struct via the builder pattern


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


## ListWarehouseStock

> []WarehouseStock ListWarehouseStock(ctx, warehouseId).Execute()



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
	warehouseId := "warehouseId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WarehouseStockAPI.ListWarehouseStock(context.Background(), warehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WarehouseStockAPI.ListWarehouseStock``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWarehouseStock`: []WarehouseStock
	fmt.Fprintf(os.Stdout, "Response from `WarehouseStockAPI.ListWarehouseStock`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**warehouseId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListWarehouseStockRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]WarehouseStock**](WarehouseStock.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateWarehouseStock

> WarehouseStock UpdateWarehouseStock(ctx, warehouseId, productId).StockAdjustment(stockAdjustment).Execute()



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
	warehouseId := "warehouseId_example" // string | 
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	stockAdjustment := *openapiclient.NewStockAdjustment(int64(123)) // StockAdjustment | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WarehouseStockAPI.UpdateWarehouseStock(context.Background(), warehouseId, productId).StockAdjustment(stockAdjustment).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WarehouseStockAPI.UpdateWarehouseStock``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWarehouseStock`: WarehouseStock
	fmt.Fprintf(os.Stdout, "Response from `WarehouseStockAPI.UpdateWarehouseStock`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**warehouseId** | **string** |  | 
**productId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateWarehouseStockRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **stockAdjustment** | [**StockAdjustment**](StockAdjustment.md) |  | 

### Return type

[**WarehouseStock**](WarehouseStock.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

