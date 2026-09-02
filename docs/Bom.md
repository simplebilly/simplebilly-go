# Bom

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

### NewBom

`func NewBom(name string, productId string, ) *Bom`

NewBom instantiates a new Bom object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBomWithDefaults

`func NewBomWithDefaults() *Bom`

NewBomWithDefaults instantiates a new Bom object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponents

`func (o *Bom) GetComponents() interface{}`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *Bom) GetComponentsOk() (*interface{}, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *Bom) SetComponents(v interface{})`

SetComponents sets Components field to given value.

### HasComponents

`func (o *Bom) HasComponents() bool`

HasComponents returns a boolean if a field has been set.

### SetComponentsNil

`func (o *Bom) SetComponentsNil(b bool)`

 SetComponentsNil sets the value for Components to be an explicit nil

### UnsetComponents
`func (o *Bom) UnsetComponents()`

UnsetComponents ensures that no value is present for Components, not even an explicit nil
### GetDescription

`func (o *Bom) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Bom) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Bom) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Bom) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Bom) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Bom) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *Bom) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Bom) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Bom) SetName(v string)`

SetName sets Name field to given value.


### GetOutputQuantity

`func (o *Bom) GetOutputQuantity() int64`

GetOutputQuantity returns the OutputQuantity field if non-nil, zero value otherwise.

### GetOutputQuantityOk

`func (o *Bom) GetOutputQuantityOk() (*int64, bool)`

GetOutputQuantityOk returns a tuple with the OutputQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputQuantity

`func (o *Bom) SetOutputQuantity(v int64)`

SetOutputQuantity sets OutputQuantity field to given value.

### HasOutputQuantity

`func (o *Bom) HasOutputQuantity() bool`

HasOutputQuantity returns a boolean if a field has been set.

### GetProductId

`func (o *Bom) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *Bom) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *Bom) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetStatus

`func (o *Bom) GetStatus() BomStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Bom) GetStatusOk() (*BomStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Bom) SetStatus(v BomStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Bom) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


