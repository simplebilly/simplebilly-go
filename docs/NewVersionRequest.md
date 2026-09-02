# NewVersionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FileName** | **string** | Storage key of the already-uploaded bytes. | 
**FileSize** | Pointer to **NullableInt64** |  | [optional] 
**MimeType** | Pointer to **NullableString** |  | [optional] 
**OriginalName** | Pointer to **NullableString** |  | [optional] 
**Sha256Hash** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewNewVersionRequest

`func NewNewVersionRequest(fileName string, ) *NewVersionRequest`

NewNewVersionRequest instantiates a new NewVersionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNewVersionRequestWithDefaults

`func NewNewVersionRequestWithDefaults() *NewVersionRequest`

NewNewVersionRequestWithDefaults instantiates a new NewVersionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFileName

`func (o *NewVersionRequest) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *NewVersionRequest) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *NewVersionRequest) SetFileName(v string)`

SetFileName sets FileName field to given value.


### GetFileSize

`func (o *NewVersionRequest) GetFileSize() int64`

GetFileSize returns the FileSize field if non-nil, zero value otherwise.

### GetFileSizeOk

`func (o *NewVersionRequest) GetFileSizeOk() (*int64, bool)`

GetFileSizeOk returns a tuple with the FileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSize

`func (o *NewVersionRequest) SetFileSize(v int64)`

SetFileSize sets FileSize field to given value.

### HasFileSize

`func (o *NewVersionRequest) HasFileSize() bool`

HasFileSize returns a boolean if a field has been set.

### SetFileSizeNil

`func (o *NewVersionRequest) SetFileSizeNil(b bool)`

 SetFileSizeNil sets the value for FileSize to be an explicit nil

### UnsetFileSize
`func (o *NewVersionRequest) UnsetFileSize()`

UnsetFileSize ensures that no value is present for FileSize, not even an explicit nil
### GetMimeType

`func (o *NewVersionRequest) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *NewVersionRequest) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *NewVersionRequest) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *NewVersionRequest) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *NewVersionRequest) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *NewVersionRequest) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetOriginalName

`func (o *NewVersionRequest) GetOriginalName() string`

GetOriginalName returns the OriginalName field if non-nil, zero value otherwise.

### GetOriginalNameOk

`func (o *NewVersionRequest) GetOriginalNameOk() (*string, bool)`

GetOriginalNameOk returns a tuple with the OriginalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalName

`func (o *NewVersionRequest) SetOriginalName(v string)`

SetOriginalName sets OriginalName field to given value.

### HasOriginalName

`func (o *NewVersionRequest) HasOriginalName() bool`

HasOriginalName returns a boolean if a field has been set.

### SetOriginalNameNil

`func (o *NewVersionRequest) SetOriginalNameNil(b bool)`

 SetOriginalNameNil sets the value for OriginalName to be an explicit nil

### UnsetOriginalName
`func (o *NewVersionRequest) UnsetOriginalName()`

UnsetOriginalName ensures that no value is present for OriginalName, not even an explicit nil
### GetSha256Hash

`func (o *NewVersionRequest) GetSha256Hash() string`

GetSha256Hash returns the Sha256Hash field if non-nil, zero value otherwise.

### GetSha256HashOk

`func (o *NewVersionRequest) GetSha256HashOk() (*string, bool)`

GetSha256HashOk returns a tuple with the Sha256Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256Hash

`func (o *NewVersionRequest) SetSha256Hash(v string)`

SetSha256Hash sets Sha256Hash field to given value.

### HasSha256Hash

`func (o *NewVersionRequest) HasSha256Hash() bool`

HasSha256Hash returns a boolean if a field has been set.

### SetSha256HashNil

`func (o *NewVersionRequest) SetSha256HashNil(b bool)`

 SetSha256HashNil sets the value for Sha256Hash to be an explicit nil

### UnsetSha256Hash
`func (o *NewVersionRequest) UnsetSha256Hash()`

UnsetSha256Hash ensures that no value is present for Sha256Hash, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


