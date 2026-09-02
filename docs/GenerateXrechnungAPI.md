# \GenerateXrechnungAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GenerateXrechnungApi**](GenerateXrechnungAPI.md#GenerateXrechnungApi) | **Get** /api/v1/invoices/{id}/xrechnung | 



## GenerateXrechnungApi

> XRechnungResponse GenerateXrechnungApi(ctx, id).SupplierName(supplierName).SupplierStreet(supplierStreet).SupplierCity(supplierCity).SupplierZip(supplierZip).SupplierCountry(supplierCountry).SupplierVatId(supplierVatId).Execute()



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
	resp, r, err := apiClient.GenerateXrechnungAPI.GenerateXrechnungApi(context.Background(), id).SupplierName(supplierName).SupplierStreet(supplierStreet).SupplierCity(supplierCity).SupplierZip(supplierZip).SupplierCountry(supplierCountry).SupplierVatId(supplierVatId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GenerateXrechnungAPI.GenerateXrechnungApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateXrechnungApi`: XRechnungResponse
	fmt.Fprintf(os.Stdout, "Response from `GenerateXrechnungAPI.GenerateXrechnungApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGenerateXrechnungApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **supplierName** | **string** |  | 
 **supplierStreet** | **string** |  | 
 **supplierCity** | **string** |  | 
 **supplierZip** | **string** |  | 
 **supplierCountry** | **string** |  | 
 **supplierVatId** | **string** |  | 

### Return type

[**XRechnungResponse**](XRechnungResponse.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

