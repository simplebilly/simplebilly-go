# \SupplierInvoiceAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateSupplierInvoice**](SupplierInvoiceAPI.md#CreateSupplierInvoice) | **Post** /api/v1/supplier-invoices | 
[**DeleteSupplierInvoice**](SupplierInvoiceAPI.md#DeleteSupplierInvoice) | **Delete** /api/v1/supplier-invoices/{supplier_invoice_id} | 
[**GetSupplierInvoice**](SupplierInvoiceAPI.md#GetSupplierInvoice) | **Get** /api/v1/supplier-invoices/{supplier_invoice_id} | 
[**ListSupplierInvoices**](SupplierInvoiceAPI.md#ListSupplierInvoices) | **Get** /api/v1/supplier-invoices/ | 
[**UpdateSupplierInvoice**](SupplierInvoiceAPI.md#UpdateSupplierInvoice) | **Put** /api/v1/supplier-invoices/{supplier_invoice_id} | 
[**UpdateSupplierInvoiceStatus**](SupplierInvoiceAPI.md#UpdateSupplierInvoiceStatus) | **Put** /api/v1/supplier-invoices/{supplier_invoice_id}/status | 



## CreateSupplierInvoice

> SupplierInvoice CreateSupplierInvoice(ctx).SupplierInvoice(supplierInvoice).Execute()



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
	supplierInvoice := *openapiclient.NewSupplierInvoice(time.Now(), "InvoiceNumber_example", interface{}(123), openapiclient.SupplierInvoiceStatus("draft")) // SupplierInvoice | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierInvoiceAPI.CreateSupplierInvoice(context.Background()).SupplierInvoice(supplierInvoice).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierInvoiceAPI.CreateSupplierInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateSupplierInvoice`: SupplierInvoice
	fmt.Fprintf(os.Stdout, "Response from `SupplierInvoiceAPI.CreateSupplierInvoice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSupplierInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **supplierInvoice** | [**SupplierInvoice**](SupplierInvoice.md) |  | 

### Return type

[**SupplierInvoice**](SupplierInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteSupplierInvoice

> DeleteSupplierInvoice(ctx, supplierInvoiceId).Execute()



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
	supplierInvoiceId := "supplierInvoiceId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SupplierInvoiceAPI.DeleteSupplierInvoice(context.Background(), supplierInvoiceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierInvoiceAPI.DeleteSupplierInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierInvoiceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteSupplierInvoiceRequest struct via the builder pattern


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


## GetSupplierInvoice

> SupplierInvoice GetSupplierInvoice(ctx, supplierInvoiceId).Execute()



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
	supplierInvoiceId := "supplierInvoiceId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierInvoiceAPI.GetSupplierInvoice(context.Background(), supplierInvoiceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierInvoiceAPI.GetSupplierInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSupplierInvoice`: SupplierInvoice
	fmt.Fprintf(os.Stdout, "Response from `SupplierInvoiceAPI.GetSupplierInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierInvoiceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSupplierInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SupplierInvoice**](SupplierInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSupplierInvoices

> []SupplierInvoice ListSupplierInvoices(ctx).Page(page).PageSize(pageSize).Status(status).PurchaseOrderId(purchaseOrderId).SupplierName(supplierName).Execute()



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
	purchaseOrderId := "purchaseOrderId_example" // string |  (optional)
	supplierName := "supplierName_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierInvoiceAPI.ListSupplierInvoices(context.Background()).Page(page).PageSize(pageSize).Status(status).PurchaseOrderId(purchaseOrderId).SupplierName(supplierName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierInvoiceAPI.ListSupplierInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSupplierInvoices`: []SupplierInvoice
	fmt.Fprintf(os.Stdout, "Response from `SupplierInvoiceAPI.ListSupplierInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListSupplierInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **purchaseOrderId** | **string** |  | 
 **supplierName** | **string** |  | 

### Return type

[**[]SupplierInvoice**](SupplierInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSupplierInvoice

> SupplierInvoice UpdateSupplierInvoice(ctx, supplierInvoiceId).Body(body).Execute()



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
	supplierInvoiceId := "supplierInvoiceId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierInvoiceAPI.UpdateSupplierInvoice(context.Background(), supplierInvoiceId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierInvoiceAPI.UpdateSupplierInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateSupplierInvoice`: SupplierInvoice
	fmt.Fprintf(os.Stdout, "Response from `SupplierInvoiceAPI.UpdateSupplierInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierInvoiceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSupplierInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**SupplierInvoice**](SupplierInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSupplierInvoiceStatus

> SupplierInvoice UpdateSupplierInvoiceStatus(ctx, supplierInvoiceId).SupplierInvoiceStatusUpdate(supplierInvoiceStatusUpdate).Execute()



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
	supplierInvoiceId := "supplierInvoiceId_example" // string | 
	supplierInvoiceStatusUpdate := *openapiclient.NewSupplierInvoiceStatusUpdate("Status_example") // SupplierInvoiceStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierInvoiceAPI.UpdateSupplierInvoiceStatus(context.Background(), supplierInvoiceId).SupplierInvoiceStatusUpdate(supplierInvoiceStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierInvoiceAPI.UpdateSupplierInvoiceStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateSupplierInvoiceStatus`: SupplierInvoice
	fmt.Fprintf(os.Stdout, "Response from `SupplierInvoiceAPI.UpdateSupplierInvoiceStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierInvoiceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSupplierInvoiceStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **supplierInvoiceStatusUpdate** | [**SupplierInvoiceStatusUpdate**](SupplierInvoiceStatusUpdate.md) |  | 

### Return type

[**SupplierInvoice**](SupplierInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

