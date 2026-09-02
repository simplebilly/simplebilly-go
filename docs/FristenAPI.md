# \FristenAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FristenApi**](FristenAPI.md#FristenApi) | **Get** /api/v1/bookkeeping/fristen | 



## FristenApi

> FristenErgebnis FristenApi(ctx).Bundesland(bundesland).Voranmeldungsrhythmus(voranmeldungsrhythmus).Dauerfristverlaengerung(dauerfristverlaengerung).EstAktiv(estAktiv).GewstAktiv(gewstAktiv).Monate(monate).Execute()



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
	bundesland := "bundesland_example" // string |  (optional)
	voranmeldungsrhythmus := "voranmeldungsrhythmus_example" // string |  (optional)
	dauerfristverlaengerung := true // bool |  (optional)
	estAktiv := true // bool |  (optional)
	gewstAktiv := true // bool |  (optional)
	monate := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FristenAPI.FristenApi(context.Background()).Bundesland(bundesland).Voranmeldungsrhythmus(voranmeldungsrhythmus).Dauerfristverlaengerung(dauerfristverlaengerung).EstAktiv(estAktiv).GewstAktiv(gewstAktiv).Monate(monate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FristenAPI.FristenApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FristenApi`: FristenErgebnis
	fmt.Fprintf(os.Stdout, "Response from `FristenAPI.FristenApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFristenApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bundesland** | **string** |  | 
 **voranmeldungsrhythmus** | **string** |  | 
 **dauerfristverlaengerung** | **bool** |  | 
 **estAktiv** | **bool** |  | 
 **gewstAktiv** | **bool** |  | 
 **monate** | **int32** |  | 

### Return type

[**FristenErgebnis**](FristenErgebnis.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

