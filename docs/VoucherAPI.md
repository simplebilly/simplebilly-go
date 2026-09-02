# \VoucherAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateVoucher**](VoucherAPI.md#CreateVoucher) | **Post** /api/v1/vouchers | 
[**DeleteVoucher**](VoucherAPI.md#DeleteVoucher) | **Delete** /api/v1/vouchers/{voucher_id} | 
[**GetVoucher**](VoucherAPI.md#GetVoucher) | **Get** /api/v1/vouchers/{voucher_id} | 
[**ListVouchers**](VoucherAPI.md#ListVouchers) | **Get** /api/v1/vouchers/ | 
[**UpdateVoucher**](VoucherAPI.md#UpdateVoucher) | **Put** /api/v1/vouchers/{voucher_id} | 
[**VoucherRestore**](VoucherAPI.md#VoucherRestore) | **Post** /api/v1/vouchers/{voucher_id}/restore | 



## CreateVoucher

> Voucher CreateVoucher(ctx).VoucherCreate(voucherCreate).Execute()



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
	voucherCreate := *openapiclient.NewVoucherCreate("Currency_example", time.Now(), openapiclient.VoucherStatus("open"), openapiclient.VoucherType("invoice")) // VoucherCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VoucherAPI.CreateVoucher(context.Background()).VoucherCreate(voucherCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VoucherAPI.CreateVoucher``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateVoucher`: Voucher
	fmt.Fprintf(os.Stdout, "Response from `VoucherAPI.CreateVoucher`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateVoucherRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **voucherCreate** | [**VoucherCreate**](VoucherCreate.md) |  | 

### Return type

[**Voucher**](Voucher.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteVoucher

> DeleteVoucher(ctx, voucherId).Execute()



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
	voucherId := "voucherId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VoucherAPI.DeleteVoucher(context.Background(), voucherId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VoucherAPI.DeleteVoucher``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**voucherId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteVoucherRequest struct via the builder pattern


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


## GetVoucher

> Voucher GetVoucher(ctx, voucherId).Execute()



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
	voucherId := "voucherId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VoucherAPI.GetVoucher(context.Background(), voucherId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VoucherAPI.GetVoucher``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVoucher`: Voucher
	fmt.Fprintf(os.Stdout, "Response from `VoucherAPI.GetVoucher`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**voucherId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVoucherRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Voucher**](Voucher.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVouchers

> []Voucher ListVouchers(ctx).Page(page).PageSize(pageSize).VoucherType(voucherType).VoucherStatus(voucherStatus).ContactName(contactName).DateFrom(dateFrom).DateTo(dateTo).Execute()



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
	voucherType := "voucherType_example" // string |  (optional)
	voucherStatus := "voucherStatus_example" // string |  (optional)
	contactName := "contactName_example" // string |  (optional)
	dateFrom := time.Now() // string |  (optional)
	dateTo := time.Now() // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VoucherAPI.ListVouchers(context.Background()).Page(page).PageSize(pageSize).VoucherType(voucherType).VoucherStatus(voucherStatus).ContactName(contactName).DateFrom(dateFrom).DateTo(dateTo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VoucherAPI.ListVouchers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVouchers`: []Voucher
	fmt.Fprintf(os.Stdout, "Response from `VoucherAPI.ListVouchers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListVouchersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **voucherType** | **string** |  | 
 **voucherStatus** | **string** |  | 
 **contactName** | **string** |  | 
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 

### Return type

[**[]Voucher**](Voucher.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateVoucher

> Voucher UpdateVoucher(ctx, voucherId).Body(body).Execute()



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
	voucherId := "voucherId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VoucherAPI.UpdateVoucher(context.Background(), voucherId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VoucherAPI.UpdateVoucher``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateVoucher`: Voucher
	fmt.Fprintf(os.Stdout, "Response from `VoucherAPI.UpdateVoucher`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**voucherId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateVoucherRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**Voucher**](Voucher.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VoucherRestore

> Voucher VoucherRestore(ctx, voucherId).Execute()



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
	voucherId := "voucherId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VoucherAPI.VoucherRestore(context.Background(), voucherId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VoucherAPI.VoucherRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VoucherRestore`: Voucher
	fmt.Fprintf(os.Stdout, "Response from `VoucherAPI.VoucherRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**voucherId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiVoucherRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Voucher**](Voucher.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

