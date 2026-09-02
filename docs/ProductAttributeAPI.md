# \ProductAttributeAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProductAttribute**](ProductAttributeAPI.md#CreateProductAttribute) | **Post** /api/v1/product-attributes | 
[**DeleteProductAttribute**](ProductAttributeAPI.md#DeleteProductAttribute) | **Delete** /api/v1/product-attributes/{attribute_id} | 
[**GetProductAttribute**](ProductAttributeAPI.md#GetProductAttribute) | **Get** /api/v1/product-attributes/{attribute_id} | 
[**ListProductAttributes**](ProductAttributeAPI.md#ListProductAttributes) | **Get** /api/v1/product-attributes/ | 
[**UpdateProductAttribute**](ProductAttributeAPI.md#UpdateProductAttribute) | **Put** /api/v1/product-attributes/{attribute_id} | 



## CreateProductAttribute

> ProductAttribute CreateProductAttribute(ctx).ProductAttributeCreate(productAttributeCreate).Execute()



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
	productAttributeCreate := *openapiclient.NewProductAttributeCreate("Name_example", "ProductId_example", "Value_example") // ProductAttributeCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAttributeAPI.CreateProductAttribute(context.Background()).ProductAttributeCreate(productAttributeCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAttributeAPI.CreateProductAttribute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProductAttribute`: ProductAttribute
	fmt.Fprintf(os.Stdout, "Response from `ProductAttributeAPI.CreateProductAttribute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProductAttributeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productAttributeCreate** | [**ProductAttributeCreate**](ProductAttributeCreate.md) |  | 

### Return type

[**ProductAttribute**](ProductAttribute.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProductAttribute

> DeleteProductAttribute(ctx, attributeId).Execute()



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
	attributeId := "attributeId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProductAttributeAPI.DeleteProductAttribute(context.Background(), attributeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAttributeAPI.DeleteProductAttribute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attributeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProductAttributeRequest struct via the builder pattern


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


## GetProductAttribute

> ProductAttribute GetProductAttribute(ctx, attributeId).Execute()



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
	attributeId := "attributeId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAttributeAPI.GetProductAttribute(context.Background(), attributeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAttributeAPI.GetProductAttribute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProductAttribute`: ProductAttribute
	fmt.Fprintf(os.Stdout, "Response from `ProductAttributeAPI.GetProductAttribute`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attributeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProductAttributeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductAttribute**](ProductAttribute.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProductAttributes

> []ProductAttribute ListProductAttributes(ctx).Page(page).PageSize(pageSize).ProductId(productId).IsFilterable(isFilterable).Search(search).Execute()



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
	isFilterable := true // bool |  (optional)
	search := "search_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAttributeAPI.ListProductAttributes(context.Background()).Page(page).PageSize(pageSize).ProductId(productId).IsFilterable(isFilterable).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAttributeAPI.ListProductAttributes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProductAttributes`: []ProductAttribute
	fmt.Fprintf(os.Stdout, "Response from `ProductAttributeAPI.ListProductAttributes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListProductAttributesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **productId** | **string** |  | 
 **isFilterable** | **bool** |  | 
 **search** | **string** |  | 

### Return type

[**[]ProductAttribute**](ProductAttribute.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProductAttribute

> ProductAttribute UpdateProductAttribute(ctx, attributeId).ProductAttributeUpdate(productAttributeUpdate).Execute()



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
	attributeId := "attributeId_example" // string | 
	productAttributeUpdate := *openapiclient.NewProductAttributeUpdate() // ProductAttributeUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAttributeAPI.UpdateProductAttribute(context.Background(), attributeId).ProductAttributeUpdate(productAttributeUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAttributeAPI.UpdateProductAttribute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProductAttribute`: ProductAttribute
	fmt.Fprintf(os.Stdout, "Response from `ProductAttributeAPI.UpdateProductAttribute`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attributeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProductAttributeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productAttributeUpdate** | [**ProductAttributeUpdate**](ProductAttributeUpdate.md) |  | 

### Return type

[**ProductAttribute**](ProductAttribute.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

