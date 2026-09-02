# \PaymentConditionAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListPaymentConditionsApi**](PaymentConditionAPI.md#ListPaymentConditionsApi) | **Get** /api/v1/payment-conditions | 



## ListPaymentConditionsApi

> []PaymentCondition ListPaymentConditionsApi(ctx).Execute()



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
	resp, r, err := apiClient.PaymentConditionAPI.ListPaymentConditionsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentConditionAPI.ListPaymentConditionsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPaymentConditionsApi`: []PaymentCondition
	fmt.Fprintf(os.Stdout, "Response from `PaymentConditionAPI.ListPaymentConditionsApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPaymentConditionsApiRequest struct via the builder pattern


### Return type

[**[]PaymentCondition**](PaymentCondition.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

