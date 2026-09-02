# ApiResponseVecTeam

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ApiResponseTeamData**](ApiResponseTeamData.md) |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewApiResponseVecTeam

`func NewApiResponseVecTeam(success bool, ) *ApiResponseVecTeam`

NewApiResponseVecTeam instantiates a new ApiResponseVecTeam object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseVecTeamWithDefaults

`func NewApiResponseVecTeamWithDefaults() *ApiResponseVecTeam`

NewApiResponseVecTeamWithDefaults instantiates a new ApiResponseVecTeam object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ApiResponseVecTeam) GetData() []ApiResponseTeamData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ApiResponseVecTeam) GetDataOk() (*[]ApiResponseTeamData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ApiResponseVecTeam) SetData(v []ApiResponseTeamData)`

SetData sets Data field to given value.

### HasData

`func (o *ApiResponseVecTeam) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ApiResponseVecTeam) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiResponseVecTeam) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiResponseVecTeam) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ApiResponseVecTeam) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ApiResponseVecTeam) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ApiResponseVecTeam) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMessage

`func (o *ApiResponseVecTeam) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ApiResponseVecTeam) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ApiResponseVecTeam) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ApiResponseVecTeam) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *ApiResponseVecTeam) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *ApiResponseVecTeam) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetSuccess

`func (o *ApiResponseVecTeam) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ApiResponseVecTeam) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ApiResponseVecTeam) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


