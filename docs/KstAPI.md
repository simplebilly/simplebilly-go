# \KstAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**KstApi**](KstAPI.md#KstApi) | **Get** /api/v1/bookkeeping/kst | 



## KstApi

> KstErgebnis KstApi(ctx).Year(year).Gewinn(gewinn).Execute()



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
	gewinn := "gewinn_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KstAPI.KstApi(context.Background()).Year(year).Gewinn(gewinn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KstAPI.KstApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KstApi`: KstErgebnis
	fmt.Fprintf(os.Stdout, "Response from `KstAPI.KstApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiKstApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 
 **gewinn** | **string** |  | 

### Return type

[**KstErgebnis**](KstErgebnis.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

