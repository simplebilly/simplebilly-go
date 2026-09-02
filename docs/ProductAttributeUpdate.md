# ProductAttributeUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsFilterable** | Pointer to **NullableBool** | Whether this attribute participates in the shop&#39;s faceted filters. | [optional] 
**Name** | Pointer to **NullableString** | Attribute name, e.g. &#x60;Material&#x60;, &#x60;Farbe&#x60;, &#x60;Gewicht&#x60;. | [optional] 
**Position** | Pointer to **NullableInt32** | Ordering position within the product&#39;s attribute list. | [optional] 
**ProductId** | Pointer to **NullableString** | The product this attribute belongs to. References the product entity. | [optional] 
**Unit** | Pointer to **NullableString** | Optional unit of measure for numeric attributes, e.g. &#x60;g&#x60;, &#x60;cm&#x60;. | [optional] 
**Value** | Pointer to **NullableString** | Attribute value, e.g. &#x60;Baumwolle&#x60;, &#x60;Rot&#x60;, &#x60;180g&#x60;. | [optional] 

## Methods

### NewProductAttributeUpdate

`func NewProductAttributeUpdate() *ProductAttributeUpdate`

NewProductAttributeUpdate instantiates a new ProductAttributeUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductAttributeUpdateWithDefaults

`func NewProductAttributeUpdateWithDefaults() *ProductAttributeUpdate`

NewProductAttributeUpdateWithDefaults instantiates a new ProductAttributeUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsFilterable

`func (o *ProductAttributeUpdate) GetIsFilterable() bool`

GetIsFilterable returns the IsFilterable field if non-nil, zero value otherwise.

### GetIsFilterableOk

`func (o *ProductAttributeUpdate) GetIsFilterableOk() (*bool, bool)`

GetIsFilterableOk returns a tuple with the IsFilterable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFilterable

`func (o *ProductAttributeUpdate) SetIsFilterable(v bool)`

SetIsFilterable sets IsFilterable field to given value.

### HasIsFilterable

`func (o *ProductAttributeUpdate) HasIsFilterable() bool`

HasIsFilterable returns a boolean if a field has been set.

### SetIsFilterableNil

`func (o *ProductAttributeUpdate) SetIsFilterableNil(b bool)`

 SetIsFilterableNil sets the value for IsFilterable to be an explicit nil

### UnsetIsFilterable
`func (o *ProductAttributeUpdate) UnsetIsFilterable()`

UnsetIsFilterable ensures that no value is present for IsFilterable, not even an explicit nil
### GetName

`func (o *ProductAttributeUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductAttributeUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductAttributeUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductAttributeUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ProductAttributeUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProductAttributeUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetPosition

`func (o *ProductAttributeUpdate) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *ProductAttributeUpdate) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *ProductAttributeUpdate) SetPosition(v int32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *ProductAttributeUpdate) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### SetPositionNil

`func (o *ProductAttributeUpdate) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *ProductAttributeUpdate) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetProductId

`func (o *ProductAttributeUpdate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ProductAttributeUpdate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ProductAttributeUpdate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *ProductAttributeUpdate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *ProductAttributeUpdate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *ProductAttributeUpdate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetUnit

`func (o *ProductAttributeUpdate) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ProductAttributeUpdate) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ProductAttributeUpdate) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ProductAttributeUpdate) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### SetUnitNil

`func (o *ProductAttributeUpdate) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *ProductAttributeUpdate) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetValue

`func (o *ProductAttributeUpdate) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ProductAttributeUpdate) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ProductAttributeUpdate) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *ProductAttributeUpdate) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *ProductAttributeUpdate) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *ProductAttributeUpdate) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


