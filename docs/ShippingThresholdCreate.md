# ShippingThresholdCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsActive** | Pointer to **bool** |  | [optional] 
**MaxSellable** | Pointer to **NullableInt64** | Optional ceiling for the deliverable quantity. | [optional] 
**Name** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**ProductId** | Pointer to **NullableString** | None &#x3D; applies to all products. References the product entity. | [optional] 
**ReserveStock** | Pointer to **int64** | Buffer of stock that must not be sold. | [optional] 
**WarehouseId** | Pointer to **NullableString** | None &#x3D; applies to all warehouses. References the warehouse entity. | [optional] 

## Methods

### NewShippingThresholdCreate

`func NewShippingThresholdCreate(name string, ) *ShippingThresholdCreate`

NewShippingThresholdCreate instantiates a new ShippingThresholdCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingThresholdCreateWithDefaults

`func NewShippingThresholdCreateWithDefaults() *ShippingThresholdCreate`

NewShippingThresholdCreateWithDefaults instantiates a new ShippingThresholdCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsActive

`func (o *ShippingThresholdCreate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ShippingThresholdCreate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ShippingThresholdCreate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ShippingThresholdCreate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetMaxSellable

`func (o *ShippingThresholdCreate) GetMaxSellable() int64`

GetMaxSellable returns the MaxSellable field if non-nil, zero value otherwise.

### GetMaxSellableOk

`func (o *ShippingThresholdCreate) GetMaxSellableOk() (*int64, bool)`

GetMaxSellableOk returns a tuple with the MaxSellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSellable

`func (o *ShippingThresholdCreate) SetMaxSellable(v int64)`

SetMaxSellable sets MaxSellable field to given value.

### HasMaxSellable

`func (o *ShippingThresholdCreate) HasMaxSellable() bool`

HasMaxSellable returns a boolean if a field has been set.

### SetMaxSellableNil

`func (o *ShippingThresholdCreate) SetMaxSellableNil(b bool)`

 SetMaxSellableNil sets the value for MaxSellable to be an explicit nil

### UnsetMaxSellable
`func (o *ShippingThresholdCreate) UnsetMaxSellable()`

UnsetMaxSellable ensures that no value is present for MaxSellable, not even an explicit nil
### GetName

`func (o *ShippingThresholdCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShippingThresholdCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShippingThresholdCreate) SetName(v string)`

SetName sets Name field to given value.


### GetNotes

`func (o *ShippingThresholdCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ShippingThresholdCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ShippingThresholdCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ShippingThresholdCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ShippingThresholdCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ShippingThresholdCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetProductId

`func (o *ShippingThresholdCreate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ShippingThresholdCreate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ShippingThresholdCreate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *ShippingThresholdCreate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *ShippingThresholdCreate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *ShippingThresholdCreate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetReserveStock

`func (o *ShippingThresholdCreate) GetReserveStock() int64`

GetReserveStock returns the ReserveStock field if non-nil, zero value otherwise.

### GetReserveStockOk

`func (o *ShippingThresholdCreate) GetReserveStockOk() (*int64, bool)`

GetReserveStockOk returns a tuple with the ReserveStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReserveStock

`func (o *ShippingThresholdCreate) SetReserveStock(v int64)`

SetReserveStock sets ReserveStock field to given value.

### HasReserveStock

`func (o *ShippingThresholdCreate) HasReserveStock() bool`

HasReserveStock returns a boolean if a field has been set.

### GetWarehouseId

`func (o *ShippingThresholdCreate) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *ShippingThresholdCreate) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *ShippingThresholdCreate) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.

### HasWarehouseId

`func (o *ShippingThresholdCreate) HasWarehouseId() bool`

HasWarehouseId returns a boolean if a field has been set.

### SetWarehouseIdNil

`func (o *ShippingThresholdCreate) SetWarehouseIdNil(b bool)`

 SetWarehouseIdNil sets the value for WarehouseId to be an explicit nil

### UnsetWarehouseId
`func (o *ShippingThresholdCreate) UnsetWarehouseId()`

UnsetWarehouseId ensures that no value is present for WarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


