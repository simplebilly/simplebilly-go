# \PurchaseOrderAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePurchaseOrder**](PurchaseOrderAPI.md#CreatePurchaseOrder) | **Post** /api/v1/purchase-orders | 
[**DeletePurchaseOrder**](PurchaseOrderAPI.md#DeletePurchaseOrder) | **Delete** /api/v1/purchase-orders/{purchase_order_id} | 
[**GetPurchaseOrder**](PurchaseOrderAPI.md#GetPurchaseOrder) | **Get** /api/v1/purchase-orders/{purchase_order_id} | 
[**ListPurchaseOrders**](PurchaseOrderAPI.md#ListPurchaseOrders) | **Get** /api/v1/purchase-orders/ | 
[**MatchInvoice**](PurchaseOrderAPI.md#MatchInvoice) | **Post** /api/v1/purchase-orders/{purchase_order_id}/match-invoice | 3-way invoice check (Rechnungsprüfung): compares the purchase order line items, the quantities received via goods receipts, and the supplier invoice line items, reporting quantity and price variances per product.
[**UpdatePurchaseOrder**](PurchaseOrderAPI.md#UpdatePurchaseOrder) | **Put** /api/v1/purchase-orders/{purchase_order_id} | 
[**UpdatePurchaseOrderStatus**](PurchaseOrderAPI.md#UpdatePurchaseOrderStatus) | **Put** /api/v1/purchase-orders/{purchase_order_id}/status | 



## CreatePurchaseOrder

> PurchaseOrder CreatePurchaseOrder(ctx).PurchaseOrder(purchaseOrder).Execute()



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
	purchaseOrder := *openapiclient.NewPurchaseOrder(time.Now(), "PoNumber_example", openapiclient.PurchaseOrderStatus("draft")) // PurchaseOrder | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderAPI.CreatePurchaseOrder(context.Background()).PurchaseOrder(purchaseOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderAPI.CreatePurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePurchaseOrder`: PurchaseOrder
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderAPI.CreatePurchaseOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePurchaseOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purchaseOrder** | [**PurchaseOrder**](PurchaseOrder.md) |  | 

### Return type

[**PurchaseOrder**](PurchaseOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePurchaseOrder

> DeletePurchaseOrder(ctx, purchaseOrderId).Execute()



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
	purchaseOrderId := "purchaseOrderId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PurchaseOrderAPI.DeletePurchaseOrder(context.Background(), purchaseOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderAPI.DeletePurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**purchaseOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePurchaseOrderRequest struct via the builder pattern


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


## GetPurchaseOrder

> PurchaseOrder GetPurchaseOrder(ctx, purchaseOrderId).Execute()



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
	purchaseOrderId := "purchaseOrderId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderAPI.GetPurchaseOrder(context.Background(), purchaseOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderAPI.GetPurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPurchaseOrder`: PurchaseOrder
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderAPI.GetPurchaseOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**purchaseOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPurchaseOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PurchaseOrder**](PurchaseOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPurchaseOrders

> []PurchaseOrder ListPurchaseOrders(ctx).Page(page).PageSize(pageSize).Status(status).SupplierName(supplierName).Search(search).Execute()



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
	supplierName := "supplierName_example" // string |  (optional)
	search := "search_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderAPI.ListPurchaseOrders(context.Background()).Page(page).PageSize(pageSize).Status(status).SupplierName(supplierName).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderAPI.ListPurchaseOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPurchaseOrders`: []PurchaseOrder
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderAPI.ListPurchaseOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPurchaseOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **supplierName** | **string** |  | 
 **search** | **string** |  | 

### Return type

[**[]PurchaseOrder**](PurchaseOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MatchInvoice

> interface{} MatchInvoice(ctx, purchaseOrderId).InvoiceMatchRequest(invoiceMatchRequest).Execute()

3-way invoice check (Rechnungsprüfung): compares the purchase order line items, the quantities received via goods receipts, and the supplier invoice line items, reporting quantity and price variances per product.

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
	purchaseOrderId := "purchaseOrderId_example" // string | 
	invoiceMatchRequest := *openapiclient.NewInvoiceMatchRequest("SupplierInvoiceId_example") // InvoiceMatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderAPI.MatchInvoice(context.Background(), purchaseOrderId).InvoiceMatchRequest(invoiceMatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderAPI.MatchInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MatchInvoice`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderAPI.MatchInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**purchaseOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMatchInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **invoiceMatchRequest** | [**InvoiceMatchRequest**](InvoiceMatchRequest.md) |  | 

### Return type

**interface{}**

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePurchaseOrder

> PurchaseOrder UpdatePurchaseOrder(ctx, purchaseOrderId).Body(body).Execute()



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
	purchaseOrderId := "purchaseOrderId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderAPI.UpdatePurchaseOrder(context.Background(), purchaseOrderId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderAPI.UpdatePurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePurchaseOrder`: PurchaseOrder
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderAPI.UpdatePurchaseOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**purchaseOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePurchaseOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**PurchaseOrder**](PurchaseOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePurchaseOrderStatus

> PurchaseOrder UpdatePurchaseOrderStatus(ctx, purchaseOrderId).PurchaseOrderStatusUpdate(purchaseOrderStatusUpdate).Execute()



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
	purchaseOrderId := "purchaseOrderId_example" // string | 
	purchaseOrderStatusUpdate := *openapiclient.NewPurchaseOrderStatusUpdate("Status_example") // PurchaseOrderStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrderAPI.UpdatePurchaseOrderStatus(context.Background(), purchaseOrderId).PurchaseOrderStatusUpdate(purchaseOrderStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrderAPI.UpdatePurchaseOrderStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePurchaseOrderStatus`: PurchaseOrder
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrderAPI.UpdatePurchaseOrderStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**purchaseOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePurchaseOrderStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **purchaseOrderStatusUpdate** | [**PurchaseOrderStatusUpdate**](PurchaseOrderStatusUpdate.md) |  | 

### Return type

[**PurchaseOrder**](PurchaseOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

