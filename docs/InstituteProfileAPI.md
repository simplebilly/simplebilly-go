# \InstituteProfileAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetInstituteProfile**](InstituteProfileAPI.md#GetInstituteProfile) | **Get** /api/v1/institute-profile | Current institute profile (created with defaults when missing).
[**UpdateInstituteProfile**](InstituteProfileAPI.md#UpdateInstituteProfile) | **Put** /api/v1/institute-profile | Update the institute profile (institute_type and/or kapitalmarktorientiert).



## GetInstituteProfile

> InstituteProfile GetInstituteProfile(ctx).Execute()

Current institute profile (created with defaults when missing).

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
	resp, r, err := apiClient.InstituteProfileAPI.GetInstituteProfile(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstituteProfileAPI.GetInstituteProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInstituteProfile`: InstituteProfile
	fmt.Fprintf(os.Stdout, "Response from `InstituteProfileAPI.GetInstituteProfile`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetInstituteProfileRequest struct via the builder pattern


### Return type

[**InstituteProfile**](InstituteProfile.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateInstituteProfile

> InstituteProfile UpdateInstituteProfile(ctx).InstituteProfileUpdate(instituteProfileUpdate).Execute()

Update the institute profile (institute_type and/or kapitalmarktorientiert).

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
	instituteProfileUpdate := *openapiclient.NewInstituteProfileUpdate() // InstituteProfileUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstituteProfileAPI.UpdateInstituteProfile(context.Background()).InstituteProfileUpdate(instituteProfileUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstituteProfileAPI.UpdateInstituteProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateInstituteProfile`: InstituteProfile
	fmt.Fprintf(os.Stdout, "Response from `InstituteProfileAPI.UpdateInstituteProfile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateInstituteProfileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **instituteProfileUpdate** | [**InstituteProfileUpdate**](InstituteProfileUpdate.md) |  | 

### Return type

[**InstituteProfile**](InstituteProfile.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

