# \ReplenishmentAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApplyReplenishments**](ReplenishmentAPI.md#ApplyReplenishments) | **Post** /api/v1/replenishments/apply | Create one draft stock transfer per (source → target) pair carrying all suggested product lines for that pair.
[**GetReplenishments**](ReplenishmentAPI.md#GetReplenishments) | **Get** /api/v1/replenishments | 



## ApplyReplenishments

> interface{} ApplyReplenishments(ctx).TargetWarehouseId(targetWarehouseId).SourceWarehouseId(sourceWarehouseId).Execute()

Create one draft stock transfer per (source → target) pair carrying all suggested product lines for that pair.

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
	targetWarehouseId := "targetWarehouseId_example" // string | Warehouse to be replenished. Defaults to the tenant's default warehouse. (optional)
	sourceWarehouseId := "sourceWarehouseId_example" // string | Restrict source warehouses to this id. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReplenishmentAPI.ApplyReplenishments(context.Background()).TargetWarehouseId(targetWarehouseId).SourceWarehouseId(sourceWarehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplenishmentAPI.ApplyReplenishments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApplyReplenishments`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `ReplenishmentAPI.ApplyReplenishments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApplyReplenishmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **targetWarehouseId** | **string** | Warehouse to be replenished. Defaults to the tenant&#39;s default warehouse. | 
 **sourceWarehouseId** | **string** | Restrict source warehouses to this id. | 

### Return type

**interface{}**

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetReplenishments

> ReplenishmentResponse GetReplenishments(ctx).TargetWarehouseId(targetWarehouseId).SourceWarehouseId(sourceWarehouseId).Execute()



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
	targetWarehouseId := "targetWarehouseId_example" // string | Warehouse to be replenished. Defaults to the tenant's default warehouse. (optional)
	sourceWarehouseId := "sourceWarehouseId_example" // string | Restrict source warehouses to this id. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReplenishmentAPI.GetReplenishments(context.Background()).TargetWarehouseId(targetWarehouseId).SourceWarehouseId(sourceWarehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplenishmentAPI.GetReplenishments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReplenishments`: ReplenishmentResponse
	fmt.Fprintf(os.Stdout, "Response from `ReplenishmentAPI.GetReplenishments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetReplenishmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **targetWarehouseId** | **string** | Warehouse to be replenished. Defaults to the tenant&#39;s default warehouse. | 
 **sourceWarehouseId** | **string** | Restrict source warehouses to this id. | 

### Return type

[**ReplenishmentResponse**](ReplenishmentResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

