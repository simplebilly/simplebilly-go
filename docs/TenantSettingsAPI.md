# \TenantSettingsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetTenantSettings**](TenantSettingsAPI.md#GetTenantSettings) | **Get** /api/v1/settings/tenant | 
[**UpdateTenantSettings**](TenantSettingsAPI.md#UpdateTenantSettings) | **Put** /api/v1/settings/tenant | 



## GetTenantSettings

> TenantSettings GetTenantSettings(ctx).Execute()



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
	resp, r, err := apiClient.TenantSettingsAPI.GetTenantSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantSettingsAPI.GetTenantSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTenantSettings`: TenantSettings
	fmt.Fprintf(os.Stdout, "Response from `TenantSettingsAPI.GetTenantSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetTenantSettingsRequest struct via the builder pattern


### Return type

[**TenantSettings**](TenantSettings.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTenantSettings

> TenantSettings UpdateTenantSettings(ctx).UpdateTenantSettings(updateTenantSettings).Execute()



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
	updateTenantSettings := *openapiclient.NewUpdateTenantSettings(openapiclient.CompanyType("gmbh")) // UpdateTenantSettings | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantSettingsAPI.UpdateTenantSettings(context.Background()).UpdateTenantSettings(updateTenantSettings).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantSettingsAPI.UpdateTenantSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTenantSettings`: TenantSettings
	fmt.Fprintf(os.Stdout, "Response from `TenantSettingsAPI.UpdateTenantSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTenantSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateTenantSettings** | [**UpdateTenantSettings**](UpdateTenantSettings.md) |  | 

### Return type

[**TenantSettings**](TenantSettings.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

