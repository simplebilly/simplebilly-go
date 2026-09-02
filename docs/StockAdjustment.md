# StockAdjustment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BatchNumber** | Pointer to **NullableString** |  | [optional] 
**BinLocation** | Pointer to **NullableString** |  | [optional] 
**ExpiryDate** | Pointer to **NullableString** |  | [optional] 
**ProductId** | Pointer to **string** |  | [optional] 
**Quantity** | **int64** |  | 
**SerialNumbers** | Pointer to **[]string** |  | [optional] 

## Methods

### NewStockAdjustment

`func NewStockAdjustment(quantity int64, ) *StockAdjustment`

NewStockAdjustment instantiates a new StockAdjustment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStockAdjustmentWithDefaults

`func NewStockAdjustmentWithDefaults() *StockAdjustment`

NewStockAdjustmentWithDefaults instantiates a new StockAdjustment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBatchNumber

`func (o *StockAdjustment) GetBatchNumber() string`

GetBatchNumber returns the BatchNumber field if non-nil, zero value otherwise.

### GetBatchNumberOk

`func (o *StockAdjustment) GetBatchNumberOk() (*string, bool)`

GetBatchNumberOk returns a tuple with the BatchNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchNumber

`func (o *StockAdjustment) SetBatchNumber(v string)`

SetBatchNumber sets BatchNumber field to given value.

### HasBatchNumber

`func (o *StockAdjustment) HasBatchNumber() bool`

HasBatchNumber returns a boolean if a field has been set.

### SetBatchNumberNil

`func (o *StockAdjustment) SetBatchNumberNil(b bool)`

 SetBatchNumberNil sets the value for BatchNumber to be an explicit nil

### UnsetBatchNumber
`func (o *StockAdjustment) UnsetBatchNumber()`

UnsetBatchNumber ensures that no value is present for BatchNumber, not even an explicit nil
### GetBinLocation

`func (o *StockAdjustment) GetBinLocation() string`

GetBinLocation returns the BinLocation field if non-nil, zero value otherwise.

### GetBinLocationOk

`func (o *StockAdjustment) GetBinLocationOk() (*string, bool)`

GetBinLocationOk returns a tuple with the BinLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBinLocation

`func (o *StockAdjustment) SetBinLocation(v string)`

SetBinLocation sets BinLocation field to given value.

### HasBinLocation

`func (o *StockAdjustment) HasBinLocation() bool`

HasBinLocation returns a boolean if a field has been set.

### SetBinLocationNil

`func (o *StockAdjustment) SetBinLocationNil(b bool)`

 SetBinLocationNil sets the value for BinLocation to be an explicit nil

### UnsetBinLocation
`func (o *StockAdjustment) UnsetBinLocation()`

UnsetBinLocation ensures that no value is present for BinLocation, not even an explicit nil
### GetExpiryDate

`func (o *StockAdjustment) GetExpiryDate() string`

GetExpiryDate returns the ExpiryDate field if non-nil, zero value otherwise.

### GetExpiryDateOk

`func (o *StockAdjustment) GetExpiryDateOk() (*string, bool)`

GetExpiryDateOk returns a tuple with the ExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDate

`func (o *StockAdjustment) SetExpiryDate(v string)`

SetExpiryDate sets ExpiryDate field to given value.

### HasExpiryDate

`func (o *StockAdjustment) HasExpiryDate() bool`

HasExpiryDate returns a boolean if a field has been set.

### SetExpiryDateNil

`func (o *StockAdjustment) SetExpiryDateNil(b bool)`

 SetExpiryDateNil sets the value for ExpiryDate to be an explicit nil

### UnsetExpiryDate
`func (o *StockAdjustment) UnsetExpiryDate()`

UnsetExpiryDate ensures that no value is present for ExpiryDate, not even an explicit nil
### GetProductId

`func (o *StockAdjustment) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *StockAdjustment) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *StockAdjustment) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *StockAdjustment) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetQuantity

`func (o *StockAdjustment) GetQuantity() int64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *StockAdjustment) GetQuantityOk() (*int64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *StockAdjustment) SetQuantity(v int64)`

SetQuantity sets Quantity field to given value.


### GetSerialNumbers

`func (o *StockAdjustment) GetSerialNumbers() []string`

GetSerialNumbers returns the SerialNumbers field if non-nil, zero value otherwise.

### GetSerialNumbersOk

`func (o *StockAdjustment) GetSerialNumbersOk() (*[]string, bool)`

GetSerialNumbersOk returns a tuple with the SerialNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumbers

`func (o *StockAdjustment) SetSerialNumbers(v []string)`

SetSerialNumbers sets SerialNumbers field to given value.

### HasSerialNumbers

`func (o *StockAdjustment) HasSerialNumbers() bool`

HasSerialNumbers returns a boolean if a field has been set.

### SetSerialNumbersNil

`func (o *StockAdjustment) SetSerialNumbersNil(b bool)`

 SetSerialNumbersNil sets the value for SerialNumbers to be an explicit nil

### UnsetSerialNumbers
`func (o *StockAdjustment) UnsetSerialNumbers()`

UnsetSerialNumbers ensures that no value is present for SerialNumbers, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


