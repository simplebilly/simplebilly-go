# PriceTierCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerGroupId** | Pointer to **NullableString** | None &#x3D; tier applies to all customers; otherwise a customer group id. | [optional] 
**MinQuantity** | Pointer to **int64** | Quantity from which this tier applies (inclusive). | [optional] 
**ProductId** | **string** | References the product entity. | 
**UnitPrice** | **string** | Net unit price once &#x60;min_quantity&#x60; is reached. | 

## Methods

### NewPriceTierCreate

`func NewPriceTierCreate(productId string, unitPrice string, ) *PriceTierCreate`

NewPriceTierCreate instantiates a new PriceTierCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceTierCreateWithDefaults

`func NewPriceTierCreateWithDefaults() *PriceTierCreate`

NewPriceTierCreateWithDefaults instantiates a new PriceTierCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerGroupId

`func (o *PriceTierCreate) GetCustomerGroupId() string`

GetCustomerGroupId returns the CustomerGroupId field if non-nil, zero value otherwise.

### GetCustomerGroupIdOk

`func (o *PriceTierCreate) GetCustomerGroupIdOk() (*string, bool)`

GetCustomerGroupIdOk returns a tuple with the CustomerGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerGroupId

`func (o *PriceTierCreate) SetCustomerGroupId(v string)`

SetCustomerGroupId sets CustomerGroupId field to given value.

### HasCustomerGroupId

`func (o *PriceTierCreate) HasCustomerGroupId() bool`

HasCustomerGroupId returns a boolean if a field has been set.

### SetCustomerGroupIdNil

`func (o *PriceTierCreate) SetCustomerGroupIdNil(b bool)`

 SetCustomerGroupIdNil sets the value for CustomerGroupId to be an explicit nil

### UnsetCustomerGroupId
`func (o *PriceTierCreate) UnsetCustomerGroupId()`

UnsetCustomerGroupId ensures that no value is present for CustomerGroupId, not even an explicit nil
### GetMinQuantity

`func (o *PriceTierCreate) GetMinQuantity() int64`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *PriceTierCreate) GetMinQuantityOk() (*int64, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *PriceTierCreate) SetMinQuantity(v int64)`

SetMinQuantity sets MinQuantity field to given value.

### HasMinQuantity

`func (o *PriceTierCreate) HasMinQuantity() bool`

HasMinQuantity returns a boolean if a field has been set.

### GetProductId

`func (o *PriceTierCreate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *PriceTierCreate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *PriceTierCreate) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetUnitPrice

`func (o *PriceTierCreate) GetUnitPrice() string`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *PriceTierCreate) GetUnitPriceOk() (*string, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *PriceTierCreate) SetUnitPrice(v string)`

SetUnitPrice sets UnitPrice field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


