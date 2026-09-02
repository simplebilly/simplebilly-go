# \ReturnOrderAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateReturnOrder**](ReturnOrderAPI.md#CreateReturnOrder) | **Post** /api/v1/returns | 
[**DeleteReturnOrder**](ReturnOrderAPI.md#DeleteReturnOrder) | **Delete** /api/v1/returns/{return_order_id} | 
[**GetReturnOrder**](ReturnOrderAPI.md#GetReturnOrder) | **Get** /api/v1/returns/{return_order_id} | 
[**ListReturnOrders**](ReturnOrderAPI.md#ListReturnOrders) | **Get** /api/v1/returns/ | 
[**ReturnLogisticsQueue**](ReturnOrderAPI.md#ReturnLogisticsQueue) | **Get** /api/v1/returns/logistics-queue | 
[**ReturnLogisticsSummary**](ReturnOrderAPI.md#ReturnLogisticsSummary) | **Get** /api/v1/returns/logistics-summary | Returns-logistics aggregation for the dashboard: quantities received, restocked and scrapped per warehouse.
[**UpdateReturnOrder**](ReturnOrderAPI.md#UpdateReturnOrder) | **Put** /api/v1/returns/{return_order_id} | 
[**UpdateReturnOrderStatus**](ReturnOrderAPI.md#UpdateReturnOrderStatus) | **Put** /api/v1/returns/{return_order_id}/status | 



## CreateReturnOrder

> ReturnOrder CreateReturnOrder(ctx).ReturnOrder(returnOrder).Execute()



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
	returnOrder := *openapiclient.NewReturnOrder("ReturnNumber_example", openapiclient.ReturnOrderStatus("requested")) // ReturnOrder | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReturnOrderAPI.CreateReturnOrder(context.Background()).ReturnOrder(returnOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.CreateReturnOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateReturnOrder`: ReturnOrder
	fmt.Fprintf(os.Stdout, "Response from `ReturnOrderAPI.CreateReturnOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateReturnOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **returnOrder** | [**ReturnOrder**](ReturnOrder.md) |  | 

### Return type

[**ReturnOrder**](ReturnOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteReturnOrder

> DeleteReturnOrder(ctx, returnOrderId).Execute()



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
	returnOrderId := "returnOrderId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ReturnOrderAPI.DeleteReturnOrder(context.Background(), returnOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.DeleteReturnOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**returnOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteReturnOrderRequest struct via the builder pattern


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


## GetReturnOrder

> ReturnOrder GetReturnOrder(ctx, returnOrderId).Execute()



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
	returnOrderId := "returnOrderId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReturnOrderAPI.GetReturnOrder(context.Background(), returnOrderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.GetReturnOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReturnOrder`: ReturnOrder
	fmt.Fprintf(os.Stdout, "Response from `ReturnOrderAPI.GetReturnOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**returnOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetReturnOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReturnOrder**](ReturnOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListReturnOrders

> []ReturnOrder ListReturnOrders(ctx).Page(page).PageSize(pageSize).Status(status).CustomerName(customerName).OrderNumber(orderNumber).Execute()



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
	customerName := "customerName_example" // string |  (optional)
	orderNumber := "orderNumber_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReturnOrderAPI.ListReturnOrders(context.Background()).Page(page).PageSize(pageSize).Status(status).CustomerName(customerName).OrderNumber(orderNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.ListReturnOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListReturnOrders`: []ReturnOrder
	fmt.Fprintf(os.Stdout, "Response from `ReturnOrderAPI.ListReturnOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListReturnOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **customerName** | **string** |  | 
 **orderNumber** | **string** |  | 

### Return type

[**[]ReturnOrder**](ReturnOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReturnLogisticsQueue

> []ReturnLogisticsQueueItem ReturnLogisticsQueue(ctx).Execute()



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
	resp, r, err := apiClient.ReturnOrderAPI.ReturnLogisticsQueue(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.ReturnLogisticsQueue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReturnLogisticsQueue`: []ReturnLogisticsQueueItem
	fmt.Fprintf(os.Stdout, "Response from `ReturnOrderAPI.ReturnLogisticsQueue`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiReturnLogisticsQueueRequest struct via the builder pattern


### Return type

[**[]ReturnLogisticsQueueItem**](ReturnLogisticsQueueItem.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReturnLogisticsSummary

> ReturnLogisticsSummary ReturnLogisticsSummary(ctx).Execute()

Returns-logistics aggregation for the dashboard: quantities received, restocked and scrapped per warehouse.

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
	resp, r, err := apiClient.ReturnOrderAPI.ReturnLogisticsSummary(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.ReturnLogisticsSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReturnLogisticsSummary`: ReturnLogisticsSummary
	fmt.Fprintf(os.Stdout, "Response from `ReturnOrderAPI.ReturnLogisticsSummary`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiReturnLogisticsSummaryRequest struct via the builder pattern


### Return type

[**ReturnLogisticsSummary**](ReturnLogisticsSummary.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateReturnOrder

> ReturnOrder UpdateReturnOrder(ctx, returnOrderId).Body(body).Execute()



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
	returnOrderId := "returnOrderId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReturnOrderAPI.UpdateReturnOrder(context.Background(), returnOrderId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.UpdateReturnOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateReturnOrder`: ReturnOrder
	fmt.Fprintf(os.Stdout, "Response from `ReturnOrderAPI.UpdateReturnOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**returnOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateReturnOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**ReturnOrder**](ReturnOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateReturnOrderStatus

> ReturnOrder UpdateReturnOrderStatus(ctx, returnOrderId).ReturnOrderStatusUpdate(returnOrderStatusUpdate).Execute()



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
	returnOrderId := "returnOrderId_example" // string | 
	returnOrderStatusUpdate := *openapiclient.NewReturnOrderStatusUpdate("Status_example") // ReturnOrderStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReturnOrderAPI.UpdateReturnOrderStatus(context.Background(), returnOrderId).ReturnOrderStatusUpdate(returnOrderStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReturnOrderAPI.UpdateReturnOrderStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateReturnOrderStatus`: ReturnOrder
	fmt.Fprintf(os.Stdout, "Response from `ReturnOrderAPI.UpdateReturnOrderStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**returnOrderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateReturnOrderStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **returnOrderStatusUpdate** | [**ReturnOrderStatusUpdate**](ReturnOrderStatusUpdate.md) |  | 

### Return type

[**ReturnOrder**](ReturnOrder.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

