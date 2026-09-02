# \TicketMessageAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListMessagesApi**](TicketMessageAPI.md#ListMessagesApi) | **Get** /api/v1/support/tickets/{ticket_id}/messages | 
[**SendMessageApi**](TicketMessageAPI.md#SendMessageApi) | **Post** /api/v1/support/tickets/{ticket_id}/messages | 



## ListMessagesApi

> []TicketMessage ListMessagesApi(ctx, ticketId).Execute()



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
	resp, r, err := apiClient.TicketMessageAPI.ListMessagesApi(context.Background(), ticketId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TicketMessageAPI.ListMessagesApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMessagesApi`: []TicketMessage
	fmt.Fprintf(os.Stdout, "Response from `TicketMessageAPI.ListMessagesApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ticketId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListMessagesApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]TicketMessage**](TicketMessage.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendMessageApi

> TicketMessage SendMessageApi(ctx, ticketId).SendMessageDto(sendMessageDto).Execute()



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
	sendMessageDto := *openapiclient.NewSendMessageDto("Body_example") // SendMessageDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TicketMessageAPI.SendMessageApi(context.Background(), ticketId).SendMessageDto(sendMessageDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TicketMessageAPI.SendMessageApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendMessageApi`: TicketMessage
	fmt.Fprintf(os.Stdout, "Response from `TicketMessageAPI.SendMessageApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ticketId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendMessageApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sendMessageDto** | [**SendMessageDto**](SendMessageDto.md) |  | 

### Return type

[**TicketMessage**](TicketMessage.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

