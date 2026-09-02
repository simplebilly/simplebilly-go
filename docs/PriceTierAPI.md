# \PriceTierAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePriceTier**](PriceTierAPI.md#CreatePriceTier) | **Post** /api/v1/price-tiers | 
[**DeletePriceTier**](PriceTierAPI.md#DeletePriceTier) | **Delete** /api/v1/price-tiers/{price_tier_id} | 
[**GetPriceTier**](PriceTierAPI.md#GetPriceTier) | **Get** /api/v1/price-tiers/{price_tier_id} | 
[**GetResolvedPrice**](PriceTierAPI.md#GetResolvedPrice) | **Get** /api/v1/price-tiers/resolved | 
[**ListPriceTiers**](PriceTierAPI.md#ListPriceTiers) | **Get** /api/v1/price-tiers/ | 
[**UpdatePriceTier**](PriceTierAPI.md#UpdatePriceTier) | **Put** /api/v1/price-tiers/{price_tier_id} | 



## CreatePriceTier

> PriceTier CreatePriceTier(ctx).PriceTierCreate(priceTierCreate).Execute()



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
	priceTierCreate := *openapiclient.NewPriceTierCreate("ProductId_example", "UnitPrice_example") // PriceTierCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PriceTierAPI.CreatePriceTier(context.Background()).PriceTierCreate(priceTierCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceTierAPI.CreatePriceTier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePriceTier`: PriceTier
	fmt.Fprintf(os.Stdout, "Response from `PriceTierAPI.CreatePriceTier`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePriceTierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **priceTierCreate** | [**PriceTierCreate**](PriceTierCreate.md) |  | 

### Return type

[**PriceTier**](PriceTier.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePriceTier

> DeletePriceTier(ctx, priceTierId).Execute()



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
	priceTierId := "priceTierId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PriceTierAPI.DeletePriceTier(context.Background(), priceTierId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceTierAPI.DeletePriceTier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**priceTierId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePriceTierRequest struct via the builder pattern


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


## GetPriceTier

> PriceTier GetPriceTier(ctx, priceTierId).Execute()



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
	priceTierId := "priceTierId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PriceTierAPI.GetPriceTier(context.Background(), priceTierId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceTierAPI.GetPriceTier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPriceTier`: PriceTier
	fmt.Fprintf(os.Stdout, "Response from `PriceTierAPI.GetPriceTier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**priceTierId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPriceTierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PriceTier**](PriceTier.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetResolvedPrice

> ResolvedPriceResponse GetResolvedPrice(ctx).ProductId(productId).Quantity(quantity).ContactId(contactId).Execute()



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
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	quantity := int64(789) // int64 |  (optional)
	contactId := "contactId_example" // string | Contact used to match customer-group-scoped tiers. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PriceTierAPI.GetResolvedPrice(context.Background()).ProductId(productId).Quantity(quantity).ContactId(contactId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceTierAPI.GetResolvedPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetResolvedPrice`: ResolvedPriceResponse
	fmt.Fprintf(os.Stdout, "Response from `PriceTierAPI.GetResolvedPrice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetResolvedPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productId** | **string** |  | 
 **quantity** | **int64** |  | 
 **contactId** | **string** | Contact used to match customer-group-scoped tiers. | 

### Return type

[**ResolvedPriceResponse**](ResolvedPriceResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPriceTiers

> []PriceTier ListPriceTiers(ctx).Page(page).PageSize(pageSize).ProductId(productId).CustomerGroupId(customerGroupId).Execute()



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
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	customerGroupId := "customerGroupId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PriceTierAPI.ListPriceTiers(context.Background()).Page(page).PageSize(pageSize).ProductId(productId).CustomerGroupId(customerGroupId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceTierAPI.ListPriceTiers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPriceTiers`: []PriceTier
	fmt.Fprintf(os.Stdout, "Response from `PriceTierAPI.ListPriceTiers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPriceTiersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **productId** | **string** |  | 
 **customerGroupId** | **string** |  | 

### Return type

[**[]PriceTier**](PriceTier.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePriceTier

> PriceTier UpdatePriceTier(ctx, priceTierId).PriceTierUpdate(priceTierUpdate).Execute()



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
	priceTierId := "priceTierId_example" // string | 
	priceTierUpdate := *openapiclient.NewPriceTierUpdate("UnitPrice_example") // PriceTierUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PriceTierAPI.UpdatePriceTier(context.Background(), priceTierId).PriceTierUpdate(priceTierUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PriceTierAPI.UpdatePriceTier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePriceTier`: PriceTier
	fmt.Fprintf(os.Stdout, "Response from `PriceTierAPI.UpdatePriceTier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**priceTierId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePriceTierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **priceTierUpdate** | [**PriceTierUpdate**](PriceTierUpdate.md) |  | 

### Return type

[**PriceTier**](PriceTier.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

