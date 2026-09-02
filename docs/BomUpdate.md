# BomUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Components** | Pointer to **interface{}** | JSON array of &#x60;{product_id, name, quantity, unit, scrap_rate}&#x60;. | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**OutputQuantity** | Pointer to **NullableInt64** | Output quantity per production run (defaults to 1). | [optional] 
**ProductId** | Pointer to **NullableString** | The finished product this BOM produces. References the product entity. | [optional] 
**Status** | Pointer to [**NullableBomStatus**](BomStatus.md) | One of: draft | active | archived | [optional] 

## Methods

### NewBomUpdate

`func NewBomUpdate() *BomUpdate`

NewBomUpdate instantiates a new BomUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBomUpdateWithDefaults

`func NewBomUpdateWithDefaults() *BomUpdate`

NewBomUpdateWithDefaults instantiates a new BomUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponents

`func (o *BomUpdate) GetComponents() interface{}`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *BomUpdate) GetComponentsOk() (*interface{}, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *BomUpdate) SetComponents(v interface{})`

SetComponents sets Components field to given value.

### HasComponents

`func (o *BomUpdate) HasComponents() bool`

HasComponents returns a boolean if a field has been set.

### SetComponentsNil

`func (o *BomUpdate) SetComponentsNil(b bool)`

 SetComponentsNil sets the value for Components to be an explicit nil

### UnsetComponents
`func (o *BomUpdate) UnsetComponents()`

UnsetComponents ensures that no value is present for Components, not even an explicit nil
### GetDescription

`func (o *BomUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *BomUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *BomUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *BomUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *BomUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *BomUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *BomUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BomUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BomUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *BomUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *BomUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *BomUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetOutputQuantity

`func (o *BomUpdate) GetOutputQuantity() int64`

GetOutputQuantity returns the OutputQuantity field if non-nil, zero value otherwise.

### GetOutputQuantityOk

`func (o *BomUpdate) GetOutputQuantityOk() (*int64, bool)`

GetOutputQuantityOk returns a tuple with the OutputQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputQuantity

`func (o *BomUpdate) SetOutputQuantity(v int64)`

SetOutputQuantity sets OutputQuantity field to given value.

### HasOutputQuantity

`func (o *BomUpdate) HasOutputQuantity() bool`

HasOutputQuantity returns a boolean if a field has been set.

### SetOutputQuantityNil

`func (o *BomUpdate) SetOutputQuantityNil(b bool)`

 SetOutputQuantityNil sets the value for OutputQuantity to be an explicit nil

### UnsetOutputQuantity
`func (o *BomUpdate) UnsetOutputQuantity()`

UnsetOutputQuantity ensures that no value is present for OutputQuantity, not even an explicit nil
### GetProductId

`func (o *BomUpdate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *BomUpdate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *BomUpdate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *BomUpdate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *BomUpdate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *BomUpdate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetStatus

`func (o *BomUpdate) GetStatus() BomStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BomUpdate) GetStatusOk() (*BomStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BomUpdate) SetStatus(v BomStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BomUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *BomUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *BomUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


