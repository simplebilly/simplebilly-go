# \BankingAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BankLookupApi**](BankingAPI.md#BankLookupApi) | **Get** /api/v1/bookkeeping/banking/lookup | 
[**BankTransactionsApi**](BankingAPI.md#BankTransactionsApi) | **Get** /api/v1/bookkeeping/banking/transactions | 
[**HebesatzLookupApi**](BankingAPI.md#HebesatzLookupApi) | **Get** /api/v1/bookkeeping/hebesatz | 



## BankLookupApi

> BankLookup BankLookupApi(ctx).Iban(iban).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BankingAPI.BankLookupApi(context.Background()).Iban(iban).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BankingAPI.BankLookupApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BankLookupApi`: BankLookup
	fmt.Fprintf(os.Stdout, "Response from `BankingAPI.BankLookupApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBankLookupApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **iban** | **string** |  | 

### Return type

[**BankLookup**](BankLookup.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BankTransactionsApi

> BankTransactionsApi(ctx).Execute()



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
	r, err := apiClient.BankingAPI.BankTransactionsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BankingAPI.BankTransactionsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiBankTransactionsApiRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HebesatzLookupApi

> []HebesatzLookup HebesatzLookupApi(ctx).Gemeindeschluessel(gemeindeschluessel).Plz(plz).Name(name).Stichtag(stichtag).CountryCode(countryCode).Execute()



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
	gemeindeschluessel := "gemeindeschluessel_example" // string |  (optional)
	plz := "plz_example" // string |  (optional)
	name := "name_example" // string |  (optional)
	stichtag := "stichtag_example" // string | Stichtag for validity (YYYY-MM-DD); defaults to today. Picks row where valid_from <= date <= valid_to. (optional)
	countryCode := "countryCode_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BankingAPI.HebesatzLookupApi(context.Background()).Gemeindeschluessel(gemeindeschluessel).Plz(plz).Name(name).Stichtag(stichtag).CountryCode(countryCode).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BankingAPI.HebesatzLookupApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HebesatzLookupApi`: []HebesatzLookup
	fmt.Fprintf(os.Stdout, "Response from `BankingAPI.HebesatzLookupApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiHebesatzLookupApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **gemeindeschluessel** | **string** |  | 
 **plz** | **string** |  | 
 **name** | **string** |  | 
 **stichtag** | **string** | Stichtag for validity (YYYY-MM-DD); defaults to today. Picks row where valid_from &lt;&#x3D; date &lt;&#x3D; valid_to. | 
 **countryCode** | **string** |  | 

### Return type

[**[]HebesatzLookup**](HebesatzLookup.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

