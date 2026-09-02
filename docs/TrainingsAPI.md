# \TrainingsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetMyTrainings**](TrainingsAPI.md#GetMyTrainings) | **Get** /api/v1/trainings/me | 
[**GetTrainingContent**](TrainingsAPI.md#GetTrainingContent) | **Get** /api/v1/trainings/content/{code} | 
[**GetTrainingOverview**](TrainingsAPI.md#GetTrainingOverview) | **Get** /api/v1/trainings/overview | 
[**SubmitTrainingResult**](TrainingsAPI.md#SubmitTrainingResult) | **Post** /api/v1/trainings/submit-result | 



## GetMyTrainings

> []MyTrainingItem GetMyTrainings(ctx).Execute()



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
	resp, r, err := apiClient.TrainingsAPI.GetMyTrainings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingsAPI.GetMyTrainings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMyTrainings`: []MyTrainingItem
	fmt.Fprintf(os.Stdout, "Response from `TrainingsAPI.GetMyTrainings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMyTrainingsRequest struct via the builder pattern


### Return type

[**[]MyTrainingItem**](MyTrainingItem.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrainingContent

> TrainingContent GetTrainingContent(ctx, code).Execute()



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
	code := "code_example" // string | Training code, e.g. data_privacy

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrainingsAPI.GetTrainingContent(context.Background(), code).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingsAPI.GetTrainingContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrainingContent`: TrainingContent
	fmt.Fprintf(os.Stdout, "Response from `TrainingsAPI.GetTrainingContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**code** | **string** | Training code, e.g. data_privacy | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTrainingContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TrainingContent**](TrainingContent.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrainingOverview

> []HrTrainingOverview GetTrainingOverview(ctx).Execute()



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
	resp, r, err := apiClient.TrainingsAPI.GetTrainingOverview(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingsAPI.GetTrainingOverview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrainingOverview`: []HrTrainingOverview
	fmt.Fprintf(os.Stdout, "Response from `TrainingsAPI.GetTrainingOverview`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetTrainingOverviewRequest struct via the builder pattern


### Return type

[**[]HrTrainingOverview**](HrTrainingOverview.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubmitTrainingResult

> SubmitResultResponse SubmitTrainingResult(ctx).SubmitResultDto(submitResultDto).Execute()



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
	submitResultDto := *openapiclient.NewSubmitResultDto([]int32{int32(123)}, int32(123), "TrainingCode_example") // SubmitResultDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrainingsAPI.SubmitTrainingResult(context.Background()).SubmitResultDto(submitResultDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrainingsAPI.SubmitTrainingResult``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubmitTrainingResult`: SubmitResultResponse
	fmt.Fprintf(os.Stdout, "Response from `TrainingsAPI.SubmitTrainingResult`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubmitTrainingResultRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **submitResultDto** | [**SubmitResultDto**](SubmitResultDto.md) |  | 

### Return type

[**SubmitResultResponse**](SubmitResultResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

