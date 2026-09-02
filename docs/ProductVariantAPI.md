# \ProductVariantAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProductVariant**](ProductVariantAPI.md#CreateProductVariant) | **Post** /api/v1/product-variants | 
[**DeleteProductVariant**](ProductVariantAPI.md#DeleteProductVariant) | **Delete** /api/v1/product-variants/{variant_id} | 
[**GenerateProductVariants**](ProductVariantAPI.md#GenerateProductVariants) | **Post** /api/v1/product-variants/generate | 
[**GetProductVariant**](ProductVariantAPI.md#GetProductVariant) | **Get** /api/v1/product-variants/{variant_id} | 
[**ListProductVariants**](ProductVariantAPI.md#ListProductVariants) | **Get** /api/v1/product-variants/ | 
[**UpdateProductVariant**](ProductVariantAPI.md#UpdateProductVariant) | **Put** /api/v1/product-variants/{variant_id} | 



## CreateProductVariant

> ProductVariant CreateProductVariant(ctx).ProductVariant(productVariant).Execute()



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
	productVariant := *openapiclient.NewProductVariant("ProductId_example", "Sku_example") // ProductVariant | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductVariantAPI.CreateProductVariant(context.Background()).ProductVariant(productVariant).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductVariantAPI.CreateProductVariant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProductVariant`: ProductVariant
	fmt.Fprintf(os.Stdout, "Response from `ProductVariantAPI.CreateProductVariant`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProductVariantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productVariant** | [**ProductVariant**](ProductVariant.md) |  | 

### Return type

[**ProductVariant**](ProductVariant.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProductVariant

> DeleteProductVariant(ctx, variantId).Execute()



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
	variantId := "variantId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProductVariantAPI.DeleteProductVariant(context.Background(), variantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductVariantAPI.DeleteProductVariant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**variantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProductVariantRequest struct via the builder pattern


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


## GenerateProductVariants

> []ProductVariant GenerateProductVariants(ctx).GenerateVariantsRequest(generateVariantsRequest).Execute()



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
	generateVariantsRequest := *openapiclient.NewGenerateVariantsRequest("ProductId_example") // GenerateVariantsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductVariantAPI.GenerateProductVariants(context.Background()).GenerateVariantsRequest(generateVariantsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductVariantAPI.GenerateProductVariants``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateProductVariants`: []ProductVariant
	fmt.Fprintf(os.Stdout, "Response from `ProductVariantAPI.GenerateProductVariants`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateProductVariantsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateVariantsRequest** | [**GenerateVariantsRequest**](GenerateVariantsRequest.md) |  | 

### Return type

[**[]ProductVariant**](ProductVariant.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProductVariant

> ProductVariant GetProductVariant(ctx, variantId).Execute()



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
	variantId := "variantId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductVariantAPI.GetProductVariant(context.Background(), variantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductVariantAPI.GetProductVariant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProductVariant`: ProductVariant
	fmt.Fprintf(os.Stdout, "Response from `ProductVariantAPI.GetProductVariant`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**variantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProductVariantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductVariant**](ProductVariant.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProductVariants

> []ProductVariant ListProductVariants(ctx).Page(page).PageSize(pageSize).ProductId(productId).IsActive(isActive).Execute()



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
	isActive := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductVariantAPI.ListProductVariants(context.Background()).Page(page).PageSize(pageSize).ProductId(productId).IsActive(isActive).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductVariantAPI.ListProductVariants``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProductVariants`: []ProductVariant
	fmt.Fprintf(os.Stdout, "Response from `ProductVariantAPI.ListProductVariants`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListProductVariantsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **productId** | **string** |  | 
 **isActive** | **bool** |  | 

### Return type

[**[]ProductVariant**](ProductVariant.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProductVariant

> ProductVariant UpdateProductVariant(ctx, variantId).Body(body).Execute()



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
	variantId := "variantId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductVariantAPI.UpdateProductVariant(context.Background(), variantId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductVariantAPI.UpdateProductVariant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProductVariant`: ProductVariant
	fmt.Fprintf(os.Stdout, "Response from `ProductVariantAPI.UpdateProductVariant`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**variantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProductVariantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**ProductVariant**](ProductVariant.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

