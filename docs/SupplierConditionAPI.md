# \SupplierConditionAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateSupplierCondition**](SupplierConditionAPI.md#CreateSupplierCondition) | **Post** /api/v1/supplier-conditions | 
[**DeleteSupplierCondition**](SupplierConditionAPI.md#DeleteSupplierCondition) | **Delete** /api/v1/supplier-conditions/{supplier_condition_id} | 
[**GetSupplierCondition**](SupplierConditionAPI.md#GetSupplierCondition) | **Get** /api/v1/supplier-conditions/{supplier_condition_id} | 
[**ListSupplierConditions**](SupplierConditionAPI.md#ListSupplierConditions) | **Get** /api/v1/supplier-conditions/ | 
[**UpdateSupplierCondition**](SupplierConditionAPI.md#UpdateSupplierCondition) | **Put** /api/v1/supplier-conditions/{supplier_condition_id} | 



## CreateSupplierCondition

> SupplierCondition CreateSupplierCondition(ctx).SupplierConditionCreate(supplierConditionCreate).Execute()



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
	supplierConditionCreate := *openapiclient.NewSupplierConditionCreate("Currency_example", "SupplierContactId_example") // SupplierConditionCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierConditionAPI.CreateSupplierCondition(context.Background()).SupplierConditionCreate(supplierConditionCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierConditionAPI.CreateSupplierCondition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateSupplierCondition`: SupplierCondition
	fmt.Fprintf(os.Stdout, "Response from `SupplierConditionAPI.CreateSupplierCondition`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSupplierConditionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **supplierConditionCreate** | [**SupplierConditionCreate**](SupplierConditionCreate.md) |  | 

### Return type

[**SupplierCondition**](SupplierCondition.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteSupplierCondition

> DeleteSupplierCondition(ctx, supplierConditionId).Execute()



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
	supplierConditionId := "supplierConditionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SupplierConditionAPI.DeleteSupplierCondition(context.Background(), supplierConditionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierConditionAPI.DeleteSupplierCondition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierConditionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteSupplierConditionRequest struct via the builder pattern


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


## GetSupplierCondition

> SupplierCondition GetSupplierCondition(ctx, supplierConditionId).Execute()



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
	supplierConditionId := "supplierConditionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierConditionAPI.GetSupplierCondition(context.Background(), supplierConditionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierConditionAPI.GetSupplierCondition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSupplierCondition`: SupplierCondition
	fmt.Fprintf(os.Stdout, "Response from `SupplierConditionAPI.GetSupplierCondition`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierConditionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSupplierConditionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SupplierCondition**](SupplierCondition.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSupplierConditions

> []SupplierCondition ListSupplierConditions(ctx).Page(page).PageSize(pageSize).SupplierContactId(supplierContactId).Search(search).Execute()



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
	supplierContactId := "supplierContactId_example" // string |  (optional)
	search := "search_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierConditionAPI.ListSupplierConditions(context.Background()).Page(page).PageSize(pageSize).SupplierContactId(supplierContactId).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierConditionAPI.ListSupplierConditions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSupplierConditions`: []SupplierCondition
	fmt.Fprintf(os.Stdout, "Response from `SupplierConditionAPI.ListSupplierConditions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListSupplierConditionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **supplierContactId** | **string** |  | 
 **search** | **string** |  | 

### Return type

[**[]SupplierCondition**](SupplierCondition.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSupplierCondition

> SupplierCondition UpdateSupplierCondition(ctx, supplierConditionId).SupplierConditionUpdate(supplierConditionUpdate).Execute()



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
	supplierConditionId := "supplierConditionId_example" // string | 
	supplierConditionUpdate := *openapiclient.NewSupplierConditionUpdate() // SupplierConditionUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupplierConditionAPI.UpdateSupplierCondition(context.Background(), supplierConditionId).SupplierConditionUpdate(supplierConditionUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupplierConditionAPI.UpdateSupplierCondition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateSupplierCondition`: SupplierCondition
	fmt.Fprintf(os.Stdout, "Response from `SupplierConditionAPI.UpdateSupplierCondition`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**supplierConditionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSupplierConditionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **supplierConditionUpdate** | [**SupplierConditionUpdate**](SupplierConditionUpdate.md) |  | 

### Return type

[**SupplierCondition**](SupplierCondition.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

