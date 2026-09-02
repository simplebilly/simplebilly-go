# PriceTierUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerGroupId** | Pointer to **NullableString** | None &#x3D; tier applies to all customers; otherwise a customer group id. | [optional] 
**MinQuantity** | Pointer to **NullableInt64** | Quantity from which this tier applies (inclusive). | [optional] 
**ProductId** | Pointer to **NullableString** | References the product entity. | [optional] 
**UnitPrice** | **string** | Net unit price once &#x60;min_quantity&#x60; is reached. | 

## Methods

### NewPriceTierUpdate

`func NewPriceTierUpdate(unitPrice string, ) *PriceTierUpdate`

NewPriceTierUpdate instantiates a new PriceTierUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceTierUpdateWithDefaults

`func NewPriceTierUpdateWithDefaults() *PriceTierUpdate`

NewPriceTierUpdateWithDefaults instantiates a new PriceTierUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerGroupId

`func (o *PriceTierUpdate) GetCustomerGroupId() string`

GetCustomerGroupId returns the CustomerGroupId field if non-nil, zero value otherwise.

### GetCustomerGroupIdOk

`func (o *PriceTierUpdate) GetCustomerGroupIdOk() (*string, bool)`

GetCustomerGroupIdOk returns a tuple with the CustomerGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerGroupId

`func (o *PriceTierUpdate) SetCustomerGroupId(v string)`

SetCustomerGroupId sets CustomerGroupId field to given value.

### HasCustomerGroupId

`func (o *PriceTierUpdate) HasCustomerGroupId() bool`

HasCustomerGroupId returns a boolean if a field has been set.

### SetCustomerGroupIdNil

`func (o *PriceTierUpdate) SetCustomerGroupIdNil(b bool)`

 SetCustomerGroupIdNil sets the value for CustomerGroupId to be an explicit nil

### UnsetCustomerGroupId
`func (o *PriceTierUpdate) UnsetCustomerGroupId()`

UnsetCustomerGroupId ensures that no value is present for CustomerGroupId, not even an explicit nil
### GetMinQuantity

`func (o *PriceTierUpdate) GetMinQuantity() int64`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *PriceTierUpdate) GetMinQuantityOk() (*int64, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *PriceTierUpdate) SetMinQuantity(v int64)`

SetMinQuantity sets MinQuantity field to given value.

### HasMinQuantity

`func (o *PriceTierUpdate) HasMinQuantity() bool`

HasMinQuantity returns a boolean if a field has been set.

### SetMinQuantityNil

`func (o *PriceTierUpdate) SetMinQuantityNil(b bool)`

 SetMinQuantityNil sets the value for MinQuantity to be an explicit nil

### UnsetMinQuantity
`func (o *PriceTierUpdate) UnsetMinQuantity()`

UnsetMinQuantity ensures that no value is present for MinQuantity, not even an explicit nil
### GetProductId

`func (o *PriceTierUpdate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *PriceTierUpdate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *PriceTierUpdate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *PriceTierUpdate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *PriceTierUpdate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *PriceTierUpdate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetUnitPrice

`func (o *PriceTierUpdate) GetUnitPrice() string`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *PriceTierUpdate) GetUnitPriceOk() (*string, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *PriceTierUpdate) SetUnitPrice(v string)`

SetUnitPrice sets UnitPrice field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


