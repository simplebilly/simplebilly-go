# DeliverableResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvailableStock** | **int64** |  | 
**DeliverableQuantity** | **int64** |  | 
**MaxSellable** | Pointer to **NullableInt64** |  | [optional] 
**ProductId** | **string** |  | 
**ReservedStock** | **int64** |  | 
**WarehouseId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDeliverableResponse

`func NewDeliverableResponse(availableStock int64, deliverableQuantity int64, productId string, reservedStock int64, ) *DeliverableResponse`

NewDeliverableResponse instantiates a new DeliverableResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverableResponseWithDefaults

`func NewDeliverableResponseWithDefaults() *DeliverableResponse`

NewDeliverableResponseWithDefaults instantiates a new DeliverableResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailableStock

`func (o *DeliverableResponse) GetAvailableStock() int64`

GetAvailableStock returns the AvailableStock field if non-nil, zero value otherwise.

### GetAvailableStockOk

`func (o *DeliverableResponse) GetAvailableStockOk() (*int64, bool)`

GetAvailableStockOk returns a tuple with the AvailableStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableStock

`func (o *DeliverableResponse) SetAvailableStock(v int64)`

SetAvailableStock sets AvailableStock field to given value.


### GetDeliverableQuantity

`func (o *DeliverableResponse) GetDeliverableQuantity() int64`

GetDeliverableQuantity returns the DeliverableQuantity field if non-nil, zero value otherwise.

### GetDeliverableQuantityOk

`func (o *DeliverableResponse) GetDeliverableQuantityOk() (*int64, bool)`

GetDeliverableQuantityOk returns a tuple with the DeliverableQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverableQuantity

`func (o *DeliverableResponse) SetDeliverableQuantity(v int64)`

SetDeliverableQuantity sets DeliverableQuantity field to given value.


### GetMaxSellable

`func (o *DeliverableResponse) GetMaxSellable() int64`

GetMaxSellable returns the MaxSellable field if non-nil, zero value otherwise.

### GetMaxSellableOk

`func (o *DeliverableResponse) GetMaxSellableOk() (*int64, bool)`

GetMaxSellableOk returns a tuple with the MaxSellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSellable

`func (o *DeliverableResponse) SetMaxSellable(v int64)`

SetMaxSellable sets MaxSellable field to given value.

### HasMaxSellable

`func (o *DeliverableResponse) HasMaxSellable() bool`

HasMaxSellable returns a boolean if a field has been set.

### SetMaxSellableNil

`func (o *DeliverableResponse) SetMaxSellableNil(b bool)`

 SetMaxSellableNil sets the value for MaxSellable to be an explicit nil

### UnsetMaxSellable
`func (o *DeliverableResponse) UnsetMaxSellable()`

UnsetMaxSellable ensures that no value is present for MaxSellable, not even an explicit nil
### GetProductId

`func (o *DeliverableResponse) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *DeliverableResponse) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *DeliverableResponse) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetReservedStock

`func (o *DeliverableResponse) GetReservedStock() int64`

GetReservedStock returns the ReservedStock field if non-nil, zero value otherwise.

### GetReservedStockOk

`func (o *DeliverableResponse) GetReservedStockOk() (*int64, bool)`

GetReservedStockOk returns a tuple with the ReservedStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedStock

`func (o *DeliverableResponse) SetReservedStock(v int64)`

SetReservedStock sets ReservedStock field to given value.


### GetWarehouseId

`func (o *DeliverableResponse) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *DeliverableResponse) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *DeliverableResponse) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.

### HasWarehouseId

`func (o *DeliverableResponse) HasWarehouseId() bool`

HasWarehouseId returns a boolean if a field has been set.

### SetWarehouseIdNil

`func (o *DeliverableResponse) SetWarehouseIdNil(b bool)`

 SetWarehouseIdNil sets the value for WarehouseId to be an explicit nil

### UnsetWarehouseId
`func (o *DeliverableResponse) UnsetWarehouseId()`

UnsetWarehouseId ensures that no value is present for WarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


