# LegalDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **string** | Plain text, &#x60;\\n\\n&#x60; separates paragraphs. | 
**DocType** | [**LegalDocType**](LegalDocType.md) |  | 
**Lang** | [**LanguageCode**](LanguageCode.md) |  | 
**Title** | **string** |  | 

## Methods

### NewLegalDocument

`func NewLegalDocument(content string, docType LegalDocType, lang LanguageCode, title string, ) *LegalDocument`

NewLegalDocument instantiates a new LegalDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLegalDocumentWithDefaults

`func NewLegalDocumentWithDefaults() *LegalDocument`

NewLegalDocumentWithDefaults instantiates a new LegalDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *LegalDocument) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *LegalDocument) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *LegalDocument) SetContent(v string)`

SetContent sets Content field to given value.


### GetDocType

`func (o *LegalDocument) GetDocType() LegalDocType`

GetDocType returns the DocType field if non-nil, zero value otherwise.

### GetDocTypeOk

`func (o *LegalDocument) GetDocTypeOk() (*LegalDocType, bool)`

GetDocTypeOk returns a tuple with the DocType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocType

`func (o *LegalDocument) SetDocType(v LegalDocType)`

SetDocType sets DocType field to given value.


### GetLang

`func (o *LegalDocument) GetLang() LanguageCode`

GetLang returns the Lang field if non-nil, zero value otherwise.

### GetLangOk

`func (o *LegalDocument) GetLangOk() (*LanguageCode, bool)`

GetLangOk returns a tuple with the Lang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLang

`func (o *LegalDocument) SetLang(v LanguageCode)`

SetLang sets Lang field to given value.


### GetTitle

`func (o *LegalDocument) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *LegalDocument) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *LegalDocument) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


