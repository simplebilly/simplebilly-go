# ProductCategoryUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**ParentCategoryId** | Pointer to **NullableString** | References the category entity. | [optional] 
**SortOrder** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewProductCategoryUpdate

`func NewProductCategoryUpdate() *ProductCategoryUpdate`

NewProductCategoryUpdate instantiates a new ProductCategoryUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductCategoryUpdateWithDefaults

`func NewProductCategoryUpdateWithDefaults() *ProductCategoryUpdate`

NewProductCategoryUpdateWithDefaults instantiates a new ProductCategoryUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ProductCategoryUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductCategoryUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductCategoryUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductCategoryUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ProductCategoryUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProductCategoryUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *ProductCategoryUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductCategoryUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductCategoryUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductCategoryUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ProductCategoryUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProductCategoryUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetParentCategoryId

`func (o *ProductCategoryUpdate) GetParentCategoryId() string`

GetParentCategoryId returns the ParentCategoryId field if non-nil, zero value otherwise.

### GetParentCategoryIdOk

`func (o *ProductCategoryUpdate) GetParentCategoryIdOk() (*string, bool)`

GetParentCategoryIdOk returns a tuple with the ParentCategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentCategoryId

`func (o *ProductCategoryUpdate) SetParentCategoryId(v string)`

SetParentCategoryId sets ParentCategoryId field to given value.

### HasParentCategoryId

`func (o *ProductCategoryUpdate) HasParentCategoryId() bool`

HasParentCategoryId returns a boolean if a field has been set.

### SetParentCategoryIdNil

`func (o *ProductCategoryUpdate) SetParentCategoryIdNil(b bool)`

 SetParentCategoryIdNil sets the value for ParentCategoryId to be an explicit nil

### UnsetParentCategoryId
`func (o *ProductCategoryUpdate) UnsetParentCategoryId()`

UnsetParentCategoryId ensures that no value is present for ParentCategoryId, not even an explicit nil
### GetSortOrder

`func (o *ProductCategoryUpdate) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ProductCategoryUpdate) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ProductCategoryUpdate) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.

### HasSortOrder

`func (o *ProductCategoryUpdate) HasSortOrder() bool`

HasSortOrder returns a boolean if a field has been set.

### SetSortOrderNil

`func (o *ProductCategoryUpdate) SetSortOrderNil(b bool)`

 SetSortOrderNil sets the value for SortOrder to be an explicit nil

### UnsetSortOrder
`func (o *ProductCategoryUpdate) UnsetSortOrder()`

UnsetSortOrder ensures that no value is present for SortOrder, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


