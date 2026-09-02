# Attachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactId** | Pointer to **NullableString** | Contact this attachment belongs to (per-contact DMS). References the contact entity. | [optional] 
**FileName** | **string** |  | 
**FileSize** | Pointer to **NullableInt64** |  | [optional] 
**MimeType** | Pointer to **NullableString** |  | [optional] 
**OcrText** | Pointer to **NullableString** | Raw text extracted by client-side OCR (tesseract.js), if run. | [optional] 
**OriginalName** | **string** |  | 
**PdfaPath** | Pointer to **NullableString** |  | [optional] 
**Sha256Hash** | Pointer to **NullableString** |  | [optional] 
**UploadedBy** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAttachment

`func NewAttachment(fileName string, originalName string, ) *Attachment`

NewAttachment instantiates a new Attachment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttachmentWithDefaults

`func NewAttachmentWithDefaults() *Attachment`

NewAttachmentWithDefaults instantiates a new Attachment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactId

`func (o *Attachment) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *Attachment) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *Attachment) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *Attachment) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *Attachment) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *Attachment) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetFileName

`func (o *Attachment) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *Attachment) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *Attachment) SetFileName(v string)`

SetFileName sets FileName field to given value.


### GetFileSize

`func (o *Attachment) GetFileSize() int64`

GetFileSize returns the FileSize field if non-nil, zero value otherwise.

### GetFileSizeOk

`func (o *Attachment) GetFileSizeOk() (*int64, bool)`

GetFileSizeOk returns a tuple with the FileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSize

`func (o *Attachment) SetFileSize(v int64)`

SetFileSize sets FileSize field to given value.

### HasFileSize

`func (o *Attachment) HasFileSize() bool`

HasFileSize returns a boolean if a field has been set.

### SetFileSizeNil

`func (o *Attachment) SetFileSizeNil(b bool)`

 SetFileSizeNil sets the value for FileSize to be an explicit nil

### UnsetFileSize
`func (o *Attachment) UnsetFileSize()`

UnsetFileSize ensures that no value is present for FileSize, not even an explicit nil
### GetMimeType

`func (o *Attachment) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *Attachment) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *Attachment) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *Attachment) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *Attachment) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *Attachment) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetOcrText

`func (o *Attachment) GetOcrText() string`

GetOcrText returns the OcrText field if non-nil, zero value otherwise.

### GetOcrTextOk

`func (o *Attachment) GetOcrTextOk() (*string, bool)`

GetOcrTextOk returns a tuple with the OcrText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOcrText

`func (o *Attachment) SetOcrText(v string)`

SetOcrText sets OcrText field to given value.

### HasOcrText

`func (o *Attachment) HasOcrText() bool`

HasOcrText returns a boolean if a field has been set.

### SetOcrTextNil

`func (o *Attachment) SetOcrTextNil(b bool)`

 SetOcrTextNil sets the value for OcrText to be an explicit nil

### UnsetOcrText
`func (o *Attachment) UnsetOcrText()`

UnsetOcrText ensures that no value is present for OcrText, not even an explicit nil
### GetOriginalName

`func (o *Attachment) GetOriginalName() string`

GetOriginalName returns the OriginalName field if non-nil, zero value otherwise.

### GetOriginalNameOk

`func (o *Attachment) GetOriginalNameOk() (*string, bool)`

GetOriginalNameOk returns a tuple with the OriginalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalName

`func (o *Attachment) SetOriginalName(v string)`

SetOriginalName sets OriginalName field to given value.


### GetPdfaPath

`func (o *Attachment) GetPdfaPath() string`

GetPdfaPath returns the PdfaPath field if non-nil, zero value otherwise.

### GetPdfaPathOk

`func (o *Attachment) GetPdfaPathOk() (*string, bool)`

GetPdfaPathOk returns a tuple with the PdfaPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfaPath

`func (o *Attachment) SetPdfaPath(v string)`

SetPdfaPath sets PdfaPath field to given value.

### HasPdfaPath

`func (o *Attachment) HasPdfaPath() bool`

HasPdfaPath returns a boolean if a field has been set.

### SetPdfaPathNil

`func (o *Attachment) SetPdfaPathNil(b bool)`

 SetPdfaPathNil sets the value for PdfaPath to be an explicit nil

### UnsetPdfaPath
`func (o *Attachment) UnsetPdfaPath()`

UnsetPdfaPath ensures that no value is present for PdfaPath, not even an explicit nil
### GetSha256Hash

`func (o *Attachment) GetSha256Hash() string`

GetSha256Hash returns the Sha256Hash field if non-nil, zero value otherwise.

### GetSha256HashOk

`func (o *Attachment) GetSha256HashOk() (*string, bool)`

GetSha256HashOk returns a tuple with the Sha256Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256Hash

`func (o *Attachment) SetSha256Hash(v string)`

SetSha256Hash sets Sha256Hash field to given value.

### HasSha256Hash

`func (o *Attachment) HasSha256Hash() bool`

HasSha256Hash returns a boolean if a field has been set.

### SetSha256HashNil

`func (o *Attachment) SetSha256HashNil(b bool)`

 SetSha256HashNil sets the value for Sha256Hash to be an explicit nil

### UnsetSha256Hash
`func (o *Attachment) UnsetSha256Hash()`

UnsetSha256Hash ensures that no value is present for Sha256Hash, not even an explicit nil
### GetUploadedBy

`func (o *Attachment) GetUploadedBy() string`

GetUploadedBy returns the UploadedBy field if non-nil, zero value otherwise.

### GetUploadedByOk

`func (o *Attachment) GetUploadedByOk() (*string, bool)`

GetUploadedByOk returns a tuple with the UploadedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadedBy

`func (o *Attachment) SetUploadedBy(v string)`

SetUploadedBy sets UploadedBy field to given value.

### HasUploadedBy

`func (o *Attachment) HasUploadedBy() bool`

HasUploadedBy returns a boolean if a field has been set.

### SetUploadedByNil

`func (o *Attachment) SetUploadedByNil(b bool)`

 SetUploadedByNil sets the value for UploadedBy to be an explicit nil

### UnsetUploadedBy
`func (o *Attachment) UnsetUploadedBy()`

UnsetUploadedBy ensures that no value is present for UploadedBy, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


