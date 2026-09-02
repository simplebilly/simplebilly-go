# ReorderProposalLine

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentStock** | **int64** |  | 
**MaxStock** | Pointer to **NullableInt64** |  | [optional] 
**MinStock** | Pointer to **NullableInt64** |  | [optional] 
**ProductId** | **string** |  | 
**ProductName** | **string** |  | 
**ReorderQuantity** | Pointer to **NullableInt64** |  | [optional] 
**Sku** | **string** |  | 
**SuggestedQuantity** | **int64** |  | 

## Methods

### NewReorderProposalLine

`func NewReorderProposalLine(currentStock int64, productId string, productName string, sku string, suggestedQuantity int64, ) *ReorderProposalLine`

NewReorderProposalLine instantiates a new ReorderProposalLine object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReorderProposalLineWithDefaults

`func NewReorderProposalLineWithDefaults() *ReorderProposalLine`

NewReorderProposalLineWithDefaults instantiates a new ReorderProposalLine object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentStock

`func (o *ReorderProposalLine) GetCurrentStock() int64`

GetCurrentStock returns the CurrentStock field if non-nil, zero value otherwise.

### GetCurrentStockOk

`func (o *ReorderProposalLine) GetCurrentStockOk() (*int64, bool)`

GetCurrentStockOk returns a tuple with the CurrentStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStock

`func (o *ReorderProposalLine) SetCurrentStock(v int64)`

SetCurrentStock sets CurrentStock field to given value.


### GetMaxStock

`func (o *ReorderProposalLine) GetMaxStock() int64`

GetMaxStock returns the MaxStock field if non-nil, zero value otherwise.

### GetMaxStockOk

`func (o *ReorderProposalLine) GetMaxStockOk() (*int64, bool)`

GetMaxStockOk returns a tuple with the MaxStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxStock

`func (o *ReorderProposalLine) SetMaxStock(v int64)`

SetMaxStock sets MaxStock field to given value.

### HasMaxStock

`func (o *ReorderProposalLine) HasMaxStock() bool`

HasMaxStock returns a boolean if a field has been set.

### SetMaxStockNil

`func (o *ReorderProposalLine) SetMaxStockNil(b bool)`

 SetMaxStockNil sets the value for MaxStock to be an explicit nil

### UnsetMaxStock
`func (o *ReorderProposalLine) UnsetMaxStock()`

UnsetMaxStock ensures that no value is present for MaxStock, not even an explicit nil
### GetMinStock

`func (o *ReorderProposalLine) GetMinStock() int64`

GetMinStock returns the MinStock field if non-nil, zero value otherwise.

### GetMinStockOk

`func (o *ReorderProposalLine) GetMinStockOk() (*int64, bool)`

GetMinStockOk returns a tuple with the MinStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinStock

`func (o *ReorderProposalLine) SetMinStock(v int64)`

SetMinStock sets MinStock field to given value.

### HasMinStock

`func (o *ReorderProposalLine) HasMinStock() bool`

HasMinStock returns a boolean if a field has been set.

### SetMinStockNil

`func (o *ReorderProposalLine) SetMinStockNil(b bool)`

 SetMinStockNil sets the value for MinStock to be an explicit nil

### UnsetMinStock
`func (o *ReorderProposalLine) UnsetMinStock()`

UnsetMinStock ensures that no value is present for MinStock, not even an explicit nil
### GetProductId

`func (o *ReorderProposalLine) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ReorderProposalLine) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ReorderProposalLine) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetProductName

`func (o *ReorderProposalLine) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *ReorderProposalLine) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *ReorderProposalLine) SetProductName(v string)`

SetProductName sets ProductName field to given value.


### GetReorderQuantity

`func (o *ReorderProposalLine) GetReorderQuantity() int64`

GetReorderQuantity returns the ReorderQuantity field if non-nil, zero value otherwise.

### GetReorderQuantityOk

`func (o *ReorderProposalLine) GetReorderQuantityOk() (*int64, bool)`

GetReorderQuantityOk returns a tuple with the ReorderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReorderQuantity

`func (o *ReorderProposalLine) SetReorderQuantity(v int64)`

SetReorderQuantity sets ReorderQuantity field to given value.

### HasReorderQuantity

`func (o *ReorderProposalLine) HasReorderQuantity() bool`

HasReorderQuantity returns a boolean if a field has been set.

### SetReorderQuantityNil

`func (o *ReorderProposalLine) SetReorderQuantityNil(b bool)`

 SetReorderQuantityNil sets the value for ReorderQuantity to be an explicit nil

### UnsetReorderQuantity
`func (o *ReorderProposalLine) UnsetReorderQuantity()`

UnsetReorderQuantity ensures that no value is present for ReorderQuantity, not even an explicit nil
### GetSku

`func (o *ReorderProposalLine) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ReorderProposalLine) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ReorderProposalLine) SetSku(v string)`

SetSku sets Sku field to given value.


### GetSuggestedQuantity

`func (o *ReorderProposalLine) GetSuggestedQuantity() int64`

GetSuggestedQuantity returns the SuggestedQuantity field if non-nil, zero value otherwise.

### GetSuggestedQuantityOk

`func (o *ReorderProposalLine) GetSuggestedQuantityOk() (*int64, bool)`

GetSuggestedQuantityOk returns a tuple with the SuggestedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedQuantity

`func (o *ReorderProposalLine) SetSuggestedQuantity(v int64)`

SetSuggestedQuantity sets SuggestedQuantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


