# \ProformaInvoiceAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ConvertProformaToInvoice**](ProformaInvoiceAPI.md#ConvertProformaToInvoice) | **Post** /api/v1/proforma-invoices/{proforma_id}/convert | 
[**CreateProformaInvoice**](ProformaInvoiceAPI.md#CreateProformaInvoice) | **Post** /api/v1/proforma-invoices | 
[**DeleteProformaInvoice**](ProformaInvoiceAPI.md#DeleteProformaInvoice) | **Delete** /api/v1/proforma-invoices/{proforma_id} | 
[**GetProformaInvoice**](ProformaInvoiceAPI.md#GetProformaInvoice) | **Get** /api/v1/proforma-invoices/{proforma_id} | 
[**ListProformaInvoices**](ProformaInvoiceAPI.md#ListProformaInvoices) | **Get** /api/v1/proforma-invoices/ | 
[**UpdateProformaInvoice**](ProformaInvoiceAPI.md#UpdateProformaInvoice) | **Put** /api/v1/proforma-invoices/{proforma_id} | 



## ConvertProformaToInvoice

> ConvertResponse ConvertProformaToInvoice(ctx, proformaId).Execute()



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
	proformaId := "proformaId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProformaInvoiceAPI.ConvertProformaToInvoice(context.Background(), proformaId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProformaInvoiceAPI.ConvertProformaToInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConvertProformaToInvoice`: ConvertResponse
	fmt.Fprintf(os.Stdout, "Response from `ProformaInvoiceAPI.ConvertProformaToInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**proformaId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiConvertProformaToInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConvertResponse**](ConvertResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateProformaInvoice

> ProformaInvoice CreateProformaInvoice(ctx).ProformaInvoice(proformaInvoice).Execute()



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
	proformaInvoice := *openapiclient.NewProformaInvoice(openapiclient.CurrencyCode("ADP"), time.Now(), interface{}(123), openapiclient.ProformaInvoiceStatus("draft"), "Subtotal_example", "TotalAmount_example", "TotalTax_example") // ProformaInvoice | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProformaInvoiceAPI.CreateProformaInvoice(context.Background()).ProformaInvoice(proformaInvoice).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProformaInvoiceAPI.CreateProformaInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProformaInvoice`: ProformaInvoice
	fmt.Fprintf(os.Stdout, "Response from `ProformaInvoiceAPI.CreateProformaInvoice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProformaInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **proformaInvoice** | [**ProformaInvoice**](ProformaInvoice.md) |  | 

### Return type

[**ProformaInvoice**](ProformaInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProformaInvoice

> DeleteProformaInvoice(ctx, proformaId).Execute()



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
	proformaId := "proformaId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProformaInvoiceAPI.DeleteProformaInvoice(context.Background(), proformaId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProformaInvoiceAPI.DeleteProformaInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**proformaId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProformaInvoiceRequest struct via the builder pattern


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


## GetProformaInvoice

> ProformaInvoice GetProformaInvoice(ctx, proformaId).Execute()



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
	proformaId := "proformaId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProformaInvoiceAPI.GetProformaInvoice(context.Background(), proformaId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProformaInvoiceAPI.GetProformaInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProformaInvoice`: ProformaInvoice
	fmt.Fprintf(os.Stdout, "Response from `ProformaInvoiceAPI.GetProformaInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**proformaId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProformaInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProformaInvoice**](ProformaInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProformaInvoices

> []ProformaInvoice ListProformaInvoices(ctx).Page(page).PageSize(pageSize).Status(status).CustomerId(customerId).OrderNumber(orderNumber).Execute()



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
	customerId := "customerId_example" // string |  (optional)
	orderNumber := "orderNumber_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProformaInvoiceAPI.ListProformaInvoices(context.Background()).Page(page).PageSize(pageSize).Status(status).CustomerId(customerId).OrderNumber(orderNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProformaInvoiceAPI.ListProformaInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProformaInvoices`: []ProformaInvoice
	fmt.Fprintf(os.Stdout, "Response from `ProformaInvoiceAPI.ListProformaInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListProformaInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **customerId** | **string** |  | 
 **orderNumber** | **string** |  | 

### Return type

[**[]ProformaInvoice**](ProformaInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProformaInvoice

> ProformaInvoice UpdateProformaInvoice(ctx, proformaId).Body(body).Execute()



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
	proformaId := "proformaId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProformaInvoiceAPI.UpdateProformaInvoice(context.Background(), proformaId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProformaInvoiceAPI.UpdateProformaInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProformaInvoice`: ProformaInvoice
	fmt.Fprintf(os.Stdout, "Response from `ProformaInvoiceAPI.UpdateProformaInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**proformaId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProformaInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**ProformaInvoice**](ProformaInvoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

