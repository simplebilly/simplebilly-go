# \ShippingAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCredentialsApi**](ShippingAPI.md#GetCredentialsApi) | **Get** /api/v1/shipping/credentials | 
[**GetRatesApi**](ShippingAPI.md#GetRatesApi) | **Post** /api/v1/shipping/rates | 
[**ListProvidersApi**](ShippingAPI.md#ListProvidersApi) | **Get** /api/v1/shipping/providers | 
[**SaveCredentialsApi**](ShippingAPI.md#SaveCredentialsApi) | **Put** /api/v1/shipping/credentials | 



## GetCredentialsApi

> ShippingCredentials GetCredentialsApi(ctx).Execute()



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
	resp, r, err := apiClient.ShippingAPI.GetCredentialsApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingAPI.GetCredentialsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCredentialsApi`: ShippingCredentials
	fmt.Fprintf(os.Stdout, "Response from `ShippingAPI.GetCredentialsApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCredentialsApiRequest struct via the builder pattern


### Return type

[**ShippingCredentials**](ShippingCredentials.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRatesApi

> RateResponse GetRatesApi(ctx).RateRequest(rateRequest).Execute()



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
	rateRequest := *openapiclient.NewRateRequest([]openapiclient.Package{*openapiclient.NewPackage(float64(123))}, *openapiclient.NewAddress("City_example", "Country_example", "Name_example", "Street_example", "StreetNumber_example", "Zip_example"), *openapiclient.NewAddress("City_example", "Country_example", "Name_example", "Street_example", "StreetNumber_example", "Zip_example")) // RateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingAPI.GetRatesApi(context.Background()).RateRequest(rateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingAPI.GetRatesApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRatesApi`: RateResponse
	fmt.Fprintf(os.Stdout, "Response from `ShippingAPI.GetRatesApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRatesApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rateRequest** | [**RateRequest**](RateRequest.md) |  | 

### Return type

[**RateResponse**](RateResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProvidersApi

> []ProviderInfo ListProvidersApi(ctx).Execute()



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
	resp, r, err := apiClient.ShippingAPI.ListProvidersApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingAPI.ListProvidersApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProvidersApi`: []ProviderInfo
	fmt.Fprintf(os.Stdout, "Response from `ShippingAPI.ListProvidersApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListProvidersApiRequest struct via the builder pattern


### Return type

[**[]ProviderInfo**](ProviderInfo.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveCredentialsApi

> ShippingCredentials SaveCredentialsApi(ctx).ShippingCredentials(shippingCredentials).Execute()



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
	shippingCredentials := *openapiclient.NewShippingCredentials() // ShippingCredentials | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShippingAPI.SaveCredentialsApi(context.Background()).ShippingCredentials(shippingCredentials).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShippingAPI.SaveCredentialsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveCredentialsApi`: ShippingCredentials
	fmt.Fprintf(os.Stdout, "Response from `ShippingAPI.SaveCredentialsApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaveCredentialsApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **shippingCredentials** | [**ShippingCredentials**](ShippingCredentials.md) |  | 

### Return type

[**ShippingCredentials**](ShippingCredentials.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

