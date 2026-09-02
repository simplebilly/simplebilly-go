# \LeadAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListLeadsApi**](LeadAPI.md#ListLeadsApi) | **Get** /api/v1/support/leads | 
[**UpdateLeadApi**](LeadAPI.md#UpdateLeadApi) | **Put** /api/v1/support/leads/{lead_id} | 



## ListLeadsApi

> []Lead ListLeadsApi(ctx).Status(status).Source(source).Search(search).Page(page).PageSize(pageSize).Execute()



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
	source := "source_example" // string |  (optional)
	search := "search_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LeadAPI.ListLeadsApi(context.Background()).Status(status).Source(source).Search(search).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LeadAPI.ListLeadsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListLeadsApi`: []Lead
	fmt.Fprintf(os.Stdout, "Response from `LeadAPI.ListLeadsApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListLeadsApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | 
 **source** | **string** |  | 
 **search** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 

### Return type

[**[]Lead**](Lead.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateLeadApi

> Lead UpdateLeadApi(ctx, leadId).LeadUpdate(leadUpdate).Execute()



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
	leadId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	leadUpdate := *openapiclient.NewLeadUpdate() // LeadUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LeadAPI.UpdateLeadApi(context.Background(), leadId).LeadUpdate(leadUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LeadAPI.UpdateLeadApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateLeadApi`: Lead
	fmt.Fprintf(os.Stdout, "Response from `LeadAPI.UpdateLeadApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**leadId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateLeadApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **leadUpdate** | [**LeadUpdate**](LeadUpdate.md) |  | 

### Return type

[**Lead**](Lead.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

