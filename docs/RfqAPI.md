# \RfqAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ConvertRfq**](RfqAPI.md#ConvertRfq) | **Post** /api/v1/rfqs/{rfq_id}/convert | Convert an RFQ into a draft purchase order using the quoted unit prices (falling back to the requested prices, then leaving them blank). Marks the RFQ as &#x60;converted&#x60;.
[**CreateRfq**](RfqAPI.md#CreateRfq) | **Post** /api/v1/rfqs | 
[**DeleteRfq**](RfqAPI.md#DeleteRfq) | **Delete** /api/v1/rfqs/{rfq_id} | 
[**GetRfq**](RfqAPI.md#GetRfq) | **Get** /api/v1/rfqs/{rfq_id} | 
[**ListRfqs**](RfqAPI.md#ListRfqs) | **Get** /api/v1/rfqs/ | 
[**UpdateRfq**](RfqAPI.md#UpdateRfq) | **Put** /api/v1/rfqs/{rfq_id} | 
[**UpdateRfqStatus**](RfqAPI.md#UpdateRfqStatus) | **Put** /api/v1/rfqs/{rfq_id}/status | 



## ConvertRfq

> interface{} ConvertRfq(ctx, rfqId).Execute()

Convert an RFQ into a draft purchase order using the quoted unit prices (falling back to the requested prices, then leaving them blank). Marks the RFQ as `converted`.

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
	rfqId := "rfqId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RfqAPI.ConvertRfq(context.Background(), rfqId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RfqAPI.ConvertRfq``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConvertRfq`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `RfqAPI.ConvertRfq`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**rfqId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiConvertRfqRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## CreateRfq

> Rfq CreateRfq(ctx).Rfq(rfq).Execute()



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
	rfq := *openapiclient.NewRfq(interface{}(123), time.Now(), "RfqNumber_example", openapiclient.RfqStatus("draft")) // Rfq | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RfqAPI.CreateRfq(context.Background()).Rfq(rfq).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RfqAPI.CreateRfq``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateRfq`: Rfq
	fmt.Fprintf(os.Stdout, "Response from `RfqAPI.CreateRfq`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRfqRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rfq** | [**Rfq**](Rfq.md) |  | 

### Return type

[**Rfq**](Rfq.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteRfq

> DeleteRfq(ctx, rfqId).Execute()



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
	rfqId := "rfqId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RfqAPI.DeleteRfq(context.Background(), rfqId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RfqAPI.DeleteRfq``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**rfqId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteRfqRequest struct via the builder pattern


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


## GetRfq

> Rfq GetRfq(ctx, rfqId).Execute()



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
	rfqId := "rfqId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RfqAPI.GetRfq(context.Background(), rfqId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RfqAPI.GetRfq``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRfq`: Rfq
	fmt.Fprintf(os.Stdout, "Response from `RfqAPI.GetRfq`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**rfqId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRfqRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Rfq**](Rfq.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRfqs

> []Rfq ListRfqs(ctx).Page(page).PageSize(pageSize).Status(status).SupplierName(supplierName).Execute()



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
	supplierName := "supplierName_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RfqAPI.ListRfqs(context.Background()).Page(page).PageSize(pageSize).Status(status).SupplierName(supplierName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RfqAPI.ListRfqs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRfqs`: []Rfq
	fmt.Fprintf(os.Stdout, "Response from `RfqAPI.ListRfqs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListRfqsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **status** | **string** |  | 
 **supplierName** | **string** |  | 

### Return type

[**[]Rfq**](Rfq.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRfq

> Rfq UpdateRfq(ctx, rfqId).Body(body).Execute()



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
	rfqId := "rfqId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RfqAPI.UpdateRfq(context.Background(), rfqId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RfqAPI.UpdateRfq``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateRfq`: Rfq
	fmt.Fprintf(os.Stdout, "Response from `RfqAPI.UpdateRfq`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**rfqId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRfqRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**Rfq**](Rfq.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRfqStatus

> Rfq UpdateRfqStatus(ctx, rfqId).RfqStatusUpdate(rfqStatusUpdate).Execute()



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
	rfqId := "rfqId_example" // string | 
	rfqStatusUpdate := *openapiclient.NewRfqStatusUpdate("Status_example") // RfqStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RfqAPI.UpdateRfqStatus(context.Background(), rfqId).RfqStatusUpdate(rfqStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RfqAPI.UpdateRfqStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateRfqStatus`: Rfq
	fmt.Fprintf(os.Stdout, "Response from `RfqAPI.UpdateRfqStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**rfqId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRfqStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rfqStatusUpdate** | [**RfqStatusUpdate**](RfqStatusUpdate.md) |  | 

### Return type

[**Rfq**](Rfq.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

