# \DatevAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DatevExportApi**](DatevAPI.md#DatevExportApi) | **Get** /api/v1/bookkeeping/datev/export | Export bookkeeping data as DATEV CSV
[**DatevPreviewApi**](DatevAPI.md#DatevPreviewApi) | **Get** /api/v1/bookkeeping/datev/preview | Exported_datev_bookings: returns formed bookings for review



## DatevExportApi

> DatevExportResponse DatevExportApi(ctx).AccountSchema(accountSchema).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()

Export bookkeeping data as DATEV CSV

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
	accountSchema := "accountSchema_example" // string |  (optional)
	dateFrom := "dateFrom_example" // string |  (optional)
	dateTo := "dateTo_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatevAPI.DatevExportApi(context.Background()).AccountSchema(accountSchema).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatevAPI.DatevExportApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DatevExportApi`: DatevExportResponse
	fmt.Fprintf(os.Stdout, "Response from `DatevAPI.DatevExportApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDatevExportApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountSchema** | **string** |  | 
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**DatevExportResponse**](DatevExportResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DatevPreviewApi

> []DatevBookingPreview DatevPreviewApi(ctx).AccountSchema(accountSchema).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()

Exported_datev_bookings: returns formed bookings for review

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
	accountSchema := "accountSchema_example" // string |  (optional)
	dateFrom := "dateFrom_example" // string |  (optional)
	dateTo := "dateTo_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatevAPI.DatevPreviewApi(context.Background()).AccountSchema(accountSchema).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatevAPI.DatevPreviewApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DatevPreviewApi`: []DatevBookingPreview
	fmt.Fprintf(os.Stdout, "Response from `DatevAPI.DatevPreviewApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDatevPreviewApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountSchema** | **string** |  | 
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**[]DatevBookingPreview**](DatevBookingPreview.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

