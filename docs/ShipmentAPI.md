# \ShipmentAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateShipment**](ShipmentAPI.md#CreateShipment) | **Post** /api/v1/shipments | 
[**CreateShipmentFromOrder**](ShipmentAPI.md#CreateShipmentFromOrder) | **Post** /api/v1/orders/{order_number}/shipments | Create a real shipment for an order: calls the configured carrier&#39;s label API, stores the returned tracking/label on a new shipment row, and marks the order as shipped.
[**DeleteShipment**](ShipmentAPI.md#DeleteShipment) | **Delete** /api/v1/shipments/{shipment_id} | 
[**GetShipment**](ShipmentAPI.md#GetShipment) | **Get** /api/v1/shipments/{shipment_id} | 
[**ListShipments**](ShipmentAPI.md#ListShipments) | **Get** /api/v1/shipments | 
[**TrackOrderPublic**](ShipmentAPI.md#TrackOrderPublic) | **Post** /api/v1/public/track | Customer-facing tracking lookup: order number + email → shipment status and live carrier events. No auth (public storefront API).
[**TrackShipmentApi**](ShipmentAPI.md#TrackShipmentApi) | **Get** /api/v1/shipments/{shipment_id}/tracking | 
[**UpdateShipmentStatus**](ShipmentAPI.md#UpdateShipmentStatus) | **Put** /api/v1/shipments/{shipment_id}/status | 



## CreateShipment

> Shipment CreateShipment(ctx).Shipment(shipment).Execute()



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
	shipment := *openapiclient.NewShipment("OrderId_example", time.Now(), "ShippingCarrier_example", "Status_example") // Shipment | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentAPI.CreateShipment(context.Background()).Shipment(shipment).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.CreateShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateShipment`: Shipment
	fmt.Fprintf(os.Stdout, "Response from `ShipmentAPI.CreateShipment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **shipment** | [**Shipment**](Shipment.md) |  | 

### Return type

[**Shipment**](Shipment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateShipmentFromOrder

> Shipment CreateShipmentFromOrder(ctx, orderNumber).CreateShipmentRequest(createShipmentRequest).Execute()

Create a real shipment for an order: calls the configured carrier's label API, stores the returned tracking/label on a new shipment row, and marks the order as shipped.

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
	orderNumber := "orderNumber_example" // string | 
	createShipmentRequest := *openapiclient.NewCreateShipmentRequest("Carrier_example") // CreateShipmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentAPI.CreateShipmentFromOrder(context.Background(), orderNumber).CreateShipmentRequest(createShipmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.CreateShipmentFromOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateShipmentFromOrder`: Shipment
	fmt.Fprintf(os.Stdout, "Response from `ShipmentAPI.CreateShipmentFromOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderNumber** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateShipmentFromOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createShipmentRequest** | [**CreateShipmentRequest**](CreateShipmentRequest.md) |  | 

### Return type

[**Shipment**](Shipment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteShipment

> DeleteShipment(ctx, shipmentId).Execute()



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
	shipmentId := "shipmentId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ShipmentAPI.DeleteShipment(context.Background(), shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.DeleteShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteShipmentRequest struct via the builder pattern


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


## GetShipment

> Shipment GetShipment(ctx, shipmentId).Execute()



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
	shipmentId := "shipmentId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentAPI.GetShipment(context.Background(), shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.GetShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetShipment`: Shipment
	fmt.Fprintf(os.Stdout, "Response from `ShipmentAPI.GetShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Shipment**](Shipment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListShipments

> []Shipment ListShipments(ctx).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()



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
	page := int32(1) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	search := "search_example" // string |  (optional)
	includeDeleted := true // bool | Soft-delete entities: set true to include rows with `deleted_at` set. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentAPI.ListShipments(context.Background()).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.ListShipments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListShipments`: []Shipment
	fmt.Fprintf(os.Stdout, "Response from `ShipmentAPI.ListShipments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListShipmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 
 **includeDeleted** | **bool** | Soft-delete entities: set true to include rows with &#x60;deleted_at&#x60; set. | 

### Return type

[**[]Shipment**](Shipment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrackOrderPublic

> TrackOrderResponse TrackOrderPublic(ctx).TrackOrderRequest(trackOrderRequest).Execute()

Customer-facing tracking lookup: order number + email → shipment status and live carrier events. No auth (public storefront API).

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
	trackOrderRequest := *openapiclient.NewTrackOrderRequest("Email_example", "OrderNumber_example") // TrackOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentAPI.TrackOrderPublic(context.Background()).TrackOrderRequest(trackOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.TrackOrderPublic``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrackOrderPublic`: TrackOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `ShipmentAPI.TrackOrderPublic`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTrackOrderPublicRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **trackOrderRequest** | [**TrackOrderRequest**](TrackOrderRequest.md) |  | 

### Return type

[**TrackOrderResponse**](TrackOrderResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrackShipmentApi

> TrackingInfo TrackShipmentApi(ctx, shipmentId).Execute()



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
	shipmentId := "shipmentId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentAPI.TrackShipmentApi(context.Background(), shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.TrackShipmentApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrackShipmentApi`: TrackingInfo
	fmt.Fprintf(os.Stdout, "Response from `ShipmentAPI.TrackShipmentApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTrackShipmentApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TrackingInfo**](TrackingInfo.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateShipmentStatus

> Shipment UpdateShipmentStatus(ctx, shipmentId).ShipmentStatusUpdate(shipmentStatusUpdate).Execute()



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
	shipmentId := "shipmentId_example" // string | 
	shipmentStatusUpdate := *openapiclient.NewShipmentStatusUpdate("Status_example") // ShipmentStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentAPI.UpdateShipmentStatus(context.Background(), shipmentId).ShipmentStatusUpdate(shipmentStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentAPI.UpdateShipmentStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateShipmentStatus`: Shipment
	fmt.Fprintf(os.Stdout, "Response from `ShipmentAPI.UpdateShipmentStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**shipmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateShipmentStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **shipmentStatusUpdate** | [**ShipmentStatusUpdate**](ShipmentStatusUpdate.md) |  | 

### Return type

[**Shipment**](Shipment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

