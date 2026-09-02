# ApiResponseVecUserTenantInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ApiResponseVecUserTenantInfoDataInner**](ApiResponseVecUserTenantInfoDataInner.md) |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewApiResponseVecUserTenantInfo

`func NewApiResponseVecUserTenantInfo(success bool, ) *ApiResponseVecUserTenantInfo`

NewApiResponseVecUserTenantInfo instantiates a new ApiResponseVecUserTenantInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseVecUserTenantInfoWithDefaults

`func NewApiResponseVecUserTenantInfoWithDefaults() *ApiResponseVecUserTenantInfo`

NewApiResponseVecUserTenantInfoWithDefaults instantiates a new ApiResponseVecUserTenantInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ApiResponseVecUserTenantInfo) GetData() []ApiResponseVecUserTenantInfoDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ApiResponseVecUserTenantInfo) GetDataOk() (*[]ApiResponseVecUserTenantInfoDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ApiResponseVecUserTenantInfo) SetData(v []ApiResponseVecUserTenantInfoDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *ApiResponseVecUserTenantInfo) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ApiResponseVecUserTenantInfo) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiResponseVecUserTenantInfo) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiResponseVecUserTenantInfo) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ApiResponseVecUserTenantInfo) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ApiResponseVecUserTenantInfo) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ApiResponseVecUserTenantInfo) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMessage

`func (o *ApiResponseVecUserTenantInfo) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ApiResponseVecUserTenantInfo) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ApiResponseVecUserTenantInfo) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ApiResponseVecUserTenantInfo) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *ApiResponseVecUserTenantInfo) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *ApiResponseVecUserTenantInfo) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetSuccess

`func (o *ApiResponseVecUserTenantInfo) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ApiResponseVecUserTenantInfo) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ApiResponseVecUserTenantInfo) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


