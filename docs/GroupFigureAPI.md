# \GroupFigureAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateGroupFigure**](GroupFigureAPI.md#CreateGroupFigure) | **Post** /api/v1/group-figures | 
[**DeleteGroupFigure**](GroupFigureAPI.md#DeleteGroupFigure) | **Delete** /api/v1/group-figures/{year} | 
[**GetGroupFigure**](GroupFigureAPI.md#GetGroupFigure) | **Get** /api/v1/group-figures/{year} | 
[**GetGroupFigures**](GroupFigureAPI.md#GetGroupFigures) | **Get** /api/v1/group-figures/ | 
[**UpdateGroupFigure**](GroupFigureAPI.md#UpdateGroupFigure) | **Put** /api/v1/group-figures/{year} | 



## CreateGroupFigure

> GroupFigure CreateGroupFigure(ctx).GroupFigureCreate(groupFigureCreate).Execute()



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
	groupFigureCreate := *openapiclient.NewGroupFigureCreate() // GroupFigureCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupFigureAPI.CreateGroupFigure(context.Background()).GroupFigureCreate(groupFigureCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupFigureAPI.CreateGroupFigure``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGroupFigure`: GroupFigure
	fmt.Fprintf(os.Stdout, "Response from `GroupFigureAPI.CreateGroupFigure`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateGroupFigureRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **groupFigureCreate** | [**GroupFigureCreate**](GroupFigureCreate.md) |  | 

### Return type

[**GroupFigure**](GroupFigure.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteGroupFigure

> DeleteGroupFigure(ctx, year).Execute()



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
	r, err := apiClient.GroupFigureAPI.DeleteGroupFigure(context.Background(), year).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupFigureAPI.DeleteGroupFigure``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**year** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteGroupFigureRequest struct via the builder pattern


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


## GetGroupFigure

> GroupFigure GetGroupFigure(ctx, year).Execute()



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
	resp, r, err := apiClient.GroupFigureAPI.GetGroupFigure(context.Background(), year).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupFigureAPI.GetGroupFigure``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroupFigure`: GroupFigure
	fmt.Fprintf(os.Stdout, "Response from `GroupFigureAPI.GetGroupFigure`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**year** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupFigureRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GroupFigure**](GroupFigure.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroupFigures

> []GroupFigure GetGroupFigures(ctx).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()



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
	page := int32(1) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	search := "search_example" // string |  (optional)
	includeDeleted := true // bool | Soft-delete entities: set true to include rows with `deleted_at` set. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupFigureAPI.GetGroupFigures(context.Background()).Page(page).PageSize(pageSize).Search(search).IncludeDeleted(includeDeleted).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupFigureAPI.GetGroupFigures``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroupFigures`: []GroupFigure
	fmt.Fprintf(os.Stdout, "Response from `GroupFigureAPI.GetGroupFigures`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupFiguresRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **search** | **string** |  | 
 **includeDeleted** | **bool** | Soft-delete entities: set true to include rows with &#x60;deleted_at&#x60; set. | 

### Return type

[**[]GroupFigure**](GroupFigure.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGroupFigure

> GroupFigure UpdateGroupFigure(ctx, year).GroupFigureUpdate(groupFigureUpdate).Execute()



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
	groupFigureUpdate := *openapiclient.NewGroupFigureUpdate() // GroupFigureUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupFigureAPI.UpdateGroupFigure(context.Background(), year).GroupFigureUpdate(groupFigureUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupFigureAPI.UpdateGroupFigure``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGroupFigure`: GroupFigure
	fmt.Fprintf(os.Stdout, "Response from `GroupFigureAPI.UpdateGroupFigure`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**year** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGroupFigureRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **groupFigureUpdate** | [**GroupFigureUpdate**](GroupFigureUpdate.md) |  | 

### Return type

[**GroupFigure**](GroupFigure.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

