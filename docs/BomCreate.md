# BomCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Components** | Pointer to **interface{}** | JSON array of &#x60;{product_id, name, quantity, unit, scrap_rate}&#x60;. | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**OutputQuantity** | Pointer to **int64** | Output quantity per production run (defaults to 1). | [optional] 
**ProductId** | **string** | The finished product this BOM produces. References the product entity. | 
**Status** | Pointer to [**BomStatus**](BomStatus.md) | One of: draft | active | archived | [optional] 

## Methods

### NewBomCreate

`func NewBomCreate(name string, productId string, ) *BomCreate`

NewBomCreate instantiates a new BomCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBomCreateWithDefaults

`func NewBomCreateWithDefaults() *BomCreate`

NewBomCreateWithDefaults instantiates a new BomCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponents

`func (o *BomCreate) GetComponents() interface{}`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *BomCreate) GetComponentsOk() (*interface{}, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *BomCreate) SetComponents(v interface{})`

SetComponents sets Components field to given value.

### HasComponents

`func (o *BomCreate) HasComponents() bool`

HasComponents returns a boolean if a field has been set.

### SetComponentsNil

`func (o *BomCreate) SetComponentsNil(b bool)`

 SetComponentsNil sets the value for Components to be an explicit nil

### UnsetComponents
`func (o *BomCreate) UnsetComponents()`

UnsetComponents ensures that no value is present for Components, not even an explicit nil
### GetDescription

`func (o *BomCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *BomCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *BomCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *BomCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *BomCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *BomCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *BomCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BomCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BomCreate) SetName(v string)`

SetName sets Name field to given value.


### GetOutputQuantity

`func (o *BomCreate) GetOutputQuantity() int64`

GetOutputQuantity returns the OutputQuantity field if non-nil, zero value otherwise.

### GetOutputQuantityOk

`func (o *BomCreate) GetOutputQuantityOk() (*int64, bool)`

GetOutputQuantityOk returns a tuple with the OutputQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputQuantity

`func (o *BomCreate) SetOutputQuantity(v int64)`

SetOutputQuantity sets OutputQuantity field to given value.

### HasOutputQuantity

`func (o *BomCreate) HasOutputQuantity() bool`

HasOutputQuantity returns a boolean if a field has been set.

### GetProductId

`func (o *BomCreate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *BomCreate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *BomCreate) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetStatus

`func (o *BomCreate) GetStatus() BomStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BomCreate) GetStatusOk() (*BomStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BomCreate) SetStatus(v BomStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BomCreate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


