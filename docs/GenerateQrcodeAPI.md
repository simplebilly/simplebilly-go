# \GenerateQrcodeAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GenerateQrcodeApi**](GenerateQrcodeAPI.md#GenerateQrcodeApi) | **Get** /api/v1/invoices/{id}/qrcode | 



## GenerateQrcodeApi

> QRCodeResponse GenerateQrcodeApi(ctx, id).Iban(iban).HolderName(holderName).Bic(bic).Amount(amount).Reference(reference).Purpose(purpose).Execute()



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
	iban := "iban_example" // string | 
	id := "id_example" // string | 
	holderName := "holderName_example" // string |  (optional)
	bic := "bic_example" // string |  (optional)
	amount := "amount_example" // string |  (optional)
	reference := "reference_example" // string |  (optional)
	purpose := "purpose_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GenerateQrcodeAPI.GenerateQrcodeApi(context.Background(), id).Iban(iban).HolderName(holderName).Bic(bic).Amount(amount).Reference(reference).Purpose(purpose).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GenerateQrcodeAPI.GenerateQrcodeApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateQrcodeApi`: QRCodeResponse
	fmt.Fprintf(os.Stdout, "Response from `GenerateQrcodeAPI.GenerateQrcodeApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGenerateQrcodeApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **iban** | **string** |  | 

 **holderName** | **string** |  | 
 **bic** | **string** |  | 
 **amount** | **string** |  | 
 **reference** | **string** |  | 
 **purpose** | **string** |  | 

### Return type

[**QRCodeResponse**](QRCodeResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

