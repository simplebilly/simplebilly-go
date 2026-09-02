# \InventoryCountAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateInventoryCount**](InventoryCountAPI.md#CreateInventoryCount) | **Post** /api/v1/inventory-counts | 
[**DeleteInventoryCount**](InventoryCountAPI.md#DeleteInventoryCount) | **Delete** /api/v1/inventory-counts/{inventory_count_id} | 
[**GenerateInventoryCount**](InventoryCountAPI.md#GenerateInventoryCount) | **Post** /api/v1/inventory-counts/generate | 
[**GetInventoryCount**](InventoryCountAPI.md#GetInventoryCount) | **Get** /api/v1/inventory-counts/{inventory_count_id} | 
[**ListInventoryCounts**](InventoryCountAPI.md#ListInventoryCounts) | **Get** /api/v1/inventory-counts/ | 
[**UpdateInventoryCount**](InventoryCountAPI.md#UpdateInventoryCount) | **Put** /api/v1/inventory-counts/{inventory_count_id} | 
[**UpdateInventoryCountStatus**](InventoryCountAPI.md#UpdateInventoryCountStatus) | **Put** /api/v1/inventory-counts/{inventory_count_id}/status | 



## CreateInventoryCount

> InventoryCount CreateInventoryCount(ctx).InventoryCount(inventoryCount).Execute()



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
	inventoryCount := *openapiclient.NewInventoryCount(time.Now(), "CountNumber_example", interface{}(123), openapiclient.InventoryCountStatus("draft"), "WarehouseId_example") // InventoryCount | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryCountAPI.CreateInventoryCount(context.Background()).InventoryCount(inventoryCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryCountAPI.CreateInventoryCount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateInventoryCount`: InventoryCount
	fmt.Fprintf(os.Stdout, "Response from `InventoryCountAPI.CreateInventoryCount`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateInventoryCountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryCount** | [**InventoryCount**](InventoryCount.md) |  | 

### Return type

[**InventoryCount**](InventoryCount.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteInventoryCount

> DeleteInventoryCount(ctx, inventoryCountId).Execute()



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
	inventoryCountId := "inventoryCountId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InventoryCountAPI.DeleteInventoryCount(context.Background(), inventoryCountId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryCountAPI.DeleteInventoryCount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**inventoryCountId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteInventoryCountRequest struct via the builder pattern


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


## GenerateInventoryCount

> InventoryCount GenerateInventoryCount(ctx).GenerateCountRequest(generateCountRequest).Execute()



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
	generateCountRequest := *openapiclient.NewGenerateCountRequest("WarehouseId_example") // GenerateCountRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryCountAPI.GenerateInventoryCount(context.Background()).GenerateCountRequest(generateCountRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryCountAPI.GenerateInventoryCount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateInventoryCount`: InventoryCount
	fmt.Fprintf(os.Stdout, "Response from `InventoryCountAPI.GenerateInventoryCount`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateInventoryCountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateCountRequest** | [**GenerateCountRequest**](GenerateCountRequest.md) |  | 

### Return type

[**InventoryCount**](InventoryCount.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetInventoryCount

> InventoryCount GetInventoryCount(ctx, inventoryCountId).Execute()



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
	inventoryCountId := "inventoryCountId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryCountAPI.GetInventoryCount(context.Background(), inventoryCountId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryCountAPI.GetInventoryCount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInventoryCount`: InventoryCount
	fmt.Fprintf(os.Stdout, "Response from `InventoryCountAPI.GetInventoryCount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**inventoryCountId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetInventoryCountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InventoryCount**](InventoryCount.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListInventoryCounts

> []InventoryCount ListInventoryCounts(ctx).Page(page).PageSize(pageSize).Status(status).WarehouseId(warehouseId).Execute()



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
	status := "status_example" // string |  (optional)
	warehouseId := "warehouseId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryCountAPI.ListInventoryCounts(context.Background()).Page(page).PageSize(pageSize).Status(status).WarehouseId(warehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryCountAPI.ListInventoryCounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListInventoryCounts`: []InventoryCount
	fmt.Fprintf(os.Stdout, "Response from `InventoryCountAPI.ListInventoryCounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListInventoryCountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **warehouseId** | **string** |  | 

### Return type

[**[]InventoryCount**](InventoryCount.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateInventoryCount

> InventoryCount UpdateInventoryCount(ctx, inventoryCountId).Body(body).Execute()



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
	inventoryCountId := "inventoryCountId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryCountAPI.UpdateInventoryCount(context.Background(), inventoryCountId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryCountAPI.UpdateInventoryCount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateInventoryCount`: InventoryCount
	fmt.Fprintf(os.Stdout, "Response from `InventoryCountAPI.UpdateInventoryCount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**inventoryCountId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateInventoryCountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**InventoryCount**](InventoryCount.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateInventoryCountStatus

> InventoryCount UpdateInventoryCountStatus(ctx, inventoryCountId).InventoryCountStatusUpdate(inventoryCountStatusUpdate).Execute()



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
	inventoryCountId := "inventoryCountId_example" // string | 
	inventoryCountStatusUpdate := *openapiclient.NewInventoryCountStatusUpdate("Status_example") // InventoryCountStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryCountAPI.UpdateInventoryCountStatus(context.Background(), inventoryCountId).InventoryCountStatusUpdate(inventoryCountStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryCountAPI.UpdateInventoryCountStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateInventoryCountStatus`: InventoryCount
	fmt.Fprintf(os.Stdout, "Response from `InventoryCountAPI.UpdateInventoryCountStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**inventoryCountId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateInventoryCountStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **inventoryCountStatusUpdate** | [**InventoryCountStatusUpdate**](InventoryCountStatusUpdate.md) |  | 

### Return type

[**InventoryCount**](InventoryCount.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

