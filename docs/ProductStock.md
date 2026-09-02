# ProductStock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**ProductId** | **string** |  | 
**Sku** | **string** |  | 
**StockQuantity** | Pointer to **NullableInt64** |  | [optional] 

## Methods

### NewProductStock

`func NewProductStock(name string, productId string, sku string, ) *ProductStock`

NewProductStock instantiates a new ProductStock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductStockWithDefaults

`func NewProductStockWithDefaults() *ProductStock`

NewProductStockWithDefaults instantiates a new ProductStock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ProductStock) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductStock) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductStock) SetName(v string)`

SetName sets Name field to given value.


### GetProductId

`func (o *ProductStock) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ProductStock) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ProductStock) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetSku

`func (o *ProductStock) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ProductStock) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ProductStock) SetSku(v string)`

SetSku sets Sku field to given value.


### GetStockQuantity

`func (o *ProductStock) GetStockQuantity() int64`

GetStockQuantity returns the StockQuantity field if non-nil, zero value otherwise.

### GetStockQuantityOk

`func (o *ProductStock) GetStockQuantityOk() (*int64, bool)`

GetStockQuantityOk returns a tuple with the StockQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockQuantity

`func (o *ProductStock) SetStockQuantity(v int64)`

SetStockQuantity sets StockQuantity field to given value.

### HasStockQuantity

`func (o *ProductStock) HasStockQuantity() bool`

HasStockQuantity returns a boolean if a field has been set.

### SetStockQuantityNil

`func (o *ProductStock) SetStockQuantityNil(b bool)`

 SetStockQuantityNil sets the value for StockQuantity to be an explicit nil

### UnsetStockQuantity
`func (o *ProductStock) UnsetStockQuantity()`

UnsetStockQuantity ensures that no value is present for StockQuantity, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


