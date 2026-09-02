# \GewerbesteuerAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GewerbesteuerApi**](GewerbesteuerAPI.md#GewerbesteuerApi) | **Get** /api/v1/bookkeeping/gewerbesteuer | 



## GewerbesteuerApi

> GewerbesteuerErgebnis GewerbesteuerApi(ctx).Year(year).Hebesatz(hebesatz).Gewerbeertrag(gewerbeertrag).Country(country).Gemeindeschluessel(gemeindeschluessel).Execute()



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
	hebesatz := "hebesatz_example" // string |  (optional)
	gewerbeertrag := "gewerbeertrag_example" // string |  (optional)
	country := "country_example" // string |  (optional)
	gemeindeschluessel := "gemeindeschluessel_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GewerbesteuerAPI.GewerbesteuerApi(context.Background()).Year(year).Hebesatz(hebesatz).Gewerbeertrag(gewerbeertrag).Country(country).Gemeindeschluessel(gemeindeschluessel).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GewerbesteuerAPI.GewerbesteuerApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GewerbesteuerApi`: GewerbesteuerErgebnis
	fmt.Fprintf(os.Stdout, "Response from `GewerbesteuerAPI.GewerbesteuerApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGewerbesteuerApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 
 **hebesatz** | **string** |  | 
 **gewerbeertrag** | **string** |  | 
 **country** | **string** |  | 
 **gemeindeschluessel** | **string** |  | 

### Return type

[**GewerbesteuerErgebnis**](GewerbesteuerErgebnis.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

