# \GoodsReceiptAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateGoodsReceipt**](GoodsReceiptAPI.md#CreateGoodsReceipt) | **Post** /api/v1/goods-receipts | 
[**DeleteGoodsReceipt**](GoodsReceiptAPI.md#DeleteGoodsReceipt) | **Delete** /api/v1/goods-receipts/{goods_receipt_id} | 
[**GetGoodsReceipt**](GoodsReceiptAPI.md#GetGoodsReceipt) | **Get** /api/v1/goods-receipts/{goods_receipt_id} | 
[**ListGoodsReceipts**](GoodsReceiptAPI.md#ListGoodsReceipts) | **Get** /api/v1/goods-receipts/ | 



## CreateGoodsReceipt

> GoodsReceipt CreateGoodsReceipt(ctx).GoodsReceipt(goodsReceipt).Execute()



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
	goodsReceipt := *openapiclient.NewGoodsReceipt("GrNumber_example", interface{}(123), time.Now(), "WarehouseId_example") // GoodsReceipt | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GoodsReceiptAPI.CreateGoodsReceipt(context.Background()).GoodsReceipt(goodsReceipt).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GoodsReceiptAPI.CreateGoodsReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGoodsReceipt`: GoodsReceipt
	fmt.Fprintf(os.Stdout, "Response from `GoodsReceiptAPI.CreateGoodsReceipt`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateGoodsReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **goodsReceipt** | [**GoodsReceipt**](GoodsReceipt.md) |  | 

### Return type

[**GoodsReceipt**](GoodsReceipt.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteGoodsReceipt

> DeleteGoodsReceipt(ctx, goodsReceiptId).Execute()



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
	goodsReceiptId := "goodsReceiptId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GoodsReceiptAPI.DeleteGoodsReceipt(context.Background(), goodsReceiptId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GoodsReceiptAPI.DeleteGoodsReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**goodsReceiptId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteGoodsReceiptRequest struct via the builder pattern


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


## GetGoodsReceipt

> GoodsReceipt GetGoodsReceipt(ctx, goodsReceiptId).Execute()



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
	goodsReceiptId := "goodsReceiptId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GoodsReceiptAPI.GetGoodsReceipt(context.Background(), goodsReceiptId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GoodsReceiptAPI.GetGoodsReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGoodsReceipt`: GoodsReceipt
	fmt.Fprintf(os.Stdout, "Response from `GoodsReceiptAPI.GetGoodsReceipt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**goodsReceiptId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGoodsReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GoodsReceipt**](GoodsReceipt.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGoodsReceipts

> []GoodsReceipt ListGoodsReceipts(ctx).Page(page).PageSize(pageSize).PurchaseOrderId(purchaseOrderId).SupplierName(supplierName).WarehouseId(warehouseId).Execute()



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
	purchaseOrderId := "purchaseOrderId_example" // string |  (optional)
	supplierName := "supplierName_example" // string |  (optional)
	warehouseId := "warehouseId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GoodsReceiptAPI.ListGoodsReceipts(context.Background()).Page(page).PageSize(pageSize).PurchaseOrderId(purchaseOrderId).SupplierName(supplierName).WarehouseId(warehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GoodsReceiptAPI.ListGoodsReceipts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGoodsReceipts`: []GoodsReceipt
	fmt.Fprintf(os.Stdout, "Response from `GoodsReceiptAPI.ListGoodsReceipts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGoodsReceiptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **purchaseOrderId** | **string** |  | 
 **supplierName** | **string** |  | 
 **warehouseId** | **string** |  | 

### Return type

[**[]GoodsReceipt**](GoodsReceipt.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

