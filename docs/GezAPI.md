# \GezAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GezApi**](GezAPI.md#GezApi) | **Get** /api/v1/bookkeeping/gez | 



## GezApi

> GezReport GezApi(ctx).Jahr(jahr).Betriebsstaetten(betriebsstaetten).Kfz(kfz).Hotelzimmer(hotelzimmer).Beschaefigte(beschaefigte).Execute()



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
	jahr := int32(56) // int32 |  (optional)
	betriebsstaetten := "betriebsstaetten_example" // string | Liste der Betriebsstätten als JSON, z.B. `[{\"name\":\"Filiale 1\",\"beschaefigte\":12}]`. (optional)
	kfz := int64(789) // int64 | Gesamtzahl der betrieblich genutzten Kfz (falls keine Betriebsstätten angegeben sind). (optional)
	hotelzimmer := int64(789) // int64 | Gesamtzahl der Hotel-/Gästezimmer und Ferienwohnungen. (optional)
	beschaefigte := int64(789) // int64 | Gesamtzahl der Beschäftigten (verwendet nur, wenn `betriebsstaetten` fehlt; dann wird eine einzelne Betriebsstätte angenommen). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GezAPI.GezApi(context.Background()).Jahr(jahr).Betriebsstaetten(betriebsstaetten).Kfz(kfz).Hotelzimmer(hotelzimmer).Beschaefigte(beschaefigte).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GezAPI.GezApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GezApi`: GezReport
	fmt.Fprintf(os.Stdout, "Response from `GezAPI.GezApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGezApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jahr** | **int32** |  | 
 **betriebsstaetten** | **string** | Liste der Betriebsstätten als JSON, z.B. &#x60;[{\&quot;name\&quot;:\&quot;Filiale 1\&quot;,\&quot;beschaefigte\&quot;:12}]&#x60;. | 
 **kfz** | **int64** | Gesamtzahl der betrieblich genutzten Kfz (falls keine Betriebsstätten angegeben sind). | 
 **hotelzimmer** | **int64** | Gesamtzahl der Hotel-/Gästezimmer und Ferienwohnungen. | 
 **beschaefigte** | **int64** | Gesamtzahl der Beschäftigten (verwendet nur, wenn &#x60;betriebsstaetten&#x60; fehlt; dann wird eine einzelne Betriebsstätte angenommen). | 

### Return type

[**GezReport**](GezReport.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

