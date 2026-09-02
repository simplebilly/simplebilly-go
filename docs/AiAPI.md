# \AiAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AiSuggestApi**](AiAPI.md#AiSuggestApi) | **Post** /api/v1/support/ai/suggest | 
[**CreateWorkerApi**](AiAPI.md#CreateWorkerApi) | **Post** /api/v1/support/ai/workers | 
[**ListWorkersApi**](AiAPI.md#ListWorkersApi) | **Get** /api/v1/support/ai/workers | 
[**RunWorkerApi**](AiAPI.md#RunWorkerApi) | **Post** /api/v1/support/ai/workers/{worker_id}/run | 



## AiSuggestApi

> AiSuggestion AiSuggestApi(ctx).AiSuggestionRequest(aiSuggestionRequest).Execute()



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
	aiSuggestionRequest := *openapiclient.NewAiSuggestionRequest("TicketId_example") // AiSuggestionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.AiSuggestApi(context.Background()).AiSuggestionRequest(aiSuggestionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.AiSuggestApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AiSuggestApi`: AiSuggestion
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.AiSuggestApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAiSuggestApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aiSuggestionRequest** | [**AiSuggestionRequest**](AiSuggestionRequest.md) |  | 

### Return type

[**AiSuggestion**](AiSuggestion.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateWorkerApi

> AiWorkerConfig CreateWorkerApi(ctx).AiConfigDto(aiConfigDto).Execute()



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
	aiConfigDto := *openapiclient.NewAiConfigDto("Model_example", "Name_example", "Provider_example") // AiConfigDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.CreateWorkerApi(context.Background()).AiConfigDto(aiConfigDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.CreateWorkerApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWorkerApi`: AiWorkerConfig
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.CreateWorkerApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateWorkerApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aiConfigDto** | [**AiConfigDto**](AiConfigDto.md) |  | 

### Return type

[**AiWorkerConfig**](AiWorkerConfig.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkersApi

> []AiWorkerConfig ListWorkersApi(ctx).Execute()



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
	resp, r, err := apiClient.AiAPI.ListWorkersApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.ListWorkersApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkersApi`: []AiWorkerConfig
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.ListWorkersApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListWorkersApiRequest struct via the builder pattern


### Return type

[**[]AiWorkerConfig**](AiWorkerConfig.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunWorkerApi

> AiSuggestion RunWorkerApi(ctx, workerId).AiSuggestionRequest(aiSuggestionRequest).Execute()



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
	workerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	aiSuggestionRequest := *openapiclient.NewAiSuggestionRequest("TicketId_example") // AiSuggestionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.RunWorkerApi(context.Background(), workerId).AiSuggestionRequest(aiSuggestionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.RunWorkerApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunWorkerApi`: AiSuggestion
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.RunWorkerApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRunWorkerApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **aiSuggestionRequest** | [**AiSuggestionRequest**](AiSuggestionRequest.md) |  | 

### Return type

[**AiSuggestion**](AiSuggestion.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

