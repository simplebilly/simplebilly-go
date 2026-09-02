# \CreateSepaDirectDebitAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateSepaDirectDebitApi**](CreateSepaDirectDebitAPI.md#CreateSepaDirectDebitApi) | **Post** /api/v1/bookkeeping/sepa-direct-debit | 



## CreateSepaDirectDebitApi

> SepaDirectDebitResponse CreateSepaDirectDebitApi(ctx).CreditorName(creditorName).CreditorIban(creditorIban).CreditorId(creditorId).MandateId(mandateId).MandateDate(mandateDate).DebtorName(debtorName).DebtorIban(debtorIban).Amount(amount).CollectionDate(collectionDate).CreditorBic(creditorBic).DebtorBic(debtorBic).Description(description).Execute()



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
	creditorName := "creditorName_example" // string | 
	creditorIban := "creditorIban_example" // string | 
	creditorId := "creditorId_example" // string | 
	mandateId := "mandateId_example" // string | 
	mandateDate := "mandateDate_example" // string | 
	debtorName := "debtorName_example" // string | 
	debtorIban := "debtorIban_example" // string | 
	amount := "amount_example" // string | 
	collectionDate := "collectionDate_example" // string | 
	creditorBic := "creditorBic_example" // string |  (optional)
	debtorBic := "debtorBic_example" // string |  (optional)
	description := "description_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CreateSepaDirectDebitAPI.CreateSepaDirectDebitApi(context.Background()).CreditorName(creditorName).CreditorIban(creditorIban).CreditorId(creditorId).MandateId(mandateId).MandateDate(mandateDate).DebtorName(debtorName).DebtorIban(debtorIban).Amount(amount).CollectionDate(collectionDate).CreditorBic(creditorBic).DebtorBic(debtorBic).Description(description).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreateSepaDirectDebitAPI.CreateSepaDirectDebitApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateSepaDirectDebitApi`: SepaDirectDebitResponse
	fmt.Fprintf(os.Stdout, "Response from `CreateSepaDirectDebitAPI.CreateSepaDirectDebitApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSepaDirectDebitApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **creditorName** | **string** |  | 
 **creditorIban** | **string** |  | 
 **creditorId** | **string** |  | 
 **mandateId** | **string** |  | 
 **mandateDate** | **string** |  | 
 **debtorName** | **string** |  | 
 **debtorIban** | **string** |  | 
 **amount** | **string** |  | 
 **collectionDate** | **string** |  | 
 **creditorBic** | **string** |  | 
 **debtorBic** | **string** |  | 
 **description** | **string** |  | 

### Return type

[**SepaDirectDebitResponse**](SepaDirectDebitResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

