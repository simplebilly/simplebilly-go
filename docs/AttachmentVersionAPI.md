# \AttachmentVersionAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAttachmentVersion**](AttachmentVersionAPI.md#CreateAttachmentVersion) | **Post** /api/v1/attachments/{attachment_id}/versions | 
[**ListAttachmentVersions**](AttachmentVersionAPI.md#ListAttachmentVersions) | **Get** /api/v1/attachments/{attachment_id}/versions | 
[**RestoreAttachmentVersion**](AttachmentVersionAPI.md#RestoreAttachmentVersion) | **Post** /api/v1/attachments/{attachment_id}/versions/{version_id}/restore | 



## CreateAttachmentVersion

> AttachmentVersion CreateAttachmentVersion(ctx, attachmentId).NewVersionRequest(newVersionRequest).Execute()



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
	attachmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	newVersionRequest := *openapiclient.NewNewVersionRequest("FileName_example") // NewVersionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttachmentVersionAPI.CreateAttachmentVersion(context.Background(), attachmentId).NewVersionRequest(newVersionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentVersionAPI.CreateAttachmentVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAttachmentVersion`: AttachmentVersion
	fmt.Fprintf(os.Stdout, "Response from `AttachmentVersionAPI.CreateAttachmentVersion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateAttachmentVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **newVersionRequest** | [**NewVersionRequest**](NewVersionRequest.md) |  | 

### Return type

[**AttachmentVersion**](AttachmentVersion.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAttachmentVersions

> []AttachmentVersion ListAttachmentVersions(ctx, attachmentId).Execute()



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
	attachmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttachmentVersionAPI.ListAttachmentVersions(context.Background(), attachmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentVersionAPI.ListAttachmentVersions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAttachmentVersions`: []AttachmentVersion
	fmt.Fprintf(os.Stdout, "Response from `AttachmentVersionAPI.ListAttachmentVersions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAttachmentVersionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AttachmentVersion**](AttachmentVersion.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RestoreAttachmentVersion

> Attachment RestoreAttachmentVersion(ctx, attachmentId, versionId).Execute()



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
	attachmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	versionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttachmentVersionAPI.RestoreAttachmentVersion(context.Background(), attachmentId, versionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentVersionAPI.RestoreAttachmentVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RestoreAttachmentVersion`: Attachment
	fmt.Fprintf(os.Stdout, "Response from `AttachmentVersionAPI.RestoreAttachmentVersion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **string** |  | 
**versionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRestoreAttachmentVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Attachment**](Attachment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

