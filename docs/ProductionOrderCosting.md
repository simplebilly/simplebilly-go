# ProductionOrderCosting

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostPerUnit** | **string** | material_cost_total ÷ quantity. | 
**CostSource** | **string** | \&quot;actual\&quot; when costed from stock-movement consumption, else \&quot;planned\&quot;. | 
**Lines** | [**[]CostingLine**](CostingLine.md) |  | 
**MarginPerUnit** | Pointer to **NullableString** | sale_price − cost_per_unit. | [optional] 
**MarginPercent** | Pointer to **NullableString** | margin_per_unit ÷ cost_per_unit as a percentage. | [optional] 
**MaterialCostTotal** | **string** | Total material cost for the whole order. | 
**OrderNumber** | **string** |  | 
**ProductionOrderId** | **string** |  | 
**Quantity** | **int64** |  | 
**SalePrice** | Pointer to **NullableString** | Finished product&#39;s sale price per unit (used to compute margin). | [optional] 
**Status** | **string** |  | 

## Methods

### NewProductionOrderCosting

`func NewProductionOrderCosting(costPerUnit string, costSource string, lines []CostingLine, materialCostTotal string, orderNumber string, productionOrderId string, quantity int64, status string, ) *ProductionOrderCosting`

NewProductionOrderCosting instantiates a new ProductionOrderCosting object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOrderCostingWithDefaults

`func NewProductionOrderCostingWithDefaults() *ProductionOrderCosting`

NewProductionOrderCostingWithDefaults instantiates a new ProductionOrderCosting object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCostPerUnit

`func (o *ProductionOrderCosting) GetCostPerUnit() string`

GetCostPerUnit returns the CostPerUnit field if non-nil, zero value otherwise.

### GetCostPerUnitOk

`func (o *ProductionOrderCosting) GetCostPerUnitOk() (*string, bool)`

GetCostPerUnitOk returns a tuple with the CostPerUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPerUnit

`func (o *ProductionOrderCosting) SetCostPerUnit(v string)`

SetCostPerUnit sets CostPerUnit field to given value.


### GetCostSource

`func (o *ProductionOrderCosting) GetCostSource() string`

GetCostSource returns the CostSource field if non-nil, zero value otherwise.

### GetCostSourceOk

`func (o *ProductionOrderCosting) GetCostSourceOk() (*string, bool)`

GetCostSourceOk returns a tuple with the CostSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostSource

`func (o *ProductionOrderCosting) SetCostSource(v string)`

SetCostSource sets CostSource field to given value.


### GetLines

`func (o *ProductionOrderCosting) GetLines() []CostingLine`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *ProductionOrderCosting) GetLinesOk() (*[]CostingLine, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *ProductionOrderCosting) SetLines(v []CostingLine)`

SetLines sets Lines field to given value.


### GetMarginPerUnit

`func (o *ProductionOrderCosting) GetMarginPerUnit() string`

GetMarginPerUnit returns the MarginPerUnit field if non-nil, zero value otherwise.

### GetMarginPerUnitOk

`func (o *ProductionOrderCosting) GetMarginPerUnitOk() (*string, bool)`

GetMarginPerUnitOk returns a tuple with the MarginPerUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarginPerUnit

`func (o *ProductionOrderCosting) SetMarginPerUnit(v string)`

SetMarginPerUnit sets MarginPerUnit field to given value.

### HasMarginPerUnit

`func (o *ProductionOrderCosting) HasMarginPerUnit() bool`

HasMarginPerUnit returns a boolean if a field has been set.

### SetMarginPerUnitNil

`func (o *ProductionOrderCosting) SetMarginPerUnitNil(b bool)`

 SetMarginPerUnitNil sets the value for MarginPerUnit to be an explicit nil

### UnsetMarginPerUnit
`func (o *ProductionOrderCosting) UnsetMarginPerUnit()`

UnsetMarginPerUnit ensures that no value is present for MarginPerUnit, not even an explicit nil
### GetMarginPercent

`func (o *ProductionOrderCosting) GetMarginPercent() string`

GetMarginPercent returns the MarginPercent field if non-nil, zero value otherwise.

### GetMarginPercentOk

`func (o *ProductionOrderCosting) GetMarginPercentOk() (*string, bool)`

GetMarginPercentOk returns a tuple with the MarginPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarginPercent

`func (o *ProductionOrderCosting) SetMarginPercent(v string)`

SetMarginPercent sets MarginPercent field to given value.

### HasMarginPercent

`func (o *ProductionOrderCosting) HasMarginPercent() bool`

HasMarginPercent returns a boolean if a field has been set.

### SetMarginPercentNil

`func (o *ProductionOrderCosting) SetMarginPercentNil(b bool)`

 SetMarginPercentNil sets the value for MarginPercent to be an explicit nil

### UnsetMarginPercent
`func (o *ProductionOrderCosting) UnsetMarginPercent()`

UnsetMarginPercent ensures that no value is present for MarginPercent, not even an explicit nil
### GetMaterialCostTotal

`func (o *ProductionOrderCosting) GetMaterialCostTotal() string`

GetMaterialCostTotal returns the MaterialCostTotal field if non-nil, zero value otherwise.

### GetMaterialCostTotalOk

`func (o *ProductionOrderCosting) GetMaterialCostTotalOk() (*string, bool)`

GetMaterialCostTotalOk returns a tuple with the MaterialCostTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaterialCostTotal

`func (o *ProductionOrderCosting) SetMaterialCostTotal(v string)`

SetMaterialCostTotal sets MaterialCostTotal field to given value.


### GetOrderNumber

`func (o *ProductionOrderCosting) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ProductionOrderCosting) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ProductionOrderCosting) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetProductionOrderId

`func (o *ProductionOrderCosting) GetProductionOrderId() string`

GetProductionOrderId returns the ProductionOrderId field if non-nil, zero value otherwise.

### GetProductionOrderIdOk

`func (o *ProductionOrderCosting) GetProductionOrderIdOk() (*string, bool)`

GetProductionOrderIdOk returns a tuple with the ProductionOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionOrderId

`func (o *ProductionOrderCosting) SetProductionOrderId(v string)`

SetProductionOrderId sets ProductionOrderId field to given value.


### GetQuantity

`func (o *ProductionOrderCosting) GetQuantity() int64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOrderCosting) GetQuantityOk() (*int64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOrderCosting) SetQuantity(v int64)`

SetQuantity sets Quantity field to given value.


### GetSalePrice

`func (o *ProductionOrderCosting) GetSalePrice() string`

GetSalePrice returns the SalePrice field if non-nil, zero value otherwise.

### GetSalePriceOk

`func (o *ProductionOrderCosting) GetSalePriceOk() (*string, bool)`

GetSalePriceOk returns a tuple with the SalePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalePrice

`func (o *ProductionOrderCosting) SetSalePrice(v string)`

SetSalePrice sets SalePrice field to given value.

### HasSalePrice

`func (o *ProductionOrderCosting) HasSalePrice() bool`

HasSalePrice returns a boolean if a field has been set.

### SetSalePriceNil

`func (o *ProductionOrderCosting) SetSalePriceNil(b bool)`

 SetSalePriceNil sets the value for SalePrice to be an explicit nil

### UnsetSalePrice
`func (o *ProductionOrderCosting) UnsetSalePrice()`

UnsetSalePrice ensures that no value is present for SalePrice, not even an explicit nil
### GetStatus

`func (o *ProductionOrderCosting) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProductionOrderCosting) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProductionOrderCosting) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


