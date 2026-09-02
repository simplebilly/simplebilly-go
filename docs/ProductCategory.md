# ProductCategory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**ParentCategoryId** | Pointer to **NullableString** | References the category entity. | [optional] 
**SortOrder** | **int32** |  | 

## Methods

### NewProductCategory

`func NewProductCategory(name string, sortOrder int32, ) *ProductCategory`

NewProductCategory instantiates a new ProductCategory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductCategoryWithDefaults

`func NewProductCategoryWithDefaults() *ProductCategory`

NewProductCategoryWithDefaults instantiates a new ProductCategory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ProductCategory) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductCategory) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductCategory) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductCategory) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ProductCategory) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProductCategory) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *ProductCategory) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductCategory) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductCategory) SetName(v string)`

SetName sets Name field to given value.


### GetParentCategoryId

`func (o *ProductCategory) GetParentCategoryId() string`

GetParentCategoryId returns the ParentCategoryId field if non-nil, zero value otherwise.

### GetParentCategoryIdOk

`func (o *ProductCategory) GetParentCategoryIdOk() (*string, bool)`

GetParentCategoryIdOk returns a tuple with the ParentCategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentCategoryId

`func (o *ProductCategory) SetParentCategoryId(v string)`

SetParentCategoryId sets ParentCategoryId field to given value.

### HasParentCategoryId

`func (o *ProductCategory) HasParentCategoryId() bool`

HasParentCategoryId returns a boolean if a field has been set.

### SetParentCategoryIdNil

`func (o *ProductCategory) SetParentCategoryIdNil(b bool)`

 SetParentCategoryIdNil sets the value for ParentCategoryId to be an explicit nil

### UnsetParentCategoryId
`func (o *ProductCategory) UnsetParentCategoryId()`

UnsetParentCategoryId ensures that no value is present for ParentCategoryId, not even an explicit nil
### GetSortOrder

`func (o *ProductCategory) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ProductCategory) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ProductCategory) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


