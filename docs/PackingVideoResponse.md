# PackingVideoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**RecordingUrl** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewPackingVideoResponse

`func NewPackingVideoResponse(message string, success bool, ) *PackingVideoResponse`

NewPackingVideoResponse instantiates a new PackingVideoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPackingVideoResponseWithDefaults

`func NewPackingVideoResponseWithDefaults() *PackingVideoResponse`

NewPackingVideoResponseWithDefaults instantiates a new PackingVideoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *PackingVideoResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PackingVideoResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PackingVideoResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetRecordingUrl

`func (o *PackingVideoResponse) GetRecordingUrl() string`

GetRecordingUrl returns the RecordingUrl field if non-nil, zero value otherwise.

### GetRecordingUrlOk

`func (o *PackingVideoResponse) GetRecordingUrlOk() (*string, bool)`

GetRecordingUrlOk returns a tuple with the RecordingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordingUrl

`func (o *PackingVideoResponse) SetRecordingUrl(v string)`

SetRecordingUrl sets RecordingUrl field to given value.

### HasRecordingUrl

`func (o *PackingVideoResponse) HasRecordingUrl() bool`

HasRecordingUrl returns a boolean if a field has been set.

### SetRecordingUrlNil

`func (o *PackingVideoResponse) SetRecordingUrlNil(b bool)`

 SetRecordingUrlNil sets the value for RecordingUrl to be an explicit nil

### UnsetRecordingUrl
`func (o *PackingVideoResponse) UnsetRecordingUrl()`

UnsetRecordingUrl ensures that no value is present for RecordingUrl, not even an explicit nil
### GetSuccess

`func (o *PackingVideoResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PackingVideoResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PackingVideoResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


