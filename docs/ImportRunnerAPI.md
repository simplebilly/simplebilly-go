# \ImportRunnerAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetImportStatus**](ImportRunnerAPI.md#GetImportStatus) | **Get** /api/v1/import/{job_id} | 
[**StartImport**](ImportRunnerAPI.md#StartImport) | **Post** /api/v1/import/start | 
[**TestImportConnection**](ImportRunnerAPI.md#TestImportConnection) | **Post** /api/v1/import/test | 



## GetImportStatus

> ImportJobStatus GetImportStatus(ctx, jobId).Execute()



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
	jobId := "jobId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportRunnerAPI.GetImportStatus(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportRunnerAPI.GetImportStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetImportStatus`: ImportJobStatus
	fmt.Fprintf(os.Stdout, "Response from `ImportRunnerAPI.GetImportStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetImportStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImportJobStatus**](ImportJobStatus.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartImport

> ImportStartResponse StartImport(ctx).ImportStartRequest(importStartRequest).Execute()



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
	importStartRequest := *openapiclient.NewImportStartRequest("ApiKey_example", "Provider_example", []int32{int32(123)}) // ImportStartRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportRunnerAPI.StartImport(context.Background()).ImportStartRequest(importStartRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportRunnerAPI.StartImport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartImport`: ImportStartResponse
	fmt.Fprintf(os.Stdout, "Response from `ImportRunnerAPI.StartImport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStartImportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **importStartRequest** | [**ImportStartRequest**](ImportStartRequest.md) |  | 

### Return type

[**ImportStartResponse**](ImportStartResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestImportConnection

> ImportTestResponse TestImportConnection(ctx).ImportTestRequest(importTestRequest).Execute()



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
	importTestRequest := *openapiclient.NewImportTestRequest("ApiKey_example", "Provider_example") // ImportTestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportRunnerAPI.TestImportConnection(context.Background()).ImportTestRequest(importTestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportRunnerAPI.TestImportConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestImportConnection`: ImportTestResponse
	fmt.Fprintf(os.Stdout, "Response from `ImportRunnerAPI.TestImportConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTestImportConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **importTestRequest** | [**ImportTestRequest**](ImportTestRequest.md) |  | 

### Return type

[**ImportTestResponse**](ImportTestResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

