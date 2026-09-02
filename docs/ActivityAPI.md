# \ActivityAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateActivity**](ActivityAPI.md#CreateActivity) | **Post** /api/v1/activities | 
[**DeleteActivity**](ActivityAPI.md#DeleteActivity) | **Delete** /api/v1/activities/{activity_id} | 
[**GetActivity**](ActivityAPI.md#GetActivity) | **Get** /api/v1/activities/{activity_id} | 
[**ListActivities**](ActivityAPI.md#ListActivities) | **Get** /api/v1/activities/ | 
[**UpdateActivity**](ActivityAPI.md#UpdateActivity) | **Put** /api/v1/activities/{activity_id} | 
[**UpdateActivityStatus**](ActivityAPI.md#UpdateActivityStatus) | **Put** /api/v1/activities/{activity_id}/status | 



## CreateActivity

> Activity CreateActivity(ctx).Activity(activity).Execute()



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
	activity := *openapiclient.NewActivity(openapiclient.ActivityType("call"), openapiclient.ActivityStatus("open"), "Subject_example") // Activity | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.CreateActivity(context.Background()).Activity(activity).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.CreateActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateActivity`: Activity
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.CreateActivity`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **activity** | [**Activity**](Activity.md) |  | 

### Return type

[**Activity**](Activity.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteActivity

> DeleteActivity(ctx, activityId).Execute()



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
	activityId := "activityId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ActivityAPI.DeleteActivity(context.Background(), activityId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.DeleteActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**activityId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetActivity

> Activity GetActivity(ctx, activityId).Execute()



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
	activityId := "activityId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.GetActivity(context.Background(), activityId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.GetActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetActivity`: Activity
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.GetActivity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**activityId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Activity**](Activity.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListActivities

> []Activity ListActivities(ctx).Page(page).PageSize(pageSize).ContactId(contactId).ActivityType(activityType).Status(status).AssignedTo(assignedTo).OverdueOnly(overdueOnly).Execute()



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
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	contactId := "contactId_example" // string |  (optional)
	activityType := "activityType_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	assignedTo := "assignedTo_example" // string |  (optional)
	overdueOnly := true // bool | Only show overdue follow-ups. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.ListActivities(context.Background()).Page(page).PageSize(pageSize).ContactId(contactId).ActivityType(activityType).Status(status).AssignedTo(assignedTo).OverdueOnly(overdueOnly).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.ListActivities``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListActivities`: []Activity
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.ListActivities`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListActivitiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **contactId** | **string** |  | 
 **activityType** | **string** |  | 
 **status** | **string** |  | 
 **assignedTo** | **string** |  | 
 **overdueOnly** | **bool** | Only show overdue follow-ups. | 

### Return type

[**[]Activity**](Activity.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateActivity

> Activity UpdateActivity(ctx, activityId).Body(body).Execute()



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
	activityId := "activityId_example" // string | 
	body := interface{}(987) // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.UpdateActivity(context.Background(), activityId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.UpdateActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateActivity`: Activity
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.UpdateActivity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**activityId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **interface{}** |  | 

### Return type

[**Activity**](Activity.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateActivityStatus

> Activity UpdateActivityStatus(ctx, activityId).ActivityStatusUpdate(activityStatusUpdate).Execute()



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
	activityId := "activityId_example" // string | 
	activityStatusUpdate := *openapiclient.NewActivityStatusUpdate("Status_example") // ActivityStatusUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.UpdateActivityStatus(context.Background(), activityId).ActivityStatusUpdate(activityStatusUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.UpdateActivityStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateActivityStatus`: Activity
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.UpdateActivityStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**activityId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateActivityStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **activityStatusUpdate** | [**ActivityStatusUpdate**](ActivityStatusUpdate.md) |  | 

### Return type

[**Activity**](Activity.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

