# \SupportTicketAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTicketApi**](SupportTicketAPI.md#CreateTicketApi) | **Post** /api/v1/support/tickets | 
[**DeleteTicketApi**](SupportTicketAPI.md#DeleteTicketApi) | **Delete** /api/v1/support/tickets/{ticket_id} | 
[**GetTicketApi**](SupportTicketAPI.md#GetTicketApi) | **Get** /api/v1/support/tickets/{ticket_id} | 
[**ListTicketsApi**](SupportTicketAPI.md#ListTicketsApi) | **Get** /api/v1/support/tickets | 
[**UpdateTicketApi**](SupportTicketAPI.md#UpdateTicketApi) | **Put** /api/v1/support/tickets/{ticket_id} | 



## CreateTicketApi

> SupportTicket CreateTicketApi(ctx).CreateTicketRequest(createTicketRequest).Execute()



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
	createTicketRequest := *openapiclient.NewCreateTicketRequest("MessageBody_example", "Subject_example") // CreateTicketRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupportTicketAPI.CreateTicketApi(context.Background()).CreateTicketRequest(createTicketRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportTicketAPI.CreateTicketApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTicketApi`: SupportTicket
	fmt.Fprintf(os.Stdout, "Response from `SupportTicketAPI.CreateTicketApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTicketApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createTicketRequest** | [**CreateTicketRequest**](CreateTicketRequest.md) |  | 

### Return type

[**SupportTicket**](SupportTicket.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteTicketApi

> DeleteTicketApi(ctx, ticketId).Execute()



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
	ticketId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SupportTicketAPI.DeleteTicketApi(context.Background(), ticketId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportTicketAPI.DeleteTicketApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ticketId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteTicketApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTicketApi

> SupportTicket GetTicketApi(ctx, ticketId).Execute()



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
	ticketId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupportTicketAPI.GetTicketApi(context.Background(), ticketId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportTicketAPI.GetTicketApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTicketApi`: SupportTicket
	fmt.Fprintf(os.Stdout, "Response from `SupportTicketAPI.GetTicketApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ticketId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTicketApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SupportTicket**](SupportTicket.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTicketsApi

> []SupportTicket ListTicketsApi(ctx).Status(status).Priority(priority).AssignedTo(assignedTo).ChannelType(channelType).CustomerId(customerId).Search(search).Page(page).PageSize(pageSize).Execute()



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
	status := "status_example" // string |  (optional)
	priority := "priority_example" // string |  (optional)
	assignedTo := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	channelType := "channelType_example" // string |  (optional)
	customerId := "customerId_example" // string |  (optional)
	search := "search_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupportTicketAPI.ListTicketsApi(context.Background()).Status(status).Priority(priority).AssignedTo(assignedTo).ChannelType(channelType).CustomerId(customerId).Search(search).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportTicketAPI.ListTicketsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTicketsApi`: []SupportTicket
	fmt.Fprintf(os.Stdout, "Response from `SupportTicketAPI.ListTicketsApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTicketsApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | 
 **priority** | **string** |  | 
 **assignedTo** | **string** |  | 
 **channelType** | **string** |  | 
 **customerId** | **string** |  | 
 **search** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**[]SupportTicket**](SupportTicket.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTicketApi

> SupportTicket UpdateTicketApi(ctx, ticketId).SupportTicketUpdate(supportTicketUpdate).Execute()



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
	ticketId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	supportTicketUpdate := *openapiclient.NewSupportTicketUpdate() // SupportTicketUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupportTicketAPI.UpdateTicketApi(context.Background(), ticketId).SupportTicketUpdate(supportTicketUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportTicketAPI.UpdateTicketApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTicketApi`: SupportTicket
	fmt.Fprintf(os.Stdout, "Response from `SupportTicketAPI.UpdateTicketApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ticketId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTicketApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **supportTicketUpdate** | [**SupportTicketUpdate**](SupportTicketUpdate.md) |  | 

### Return type

[**SupportTicket**](SupportTicket.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

