# \SuitabilityAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShippingSuitabilityApi**](SuitabilityAPI.md#ShippingSuitabilityApi) | **Post** /api/v1/shipping/suitability | 



## ShippingSuitabilityApi

> SuitabilityResult ShippingSuitabilityApi(ctx).SuitabilityRequest(suitabilityRequest).Execute()



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
	suitabilityRequest := *openapiclient.NewSuitabilityRequest([]openapiclient.CartItemInput{*openapiclient.NewCartItemInput("ProductId_example", int32(123))}, *openapiclient.NewAddress("City_example", "Country_example", "Name_example", "Street_example", "StreetNumber_example", "Zip_example"), *openapiclient.NewAddress("City_example", "Country_example", "Name_example", "Street_example", "StreetNumber_example", "Zip_example")) // SuitabilityRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SuitabilityAPI.ShippingSuitabilityApi(context.Background()).SuitabilityRequest(suitabilityRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SuitabilityAPI.ShippingSuitabilityApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShippingSuitabilityApi`: SuitabilityResult
	fmt.Fprintf(os.Stdout, "Response from `SuitabilityAPI.ShippingSuitabilityApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShippingSuitabilityApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **suitabilityRequest** | [**SuitabilityRequest**](SuitabilityRequest.md) |  | 

### Return type

[**SuitabilityResult**](SuitabilityResult.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

