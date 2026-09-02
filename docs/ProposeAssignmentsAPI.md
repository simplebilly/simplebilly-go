# \ProposeAssignmentsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProposeAssignmentsApi**](ProposeAssignmentsAPI.md#ProposeAssignmentsApi) | **Get** /api/v1/bookkeeping/propose-assignments | 



## ProposeAssignmentsApi

> []ProposedAssignment ProposeAssignmentsApi(ctx).MinConfidence(minConfidence).CustomerId(customerId).Execute()



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
	minConfidence := float64(1.2) // float64 |  (optional)
	customerId := "customerId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProposeAssignmentsAPI.ProposeAssignmentsApi(context.Background()).MinConfidence(minConfidence).CustomerId(customerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProposeAssignmentsAPI.ProposeAssignmentsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProposeAssignmentsApi`: []ProposedAssignment
	fmt.Fprintf(os.Stdout, "Response from `ProposeAssignmentsAPI.ProposeAssignmentsApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProposeAssignmentsApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **minConfidence** | **float64** |  | 
 **customerId** | **string** |  | 

### Return type

[**[]ProposedAssignment**](ProposedAssignment.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

