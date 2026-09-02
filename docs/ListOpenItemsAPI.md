# \ListOpenItemsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListOpenItemsApi**](ListOpenItemsAPI.md#ListOpenItemsApi) | **Get** /api/v1/bookkeeping/open-items | 



## ListOpenItemsApi

> []OpenItem ListOpenItemsApi(ctx).ReminderLevel1Days(reminderLevel1Days).ReminderLevel2Days(reminderLevel2Days).ReminderLevel3Days(reminderLevel3Days).CustomerId(customerId).Execute()



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
	reminderLevel1Days := int64(789) // int64 |  (optional)
	reminderLevel2Days := int64(789) // int64 |  (optional)
	reminderLevel3Days := int64(789) // int64 |  (optional)
	customerId := "customerId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ListOpenItemsAPI.ListOpenItemsApi(context.Background()).ReminderLevel1Days(reminderLevel1Days).ReminderLevel2Days(reminderLevel2Days).ReminderLevel3Days(reminderLevel3Days).CustomerId(customerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ListOpenItemsAPI.ListOpenItemsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOpenItemsApi`: []OpenItem
	fmt.Fprintf(os.Stdout, "Response from `ListOpenItemsAPI.ListOpenItemsApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOpenItemsApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reminderLevel1Days** | **int64** |  | 
 **reminderLevel2Days** | **int64** |  | 
 **reminderLevel3Days** | **int64** |  | 
 **customerId** | **string** |  | 

### Return type

[**[]OpenItem**](OpenItem.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

