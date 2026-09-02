# \DeliveryDateAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeliveryDate**](DeliveryDateAPI.md#CreateDeliveryDate) | **Post** /api/v1/delivery-dates | 
[**DeleteDeliveryDate**](DeliveryDateAPI.md#DeleteDeliveryDate) | **Delete** /api/v1/delivery-dates/{delivery_date_id} | 
[**GetDeliveryDate**](DeliveryDateAPI.md#GetDeliveryDate) | **Get** /api/v1/delivery-dates/{delivery_date_id} | 
[**GetDeliveryPerformance**](DeliveryDateAPI.md#GetDeliveryPerformance) | **Get** /api/v1/delivery-dates/performance | On-time performance summary: how many promised delivery dates were met within a period.
[**ListDeliveryDates**](DeliveryDateAPI.md#ListDeliveryDates) | **Get** /api/v1/delivery-dates/ | 
[**UpdateDeliveryDate**](DeliveryDateAPI.md#UpdateDeliveryDate) | **Put** /api/v1/delivery-dates/{delivery_date_id} | 
[**UpdateDeliveryDateStatus**](DeliveryDateAPI.md#UpdateDeliveryDateStatus) | **Put** /api/v1/delivery-dates/{delivery_date_id}/status | 



## CreateDeliveryDate

> DeliveryDate CreateDeliveryDate(ctx).DeliveryDateCreate(deliveryDateCreate).Execute()



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
	deliveryDateCreate := *openapiclient.NewDeliveryDateCreate("OrderNumber_example", time.Now(), "TODO") // DeliveryDateCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryDateAPI.CreateDeliveryDate(context.Background()).DeliveryDateCreate(deliveryDateCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryDateAPI.CreateDeliveryDate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeliveryDate`: DeliveryDate
	fmt.Fprintf(os.Stdout, "Response from `DeliveryDateAPI.CreateDeliveryDate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeliveryDateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deliveryDateCreate** | [**DeliveryDateCreate**](DeliveryDateCreate.md) |  | 

### Return type

[**DeliveryDate**](DeliveryDate.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDeliveryDate

> DeleteDeliveryDate(ctx, deliveryDateId).Execute()



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
	deliveryDateId := "deliveryDateId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeliveryDateAPI.DeleteDeliveryDate(context.Background(), deliveryDateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryDateAPI.DeleteDeliveryDate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryDateId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDeliveryDateRequest struct via the builder pattern


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


## GetDeliveryDate

> DeliveryDate GetDeliveryDate(ctx, deliveryDateId).Execute()



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
	deliveryDateId := "deliveryDateId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryDateAPI.GetDeliveryDate(context.Background(), deliveryDateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryDateAPI.GetDeliveryDate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliveryDate`: DeliveryDate
	fmt.Fprintf(os.Stdout, "Response from `DeliveryDateAPI.GetDeliveryDate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryDateId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliveryDateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeliveryDate**](DeliveryDate.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeliveryPerformance

> interface{} GetDeliveryPerformance(ctx).Page(page).PageSize(pageSize).OrderNumber(orderNumber).Status(status).From(from).To(to).Execute()

On-time performance summary: how many promised delivery dates were met within a period.

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
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	orderNumber := "orderNumber_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	from := time.Now() // string | Only dates on or after this date. (optional)
	to := time.Now() // string | Only dates on or before this date. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryDateAPI.GetDeliveryPerformance(context.Background()).Page(page).PageSize(pageSize).OrderNumber(orderNumber).Status(status).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryDateAPI.GetDeliveryPerformance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliveryPerformance`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DeliveryDateAPI.GetDeliveryPerformance`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliveryPerformanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **orderNumber** | **string** |  | 
 **status** | **string** |  | 
 **from** | **string** | Only dates on or after this date. | 
 **to** | **string** | Only dates on or before this date. | 

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


## ListDeliveryDates

> []DeliveryDate ListDeliveryDates(ctx).Page(page).PageSize(pageSize).OrderNumber(orderNumber).Status(status).From(from).To(to).Execute()



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
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	orderNumber := "orderNumber_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	from := time.Now() // string | Only dates on or after this date. (optional)
	to := time.Now() // string | Only dates on or before this date. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryDateAPI.ListDeliveryDates(context.Background()).Page(page).PageSize(pageSize).OrderNumber(orderNumber).Status(status).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryDateAPI.ListDeliveryDates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliveryDates`: []DeliveryDate
	fmt.Fprintf(os.Stdout, "Response from `DeliveryDateAPI.ListDeliveryDates`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDeliveryDatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **orderNumber** | **string** |  | 
 **status** | **string** |  | 
 **from** | **string** | Only dates on or after this date. | 
 **to** | **string** | Only dates on or before this date. | 

### Return type

[**[]DeliveryDate**](DeliveryDate.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeliveryDate

> DeliveryDate UpdateDeliveryDate(ctx, deliveryDateId).Body(body).Execute()



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
	deliveryDateId := "deliveryDateId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryDateAPI.UpdateDeliveryDate(context.Background(), deliveryDateId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryDateAPI.UpdateDeliveryDate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDeliveryDate`: DeliveryDate
	fmt.Fprintf(os.Stdout, "Response from `DeliveryDateAPI.UpdateDeliveryDate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryDateId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeliveryDateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**DeliveryDate**](DeliveryDate.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeliveryDateStatus

> DeliveryDate UpdateDeliveryDateStatus(ctx, deliveryDateId).DeliveryDateStatusUpdate(deliveryDateStatusUpdate).Execute()



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
	deliveryDateId := "deliveryDateId_example" // string | 
	deliveryDateStatusUpdate := *openapiclient.NewDeliveryDateStatusUpdate("Status_example") // DeliveryDateStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryDateAPI.UpdateDeliveryDateStatus(context.Background(), deliveryDateId).DeliveryDateStatusUpdate(deliveryDateStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryDateAPI.UpdateDeliveryDateStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDeliveryDateStatus`: DeliveryDate
	fmt.Fprintf(os.Stdout, "Response from `DeliveryDateAPI.UpdateDeliveryDateStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliveryDateId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeliveryDateStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deliveryDateStatusUpdate** | [**DeliveryDateStatusUpdate**](DeliveryDateStatusUpdate.md) |  | 

### Return type

[**DeliveryDate**](DeliveryDate.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

