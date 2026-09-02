# \DeliveryAppointmentAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeliveryAppointment**](DeliveryAppointmentAPI.md#CreateDeliveryAppointment) | **Post** /api/v1/delivery-appointments | 
[**DeleteDeliveryAppointment**](DeliveryAppointmentAPI.md#DeleteDeliveryAppointment) | **Delete** /api/v1/delivery-appointments/{appointment_id} | 
[**GetDeliveryAppointment**](DeliveryAppointmentAPI.md#GetDeliveryAppointment) | **Get** /api/v1/delivery-appointments/{appointment_id} | 
[**GetPublicDeliveryAppointmentStatus**](DeliveryAppointmentAPI.md#GetPublicDeliveryAppointmentStatus) | **Get** /api/v1/public/delivery-appointments/status | Supplier/carrier checks appointment status (public, no auth). The appointment is only revealed when email AND token match.
[**ListDeliveryAppointments**](DeliveryAppointmentAPI.md#ListDeliveryAppointments) | **Get** /api/v1/delivery-appointments | 
[**RequestPublicDeliveryAppointment**](DeliveryAppointmentAPI.md#RequestPublicDeliveryAppointment) | **Post** /api/v1/public/delivery-appointments/request | Supplier/carrier requests an inbound delivery slot (public, no auth). The tenant is derived from the warehouse found by &#x60;code&#x60; — never from the request.
[**UpdateDeliveryAppointment**](DeliveryAppointmentAPI.md#UpdateDeliveryAppointment) | **Put** /api/v1/delivery-appointments/{appointment_id} | 
[**UpdateDeliveryAppointmentStatus**](DeliveryAppointmentAPI.md#UpdateDeliveryAppointmentStatus) | **Put** /api/v1/delivery-appointments/{appointment_id}/status | 



## CreateDeliveryAppointment

> DeliveryAppointment CreateDeliveryAppointment(ctx).DeliveryAppointmentCreate(deliveryAppointmentCreate).Execute()



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
	deliveryAppointmentCreate := *openapiclient.NewDeliveryAppointmentCreate("Email_example", time.Now(), openapiclient.DeliveryAppointmentStatus("requested"), "SupplierName_example", "WarehouseId_example") // DeliveryAppointmentCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryAppointmentAPI.CreateDeliveryAppointment(context.Background()).DeliveryAppointmentCreate(deliveryAppointmentCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.CreateDeliveryAppointment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeliveryAppointment`: DeliveryAppointment
	fmt.Fprintf(os.Stdout, "Response from `DeliveryAppointmentAPI.CreateDeliveryAppointment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeliveryAppointmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deliveryAppointmentCreate** | [**DeliveryAppointmentCreate**](DeliveryAppointmentCreate.md) |  | 

### Return type

[**DeliveryAppointment**](DeliveryAppointment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDeliveryAppointment

> DeleteDeliveryAppointment(ctx, appointmentId).Execute()



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
	appointmentId := "appointmentId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeliveryAppointmentAPI.DeleteDeliveryAppointment(context.Background(), appointmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.DeleteDeliveryAppointment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appointmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDeliveryAppointmentRequest struct via the builder pattern


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


## GetDeliveryAppointment

> DeliveryAppointment GetDeliveryAppointment(ctx, appointmentId).Execute()



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
	appointmentId := "appointmentId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryAppointmentAPI.GetDeliveryAppointment(context.Background(), appointmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.GetDeliveryAppointment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliveryAppointment`: DeliveryAppointment
	fmt.Fprintf(os.Stdout, "Response from `DeliveryAppointmentAPI.GetDeliveryAppointment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appointmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliveryAppointmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeliveryAppointment**](DeliveryAppointment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicDeliveryAppointmentStatus

> PublicDeliveryAppointmentStatusResponse GetPublicDeliveryAppointmentStatus(ctx).AppointmentId(appointmentId).Email(email).Token(token).Execute()

Supplier/carrier checks appointment status (public, no auth). The appointment is only revealed when email AND token match.

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
	appointmentId := "appointmentId_example" // string | 
	email := "email_example" // string | 
	token := "token_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryAppointmentAPI.GetPublicDeliveryAppointmentStatus(context.Background()).AppointmentId(appointmentId).Email(email).Token(token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.GetPublicDeliveryAppointmentStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicDeliveryAppointmentStatus`: PublicDeliveryAppointmentStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `DeliveryAppointmentAPI.GetPublicDeliveryAppointmentStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicDeliveryAppointmentStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appointmentId** | **string** |  | 
 **email** | **string** |  | 
 **token** | **string** |  | 

### Return type

[**PublicDeliveryAppointmentStatusResponse**](PublicDeliveryAppointmentStatusResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeliveryAppointments

> []DeliveryAppointment ListDeliveryAppointments(ctx).Page(page).PageSize(pageSize).Status(status).WarehouseId(warehouseId).From(from).To(to).Execute()



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
	status := "status_example" // string |  (optional)
	warehouseId := "warehouseId_example" // string |  (optional)
	from := time.Now() // string |  (optional)
	to := time.Now() // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryAppointmentAPI.ListDeliveryAppointments(context.Background()).Page(page).PageSize(pageSize).Status(status).WarehouseId(warehouseId).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.ListDeliveryAppointments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliveryAppointments`: []DeliveryAppointment
	fmt.Fprintf(os.Stdout, "Response from `DeliveryAppointmentAPI.ListDeliveryAppointments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDeliveryAppointmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **warehouseId** | **string** |  | 
 **from** | **string** |  | 
 **to** | **string** |  | 

### Return type

[**[]DeliveryAppointment**](DeliveryAppointment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestPublicDeliveryAppointment

> PublicDeliveryAppointmentResponse RequestPublicDeliveryAppointment(ctx).PublicDeliveryAppointmentRequest(publicDeliveryAppointmentRequest).Execute()

Supplier/carrier requests an inbound delivery slot (public, no auth). The tenant is derived from the warehouse found by `code` — never from the request.

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
	publicDeliveryAppointmentRequest := *openapiclient.NewPublicDeliveryAppointmentRequest("Email_example", time.Now(), "SupplierName_example", "WarehouseCode_example") // PublicDeliveryAppointmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryAppointmentAPI.RequestPublicDeliveryAppointment(context.Background()).PublicDeliveryAppointmentRequest(publicDeliveryAppointmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.RequestPublicDeliveryAppointment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RequestPublicDeliveryAppointment`: PublicDeliveryAppointmentResponse
	fmt.Fprintf(os.Stdout, "Response from `DeliveryAppointmentAPI.RequestPublicDeliveryAppointment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRequestPublicDeliveryAppointmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **publicDeliveryAppointmentRequest** | [**PublicDeliveryAppointmentRequest**](PublicDeliveryAppointmentRequest.md) |  | 

### Return type

[**PublicDeliveryAppointmentResponse**](PublicDeliveryAppointmentResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeliveryAppointment

> DeliveryAppointment UpdateDeliveryAppointment(ctx, appointmentId).Body(body).Execute()



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
	appointmentId := "appointmentId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryAppointmentAPI.UpdateDeliveryAppointment(context.Background(), appointmentId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.UpdateDeliveryAppointment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDeliveryAppointment`: DeliveryAppointment
	fmt.Fprintf(os.Stdout, "Response from `DeliveryAppointmentAPI.UpdateDeliveryAppointment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appointmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeliveryAppointmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**DeliveryAppointment**](DeliveryAppointment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeliveryAppointmentStatus

> DeliveryAppointment UpdateDeliveryAppointmentStatus(ctx, appointmentId).AppointmentStatusUpdate(appointmentStatusUpdate).Execute()



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
	appointmentId := "appointmentId_example" // string | 
	appointmentStatusUpdate := *openapiclient.NewAppointmentStatusUpdate("Status_example") // AppointmentStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliveryAppointmentAPI.UpdateDeliveryAppointmentStatus(context.Background(), appointmentId).AppointmentStatusUpdate(appointmentStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliveryAppointmentAPI.UpdateDeliveryAppointmentStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDeliveryAppointmentStatus`: DeliveryAppointment
	fmt.Fprintf(os.Stdout, "Response from `DeliveryAppointmentAPI.UpdateDeliveryAppointmentStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appointmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeliveryAppointmentStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **appointmentStatusUpdate** | [**AppointmentStatusUpdate**](AppointmentStatusUpdate.md) |  | 

### Return type

[**DeliveryAppointment**](DeliveryAppointment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

