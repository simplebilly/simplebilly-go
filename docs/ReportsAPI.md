# \ReportsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BilanzReportApi**](ReportsAPI.md#BilanzReportApi) | **Get** /api/v1/bookkeeping/reports/bilanz | Bilanz (Balance Sheet)
[**GuvReportApi**](ReportsAPI.md#GuvReportApi) | **Get** /api/v1/bookkeeping/reports/guv | Gewinn- und Verlustrechnung (P&amp;L statement)
[**KontenansichtReportApi**](ReportsAPI.md#KontenansichtReportApi) | **Get** /api/v1/bookkeeping/reports/kontenansicht | Kontenansicht (Account Overview)
[**UmsatzsteuerReportApi**](ReportsAPI.md#UmsatzsteuerReportApi) | **Get** /api/v1/bookkeeping/reports/umsatzsteuer | Umsatzsteuer-Voranmeldung (VAT report)



## BilanzReportApi

> BilanzReport BilanzReportApi(ctx).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()

Bilanz (Balance Sheet)

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
	year := int32(56) // int32 |  (optional)
	month := int32(56) // int32 |  (optional)
	dateFrom := "dateFrom_example" // string |  (optional)
	dateTo := "dateTo_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.BilanzReportApi(context.Background()).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.BilanzReportApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BilanzReportApi`: BilanzReport
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.BilanzReportApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBilanzReportApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 
 **month** | **int32** |  | 
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**BilanzReport**](BilanzReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GuvReportApi

> GuVReport GuvReportApi(ctx).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()

Gewinn- und Verlustrechnung (P&L statement)

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
	year := int32(56) // int32 |  (optional)
	month := int32(56) // int32 |  (optional)
	dateFrom := "dateFrom_example" // string |  (optional)
	dateTo := "dateTo_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.GuvReportApi(context.Background()).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.GuvReportApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GuvReportApi`: GuVReport
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.GuvReportApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGuvReportApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 
 **month** | **int32** |  | 
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**GuVReport**](GuVReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KontenansichtReportApi

> KontoReport KontenansichtReportApi(ctx).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()

Kontenansicht (Account Overview)

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
	year := int32(56) // int32 |  (optional)
	month := int32(56) // int32 |  (optional)
	dateFrom := "dateFrom_example" // string |  (optional)
	dateTo := "dateTo_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.KontenansichtReportApi(context.Background()).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.KontenansichtReportApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KontenansichtReportApi`: KontoReport
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.KontenansichtReportApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiKontenansichtReportApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 
 **month** | **int32** |  | 
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**KontoReport**](KontoReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UmsatzsteuerReportApi

> UmsatzsteuerReport UmsatzsteuerReportApi(ctx).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()

Umsatzsteuer-Voranmeldung (VAT report)

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
	year := int32(56) // int32 |  (optional)
	month := int32(56) // int32 |  (optional)
	dateFrom := "dateFrom_example" // string |  (optional)
	dateTo := "dateTo_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.UmsatzsteuerReportApi(context.Background()).Year(year).Month(month).DateFrom(dateFrom).DateTo(dateTo).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.UmsatzsteuerReportApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UmsatzsteuerReportApi`: UmsatzsteuerReport
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.UmsatzsteuerReportApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUmsatzsteuerReportApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 
 **month** | **int32** |  | 
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**UmsatzsteuerReport**](UmsatzsteuerReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

