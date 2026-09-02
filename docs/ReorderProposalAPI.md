# \ReorderProposalAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApplyReorderProposal**](ReorderProposalAPI.md#ApplyReorderProposal) | **Post** /api/v1/reorder-proposals/apply | Convert a reorder proposal into a draft purchase order.
[**GetReorderProposal**](ReorderProposalAPI.md#GetReorderProposal) | **Get** /api/v1/reorder-proposals | 



## ApplyReorderProposal

> interface{} ApplyReorderProposal(ctx).ConfiguredOnly(configuredOnly).WarehouseId(warehouseId).Execute()

Convert a reorder proposal into a draft purchase order.



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
	configuredOnly := true // bool | Only include products with a reorder point configured (`min_stock`). (optional)
	warehouseId := "warehouseId_example" // string | Limit to a single warehouse id. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReorderProposalAPI.ApplyReorderProposal(context.Background()).ConfiguredOnly(configuredOnly).WarehouseId(warehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReorderProposalAPI.ApplyReorderProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApplyReorderProposal`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `ReorderProposalAPI.ApplyReorderProposal`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApplyReorderProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **configuredOnly** | **bool** | Only include products with a reorder point configured (&#x60;min_stock&#x60;). | 
 **warehouseId** | **string** | Limit to a single warehouse id. | 

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


## GetReorderProposal

> ReorderProposalResponse GetReorderProposal(ctx).ConfiguredOnly(configuredOnly).WarehouseId(warehouseId).Execute()



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
	configuredOnly := true // bool | Only include products with a reorder point configured (`min_stock`). (optional)
	warehouseId := "warehouseId_example" // string | Limit to a single warehouse id. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReorderProposalAPI.GetReorderProposal(context.Background()).ConfiguredOnly(configuredOnly).WarehouseId(warehouseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReorderProposalAPI.GetReorderProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReorderProposal`: ReorderProposalResponse
	fmt.Fprintf(os.Stdout, "Response from `ReorderProposalAPI.GetReorderProposal`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetReorderProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **configuredOnly** | **bool** | Only include products with a reorder point configured (&#x60;min_stock&#x60;). | 
 **warehouseId** | **string** | Limit to a single warehouse id. | 

### Return type

[**ReorderProposalResponse**](ReorderProposalResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

