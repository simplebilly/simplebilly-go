# ApiResponseString

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **string** |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewApiResponseString

`func NewApiResponseString(success bool, ) *ApiResponseString`

NewApiResponseString instantiates a new ApiResponseString object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseStringWithDefaults

`func NewApiResponseStringWithDefaults() *ApiResponseString`

NewApiResponseStringWithDefaults instantiates a new ApiResponseString object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ApiResponseString) GetData() string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ApiResponseString) GetDataOk() (*string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ApiResponseString) SetData(v string)`

SetData sets Data field to given value.

### HasData

`func (o *ApiResponseString) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ApiResponseString) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiResponseString) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiResponseString) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ApiResponseString) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ApiResponseString) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ApiResponseString) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMessage

`func (o *ApiResponseString) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ApiResponseString) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ApiResponseString) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ApiResponseString) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *ApiResponseString) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *ApiResponseString) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetSuccess

`func (o *ApiResponseString) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ApiResponseString) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ApiResponseString) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


