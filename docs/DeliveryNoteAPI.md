# \DeliveryNoteAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeliveryNote**](DeliveryNoteAPI.md#CreateDeliveryNote) | **Post** /api/v1/delivery-notes | 
[**DeleteDeliveryNote**](DeliveryNoteAPI.md#DeleteDeliveryNote) | **Delete** /api/v1/delivery-notes/{delivery_note_id} | 
[**DeliverynoteRestore**](DeliveryNoteAPI.md#DeliverynoteRestore) | **Post** /api/v1/delivery-notes/{delivery_note_id}/restore | 
[**DownloadDeliveryNotePdf**](DeliveryNoteAPI.md#DownloadDeliveryNotePdf) | **Get** /api/v1/delivery-notes/{delivery_note_id}/pdf | 
[**GetDeliveryNote**](DeliveryNoteAPI.md#GetDeliveryNote) | **Get** /api/v1/delivery-notes/{delivery_note_id} | 
[**ListDeliveryNotes**](DeliveryNoteAPI.md#ListDeliveryNotes) | **Get** /api/v1/delivery-notes/ | 
[**PursueDeliveryNote**](DeliveryNoteAPI.md#PursueDeliveryNote) | **Post** /api/v1/delivery-notes/{delivery_note_id}/pursue | 



## CreateDeliveryNote

> DeliveryNote CreateDeliveryNote(ctx).DeliveryNoteCreate(deliveryNoteCreate).Execute()



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
	deliveryNoteCreate := *openapiclient.NewDeliveryNoteCreate("Currency_example", time.Now(), openapiclient.VoucherStatus("open")) // DeliveryNoteCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryNoteAPI.CreateDeliveryNote(context.Background()).DeliveryNoteCreate(deliveryNoteCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryNoteAPI.CreateDeliveryNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeliveryNote`: DeliveryNote
	fmt.Fprintf(os.Stdout, "Response from `DeliveryNoteAPI.CreateDeliveryNote`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeliveryNoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deliveryNoteCreate** | [**DeliveryNoteCreate**](DeliveryNoteCreate.md) |  | 

### Return type

[**DeliveryNote**](DeliveryNote.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDeliveryNote

> DeleteDeliveryNote(ctx, deliveryNoteId).Execute()



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
	deliveryNoteId := "deliveryNoteId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeliveryNoteAPI.DeleteDeliveryNote(context.Background(), deliveryNoteId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryNoteAPI.DeleteDeliveryNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryNoteId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDeliveryNoteRequest struct via the builder pattern


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


## DeliverynoteRestore

> DeliveryNote DeliverynoteRestore(ctx, deliveryNoteId).Execute()



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
	deliveryNoteId := "deliveryNoteId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryNoteAPI.DeliverynoteRestore(context.Background(), deliveryNoteId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryNoteAPI.DeliverynoteRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeliverynoteRestore`: DeliveryNote
	fmt.Fprintf(os.Stdout, "Response from `DeliveryNoteAPI.DeliverynoteRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryNoteId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeliverynoteRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeliveryNote**](DeliveryNote.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadDeliveryNotePdf

> DownloadDeliveryNotePdf(ctx, deliveryNoteId).Execute()



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
	deliveryNoteId := "deliveryNoteId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeliveryNoteAPI.DownloadDeliveryNotePdf(context.Background(), deliveryNoteId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryNoteAPI.DownloadDeliveryNotePdf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryNoteId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadDeliveryNotePdfRequest struct via the builder pattern


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


## GetDeliveryNote

> DeliveryNote GetDeliveryNote(ctx, deliveryNoteId).Execute()



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
	deliveryNoteId := "deliveryNoteId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryNoteAPI.GetDeliveryNote(context.Background(), deliveryNoteId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryNoteAPI.GetDeliveryNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliveryNote`: DeliveryNote
	fmt.Fprintf(os.Stdout, "Response from `DeliveryNoteAPI.GetDeliveryNote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryNoteId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliveryNoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeliveryNote**](DeliveryNote.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeliveryNotes

> []DeliveryNote ListDeliveryNotes(ctx).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()



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
	resp, r, err := apiClient.DeliveryNoteAPI.ListDeliveryNotes(context.Background()).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryNoteAPI.ListDeliveryNotes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliveryNotes`: []DeliveryNote
	fmt.Fprintf(os.Stdout, "Response from `DeliveryNoteAPI.ListDeliveryNotes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDeliveryNotesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 
 **includeDeleted** | **bool** | Soft-delete entities: set true to include rows with &#x60;deleted_at&#x60; set. | 

### Return type

[**[]DeliveryNote**](DeliveryNote.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PursueDeliveryNote

> Invoice PursueDeliveryNote(ctx, deliveryNoteId).Execute()



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
	deliveryNoteId := "deliveryNoteId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryNoteAPI.PursueDeliveryNote(context.Background(), deliveryNoteId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryNoteAPI.PursueDeliveryNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PursueDeliveryNote`: Invoice
	fmt.Fprintf(os.Stdout, "Response from `DeliveryNoteAPI.PursueDeliveryNote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryNoteId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPursueDeliveryNoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Invoice**](Invoice.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

