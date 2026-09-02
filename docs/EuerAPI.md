# \EuerAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EuerApi**](EuerAPI.md#EuerApi) | **Get** /api/v1/bookkeeping/euer | 
[**EuerKategorienApi**](EuerAPI.md#EuerKategorienApi) | **Get** /api/v1/bookkeeping/euer/kategorien | 



## EuerApi

> EuerErgebnis EuerApi(ctx).Year(year).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EuerAPI.EuerApi(context.Background()).Year(year).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EuerAPI.EuerApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EuerApi`: EuerErgebnis
	fmt.Fprintf(os.Stdout, "Response from `EuerAPI.EuerApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEuerApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 

### Return type

[**EuerErgebnis**](EuerErgebnis.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EuerKategorienApi

> EuerDetailErgebnis EuerKategorienApi(ctx).Year(year).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EuerAPI.EuerKategorienApi(context.Background()).Year(year).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EuerAPI.EuerKategorienApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EuerKategorienApi`: EuerDetailErgebnis
	fmt.Fprintf(os.Stdout, "Response from `EuerAPI.EuerKategorienApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEuerKategorienApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 

### Return type

[**EuerDetailErgebnis**](EuerDetailErgebnis.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

