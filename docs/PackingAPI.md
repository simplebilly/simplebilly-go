# \PackingAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CompletePacking**](PackingAPI.md#CompletePacking) | **Post** /api/v1/packing/{order_number}/complete | Mark packing as complete and transition order to shipped
[**GetPackingQueue**](PackingAPI.md#GetPackingQueue) | **Get** /api/v1/packing/queue | Get the packing queue - orders ready for packing
[**PrintDeliveryNote**](PackingAPI.md#PrintDeliveryNote) | **Post** /api/v1/packing/{order_number}/print-delivery-note | Print delivery note (Lieferschein) for an order
[**PrintLabel**](PackingAPI.md#PrintLabel) | **Post** /api/v1/packing/{order_number}/print-label | Print shipping label for an order
[**RecordPackingVideo**](PackingAPI.md#RecordPackingVideo) | **Post** /api/v1/packing/{order_number}/record-video | Record video of packing process



## CompletePacking

> PackingCompleteResponse CompletePacking(ctx, orderNumber).PackingCompleteRequest(packingCompleteRequest).Execute()

Mark packing as complete and transition order to shipped

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
	orderNumber := "orderNumber_example" // string | 
	packingCompleteRequest := *openapiclient.NewPackingCompleteRequest("OrderNumber_example") // PackingCompleteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PackingAPI.CompletePacking(context.Background(), orderNumber).PackingCompleteRequest(packingCompleteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PackingAPI.CompletePacking``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompletePacking`: PackingCompleteResponse
	fmt.Fprintf(os.Stdout, "Response from `PackingAPI.CompletePacking`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderNumber** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCompletePackingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **packingCompleteRequest** | [**PackingCompleteRequest**](PackingCompleteRequest.md) |  | 

### Return type

[**PackingCompleteResponse**](PackingCompleteResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPackingQueue

> PackingQueue GetPackingQueue(ctx).Page(page).PageSize(pageSize).Search(search).Execute()

Get the packing queue - orders ready for packing

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PackingAPI.GetPackingQueue(context.Background()).Page(page).PageSize(pageSize).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PackingAPI.GetPackingQueue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPackingQueue`: PackingQueue
	fmt.Fprintf(os.Stdout, "Response from `PackingAPI.GetPackingQueue`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPackingQueueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 

### Return type

[**PackingQueue**](PackingQueue.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PrintDeliveryNote

> PrintDeliveryNoteResponse PrintDeliveryNote(ctx, orderNumber).Execute()

Print delivery note (Lieferschein) for an order

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
	orderNumber := "orderNumber_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PackingAPI.PrintDeliveryNote(context.Background(), orderNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PackingAPI.PrintDeliveryNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PrintDeliveryNote`: PrintDeliveryNoteResponse
	fmt.Fprintf(os.Stdout, "Response from `PackingAPI.PrintDeliveryNote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderNumber** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPrintDeliveryNoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PrintDeliveryNoteResponse**](PrintDeliveryNoteResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PrintLabel

> PrintLabelResponse PrintLabel(ctx, orderNumber).Execute()

Print shipping label for an order

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
	orderNumber := "orderNumber_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PackingAPI.PrintLabel(context.Background(), orderNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PackingAPI.PrintLabel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PrintLabel`: PrintLabelResponse
	fmt.Fprintf(os.Stdout, "Response from `PackingAPI.PrintLabel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderNumber** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPrintLabelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PrintLabelResponse**](PrintLabelResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RecordPackingVideo

> PackingVideoResponse RecordPackingVideo(ctx, orderNumber).Body(body).Execute()

Record video of packing process

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
	orderNumber := "orderNumber_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PackingAPI.RecordPackingVideo(context.Background(), orderNumber).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PackingAPI.RecordPackingVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecordPackingVideo`: PackingVideoResponse
	fmt.Fprintf(os.Stdout, "Response from `PackingAPI.RecordPackingVideo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderNumber** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRecordPackingVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**PackingVideoResponse**](PackingVideoResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

