# \BomAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateBom**](BomAPI.md#CreateBom) | **Post** /api/v1/boms | 
[**DeleteBom**](BomAPI.md#DeleteBom) | **Delete** /api/v1/boms/{bom_id} | 
[**GetBom**](BomAPI.md#GetBom) | **Get** /api/v1/boms/{bom_id} | 
[**ListBoms**](BomAPI.md#ListBoms) | **Get** /api/v1/boms/ | 
[**UpdateBom**](BomAPI.md#UpdateBom) | **Put** /api/v1/boms/{bom_id} | 



## CreateBom

> Bom CreateBom(ctx).BomCreate(bomCreate).Execute()



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
	bomCreate := *openapiclient.NewBomCreate("Name_example", "ProductId_example") // BomCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BomAPI.CreateBom(context.Background()).BomCreate(bomCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BomAPI.CreateBom``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateBom`: Bom
	fmt.Fprintf(os.Stdout, "Response from `BomAPI.CreateBom`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateBomRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bomCreate** | [**BomCreate**](BomCreate.md) |  | 

### Return type

[**Bom**](Bom.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteBom

> DeleteBom(ctx, bomId).Execute()



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
	bomId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.BomAPI.DeleteBom(context.Background(), bomId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BomAPI.DeleteBom``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**bomId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteBomRequest struct via the builder pattern


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


## GetBom

> Bom GetBom(ctx, bomId).Execute()



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
	bomId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BomAPI.GetBom(context.Background(), bomId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BomAPI.GetBom``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBom`: Bom
	fmt.Fprintf(os.Stdout, "Response from `BomAPI.GetBom`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**bomId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBomRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Bom**](Bom.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBoms

> []Bom ListBoms(ctx).Page(page).PageSize(pageSize).Search(search).ProductId(productId).Execute()



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
	productId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by finished product id. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BomAPI.ListBoms(context.Background()).Page(page).PageSize(pageSize).Search(search).ProductId(productId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BomAPI.ListBoms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBoms`: []Bom
	fmt.Fprintf(os.Stdout, "Response from `BomAPI.ListBoms`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListBomsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 
 **productId** | **string** | Filter by finished product id. | 

### Return type

[**[]Bom**](Bom.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateBom

> Bom UpdateBom(ctx, bomId).BomUpdate(bomUpdate).Execute()



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
	bomId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	bomUpdate := *openapiclient.NewBomUpdate() // BomUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BomAPI.UpdateBom(context.Background(), bomId).BomUpdate(bomUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BomAPI.UpdateBom``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateBom`: Bom
	fmt.Fprintf(os.Stdout, "Response from `BomAPI.UpdateBom`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**bomId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateBomRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **bomUpdate** | [**BomUpdate**](BomUpdate.md) |  | 

### Return type

[**Bom**](Bom.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

