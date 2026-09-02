# ResolvedPriceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsListPrice** | **bool** | True when no tier matched and the product list price was used. | 
**PriceTierId** | Pointer to **NullableString** | Applied tier, if any matched. | [optional] 
**ProductId** | **string** |  | 
**Quantity** | **int64** |  | 
**UnitPrice** | **string** |  | 

## Methods

### NewResolvedPriceResponse

`func NewResolvedPriceResponse(isListPrice bool, productId string, quantity int64, unitPrice string, ) *ResolvedPriceResponse`

NewResolvedPriceResponse instantiates a new ResolvedPriceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResolvedPriceResponseWithDefaults

`func NewResolvedPriceResponseWithDefaults() *ResolvedPriceResponse`

NewResolvedPriceResponseWithDefaults instantiates a new ResolvedPriceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsListPrice

`func (o *ResolvedPriceResponse) GetIsListPrice() bool`

GetIsListPrice returns the IsListPrice field if non-nil, zero value otherwise.

### GetIsListPriceOk

`func (o *ResolvedPriceResponse) GetIsListPriceOk() (*bool, bool)`

GetIsListPriceOk returns a tuple with the IsListPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsListPrice

`func (o *ResolvedPriceResponse) SetIsListPrice(v bool)`

SetIsListPrice sets IsListPrice field to given value.


### GetPriceTierId

`func (o *ResolvedPriceResponse) GetPriceTierId() string`

GetPriceTierId returns the PriceTierId field if non-nil, zero value otherwise.

### GetPriceTierIdOk

`func (o *ResolvedPriceResponse) GetPriceTierIdOk() (*string, bool)`

GetPriceTierIdOk returns a tuple with the PriceTierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceTierId

`func (o *ResolvedPriceResponse) SetPriceTierId(v string)`

SetPriceTierId sets PriceTierId field to given value.

### HasPriceTierId

`func (o *ResolvedPriceResponse) HasPriceTierId() bool`

HasPriceTierId returns a boolean if a field has been set.

### SetPriceTierIdNil

`func (o *ResolvedPriceResponse) SetPriceTierIdNil(b bool)`

 SetPriceTierIdNil sets the value for PriceTierId to be an explicit nil

### UnsetPriceTierId
`func (o *ResolvedPriceResponse) UnsetPriceTierId()`

UnsetPriceTierId ensures that no value is present for PriceTierId, not even an explicit nil
### GetProductId

`func (o *ResolvedPriceResponse) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ResolvedPriceResponse) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ResolvedPriceResponse) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetQuantity

`func (o *ResolvedPriceResponse) GetQuantity() int64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ResolvedPriceResponse) GetQuantityOk() (*int64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ResolvedPriceResponse) SetQuantity(v int64)`

SetQuantity sets Quantity field to given value.


### GetUnitPrice

`func (o *ResolvedPriceResponse) GetUnitPrice() string`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *ResolvedPriceResponse) GetUnitPriceOk() (*string, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *ResolvedPriceResponse) SetUnitPrice(v string)`

SetUnitPrice sets UnitPrice field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


