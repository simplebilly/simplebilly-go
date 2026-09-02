# PrintLabelResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LabelUrl** | Pointer to **NullableString** |  | [optional] 
**Message** | **string** |  | 
**Sscc** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 
**TrackingNumber** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPrintLabelResponse

`func NewPrintLabelResponse(message string, success bool, ) *PrintLabelResponse`

NewPrintLabelResponse instantiates a new PrintLabelResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPrintLabelResponseWithDefaults

`func NewPrintLabelResponseWithDefaults() *PrintLabelResponse`

NewPrintLabelResponseWithDefaults instantiates a new PrintLabelResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLabelUrl

`func (o *PrintLabelResponse) GetLabelUrl() string`

GetLabelUrl returns the LabelUrl field if non-nil, zero value otherwise.

### GetLabelUrlOk

`func (o *PrintLabelResponse) GetLabelUrlOk() (*string, bool)`

GetLabelUrlOk returns a tuple with the LabelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelUrl

`func (o *PrintLabelResponse) SetLabelUrl(v string)`

SetLabelUrl sets LabelUrl field to given value.

### HasLabelUrl

`func (o *PrintLabelResponse) HasLabelUrl() bool`

HasLabelUrl returns a boolean if a field has been set.

### SetLabelUrlNil

`func (o *PrintLabelResponse) SetLabelUrlNil(b bool)`

 SetLabelUrlNil sets the value for LabelUrl to be an explicit nil

### UnsetLabelUrl
`func (o *PrintLabelResponse) UnsetLabelUrl()`

UnsetLabelUrl ensures that no value is present for LabelUrl, not even an explicit nil
### GetMessage

`func (o *PrintLabelResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PrintLabelResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PrintLabelResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetSscc

`func (o *PrintLabelResponse) GetSscc() string`

GetSscc returns the Sscc field if non-nil, zero value otherwise.

### GetSsccOk

`func (o *PrintLabelResponse) GetSsccOk() (*string, bool)`

GetSsccOk returns a tuple with the Sscc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSscc

`func (o *PrintLabelResponse) SetSscc(v string)`

SetSscc sets Sscc field to given value.

### HasSscc

`func (o *PrintLabelResponse) HasSscc() bool`

HasSscc returns a boolean if a field has been set.

### SetSsccNil

`func (o *PrintLabelResponse) SetSsccNil(b bool)`

 SetSsccNil sets the value for Sscc to be an explicit nil

### UnsetSscc
`func (o *PrintLabelResponse) UnsetSscc()`

UnsetSscc ensures that no value is present for Sscc, not even an explicit nil
### GetSuccess

`func (o *PrintLabelResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PrintLabelResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PrintLabelResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetTrackingNumber

`func (o *PrintLabelResponse) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *PrintLabelResponse) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *PrintLabelResponse) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *PrintLabelResponse) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### SetTrackingNumberNil

`func (o *PrintLabelResponse) SetTrackingNumberNil(b bool)`

 SetTrackingNumberNil sets the value for TrackingNumber to be an explicit nil

### UnsetTrackingNumber
`func (o *PrintLabelResponse) UnsetTrackingNumber()`

UnsetTrackingNumber ensures that no value is present for TrackingNumber, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


