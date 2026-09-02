# \OnlineshopAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSmtpConfigApi**](OnlineshopAPI.md#GetSmtpConfigApi) | **Get** /api/v1/settings/smtp | 
[**SaveSmtpConfigApi**](OnlineshopAPI.md#SaveSmtpConfigApi) | **Put** /api/v1/settings/smtp | 



## GetSmtpConfigApi

> SmtpConfig GetSmtpConfigApi(ctx).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OnlineshopAPI.GetSmtpConfigApi(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OnlineshopAPI.GetSmtpConfigApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSmtpConfigApi`: SmtpConfig
	fmt.Fprintf(os.Stdout, "Response from `OnlineshopAPI.GetSmtpConfigApi`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSmtpConfigApiRequest struct via the builder pattern


### Return type

[**SmtpConfig**](SmtpConfig.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveSmtpConfigApi

> SmtpConfig SaveSmtpConfigApi(ctx).SmtpConfig(smtpConfig).Execute()



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
	smtpConfig := *openapiclient.NewSmtpConfig(openapiclient.SmtpEncryption("StartTls"), "FromAddress_example", "Host_example", "Password_example", int32(123), "Username_example") // SmtpConfig |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OnlineshopAPI.SaveSmtpConfigApi(context.Background()).SmtpConfig(smtpConfig).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OnlineshopAPI.SaveSmtpConfigApi``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveSmtpConfigApi`: SmtpConfig
	fmt.Fprintf(os.Stdout, "Response from `OnlineshopAPI.SaveSmtpConfigApi`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaveSmtpConfigApiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smtpConfig** | [**SmtpConfig**](SmtpConfig.md) |  | 

### Return type

[**SmtpConfig**](SmtpConfig.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

