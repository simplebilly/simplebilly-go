# \CustomerCommunicationAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCommunication**](CustomerCommunicationAPI.md#CreateCommunication) | **Post** /api/v1/communications | 
[**CustomercommunicationRestore**](CustomerCommunicationAPI.md#CustomercommunicationRestore) | **Post** /api/v1/communications/{communication_id}/restore | 
[**DeleteCommunication**](CustomerCommunicationAPI.md#DeleteCommunication) | **Delete** /api/v1/communications/{communication_id} | 
[**GetCommunication**](CustomerCommunicationAPI.md#GetCommunication) | **Get** /api/v1/communications/{communication_id} | 
[**GetContactHistory**](CustomerCommunicationAPI.md#GetContactHistory) | **Get** /api/v1/contacts/{contact_id}/communications | 
[**ListCommunications**](CustomerCommunicationAPI.md#ListCommunications) | **Get** /api/v1/communications/ | 
[**UpdateCommunication**](CustomerCommunicationAPI.md#UpdateCommunication) | **Put** /api/v1/communications/{communication_id} | 



## CreateCommunication

> CustomerCommunication CreateCommunication(ctx).CustomerCommunicationCreate(customerCommunicationCreate).Execute()



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
	customerCommunicationCreate := *openapiclient.NewCustomerCommunicationCreate(openapiclient.CommunicationChannel("email"), "ContactId_example", openapiclient.CommunicationDirection("inbound")) // CustomerCommunicationCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerCommunicationAPI.CreateCommunication(context.Background()).CustomerCommunicationCreate(customerCommunicationCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerCommunicationAPI.CreateCommunication``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCommunication`: CustomerCommunication
	fmt.Fprintf(os.Stdout, "Response from `CustomerCommunicationAPI.CreateCommunication`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCommunicationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customerCommunicationCreate** | [**CustomerCommunicationCreate**](CustomerCommunicationCreate.md) |  | 

### Return type

[**CustomerCommunication**](CustomerCommunication.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CustomercommunicationRestore

> CustomerCommunication CustomercommunicationRestore(ctx, communicationId).Execute()



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
	communicationId := "communicationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerCommunicationAPI.CustomercommunicationRestore(context.Background(), communicationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerCommunicationAPI.CustomercommunicationRestore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CustomercommunicationRestore`: CustomerCommunication
	fmt.Fprintf(os.Stdout, "Response from `CustomerCommunicationAPI.CustomercommunicationRestore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**communicationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCustomercommunicationRestoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerCommunication**](CustomerCommunication.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCommunication

> DeleteCommunication(ctx, communicationId).Execute()



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
	communicationId := "communicationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CustomerCommunicationAPI.DeleteCommunication(context.Background(), communicationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerCommunicationAPI.DeleteCommunication``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**communicationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCommunicationRequest struct via the builder pattern


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


## GetCommunication

> CustomerCommunication GetCommunication(ctx, communicationId).Execute()



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
	communicationId := "communicationId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerCommunicationAPI.GetCommunication(context.Background(), communicationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerCommunicationAPI.GetCommunication``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCommunication`: CustomerCommunication
	fmt.Fprintf(os.Stdout, "Response from `CustomerCommunicationAPI.GetCommunication`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**communicationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCommunicationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CustomerCommunication**](CustomerCommunication.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetContactHistory

> ContactHistoryResponse GetContactHistory(ctx, contactId).Execute()



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
	contactId := "contactId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerCommunicationAPI.GetContactHistory(context.Background(), contactId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerCommunicationAPI.GetContactHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetContactHistory`: ContactHistoryResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomerCommunicationAPI.GetContactHistory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**contactId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetContactHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ContactHistoryResponse**](ContactHistoryResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCommunications

> []CustomerCommunication ListCommunications(ctx).Page(page).PageSize(pageSize).ContactId(contactId).Channel(channel).Direction(direction).From(from).To(to).Execute()



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
	contactId := "contactId_example" // string | Filter history to a single contact. (optional)
	channel := openapiclient.CommunicationChannel("email") // CommunicationChannel |  (optional)
	direction := openapiclient.CommunicationDirection("inbound") // CommunicationDirection |  (optional)
	from := time.Now() // string | Only include communications after this ISO date (inclusive). (optional)
	to := time.Now() // string | Only include communications before this ISO date (inclusive). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerCommunicationAPI.ListCommunications(context.Background()).Page(page).PageSize(pageSize).ContactId(contactId).Channel(channel).Direction(direction).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerCommunicationAPI.ListCommunications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCommunications`: []CustomerCommunication
	fmt.Fprintf(os.Stdout, "Response from `CustomerCommunicationAPI.ListCommunications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCommunicationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **contactId** | **string** | Filter history to a single contact. | 
 **channel** | [**CommunicationChannel**](CommunicationChannel.md) |  | 
 **direction** | [**CommunicationDirection**](CommunicationDirection.md) |  | 
 **from** | **string** | Only include communications after this ISO date (inclusive). | 
 **to** | **string** | Only include communications before this ISO date (inclusive). | 

### Return type

[**[]CustomerCommunication**](CustomerCommunication.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCommunication

> CustomerCommunication UpdateCommunication(ctx, communicationId).CustomerCommunicationUpdate(customerCommunicationUpdate).Execute()



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
	communicationId := "communicationId_example" // string | 
	customerCommunicationUpdate := *openapiclient.NewCustomerCommunicationUpdate() // CustomerCommunicationUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomerCommunicationAPI.UpdateCommunication(context.Background(), communicationId).CustomerCommunicationUpdate(customerCommunicationUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomerCommunicationAPI.UpdateCommunication``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCommunication`: CustomerCommunication
	fmt.Fprintf(os.Stdout, "Response from `CustomerCommunicationAPI.UpdateCommunication`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**communicationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCommunicationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **customerCommunicationUpdate** | [**CustomerCommunicationUpdate**](CustomerCommunicationUpdate.md) |  | 

### Return type

[**CustomerCommunication**](CustomerCommunication.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

