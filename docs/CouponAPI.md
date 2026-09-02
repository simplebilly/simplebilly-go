# \CouponAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CouponRestore**](CouponAPI.md#CouponRestore) | **Post** /api/v1/coupons/{coupon_id}/restore | 
[**CreateCoupon**](CouponAPI.md#CreateCoupon) | **Post** /api/v1/coupons | 
[**DeleteCoupon**](CouponAPI.md#DeleteCoupon) | **Delete** /api/v1/coupons/{coupon_id} | 
[**GetCoupon**](CouponAPI.md#GetCoupon) | **Get** /api/v1/coupons/{coupon_id} | 
[**ListCoupons**](CouponAPI.md#ListCoupons) | **Get** /api/v1/coupons/ | 
[**UpdateCoupon**](CouponAPI.md#UpdateCoupon) | **Put** /api/v1/coupons/{coupon_id} | 



## CouponRestore

> Coupon CouponRestore(ctx, couponId).Execute()



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
	couponId := "couponId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CouponAPI.CouponRestore(context.Background(), couponId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CouponAPI.CouponRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CouponRestore`: Coupon
	fmt.Fprintf(os.Stdout, "Response from `CouponAPI.CouponRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**couponId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCouponRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Coupon**](Coupon.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCoupon

> Coupon CreateCoupon(ctx).CouponCreate(couponCreate).Execute()



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
	couponCreate := *openapiclient.NewCouponCreate("Code_example", openapiclient.DiscountType("percentage"), "DiscountValue_example") // CouponCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CouponAPI.CreateCoupon(context.Background()).CouponCreate(couponCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CouponAPI.CreateCoupon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCoupon`: Coupon
	fmt.Fprintf(os.Stdout, "Response from `CouponAPI.CreateCoupon`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCouponRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **couponCreate** | [**CouponCreate**](CouponCreate.md) |  | 

### Return type

[**Coupon**](Coupon.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCoupon

> DeleteCoupon(ctx, couponId).Execute()



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
	couponId := "couponId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CouponAPI.DeleteCoupon(context.Background(), couponId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CouponAPI.DeleteCoupon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**couponId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCouponRequest struct via the builder pattern


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


## GetCoupon

> Coupon GetCoupon(ctx, couponId).Execute()



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
	couponId := "couponId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CouponAPI.GetCoupon(context.Background(), couponId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CouponAPI.GetCoupon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCoupon`: Coupon
	fmt.Fprintf(os.Stdout, "Response from `CouponAPI.GetCoupon`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**couponId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCouponRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Coupon**](Coupon.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCoupons

> []Coupon ListCoupons(ctx).Page(page).PageSize(pageSize).IsActive(isActive).Code(code).DiscountType(discountType).Execute()



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
	isActive := true // bool |  (optional)
	code := "code_example" // string |  (optional)
	discountType := "discountType_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CouponAPI.ListCoupons(context.Background()).Page(page).PageSize(pageSize).IsActive(isActive).Code(code).DiscountType(discountType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CouponAPI.ListCoupons``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCoupons`: []Coupon
	fmt.Fprintf(os.Stdout, "Response from `CouponAPI.ListCoupons`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCouponsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **isActive** | **bool** |  | 
 **code** | **string** |  | 
 **discountType** | **string** |  | 

### Return type

[**[]Coupon**](Coupon.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCoupon

> Coupon UpdateCoupon(ctx, couponId).CouponUpdate(couponUpdate).Execute()



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
	couponId := "couponId_example" // string | 
	couponUpdate := *openapiclient.NewCouponUpdate() // CouponUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CouponAPI.UpdateCoupon(context.Background(), couponId).CouponUpdate(couponUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CouponAPI.UpdateCoupon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCoupon`: Coupon
	fmt.Fprintf(os.Stdout, "Response from `CouponAPI.UpdateCoupon`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**couponId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCouponRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **couponUpdate** | [**CouponUpdate**](CouponUpdate.md) |  | 

### Return type

[**Coupon**](Coupon.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

