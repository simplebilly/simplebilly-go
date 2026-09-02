# \ZugferdAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GenerateZugferdApi**](ZugferdAPI.md#GenerateZugferdApi) | **Get** /api/v1/invoices/{id}/zugferd | 



## GenerateZugferdApi

> GenerateZugferdApi(ctx, id).SupplierName(supplierName).SupplierStreet(supplierStreet).SupplierCity(supplierCity).SupplierZip(supplierZip).SupplierCountry(supplierCountry).SupplierVatId(supplierVatId).Execute()



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
	id := "id_example" // string | 
	supplierName := "supplierName_example" // string |  (optional)
	supplierStreet := "supplierStreet_example" // string |  (optional)
	supplierCity := "supplierCity_example" // string |  (optional)
	supplierZip := "supplierZip_example" // string |  (optional)
	supplierCountry := "supplierCountry_example" // string |  (optional)
	supplierVatId := "supplierVatId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ZugferdAPI.GenerateZugferdApi(context.Background(), id).SupplierName(supplierName).SupplierStreet(supplierStreet).SupplierCity(supplierCity).SupplierZip(supplierZip).SupplierCountry(supplierCountry).SupplierVatId(supplierVatId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ZugferdAPI.GenerateZugferdApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGenerateZugferdApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **supplierName** | **string** |  | 
 **supplierStreet** | **string** |  | 
 **supplierCity** | **string** |  | 
 **supplierZip** | **string** |  | 
 **supplierCountry** | **string** |  | 
 **supplierVatId** | **string** |  | 

### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

