# \TimeEntriesAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ClockInTimeEntry**](TimeEntriesAPI.md#ClockInTimeEntry) | **Post** /api/v1/time-entries | Clock in for the authenticated user (resolved via their employee profile).
[**ClockOutTimeEntry**](TimeEntriesAPI.md#ClockOutTimeEntry) | **Patch** /api/v1/time-entries/{id} | Clock out an entry: the entry&#39;s owner, or anyone with &#x60;time_entries:write&#x60;.
[**GetLaborCosts**](TimeEntriesAPI.md#GetLaborCosts) | **Get** /api/v1/labor-costs | Labor-cost report: worked hours aggregated per employee / order / day, valued at the employee&#39;s hourly cost rate.
[**ListTimeEntries**](TimeEntriesAPI.md#ListTimeEntries) | **Get** /api/v1/time-entries | List time entries with optional date-range / active / employee filters.



## ClockInTimeEntry

> TimeEntryDto ClockInTimeEntry(ctx).TimeEntryClockIn(timeEntryClockIn).Execute()

Clock in for the authenticated user (resolved via their employee profile).

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
	timeEntryClockIn := *openapiclient.NewTimeEntryClockIn() // TimeEntryClockIn | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimeEntriesAPI.ClockInTimeEntry(context.Background()).TimeEntryClockIn(timeEntryClockIn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimeEntriesAPI.ClockInTimeEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClockInTimeEntry`: TimeEntryDto
	fmt.Fprintf(os.Stdout, "Response from `TimeEntriesAPI.ClockInTimeEntry`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiClockInTimeEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **timeEntryClockIn** | [**TimeEntryClockIn**](TimeEntryClockIn.md) |  | 

### Return type

[**TimeEntryDto**](TimeEntryDto.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClockOutTimeEntry

> TimeEntryDto ClockOutTimeEntry(ctx, id).TimeEntryClockOut(timeEntryClockOut).Execute()

Clock out an entry: the entry's owner, or anyone with `time_entries:write`.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	timeEntryClockOut := *openapiclient.NewTimeEntryClockOut(time.Now()) // TimeEntryClockOut | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimeEntriesAPI.ClockOutTimeEntry(context.Background(), id).TimeEntryClockOut(timeEntryClockOut).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimeEntriesAPI.ClockOutTimeEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClockOutTimeEntry`: TimeEntryDto
	fmt.Fprintf(os.Stdout, "Response from `TimeEntriesAPI.ClockOutTimeEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClockOutTimeEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **timeEntryClockOut** | [**TimeEntryClockOut**](TimeEntryClockOut.md) |  | 

### Return type

[**TimeEntryDto**](TimeEntryDto.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLaborCosts

> []LaborCostRow GetLaborCosts(ctx).From(from).To(to).GroupBy(groupBy).Execute()

Labor-cost report: worked hours aggregated per employee / order / day, valued at the employee's hourly cost rate.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	from := time.Now() // string | 
	to := time.Now() // string | 
	groupBy := "groupBy_example" // string | One of \"employee\", \"order\" or \"day\".

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimeEntriesAPI.GetLaborCosts(context.Background()).From(from).To(to).GroupBy(groupBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimeEntriesAPI.GetLaborCosts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLaborCosts`: []LaborCostRow
	fmt.Fprintf(os.Stdout, "Response from `TimeEntriesAPI.GetLaborCosts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLaborCostsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **from** | **string** |  | 
 **to** | **string** |  | 
 **groupBy** | **string** | One of \&quot;employee\&quot;, \&quot;order\&quot; or \&quot;day\&quot;. | 

### Return type

[**[]LaborCostRow**](LaborCostRow.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTimeEntries

> []TimeEntryDto ListTimeEntries(ctx).From(from).To(to).Active(active).EmployeeId(employeeId).Execute()

List time entries with optional date-range / active / employee filters.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	from := time.Now() // string |  (optional)
	to := time.Now() // string |  (optional)
	active := true // bool | Only currently running shifts (clock_in set, clock_out null). (optional)
	employeeId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimeEntriesAPI.ListTimeEntries(context.Background()).From(from).To(to).Active(active).EmployeeId(employeeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimeEntriesAPI.ListTimeEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTimeEntries`: []TimeEntryDto
	fmt.Fprintf(os.Stdout, "Response from `TimeEntriesAPI.ListTimeEntries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTimeEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **from** | **string** |  | 
 **to** | **string** |  | 
 **active** | **bool** | Only currently running shifts (clock_in set, clock_out null). | 
 **employeeId** | **string** |  | 

### Return type

[**[]TimeEntryDto**](TimeEntryDto.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

