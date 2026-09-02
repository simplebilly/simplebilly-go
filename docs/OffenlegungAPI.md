# \OffenlegungAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OffenlegungApi**](OffenlegungAPI.md#OffenlegungApi) | **Get** /api/v1/bookkeeping/offenlegung | 



## OffenlegungApi

> OffenlegungReport OffenlegungApi(ctx).Execute()



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
	resp, r, err := apiClient.OffenlegungAPI.OffenlegungApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OffenlegungAPI.OffenlegungApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OffenlegungApi`: OffenlegungReport
	fmt.Fprintf(os.Stdout, "Response from `OffenlegungAPI.OffenlegungApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOffenlegungApiRequest struct via the builder pattern


### Return type

[**OffenlegungReport**](OffenlegungReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

