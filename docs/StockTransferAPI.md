# \StockTransferAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateStockTransfer**](StockTransferAPI.md#CreateStockTransfer) | **Post** /api/v1/stock-transfers | 
[**DeleteStockTransfer**](StockTransferAPI.md#DeleteStockTransfer) | **Delete** /api/v1/stock-transfers/{stock_transfer_id} | 
[**GetStockTransfer**](StockTransferAPI.md#GetStockTransfer) | **Get** /api/v1/stock-transfers/{stock_transfer_id} | 
[**ListStockTransfers**](StockTransferAPI.md#ListStockTransfers) | **Get** /api/v1/stock-transfers/ | 
[**UpdateStockTransferStatus**](StockTransferAPI.md#UpdateStockTransferStatus) | **Put** /api/v1/stock-transfers/{stock_transfer_id}/status | 



## CreateStockTransfer

> StockTransfer CreateStockTransfer(ctx).StockTransfer(stockTransfer).Execute()



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
	stockTransfer := *openapiclient.NewStockTransfer(interface{}(123), "SourceWarehouseId_example", openapiclient.StockTransferStatus("draft"), "TargetWarehouseId_example", time.Now(), "TransferNumber_example") // StockTransfer | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StockTransferAPI.CreateStockTransfer(context.Background()).StockTransfer(stockTransfer).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StockTransferAPI.CreateStockTransfer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateStockTransfer`: StockTransfer
	fmt.Fprintf(os.Stdout, "Response from `StockTransferAPI.CreateStockTransfer`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateStockTransferRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stockTransfer** | [**StockTransfer**](StockTransfer.md) |  | 

### Return type

[**StockTransfer**](StockTransfer.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteStockTransfer

> DeleteStockTransfer(ctx, stockTransferId).Execute()



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
	stockTransferId := "stockTransferId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.StockTransferAPI.DeleteStockTransfer(context.Background(), stockTransferId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StockTransferAPI.DeleteStockTransfer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**stockTransferId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteStockTransferRequest struct via the builder pattern


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


## GetStockTransfer

> StockTransfer GetStockTransfer(ctx, stockTransferId).Execute()



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
	stockTransferId := "stockTransferId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StockTransferAPI.GetStockTransfer(context.Background(), stockTransferId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StockTransferAPI.GetStockTransfer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStockTransfer`: StockTransfer
	fmt.Fprintf(os.Stdout, "Response from `StockTransferAPI.GetStockTransfer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**stockTransferId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStockTransferRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StockTransfer**](StockTransfer.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListStockTransfers

> []StockTransfer ListStockTransfers(ctx).Page(page).PageSize(pageSize).Status(status).WarehouseId(warehouseId).Execute()



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
	status := "status_example" // string |  (optional)
	warehouseId := "warehouseId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StockTransferAPI.ListStockTransfers(context.Background()).Page(page).PageSize(pageSize).Status(status).WarehouseId(warehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StockTransferAPI.ListStockTransfers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListStockTransfers`: []StockTransfer
	fmt.Fprintf(os.Stdout, "Response from `StockTransferAPI.ListStockTransfers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListStockTransfersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **warehouseId** | **string** |  | 

### Return type

[**[]StockTransfer**](StockTransfer.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateStockTransferStatus

> StockTransfer UpdateStockTransferStatus(ctx, stockTransferId).StockTransferStatusUpdate(stockTransferStatusUpdate).Execute()



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
	stockTransferId := "stockTransferId_example" // string | 
	stockTransferStatusUpdate := *openapiclient.NewStockTransferStatusUpdate("Status_example") // StockTransferStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StockTransferAPI.UpdateStockTransferStatus(context.Background(), stockTransferId).StockTransferStatusUpdate(stockTransferStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StockTransferAPI.UpdateStockTransferStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateStockTransferStatus`: StockTransfer
	fmt.Fprintf(os.Stdout, "Response from `StockTransferAPI.UpdateStockTransferStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**stockTransferId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateStockTransferStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **stockTransferStatusUpdate** | [**StockTransferStatusUpdate**](StockTransferStatusUpdate.md) |  | 

### Return type

[**StockTransfer**](StockTransfer.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

