# \SupportChannelAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateChannelApi**](SupportChannelAPI.md#CreateChannelApi) | **Post** /api/v1/support/channels | 
[**DeleteChannelApi**](SupportChannelAPI.md#DeleteChannelApi) | **Delete** /api/v1/support/channels/{channel_id} | 
[**ListChannelsApi**](SupportChannelAPI.md#ListChannelsApi) | **Get** /api/v1/support/channels | 
[**UpdateChannelApi**](SupportChannelAPI.md#UpdateChannelApi) | **Put** /api/v1/support/channels/{channel_id} | 



## CreateChannelApi

> SupportChannel CreateChannelApi(ctx).CreateChannelDto(createChannelDto).Execute()



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
	createChannelDto := *openapiclient.NewCreateChannelDto("ChannelType_example", interface{}(123), "Name_example") // CreateChannelDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupportChannelAPI.CreateChannelApi(context.Background()).CreateChannelDto(createChannelDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportChannelAPI.CreateChannelApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateChannelApi`: SupportChannel
	fmt.Fprintf(os.Stdout, "Response from `SupportChannelAPI.CreateChannelApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateChannelApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createChannelDto** | [**CreateChannelDto**](CreateChannelDto.md) |  | 

### Return type

[**SupportChannel**](SupportChannel.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteChannelApi

> DeleteChannelApi(ctx, channelId).Execute()



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
	channelId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SupportChannelAPI.DeleteChannelApi(context.Background(), channelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportChannelAPI.DeleteChannelApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**channelId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteChannelApiRequest struct via the builder pattern


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


## ListChannelsApi

> []SupportChannel ListChannelsApi(ctx).Execute()



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
	resp, r, err := apiClient.SupportChannelAPI.ListChannelsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportChannelAPI.ListChannelsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListChannelsApi`: []SupportChannel
	fmt.Fprintf(os.Stdout, "Response from `SupportChannelAPI.ListChannelsApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListChannelsApiRequest struct via the builder pattern


### Return type

[**[]SupportChannel**](SupportChannel.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateChannelApi

> SupportChannel UpdateChannelApi(ctx, channelId).UpdateChannelDto(updateChannelDto).Execute()



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
	channelId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	updateChannelDto := *openapiclient.NewUpdateChannelDto() // UpdateChannelDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SupportChannelAPI.UpdateChannelApi(context.Background(), channelId).UpdateChannelDto(updateChannelDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SupportChannelAPI.UpdateChannelApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateChannelApi`: SupportChannel
	fmt.Fprintf(os.Stdout, "Response from `SupportChannelAPI.UpdateChannelApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**channelId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateChannelApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateChannelDto** | [**UpdateChannelDto**](UpdateChannelDto.md) |  | 

### Return type

[**SupportChannel**](SupportChannel.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

