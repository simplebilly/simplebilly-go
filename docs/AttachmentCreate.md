# AttachmentCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactId** | Pointer to **NullableString** | Contact this attachment belongs to (per-contact DMS). References the contact entity. | [optional] 
**FileName** | **string** |  | 
**FileSize** | Pointer to **NullableInt64** |  | [optional] 
**MimeType** | Pointer to **NullableString** |  | [optional] 
**OriginalName** | **string** |  | 
**PdfaPath** | Pointer to **NullableString** |  | [optional] 
**Sha256Hash** | Pointer to **NullableString** |  | [optional] 
**UploadedBy** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAttachmentCreate

`func NewAttachmentCreate(fileName string, originalName string, ) *AttachmentCreate`

NewAttachmentCreate instantiates a new AttachmentCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttachmentCreateWithDefaults

`func NewAttachmentCreateWithDefaults() *AttachmentCreate`

NewAttachmentCreateWithDefaults instantiates a new AttachmentCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactId

`func (o *AttachmentCreate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *AttachmentCreate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *AttachmentCreate) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *AttachmentCreate) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *AttachmentCreate) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *AttachmentCreate) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetFileName

`func (o *AttachmentCreate) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *AttachmentCreate) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *AttachmentCreate) SetFileName(v string)`

SetFileName sets FileName field to given value.


### GetFileSize

`func (o *AttachmentCreate) GetFileSize() int64`

GetFileSize returns the FileSize field if non-nil, zero value otherwise.

### GetFileSizeOk

`func (o *AttachmentCreate) GetFileSizeOk() (*int64, bool)`

GetFileSizeOk returns a tuple with the FileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSize

`func (o *AttachmentCreate) SetFileSize(v int64)`

SetFileSize sets FileSize field to given value.

### HasFileSize

`func (o *AttachmentCreate) HasFileSize() bool`

HasFileSize returns a boolean if a field has been set.

### SetFileSizeNil

`func (o *AttachmentCreate) SetFileSizeNil(b bool)`

 SetFileSizeNil sets the value for FileSize to be an explicit nil

### UnsetFileSize
`func (o *AttachmentCreate) UnsetFileSize()`

UnsetFileSize ensures that no value is present for FileSize, not even an explicit nil
### GetMimeType

`func (o *AttachmentCreate) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *AttachmentCreate) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *AttachmentCreate) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *AttachmentCreate) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *AttachmentCreate) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *AttachmentCreate) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetOriginalName

`func (o *AttachmentCreate) GetOriginalName() string`

GetOriginalName returns the OriginalName field if non-nil, zero value otherwise.

### GetOriginalNameOk

`func (o *AttachmentCreate) GetOriginalNameOk() (*string, bool)`

GetOriginalNameOk returns a tuple with the OriginalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalName

`func (o *AttachmentCreate) SetOriginalName(v string)`

SetOriginalName sets OriginalName field to given value.


### GetPdfaPath

`func (o *AttachmentCreate) GetPdfaPath() string`

GetPdfaPath returns the PdfaPath field if non-nil, zero value otherwise.

### GetPdfaPathOk

`func (o *AttachmentCreate) GetPdfaPathOk() (*string, bool)`

GetPdfaPathOk returns a tuple with the PdfaPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfaPath

`func (o *AttachmentCreate) SetPdfaPath(v string)`

SetPdfaPath sets PdfaPath field to given value.

### HasPdfaPath

`func (o *AttachmentCreate) HasPdfaPath() bool`

HasPdfaPath returns a boolean if a field has been set.

### SetPdfaPathNil

`func (o *AttachmentCreate) SetPdfaPathNil(b bool)`

 SetPdfaPathNil sets the value for PdfaPath to be an explicit nil

### UnsetPdfaPath
`func (o *AttachmentCreate) UnsetPdfaPath()`

UnsetPdfaPath ensures that no value is present for PdfaPath, not even an explicit nil
### GetSha256Hash

`func (o *AttachmentCreate) GetSha256Hash() string`

GetSha256Hash returns the Sha256Hash field if non-nil, zero value otherwise.

### GetSha256HashOk

`func (o *AttachmentCreate) GetSha256HashOk() (*string, bool)`

GetSha256HashOk returns a tuple with the Sha256Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256Hash

`func (o *AttachmentCreate) SetSha256Hash(v string)`

SetSha256Hash sets Sha256Hash field to given value.

### HasSha256Hash

`func (o *AttachmentCreate) HasSha256Hash() bool`

HasSha256Hash returns a boolean if a field has been set.

### SetSha256HashNil

`func (o *AttachmentCreate) SetSha256HashNil(b bool)`

 SetSha256HashNil sets the value for Sha256Hash to be an explicit nil

### UnsetSha256Hash
`func (o *AttachmentCreate) UnsetSha256Hash()`

UnsetSha256Hash ensures that no value is present for Sha256Hash, not even an explicit nil
### GetUploadedBy

`func (o *AttachmentCreate) GetUploadedBy() string`

GetUploadedBy returns the UploadedBy field if non-nil, zero value otherwise.

### GetUploadedByOk

`func (o *AttachmentCreate) GetUploadedByOk() (*string, bool)`

GetUploadedByOk returns a tuple with the UploadedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadedBy

`func (o *AttachmentCreate) SetUploadedBy(v string)`

SetUploadedBy sets UploadedBy field to given value.

### HasUploadedBy

`func (o *AttachmentCreate) HasUploadedBy() bool`

HasUploadedBy returns a boolean if a field has been set.

### SetUploadedByNil

`func (o *AttachmentCreate) SetUploadedByNil(b bool)`

 SetUploadedByNil sets the value for UploadedBy to be an explicit nil

### UnsetUploadedBy
`func (o *AttachmentCreate) UnsetUploadedBy()`

UnsetUploadedBy ensures that no value is present for UploadedBy, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


