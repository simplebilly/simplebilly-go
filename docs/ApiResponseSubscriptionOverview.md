# ApiResponseSubscriptionOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**ApiResponseSubscriptionOverviewData**](ApiResponseSubscriptionOverviewData.md) |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewApiResponseSubscriptionOverview

`func NewApiResponseSubscriptionOverview(success bool, ) *ApiResponseSubscriptionOverview`

NewApiResponseSubscriptionOverview instantiates a new ApiResponseSubscriptionOverview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseSubscriptionOverviewWithDefaults

`func NewApiResponseSubscriptionOverviewWithDefaults() *ApiResponseSubscriptionOverview`

NewApiResponseSubscriptionOverviewWithDefaults instantiates a new ApiResponseSubscriptionOverview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ApiResponseSubscriptionOverview) GetData() ApiResponseSubscriptionOverviewData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ApiResponseSubscriptionOverview) GetDataOk() (*ApiResponseSubscriptionOverviewData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ApiResponseSubscriptionOverview) SetData(v ApiResponseSubscriptionOverviewData)`

SetData sets Data field to given value.

### HasData

`func (o *ApiResponseSubscriptionOverview) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ApiResponseSubscriptionOverview) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiResponseSubscriptionOverview) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiResponseSubscriptionOverview) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ApiResponseSubscriptionOverview) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ApiResponseSubscriptionOverview) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ApiResponseSubscriptionOverview) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMessage

`func (o *ApiResponseSubscriptionOverview) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ApiResponseSubscriptionOverview) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ApiResponseSubscriptionOverview) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ApiResponseSubscriptionOverview) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *ApiResponseSubscriptionOverview) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *ApiResponseSubscriptionOverview) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetSuccess

`func (o *ApiResponseSubscriptionOverview) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ApiResponseSubscriptionOverview) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ApiResponseSubscriptionOverview) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


