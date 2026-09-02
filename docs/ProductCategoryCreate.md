# ProductCategoryCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**ParentCategoryId** | Pointer to **NullableString** | References the category entity. | [optional] 
**SortOrder** | **int32** |  | 

## Methods

### NewProductCategoryCreate

`func NewProductCategoryCreate(name string, sortOrder int32, ) *ProductCategoryCreate`

NewProductCategoryCreate instantiates a new ProductCategoryCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductCategoryCreateWithDefaults

`func NewProductCategoryCreateWithDefaults() *ProductCategoryCreate`

NewProductCategoryCreateWithDefaults instantiates a new ProductCategoryCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ProductCategoryCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductCategoryCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductCategoryCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductCategoryCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ProductCategoryCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProductCategoryCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *ProductCategoryCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductCategoryCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductCategoryCreate) SetName(v string)`

SetName sets Name field to given value.


### GetParentCategoryId

`func (o *ProductCategoryCreate) GetParentCategoryId() string`

GetParentCategoryId returns the ParentCategoryId field if non-nil, zero value otherwise.

### GetParentCategoryIdOk

`func (o *ProductCategoryCreate) GetParentCategoryIdOk() (*string, bool)`

GetParentCategoryIdOk returns a tuple with the ParentCategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentCategoryId

`func (o *ProductCategoryCreate) SetParentCategoryId(v string)`

SetParentCategoryId sets ParentCategoryId field to given value.

### HasParentCategoryId

`func (o *ProductCategoryCreate) HasParentCategoryId() bool`

HasParentCategoryId returns a boolean if a field has been set.

### SetParentCategoryIdNil

`func (o *ProductCategoryCreate) SetParentCategoryIdNil(b bool)`

 SetParentCategoryIdNil sets the value for ParentCategoryId to be an explicit nil

### UnsetParentCategoryId
`func (o *ProductCategoryCreate) UnsetParentCategoryId()`

UnsetParentCategoryId ensures that no value is present for ParentCategoryId, not even an explicit nil
### GetSortOrder

`func (o *ProductCategoryCreate) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *ProductCategoryCreate) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *ProductCategoryCreate) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


