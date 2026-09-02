# \PlausibilityAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PlausibilityCheckApi**](PlausibilityAPI.md#PlausibilityCheckApi) | **Get** /api/v1/bookkeeping/plausibility | 



## PlausibilityCheckApi

> PlausibilityReport PlausibilityCheckApi(ctx).DateFrom(dateFrom).DateTo(dateTo).Execute()



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
	dateFrom := "dateFrom_example" // string |  (optional)
	dateTo := "dateTo_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlausibilityAPI.PlausibilityCheckApi(context.Background()).DateFrom(dateFrom).DateTo(dateTo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlausibilityAPI.PlausibilityCheckApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlausibilityCheckApi`: PlausibilityReport
	fmt.Fprintf(os.Stdout, "Response from `PlausibilityAPI.PlausibilityCheckApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlausibilityCheckApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dateFrom** | **string** |  | 
 **dateTo** | **string** |  | 

### Return type

[**PlausibilityReport**](PlausibilityReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

