# StockMovement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delta** | **int64** | Signed movement: positive &#x3D; into stock, negative &#x3D; out of stock. | 
**MovementType** | [**MovementType**](MovementType.md) | One of the &#x60;MOVEMENT_*&#x60; constants. | 
**ProductId** | **string** | References the product entity. | 
**Quantity** | **int64** | Absolute quantity moved (always &gt;&#x3D; 0). | 
**Reason** | Pointer to **NullableString** |  | [optional] 
**ReferenceId** | Pointer to **NullableString** | Primary-key of the referencing entity. | [optional] 
**ReferenceType** | Pointer to [**NullableReferenceType**](ReferenceType.md) | Entity that caused the movement, e.g. &#x60;goods_receipt&#x60;, &#x60;stock_transfer&#x60;. | [optional] 
**WarehouseId** | **string** | References the warehouse entity. | 

## Methods

### NewStockMovement

`func NewStockMovement(delta int64, movementType MovementType, productId string, quantity int64, warehouseId string, ) *StockMovement`

NewStockMovement instantiates a new StockMovement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStockMovementWithDefaults

`func NewStockMovementWithDefaults() *StockMovement`

NewStockMovementWithDefaults instantiates a new StockMovement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDelta

`func (o *StockMovement) GetDelta() int64`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *StockMovement) GetDeltaOk() (*int64, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *StockMovement) SetDelta(v int64)`

SetDelta sets Delta field to given value.


### GetMovementType

`func (o *StockMovement) GetMovementType() MovementType`

GetMovementType returns the MovementType field if non-nil, zero value otherwise.

### GetMovementTypeOk

`func (o *StockMovement) GetMovementTypeOk() (*MovementType, bool)`

GetMovementTypeOk returns a tuple with the MovementType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMovementType

`func (o *StockMovement) SetMovementType(v MovementType)`

SetMovementType sets MovementType field to given value.


### GetProductId

`func (o *StockMovement) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *StockMovement) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *StockMovement) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetQuantity

`func (o *StockMovement) GetQuantity() int64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *StockMovement) GetQuantityOk() (*int64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *StockMovement) SetQuantity(v int64)`

SetQuantity sets Quantity field to given value.


### GetReason

`func (o *StockMovement) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *StockMovement) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *StockMovement) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *StockMovement) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *StockMovement) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *StockMovement) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetReferenceId

`func (o *StockMovement) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *StockMovement) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *StockMovement) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.

### HasReferenceId

`func (o *StockMovement) HasReferenceId() bool`

HasReferenceId returns a boolean if a field has been set.

### SetReferenceIdNil

`func (o *StockMovement) SetReferenceIdNil(b bool)`

 SetReferenceIdNil sets the value for ReferenceId to be an explicit nil

### UnsetReferenceId
`func (o *StockMovement) UnsetReferenceId()`

UnsetReferenceId ensures that no value is present for ReferenceId, not even an explicit nil
### GetReferenceType

`func (o *StockMovement) GetReferenceType() ReferenceType`

GetReferenceType returns the ReferenceType field if non-nil, zero value otherwise.

### GetReferenceTypeOk

`func (o *StockMovement) GetReferenceTypeOk() (*ReferenceType, bool)`

GetReferenceTypeOk returns a tuple with the ReferenceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceType

`func (o *StockMovement) SetReferenceType(v ReferenceType)`

SetReferenceType sets ReferenceType field to given value.

### HasReferenceType

`func (o *StockMovement) HasReferenceType() bool`

HasReferenceType returns a boolean if a field has been set.

### SetReferenceTypeNil

`func (o *StockMovement) SetReferenceTypeNil(b bool)`

 SetReferenceTypeNil sets the value for ReferenceType to be an explicit nil

### UnsetReferenceType
`func (o *StockMovement) UnsetReferenceType()`

UnsetReferenceType ensures that no value is present for ReferenceType, not even an explicit nil
### GetWarehouseId

`func (o *StockMovement) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *StockMovement) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *StockMovement) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


