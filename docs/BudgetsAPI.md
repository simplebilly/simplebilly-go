# \BudgetsAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BudgetsApi**](BudgetsAPI.md#BudgetsApi) | **Get** /api/v1/bookkeeping/budgets | 
[**UpsertBudgetGoalApi**](BudgetsAPI.md#UpsertBudgetGoalApi) | **Put** /api/v1/bookkeeping/budgets/goals/{category} | 



## BudgetsApi

> BudgetErgebnis BudgetsApi(ctx).Year(year).Month(month).Execute()



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
	month := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BudgetsAPI.BudgetsApi(context.Background()).Year(year).Month(month).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BudgetsAPI.BudgetsApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BudgetsApi`: BudgetErgebnis
	fmt.Fprintf(os.Stdout, "Response from `BudgetsAPI.BudgetsApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBudgetsApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **year** | **int32** |  | 
 **month** | **int32** |  | 

### Return type

[**BudgetErgebnis**](BudgetErgebnis.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertBudgetGoalApi

> Budget UpsertBudgetGoalApi(ctx, category).BudgetGoalRequest(budgetGoalRequest).Execute()



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
	category := "category_example" // string | 
	budgetGoalRequest := *openapiclient.NewBudgetGoalRequest("MonthlyGoal_example", int32(123)) // BudgetGoalRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BudgetsAPI.UpsertBudgetGoalApi(context.Background(), category).BudgetGoalRequest(budgetGoalRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BudgetsAPI.UpsertBudgetGoalApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertBudgetGoalApi`: Budget
	fmt.Fprintf(os.Stdout, "Response from `BudgetsAPI.UpsertBudgetGoalApi`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**category** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpsertBudgetGoalApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **budgetGoalRequest** | [**BudgetGoalRequest**](BudgetGoalRequest.md) |  | 

### Return type

[**Budget**](Budget.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

