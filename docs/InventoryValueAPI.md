# \InventoryValueAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetInventoryValueApi**](InventoryValueAPI.md#GetInventoryValueApi) | **Get** /api/v1/bookkeeping/inventory-value | 
[**RecordInventoryValueApi**](InventoryValueAPI.md#RecordInventoryValueApi) | **Post** /api/v1/bookkeeping/inventory-value/record | 



## GetInventoryValueApi

> CurrentInventoryValue GetInventoryValueApi(ctx).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryValueAPI.GetInventoryValueApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryValueAPI.GetInventoryValueApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInventoryValueApi`: CurrentInventoryValue
	fmt.Fprintf(os.Stdout, "Response from `InventoryValueAPI.GetInventoryValueApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetInventoryValueApiRequest struct via the builder pattern


### Return type

[**CurrentInventoryValue**](CurrentInventoryValue.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RecordInventoryValueApi

> InventoryValuePoint RecordInventoryValueApi(ctx).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryValueAPI.RecordInventoryValueApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryValueAPI.RecordInventoryValueApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecordInventoryValueApi`: InventoryValuePoint
	fmt.Fprintf(os.Stdout, "Response from `InventoryValueAPI.RecordInventoryValueApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRecordInventoryValueApiRequest struct via the builder pattern


### Return type

[**InventoryValuePoint**](InventoryValuePoint.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

