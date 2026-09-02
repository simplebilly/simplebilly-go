# \LegalDocumentAPI

All URIs are relative to *https://demo.simplebilly.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetLegalDocuments**](LegalDocumentAPI.md#GetLegalDocuments) | **Get** /api/v1/legal/documents | List all legal documents of the tenant. Missing documents are seeded from the default texts (with tenant placeholders replaced) on first access.
[**ResetLegalDocuments**](LegalDocumentAPI.md#ResetLegalDocuments) | **Post** /api/v1/legal/documents/reset | Restore default texts for all documents (or a single doc_type/lang when the optional filter is given). Returns the full tenant list.
[**UpsertLegalDocuments**](LegalDocumentAPI.md#UpsertLegalDocuments) | **Put** /api/v1/legal/documents | Upsert legal documents per (doc_type, lang). Returns the full tenant list.



## GetLegalDocuments

> []LegalDocument GetLegalDocuments(ctx).Execute()

List all legal documents of the tenant. Missing documents are seeded from the default texts (with tenant placeholders replaced) on first access.

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
	resp, r, err := apiClient.LegalDocumentAPI.GetLegalDocuments(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LegalDocumentAPI.GetLegalDocuments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLegalDocuments`: []LegalDocument
	fmt.Fprintf(os.Stdout, "Response from `LegalDocumentAPI.GetLegalDocuments`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLegalDocumentsRequest struct via the builder pattern


### Return type

[**[]LegalDocument**](LegalDocument.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResetLegalDocuments

> []LegalDocument ResetLegalDocuments(ctx).LegalDocumentReset(legalDocumentReset).Execute()

Restore default texts for all documents (or a single doc_type/lang when the optional filter is given). Returns the full tenant list.

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
	legalDocumentReset := *openapiclient.NewLegalDocumentReset() // LegalDocumentReset | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LegalDocumentAPI.ResetLegalDocuments(context.Background()).LegalDocumentReset(legalDocumentReset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LegalDocumentAPI.ResetLegalDocuments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResetLegalDocuments`: []LegalDocument
	fmt.Fprintf(os.Stdout, "Response from `LegalDocumentAPI.ResetLegalDocuments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiResetLegalDocumentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **legalDocumentReset** | [**LegalDocumentReset**](LegalDocumentReset.md) |  | 

### Return type

[**[]LegalDocument**](LegalDocument.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertLegalDocuments

> []LegalDocument UpsertLegalDocuments(ctx).LegalDocumentUpsert(legalDocumentUpsert).Execute()

Upsert legal documents per (doc_type, lang). Returns the full tenant list.

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
	legalDocumentUpsert := []openapiclient.LegalDocumentUpsert{*openapiclient.NewLegalDocumentUpsert("Content_example", "DocType_example", "Lang_example", "Title_example")} // []LegalDocumentUpsert | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LegalDocumentAPI.UpsertLegalDocuments(context.Background()).LegalDocumentUpsert(legalDocumentUpsert).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LegalDocumentAPI.UpsertLegalDocuments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertLegalDocuments`: []LegalDocument
	fmt.Fprintf(os.Stdout, "Response from `LegalDocumentAPI.UpsertLegalDocuments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpsertLegalDocumentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **legalDocumentUpsert** | [**[]LegalDocumentUpsert**](LegalDocumentUpsert.md) |  | 

### Return type

[**[]LegalDocument**](LegalDocument.md)

### Authorization

[bearer_token](../README.md#bearer_token)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

