# ShippingThresholdUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**MaxSellable** | Pointer to **NullableInt64** | Optional ceiling for the deliverable quantity. | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**ProductId** | Pointer to **NullableString** | None &#x3D; applies to all products. References the product entity. | [optional] 
**ReserveStock** | Pointer to **NullableInt64** | Buffer of stock that must not be sold. | [optional] 
**WarehouseId** | Pointer to **NullableString** | None &#x3D; applies to all warehouses. References the warehouse entity. | [optional] 

## Methods

### NewShippingThresholdUpdate

`func NewShippingThresholdUpdate() *ShippingThresholdUpdate`

NewShippingThresholdUpdate instantiates a new ShippingThresholdUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingThresholdUpdateWithDefaults

`func NewShippingThresholdUpdateWithDefaults() *ShippingThresholdUpdate`

NewShippingThresholdUpdateWithDefaults instantiates a new ShippingThresholdUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsActive

`func (o *ShippingThresholdUpdate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ShippingThresholdUpdate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ShippingThresholdUpdate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ShippingThresholdUpdate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *ShippingThresholdUpdate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *ShippingThresholdUpdate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetMaxSellable

`func (o *ShippingThresholdUpdate) GetMaxSellable() int64`

GetMaxSellable returns the MaxSellable field if non-nil, zero value otherwise.

### GetMaxSellableOk

`func (o *ShippingThresholdUpdate) GetMaxSellableOk() (*int64, bool)`

GetMaxSellableOk returns a tuple with the MaxSellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSellable

`func (o *ShippingThresholdUpdate) SetMaxSellable(v int64)`

SetMaxSellable sets MaxSellable field to given value.

### HasMaxSellable

`func (o *ShippingThresholdUpdate) HasMaxSellable() bool`

HasMaxSellable returns a boolean if a field has been set.

### SetMaxSellableNil

`func (o *ShippingThresholdUpdate) SetMaxSellableNil(b bool)`

 SetMaxSellableNil sets the value for MaxSellable to be an explicit nil

### UnsetMaxSellable
`func (o *ShippingThresholdUpdate) UnsetMaxSellable()`

UnsetMaxSellable ensures that no value is present for MaxSellable, not even an explicit nil
### GetName

`func (o *ShippingThresholdUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShippingThresholdUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShippingThresholdUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ShippingThresholdUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ShippingThresholdUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ShippingThresholdUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetNotes

`func (o *ShippingThresholdUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ShippingThresholdUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ShippingThresholdUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ShippingThresholdUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ShippingThresholdUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ShippingThresholdUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetProductId

`func (o *ShippingThresholdUpdate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ShippingThresholdUpdate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ShippingThresholdUpdate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *ShippingThresholdUpdate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *ShippingThresholdUpdate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *ShippingThresholdUpdate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetReserveStock

`func (o *ShippingThresholdUpdate) GetReserveStock() int64`

GetReserveStock returns the ReserveStock field if non-nil, zero value otherwise.

### GetReserveStockOk

`func (o *ShippingThresholdUpdate) GetReserveStockOk() (*int64, bool)`

GetReserveStockOk returns a tuple with the ReserveStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReserveStock

`func (o *ShippingThresholdUpdate) SetReserveStock(v int64)`

SetReserveStock sets ReserveStock field to given value.

### HasReserveStock

`func (o *ShippingThresholdUpdate) HasReserveStock() bool`

HasReserveStock returns a boolean if a field has been set.

### SetReserveStockNil

`func (o *ShippingThresholdUpdate) SetReserveStockNil(b bool)`

 SetReserveStockNil sets the value for ReserveStock to be an explicit nil

### UnsetReserveStock
`func (o *ShippingThresholdUpdate) UnsetReserveStock()`

UnsetReserveStock ensures that no value is present for ReserveStock, not even an explicit nil
### GetWarehouseId

`func (o *ShippingThresholdUpdate) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *ShippingThresholdUpdate) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *ShippingThresholdUpdate) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.

### HasWarehouseId

`func (o *ShippingThresholdUpdate) HasWarehouseId() bool`

HasWarehouseId returns a boolean if a field has been set.

### SetWarehouseIdNil

`func (o *ShippingThresholdUpdate) SetWarehouseIdNil(b bool)`

 SetWarehouseIdNil sets the value for WarehouseId to be an explicit nil

### UnsetWarehouseId
`func (o *ShippingThresholdUpdate) UnsetWarehouseId()`

UnsetWarehouseId ensures that no value is present for WarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


