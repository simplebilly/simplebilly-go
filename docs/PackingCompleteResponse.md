# PackingCompleteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**NewState** | **string** |  | 
**OrderNumber** | **string** |  | 
**Success** | **bool** |  | 

## Methods

### NewPackingCompleteResponse

`func NewPackingCompleteResponse(message string, newState string, orderNumber string, success bool, ) *PackingCompleteResponse`

NewPackingCompleteResponse instantiates a new PackingCompleteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPackingCompleteResponseWithDefaults

`func NewPackingCompleteResponseWithDefaults() *PackingCompleteResponse`

NewPackingCompleteResponseWithDefaults instantiates a new PackingCompleteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *PackingCompleteResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PackingCompleteResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PackingCompleteResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetNewState

`func (o *PackingCompleteResponse) GetNewState() string`

GetNewState returns the NewState field if non-nil, zero value otherwise.

### GetNewStateOk

`func (o *PackingCompleteResponse) GetNewStateOk() (*string, bool)`

GetNewStateOk returns a tuple with the NewState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewState

`func (o *PackingCompleteResponse) SetNewState(v string)`

SetNewState sets NewState field to given value.


### GetOrderNumber

`func (o *PackingCompleteResponse) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *PackingCompleteResponse) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *PackingCompleteResponse) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetSuccess

`func (o *PackingCompleteResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PackingCompleteResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PackingCompleteResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


