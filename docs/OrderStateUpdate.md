# OrderStateUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SendStateToShop** | Pointer to **bool** |  | [optional] 
**State** | **string** |  | 

## Methods

### NewOrderStateUpdate

`func NewOrderStateUpdate(state string, ) *OrderStateUpdate`

NewOrderStateUpdate instantiates a new OrderStateUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderStateUpdateWithDefaults

`func NewOrderStateUpdateWithDefaults() *OrderStateUpdate`

NewOrderStateUpdateWithDefaults instantiates a new OrderStateUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSendStateToShop

`func (o *OrderStateUpdate) GetSendStateToShop() bool`

GetSendStateToShop returns the SendStateToShop field if non-nil, zero value otherwise.

### GetSendStateToShopOk

`func (o *OrderStateUpdate) GetSendStateToShopOk() (*bool, bool)`

GetSendStateToShopOk returns a tuple with the SendStateToShop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendStateToShop

`func (o *OrderStateUpdate) SetSendStateToShop(v bool)`

SetSendStateToShop sets SendStateToShop field to given value.

### HasSendStateToShop

`func (o *OrderStateUpdate) HasSendStateToShop() bool`

HasSendStateToShop returns a boolean if a field has been set.

### GetState

`func (o *OrderStateUpdate) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *OrderStateUpdate) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *OrderStateUpdate) SetState(v string)`

SetState sets State field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


