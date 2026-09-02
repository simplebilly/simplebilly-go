# \QuotationAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateQuotation**](QuotationAPI.md#CreateQuotation) | **Post** /api/v1/quotations | 
[**DeleteQuotation**](QuotationAPI.md#DeleteQuotation) | **Delete** /api/v1/quotations/{quotation_id} | 
[**DownloadQuotationPdf**](QuotationAPI.md#DownloadQuotationPdf) | **Get** /api/v1/quotations/{quotation_id}/pdf | 
[**GetQuotation**](QuotationAPI.md#GetQuotation) | **Get** /api/v1/quotations/{quotation_id} | 
[**ListQuotations**](QuotationAPI.md#ListQuotations) | **Get** /api/v1/quotations/ | 
[**PursueQuotation**](QuotationAPI.md#PursueQuotation) | **Post** /api/v1/quotations/{quotation_id}/pursue | 
[**QuotationRestore**](QuotationAPI.md#QuotationRestore) | **Post** /api/v1/quotations/{quotation_id}/restore | 
[**UpdateQuotation**](QuotationAPI.md#UpdateQuotation) | **Put** /api/v1/quotations/{quotation_id} | 



## CreateQuotation

> Quotation CreateQuotation(ctx).QuotationCreate(quotationCreate).Execute()



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
	quotationCreate := *openapiclient.NewQuotationCreate("Currency_example", time.Now(), openapiclient.VoucherStatus("open")) // QuotationCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuotationAPI.CreateQuotation(context.Background()).QuotationCreate(quotationCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.CreateQuotation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateQuotation`: Quotation
	fmt.Fprintf(os.Stdout, "Response from `QuotationAPI.CreateQuotation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateQuotationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **quotationCreate** | [**QuotationCreate**](QuotationCreate.md) |  | 

### Return type

[**Quotation**](Quotation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteQuotation

> DeleteQuotation(ctx, quotationId).Execute()



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
	quotationId := "quotationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.QuotationAPI.DeleteQuotation(context.Background(), quotationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.DeleteQuotation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quotationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteQuotationRequest struct via the builder pattern


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


## DownloadQuotationPdf

> DownloadQuotationPdf(ctx, quotationId).Execute()



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
	quotationId := "quotationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.QuotationAPI.DownloadQuotationPdf(context.Background(), quotationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.DownloadQuotationPdf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quotationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadQuotationPdfRequest struct via the builder pattern


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


## GetQuotation

> Quotation GetQuotation(ctx, quotationId).Execute()



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
	quotationId := "quotationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuotationAPI.GetQuotation(context.Background(), quotationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.GetQuotation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetQuotation`: Quotation
	fmt.Fprintf(os.Stdout, "Response from `QuotationAPI.GetQuotation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quotationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetQuotationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Quotation**](Quotation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListQuotations

> []Quotation ListQuotations(ctx).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()



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
	resp, r, err := apiClient.QuotationAPI.ListQuotations(context.Background()).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.ListQuotations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListQuotations`: []Quotation
	fmt.Fprintf(os.Stdout, "Response from `QuotationAPI.ListQuotations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListQuotationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 
 **includeDeleted** | **bool** | Soft-delete entities: set true to include rows with &#x60;deleted_at&#x60; set. | 

### Return type

[**[]Quotation**](Quotation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PursueQuotation

> OrderConfirmation PursueQuotation(ctx, quotationId).Execute()



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
	quotationId := "quotationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuotationAPI.PursueQuotation(context.Background(), quotationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.PursueQuotation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PursueQuotation`: OrderConfirmation
	fmt.Fprintf(os.Stdout, "Response from `QuotationAPI.PursueQuotation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quotationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPursueQuotationRequest struct via the builder pattern


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


## QuotationRestore

> Quotation QuotationRestore(ctx, quotationId).Execute()



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
	quotationId := "quotationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuotationAPI.QuotationRestore(context.Background(), quotationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.QuotationRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QuotationRestore`: Quotation
	fmt.Fprintf(os.Stdout, "Response from `QuotationAPI.QuotationRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quotationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiQuotationRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Quotation**](Quotation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateQuotation

> Quotation UpdateQuotation(ctx, quotationId).Body(body).Execute()



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
	quotationId := "quotationId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuotationAPI.UpdateQuotation(context.Background(), quotationId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotationAPI.UpdateQuotation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateQuotation`: Quotation
	fmt.Fprintf(os.Stdout, "Response from `QuotationAPI.UpdateQuotation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quotationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateQuotationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**Quotation**](Quotation.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

