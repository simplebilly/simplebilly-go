# \EmissionsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateEmissionEntryApi**](EmissionsAPI.md#CreateEmissionEntryApi) | **Post** /api/v1/bookkeeping/emissions/entries | 
[**CreateEmissionTargetApi**](EmissionsAPI.md#CreateEmissionTargetApi) | **Post** /api/v1/bookkeeping/emissions/targets | 
[**DeleteEmissionEntryApi**](EmissionsAPI.md#DeleteEmissionEntryApi) | **Delete** /api/v1/bookkeeping/emissions/entries/{id} | 
[**DeleteEmissionTargetApi**](EmissionsAPI.md#DeleteEmissionTargetApi) | **Delete** /api/v1/bookkeeping/emissions/targets/{id} | 
[**EmissionsEntriesApi**](EmissionsAPI.md#EmissionsEntriesApi) | **Get** /api/v1/bookkeeping/emissions/entries | 
[**EmissionsExportApi**](EmissionsAPI.md#EmissionsExportApi) | **Get** /api/v1/bookkeeping/emissions/export | 
[**EmissionsFactorsApi**](EmissionsAPI.md#EmissionsFactorsApi) | **Get** /api/v1/bookkeeping/emissions/factors | 
[**EmissionsReportApi**](EmissionsAPI.md#EmissionsReportApi) | **Get** /api/v1/bookkeeping/emissions/report | 
[**EmissionsTargetsApi**](EmissionsAPI.md#EmissionsTargetsApi) | **Get** /api/v1/bookkeeping/emissions/targets | 



## CreateEmissionEntryApi

> EmissionEntry CreateEmissionEntryApi(ctx).CreateEmissionEntry(createEmissionEntry).Execute()



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
	createEmissionEntry := *openapiclient.NewCreateEmissionEntry("ActivityValue_example", "CategoryId_example", "Description_example", "Method_example", "Scope_example", "Unit_example", int32(123)) // CreateEmissionEntry | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmissionsAPI.CreateEmissionEntryApi(context.Background()).CreateEmissionEntry(createEmissionEntry).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.CreateEmissionEntryApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateEmissionEntryApi`: EmissionEntry
	fmt.Fprintf(os.Stdout, "Response from `EmissionsAPI.CreateEmissionEntryApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateEmissionEntryApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createEmissionEntry** | [**CreateEmissionEntry**](CreateEmissionEntry.md) |  | 

### Return type

[**EmissionEntry**](EmissionEntry.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateEmissionTargetApi

> EmissionTarget CreateEmissionTargetApi(ctx).CreateEmissionTarget(createEmissionTarget).Execute()



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
	createEmissionTarget := *openapiclient.NewCreateEmissionTarget("BaseValue_example", int32(123), "Description_example", "Scope_example", "TargetValue_example", int32(123)) // CreateEmissionTarget | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmissionsAPI.CreateEmissionTargetApi(context.Background()).CreateEmissionTarget(createEmissionTarget).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.CreateEmissionTargetApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateEmissionTargetApi`: EmissionTarget
	fmt.Fprintf(os.Stdout, "Response from `EmissionsAPI.CreateEmissionTargetApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateEmissionTargetApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createEmissionTarget** | [**CreateEmissionTarget**](CreateEmissionTarget.md) |  | 

### Return type

[**EmissionTarget**](EmissionTarget.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteEmissionEntryApi

> DeleteEmissionEntryApi(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmissionsAPI.DeleteEmissionEntryApi(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.DeleteEmissionEntryApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteEmissionEntryApiRequest struct via the builder pattern


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


## DeleteEmissionTargetApi

> DeleteEmissionTargetApi(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmissionsAPI.DeleteEmissionTargetApi(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.DeleteEmissionTargetApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteEmissionTargetApiRequest struct via the builder pattern


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


## EmissionsEntriesApi

> []EmissionEntry EmissionsEntriesApi(ctx).Year(year).Execute()



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
	year := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmissionsAPI.EmissionsEntriesApi(context.Background()).Year(year).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.EmissionsEntriesApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmissionsEntriesApi`: []EmissionEntry
	fmt.Fprintf(os.Stdout, "Response from `EmissionsAPI.EmissionsEntriesApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmissionsEntriesApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 

### Return type

[**[]EmissionEntry**](EmissionEntry.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EmissionsExportApi

> EmissionsExportResponse EmissionsExportApi(ctx).Year(year).Execute()



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
	year := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmissionsAPI.EmissionsExportApi(context.Background()).Year(year).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.EmissionsExportApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmissionsExportApi`: EmissionsExportResponse
	fmt.Fprintf(os.Stdout, "Response from `EmissionsAPI.EmissionsExportApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmissionsExportApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 

### Return type

[**EmissionsExportResponse**](EmissionsExportResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EmissionsFactorsApi

> []EmissionFactorResponse EmissionsFactorsApi(ctx).Execute()



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
	resp, r, err := apiClient.EmissionsAPI.EmissionsFactorsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.EmissionsFactorsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmissionsFactorsApi`: []EmissionFactorResponse
	fmt.Fprintf(os.Stdout, "Response from `EmissionsAPI.EmissionsFactorsApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiEmissionsFactorsApiRequest struct via the builder pattern


### Return type

[**[]EmissionFactorResponse**](EmissionFactorResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EmissionsReportApi

> EmissionsReport EmissionsReportApi(ctx).Year(year).Execute()



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
	year := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmissionsAPI.EmissionsReportApi(context.Background()).Year(year).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.EmissionsReportApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmissionsReportApi`: EmissionsReport
	fmt.Fprintf(os.Stdout, "Response from `EmissionsAPI.EmissionsReportApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmissionsReportApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 

### Return type

[**EmissionsReport**](EmissionsReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EmissionsTargetsApi

> []EmissionTarget EmissionsTargetsApi(ctx).Execute()



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
	resp, r, err := apiClient.EmissionsAPI.EmissionsTargetsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmissionsAPI.EmissionsTargetsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmissionsTargetsApi`: []EmissionTarget
	fmt.Fprintf(os.Stdout, "Response from `EmissionsAPI.EmissionsTargetsApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiEmissionsTargetsApiRequest struct via the builder pattern


### Return type

[**[]EmissionTarget**](EmissionTarget.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

