# WarehouseStock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BatchNumber** | Pointer to **NullableString** | Batch/lot number (Chargennummer) — &#x60;None&#x60; for non-batched goods. | [optional] 
**BinLocation** | Pointer to **NullableString** |  | [optional] 
**ExpiryDate** | Pointer to **NullableString** | Expiry date for batch-tracked goods. | [optional] 
**ProductId** | **string** |  | 
**Quantity** | **int64** |  | 
**SerialNumbers** | Pointer to **interface{}** | JSON array of serial numbers (Seriennummern) in this stock row. | [optional] 
**WarehouseId** | **string** |  | 

## Methods

### NewWarehouseStock

`func NewWarehouseStock(productId string, quantity int64, warehouseId string, ) *WarehouseStock`

NewWarehouseStock instantiates a new WarehouseStock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarehouseStockWithDefaults

`func NewWarehouseStockWithDefaults() *WarehouseStock`

NewWarehouseStockWithDefaults instantiates a new WarehouseStock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBatchNumber

`func (o *WarehouseStock) GetBatchNumber() string`

GetBatchNumber returns the BatchNumber field if non-nil, zero value otherwise.

### GetBatchNumberOk

`func (o *WarehouseStock) GetBatchNumberOk() (*string, bool)`

GetBatchNumberOk returns a tuple with the BatchNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchNumber

`func (o *WarehouseStock) SetBatchNumber(v string)`

SetBatchNumber sets BatchNumber field to given value.

### HasBatchNumber

`func (o *WarehouseStock) HasBatchNumber() bool`

HasBatchNumber returns a boolean if a field has been set.

### SetBatchNumberNil

`func (o *WarehouseStock) SetBatchNumberNil(b bool)`

 SetBatchNumberNil sets the value for BatchNumber to be an explicit nil

### UnsetBatchNumber
`func (o *WarehouseStock) UnsetBatchNumber()`

UnsetBatchNumber ensures that no value is present for BatchNumber, not even an explicit nil
### GetBinLocation

`func (o *WarehouseStock) GetBinLocation() string`

GetBinLocation returns the BinLocation field if non-nil, zero value otherwise.

### GetBinLocationOk

`func (o *WarehouseStock) GetBinLocationOk() (*string, bool)`

GetBinLocationOk returns a tuple with the BinLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBinLocation

`func (o *WarehouseStock) SetBinLocation(v string)`

SetBinLocation sets BinLocation field to given value.

### HasBinLocation

`func (o *WarehouseStock) HasBinLocation() bool`

HasBinLocation returns a boolean if a field has been set.

### SetBinLocationNil

`func (o *WarehouseStock) SetBinLocationNil(b bool)`

 SetBinLocationNil sets the value for BinLocation to be an explicit nil

### UnsetBinLocation
`func (o *WarehouseStock) UnsetBinLocation()`

UnsetBinLocation ensures that no value is present for BinLocation, not even an explicit nil
### GetExpiryDate

`func (o *WarehouseStock) GetExpiryDate() string`

GetExpiryDate returns the ExpiryDate field if non-nil, zero value otherwise.

### GetExpiryDateOk

`func (o *WarehouseStock) GetExpiryDateOk() (*string, bool)`

GetExpiryDateOk returns a tuple with the ExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDate

`func (o *WarehouseStock) SetExpiryDate(v string)`

SetExpiryDate sets ExpiryDate field to given value.

### HasExpiryDate

`func (o *WarehouseStock) HasExpiryDate() bool`

HasExpiryDate returns a boolean if a field has been set.

### SetExpiryDateNil

`func (o *WarehouseStock) SetExpiryDateNil(b bool)`

 SetExpiryDateNil sets the value for ExpiryDate to be an explicit nil

### UnsetExpiryDate
`func (o *WarehouseStock) UnsetExpiryDate()`

UnsetExpiryDate ensures that no value is present for ExpiryDate, not even an explicit nil
### GetProductId

`func (o *WarehouseStock) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *WarehouseStock) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *WarehouseStock) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetQuantity

`func (o *WarehouseStock) GetQuantity() int64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *WarehouseStock) GetQuantityOk() (*int64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *WarehouseStock) SetQuantity(v int64)`

SetQuantity sets Quantity field to given value.


### GetSerialNumbers

`func (o *WarehouseStock) GetSerialNumbers() interface{}`

GetSerialNumbers returns the SerialNumbers field if non-nil, zero value otherwise.

### GetSerialNumbersOk

`func (o *WarehouseStock) GetSerialNumbersOk() (*interface{}, bool)`

GetSerialNumbersOk returns a tuple with the SerialNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumbers

`func (o *WarehouseStock) SetSerialNumbers(v interface{})`

SetSerialNumbers sets SerialNumbers field to given value.

### HasSerialNumbers

`func (o *WarehouseStock) HasSerialNumbers() bool`

HasSerialNumbers returns a boolean if a field has been set.

### SetSerialNumbersNil

`func (o *WarehouseStock) SetSerialNumbersNil(b bool)`

 SetSerialNumbersNil sets the value for SerialNumbers to be an explicit nil

### UnsetSerialNumbers
`func (o *WarehouseStock) UnsetSerialNumbers()`

UnsetSerialNumbers ensures that no value is present for SerialNumbers, not even an explicit nil
### GetWarehouseId

`func (o *WarehouseStock) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *WarehouseStock) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *WarehouseStock) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


