# CostingLine

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineCost** | **string** | total_quantity × unit_purchase_price (0 when price unknown). | 
**Name** | **string** |  | 
**ProductId** | **string** |  | 
**QuantityPerUnit** | **int64** | Component quantity required per finished unit. | 
**Sku** | **string** |  | 
**TotalQuantity** | **int64** | Total component quantity consumed by this order. | 
**UnitPurchasePrice** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCostingLine

`func NewCostingLine(lineCost string, name string, productId string, quantityPerUnit int64, sku string, totalQuantity int64, ) *CostingLine`

NewCostingLine instantiates a new CostingLine object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCostingLineWithDefaults

`func NewCostingLineWithDefaults() *CostingLine`

NewCostingLineWithDefaults instantiates a new CostingLine object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineCost

`func (o *CostingLine) GetLineCost() string`

GetLineCost returns the LineCost field if non-nil, zero value otherwise.

### GetLineCostOk

`func (o *CostingLine) GetLineCostOk() (*string, bool)`

GetLineCostOk returns a tuple with the LineCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineCost

`func (o *CostingLine) SetLineCost(v string)`

SetLineCost sets LineCost field to given value.


### GetName

`func (o *CostingLine) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CostingLine) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CostingLine) SetName(v string)`

SetName sets Name field to given value.


### GetProductId

`func (o *CostingLine) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CostingLine) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CostingLine) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetQuantityPerUnit

`func (o *CostingLine) GetQuantityPerUnit() int64`

GetQuantityPerUnit returns the QuantityPerUnit field if non-nil, zero value otherwise.

### GetQuantityPerUnitOk

`func (o *CostingLine) GetQuantityPerUnitOk() (*int64, bool)`

GetQuantityPerUnitOk returns a tuple with the QuantityPerUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityPerUnit

`func (o *CostingLine) SetQuantityPerUnit(v int64)`

SetQuantityPerUnit sets QuantityPerUnit field to given value.


### GetSku

`func (o *CostingLine) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *CostingLine) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *CostingLine) SetSku(v string)`

SetSku sets Sku field to given value.


### GetTotalQuantity

`func (o *CostingLine) GetTotalQuantity() int64`

GetTotalQuantity returns the TotalQuantity field if non-nil, zero value otherwise.

### GetTotalQuantityOk

`func (o *CostingLine) GetTotalQuantityOk() (*int64, bool)`

GetTotalQuantityOk returns a tuple with the TotalQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalQuantity

`func (o *CostingLine) SetTotalQuantity(v int64)`

SetTotalQuantity sets TotalQuantity field to given value.


### GetUnitPurchasePrice

`func (o *CostingLine) GetUnitPurchasePrice() string`

GetUnitPurchasePrice returns the UnitPurchasePrice field if non-nil, zero value otherwise.

### GetUnitPurchasePriceOk

`func (o *CostingLine) GetUnitPurchasePriceOk() (*string, bool)`

GetUnitPurchasePriceOk returns a tuple with the UnitPurchasePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPurchasePrice

`func (o *CostingLine) SetUnitPurchasePrice(v string)`

SetUnitPurchasePrice sets UnitPurchasePrice field to given value.

### HasUnitPurchasePrice

`func (o *CostingLine) HasUnitPurchasePrice() bool`

HasUnitPurchasePrice returns a boolean if a field has been set.

### SetUnitPurchasePriceNil

`func (o *CostingLine) SetUnitPurchasePriceNil(b bool)`

 SetUnitPurchasePriceNil sets the value for UnitPurchasePrice to be an explicit nil

### UnsetUnitPurchasePrice
`func (o *CostingLine) UnsetUnitPurchasePrice()`

UnsetUnitPurchasePrice ensures that no value is present for UnitPurchasePrice, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


