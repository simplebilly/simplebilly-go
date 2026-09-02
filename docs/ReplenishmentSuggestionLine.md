# ReplenishmentSuggestionLine

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentStock** | **int64** | Current stock in the target warehouse. | 
**MaxStock** | Pointer to **NullableInt64** |  | [optional] 
**MinStock** | Pointer to **NullableInt64** |  | [optional] 
**ProductId** | **string** |  | 
**ProductName** | **string** |  | 
**Sku** | **string** |  | 
**SourceAvailable** | **int64** | Surplus available in the source warehouse (above its target). | 
**SourceWarehouseId** | **string** |  | 
**SuggestedQuantity** | **int64** |  | 
**TargetWarehouseId** | **string** |  | 

## Methods

### NewReplenishmentSuggestionLine

`func NewReplenishmentSuggestionLine(currentStock int64, productId string, productName string, sku string, sourceAvailable int64, sourceWarehouseId string, suggestedQuantity int64, targetWarehouseId string, ) *ReplenishmentSuggestionLine`

NewReplenishmentSuggestionLine instantiates a new ReplenishmentSuggestionLine object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReplenishmentSuggestionLineWithDefaults

`func NewReplenishmentSuggestionLineWithDefaults() *ReplenishmentSuggestionLine`

NewReplenishmentSuggestionLineWithDefaults instantiates a new ReplenishmentSuggestionLine object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentStock

`func (o *ReplenishmentSuggestionLine) GetCurrentStock() int64`

GetCurrentStock returns the CurrentStock field if non-nil, zero value otherwise.

### GetCurrentStockOk

`func (o *ReplenishmentSuggestionLine) GetCurrentStockOk() (*int64, bool)`

GetCurrentStockOk returns a tuple with the CurrentStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStock

`func (o *ReplenishmentSuggestionLine) SetCurrentStock(v int64)`

SetCurrentStock sets CurrentStock field to given value.


### GetMaxStock

`func (o *ReplenishmentSuggestionLine) GetMaxStock() int64`

GetMaxStock returns the MaxStock field if non-nil, zero value otherwise.

### GetMaxStockOk

`func (o *ReplenishmentSuggestionLine) GetMaxStockOk() (*int64, bool)`

GetMaxStockOk returns a tuple with the MaxStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxStock

`func (o *ReplenishmentSuggestionLine) SetMaxStock(v int64)`

SetMaxStock sets MaxStock field to given value.

### HasMaxStock

`func (o *ReplenishmentSuggestionLine) HasMaxStock() bool`

HasMaxStock returns a boolean if a field has been set.

### SetMaxStockNil

`func (o *ReplenishmentSuggestionLine) SetMaxStockNil(b bool)`

 SetMaxStockNil sets the value for MaxStock to be an explicit nil

### UnsetMaxStock
`func (o *ReplenishmentSuggestionLine) UnsetMaxStock()`

UnsetMaxStock ensures that no value is present for MaxStock, not even an explicit nil
### GetMinStock

`func (o *ReplenishmentSuggestionLine) GetMinStock() int64`

GetMinStock returns the MinStock field if non-nil, zero value otherwise.

### GetMinStockOk

`func (o *ReplenishmentSuggestionLine) GetMinStockOk() (*int64, bool)`

GetMinStockOk returns a tuple with the MinStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinStock

`func (o *ReplenishmentSuggestionLine) SetMinStock(v int64)`

SetMinStock sets MinStock field to given value.

### HasMinStock

`func (o *ReplenishmentSuggestionLine) HasMinStock() bool`

HasMinStock returns a boolean if a field has been set.

### SetMinStockNil

`func (o *ReplenishmentSuggestionLine) SetMinStockNil(b bool)`

 SetMinStockNil sets the value for MinStock to be an explicit nil

### UnsetMinStock
`func (o *ReplenishmentSuggestionLine) UnsetMinStock()`

UnsetMinStock ensures that no value is present for MinStock, not even an explicit nil
### GetProductId

`func (o *ReplenishmentSuggestionLine) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ReplenishmentSuggestionLine) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ReplenishmentSuggestionLine) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetProductName

`func (o *ReplenishmentSuggestionLine) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *ReplenishmentSuggestionLine) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *ReplenishmentSuggestionLine) SetProductName(v string)`

SetProductName sets ProductName field to given value.


### GetSku

`func (o *ReplenishmentSuggestionLine) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ReplenishmentSuggestionLine) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ReplenishmentSuggestionLine) SetSku(v string)`

SetSku sets Sku field to given value.


### GetSourceAvailable

`func (o *ReplenishmentSuggestionLine) GetSourceAvailable() int64`

GetSourceAvailable returns the SourceAvailable field if non-nil, zero value otherwise.

### GetSourceAvailableOk

`func (o *ReplenishmentSuggestionLine) GetSourceAvailableOk() (*int64, bool)`

GetSourceAvailableOk returns a tuple with the SourceAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceAvailable

`func (o *ReplenishmentSuggestionLine) SetSourceAvailable(v int64)`

SetSourceAvailable sets SourceAvailable field to given value.


### GetSourceWarehouseId

`func (o *ReplenishmentSuggestionLine) GetSourceWarehouseId() string`

GetSourceWarehouseId returns the SourceWarehouseId field if non-nil, zero value otherwise.

### GetSourceWarehouseIdOk

`func (o *ReplenishmentSuggestionLine) GetSourceWarehouseIdOk() (*string, bool)`

GetSourceWarehouseIdOk returns a tuple with the SourceWarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceWarehouseId

`func (o *ReplenishmentSuggestionLine) SetSourceWarehouseId(v string)`

SetSourceWarehouseId sets SourceWarehouseId field to given value.


### GetSuggestedQuantity

`func (o *ReplenishmentSuggestionLine) GetSuggestedQuantity() int64`

GetSuggestedQuantity returns the SuggestedQuantity field if non-nil, zero value otherwise.

### GetSuggestedQuantityOk

`func (o *ReplenishmentSuggestionLine) GetSuggestedQuantityOk() (*int64, bool)`

GetSuggestedQuantityOk returns a tuple with the SuggestedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedQuantity

`func (o *ReplenishmentSuggestionLine) SetSuggestedQuantity(v int64)`

SetSuggestedQuantity sets SuggestedQuantity field to given value.


### GetTargetWarehouseId

`func (o *ReplenishmentSuggestionLine) GetTargetWarehouseId() string`

GetTargetWarehouseId returns the TargetWarehouseId field if non-nil, zero value otherwise.

### GetTargetWarehouseIdOk

`func (o *ReplenishmentSuggestionLine) GetTargetWarehouseIdOk() (*string, bool)`

GetTargetWarehouseIdOk returns a tuple with the TargetWarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetWarehouseId

`func (o *ReplenishmentSuggestionLine) SetTargetWarehouseId(v string)`

SetTargetWarehouseId sets TargetWarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


