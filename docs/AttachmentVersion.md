# AttachmentVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttachmentId** | **string** | Parent attachment whose history this row records. | 
**FileName** | **string** | Storage key of this version&#39;s bytes. | 
**FileSize** | Pointer to **NullableInt64** |  | [optional] 
**MimeType** | Pointer to **NullableString** |  | [optional] 
**OriginalName** | Pointer to **NullableString** |  | [optional] 
**Sha256Hash** | Pointer to **NullableString** |  | [optional] 
**UploadedBy** | Pointer to **NullableString** |  | [optional] 
**VersionNumber** | **int32** | 1-based; ascending per attachment in upload order. | 

## Methods

### NewAttachmentVersion

`func NewAttachmentVersion(attachmentId string, fileName string, versionNumber int32, ) *AttachmentVersion`

NewAttachmentVersion instantiates a new AttachmentVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttachmentVersionWithDefaults

`func NewAttachmentVersionWithDefaults() *AttachmentVersion`

NewAttachmentVersionWithDefaults instantiates a new AttachmentVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachmentId

`func (o *AttachmentVersion) GetAttachmentId() string`

GetAttachmentId returns the AttachmentId field if non-nil, zero value otherwise.

### GetAttachmentIdOk

`func (o *AttachmentVersion) GetAttachmentIdOk() (*string, bool)`

GetAttachmentIdOk returns a tuple with the AttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentId

`func (o *AttachmentVersion) SetAttachmentId(v string)`

SetAttachmentId sets AttachmentId field to given value.


### GetFileName

`func (o *AttachmentVersion) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *AttachmentVersion) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *AttachmentVersion) SetFileName(v string)`

SetFileName sets FileName field to given value.


### GetFileSize

`func (o *AttachmentVersion) GetFileSize() int64`

GetFileSize returns the FileSize field if non-nil, zero value otherwise.

### GetFileSizeOk

`func (o *AttachmentVersion) GetFileSizeOk() (*int64, bool)`

GetFileSizeOk returns a tuple with the FileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSize

`func (o *AttachmentVersion) SetFileSize(v int64)`

SetFileSize sets FileSize field to given value.

### HasFileSize

`func (o *AttachmentVersion) HasFileSize() bool`

HasFileSize returns a boolean if a field has been set.

### SetFileSizeNil

`func (o *AttachmentVersion) SetFileSizeNil(b bool)`

 SetFileSizeNil sets the value for FileSize to be an explicit nil

### UnsetFileSize
`func (o *AttachmentVersion) UnsetFileSize()`

UnsetFileSize ensures that no value is present for FileSize, not even an explicit nil
### GetMimeType

`func (o *AttachmentVersion) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *AttachmentVersion) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *AttachmentVersion) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *AttachmentVersion) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *AttachmentVersion) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *AttachmentVersion) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetOriginalName

`func (o *AttachmentVersion) GetOriginalName() string`

GetOriginalName returns the OriginalName field if non-nil, zero value otherwise.

### GetOriginalNameOk

`func (o *AttachmentVersion) GetOriginalNameOk() (*string, bool)`

GetOriginalNameOk returns a tuple with the OriginalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalName

`func (o *AttachmentVersion) SetOriginalName(v string)`

SetOriginalName sets OriginalName field to given value.

### HasOriginalName

`func (o *AttachmentVersion) HasOriginalName() bool`

HasOriginalName returns a boolean if a field has been set.

### SetOriginalNameNil

`func (o *AttachmentVersion) SetOriginalNameNil(b bool)`

 SetOriginalNameNil sets the value for OriginalName to be an explicit nil

### UnsetOriginalName
`func (o *AttachmentVersion) UnsetOriginalName()`

UnsetOriginalName ensures that no value is present for OriginalName, not even an explicit nil
### GetSha256Hash

`func (o *AttachmentVersion) GetSha256Hash() string`

GetSha256Hash returns the Sha256Hash field if non-nil, zero value otherwise.

### GetSha256HashOk

`func (o *AttachmentVersion) GetSha256HashOk() (*string, bool)`

GetSha256HashOk returns a tuple with the Sha256Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256Hash

`func (o *AttachmentVersion) SetSha256Hash(v string)`

SetSha256Hash sets Sha256Hash field to given value.

### HasSha256Hash

`func (o *AttachmentVersion) HasSha256Hash() bool`

HasSha256Hash returns a boolean if a field has been set.

### SetSha256HashNil

`func (o *AttachmentVersion) SetSha256HashNil(b bool)`

 SetSha256HashNil sets the value for Sha256Hash to be an explicit nil

### UnsetSha256Hash
`func (o *AttachmentVersion) UnsetSha256Hash()`

UnsetSha256Hash ensures that no value is present for Sha256Hash, not even an explicit nil
### GetUploadedBy

`func (o *AttachmentVersion) GetUploadedBy() string`

GetUploadedBy returns the UploadedBy field if non-nil, zero value otherwise.

### GetUploadedByOk

`func (o *AttachmentVersion) GetUploadedByOk() (*string, bool)`

GetUploadedByOk returns a tuple with the UploadedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadedBy

`func (o *AttachmentVersion) SetUploadedBy(v string)`

SetUploadedBy sets UploadedBy field to given value.

### HasUploadedBy

`func (o *AttachmentVersion) HasUploadedBy() bool`

HasUploadedBy returns a boolean if a field has been set.

### SetUploadedByNil

`func (o *AttachmentVersion) SetUploadedByNil(b bool)`

 SetUploadedByNil sets the value for UploadedBy to be an explicit nil

### UnsetUploadedBy
`func (o *AttachmentVersion) UnsetUploadedBy()`

UnsetUploadedBy ensures that no value is present for UploadedBy, not even an explicit nil
### GetVersionNumber

`func (o *AttachmentVersion) GetVersionNumber() int32`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *AttachmentVersion) GetVersionNumberOk() (*int32, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *AttachmentVersion) SetVersionNumber(v int32)`

SetVersionNumber sets VersionNumber field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


