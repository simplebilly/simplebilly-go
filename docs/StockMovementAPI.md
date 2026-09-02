# \StockMovementAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetStockMovement**](StockMovementAPI.md#GetStockMovement) | **Get** /api/v1/stock-movements/{movement_id} | 
[**ListStockMovements**](StockMovementAPI.md#ListStockMovements) | **Get** /api/v1/stock-movements/ | 



## GetStockMovement

> StockMovement GetStockMovement(ctx, movementId).Execute()



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
	movementId := "movementId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StockMovementAPI.GetStockMovement(context.Background(), movementId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StockMovementAPI.GetStockMovement``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStockMovement`: StockMovement
	fmt.Fprintf(os.Stdout, "Response from `StockMovementAPI.GetStockMovement`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**movementId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStockMovementRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StockMovement**](StockMovement.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListStockMovements

> []StockMovement ListStockMovements(ctx).Page(page).PageSize(pageSize).ProductId(productId).WarehouseId(warehouseId).MovementType(movementType).From(from).To(to).Execute()



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
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	warehouseId := "warehouseId_example" // string |  (optional)
	movementType := "movementType_example" // string |  (optional)
	from := time.Now() // string | Only movements on or after this date (inclusive). (optional)
	to := time.Now() // string | Only movements on or before this date (inclusive). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StockMovementAPI.ListStockMovements(context.Background()).Page(page).PageSize(pageSize).ProductId(productId).WarehouseId(warehouseId).MovementType(movementType).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StockMovementAPI.ListStockMovements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListStockMovements`: []StockMovement
	fmt.Fprintf(os.Stdout, "Response from `StockMovementAPI.ListStockMovements`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListStockMovementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **productId** | **string** |  | 
 **warehouseId** | **string** |  | 
 **movementType** | **string** |  | 
 **from** | **string** | Only movements on or after this date (inclusive). | 
 **to** | **string** | Only movements on or before this date (inclusive). | 

### Return type

[**[]StockMovement**](StockMovement.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

