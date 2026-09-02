# ProductAttribute

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsFilterable** | Pointer to **bool** | Whether this attribute participates in the shop&#39;s faceted filters. | [optional] 
**Name** | **string** | Attribute name, e.g. &#x60;Material&#x60;, &#x60;Farbe&#x60;, &#x60;Gewicht&#x60;. | 
**Position** | Pointer to **int32** | Ordering position within the product&#39;s attribute list. | [optional] 
**ProductId** | **string** | The product this attribute belongs to. References the product entity. | 
**Unit** | Pointer to **NullableString** | Optional unit of measure for numeric attributes, e.g. &#x60;g&#x60;, &#x60;cm&#x60;. | [optional] 
**Value** | **string** | Attribute value, e.g. &#x60;Baumwolle&#x60;, &#x60;Rot&#x60;, &#x60;180g&#x60;. | 

## Methods

### NewProductAttribute

`func NewProductAttribute(name string, productId string, value string, ) *ProductAttribute`

NewProductAttribute instantiates a new ProductAttribute object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductAttributeWithDefaults

`func NewProductAttributeWithDefaults() *ProductAttribute`

NewProductAttributeWithDefaults instantiates a new ProductAttribute object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsFilterable

`func (o *ProductAttribute) GetIsFilterable() bool`

GetIsFilterable returns the IsFilterable field if non-nil, zero value otherwise.

### GetIsFilterableOk

`func (o *ProductAttribute) GetIsFilterableOk() (*bool, bool)`

GetIsFilterableOk returns a tuple with the IsFilterable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFilterable

`func (o *ProductAttribute) SetIsFilterable(v bool)`

SetIsFilterable sets IsFilterable field to given value.

### HasIsFilterable

`func (o *ProductAttribute) HasIsFilterable() bool`

HasIsFilterable returns a boolean if a field has been set.

### GetName

`func (o *ProductAttribute) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductAttribute) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductAttribute) SetName(v string)`

SetName sets Name field to given value.


### GetPosition

`func (o *ProductAttribute) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *ProductAttribute) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *ProductAttribute) SetPosition(v int32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *ProductAttribute) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetProductId

`func (o *ProductAttribute) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ProductAttribute) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ProductAttribute) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetUnit

`func (o *ProductAttribute) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ProductAttribute) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ProductAttribute) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ProductAttribute) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### SetUnitNil

`func (o *ProductAttribute) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *ProductAttribute) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetValue

`func (o *ProductAttribute) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ProductAttribute) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ProductAttribute) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


