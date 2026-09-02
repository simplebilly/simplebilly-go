# ProductionOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BomId** | Pointer to **NullableString** | References the BOM entity. | [optional] 
**Components** | Pointer to **interface{}** | JSON snapshot of the BOM components at creation time. | [optional] 
**EndDate** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | **string** |  | 
**ProductId** | **string** | The finished product to manufacture. References the product entity. | 
**Quantity** | **int64** | Quantity of finished product to produce. | 
**SourceWarehouseId** | Pointer to **NullableString** | Warehouse components are consumed from. References the warehouse entity. | [optional] 
**StartDate** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**ProductionOrderStatus**](ProductionOrderStatus.md) | One of: planned | in_production | completed | cancelled | [optional] 
**TargetWarehouseId** | Pointer to **NullableString** | Warehouse the finished product is added to. References the warehouse entity. | [optional] 

## Methods

### NewProductionOrder

`func NewProductionOrder(orderNumber string, productId string, quantity int64, ) *ProductionOrder`

NewProductionOrder instantiates a new ProductionOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductionOrderWithDefaults

`func NewProductionOrderWithDefaults() *ProductionOrder`

NewProductionOrderWithDefaults instantiates a new ProductionOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBomId

`func (o *ProductionOrder) GetBomId() string`

GetBomId returns the BomId field if non-nil, zero value otherwise.

### GetBomIdOk

`func (o *ProductionOrder) GetBomIdOk() (*string, bool)`

GetBomIdOk returns a tuple with the BomId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBomId

`func (o *ProductionOrder) SetBomId(v string)`

SetBomId sets BomId field to given value.

### HasBomId

`func (o *ProductionOrder) HasBomId() bool`

HasBomId returns a boolean if a field has been set.

### SetBomIdNil

`func (o *ProductionOrder) SetBomIdNil(b bool)`

 SetBomIdNil sets the value for BomId to be an explicit nil

### UnsetBomId
`func (o *ProductionOrder) UnsetBomId()`

UnsetBomId ensures that no value is present for BomId, not even an explicit nil
### GetComponents

`func (o *ProductionOrder) GetComponents() interface{}`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *ProductionOrder) GetComponentsOk() (*interface{}, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *ProductionOrder) SetComponents(v interface{})`

SetComponents sets Components field to given value.

### HasComponents

`func (o *ProductionOrder) HasComponents() bool`

HasComponents returns a boolean if a field has been set.

### SetComponentsNil

`func (o *ProductionOrder) SetComponentsNil(b bool)`

 SetComponentsNil sets the value for Components to be an explicit nil

### UnsetComponents
`func (o *ProductionOrder) UnsetComponents()`

UnsetComponents ensures that no value is present for Components, not even an explicit nil
### GetEndDate

`func (o *ProductionOrder) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *ProductionOrder) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *ProductionOrder) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *ProductionOrder) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### SetEndDateNil

`func (o *ProductionOrder) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *ProductionOrder) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetNotes

`func (o *ProductionOrder) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ProductionOrder) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ProductionOrder) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ProductionOrder) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ProductionOrder) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ProductionOrder) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderNumber

`func (o *ProductionOrder) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ProductionOrder) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ProductionOrder) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetProductId

`func (o *ProductionOrder) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ProductionOrder) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ProductionOrder) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetQuantity

`func (o *ProductionOrder) GetQuantity() int64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ProductionOrder) GetQuantityOk() (*int64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ProductionOrder) SetQuantity(v int64)`

SetQuantity sets Quantity field to given value.


### GetSourceWarehouseId

`func (o *ProductionOrder) GetSourceWarehouseId() string`

GetSourceWarehouseId returns the SourceWarehouseId field if non-nil, zero value otherwise.

### GetSourceWarehouseIdOk

`func (o *ProductionOrder) GetSourceWarehouseIdOk() (*string, bool)`

GetSourceWarehouseIdOk returns a tuple with the SourceWarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceWarehouseId

`func (o *ProductionOrder) SetSourceWarehouseId(v string)`

SetSourceWarehouseId sets SourceWarehouseId field to given value.

### HasSourceWarehouseId

`func (o *ProductionOrder) HasSourceWarehouseId() bool`

HasSourceWarehouseId returns a boolean if a field has been set.

### SetSourceWarehouseIdNil

`func (o *ProductionOrder) SetSourceWarehouseIdNil(b bool)`

 SetSourceWarehouseIdNil sets the value for SourceWarehouseId to be an explicit nil

### UnsetSourceWarehouseId
`func (o *ProductionOrder) UnsetSourceWarehouseId()`

UnsetSourceWarehouseId ensures that no value is present for SourceWarehouseId, not even an explicit nil
### GetStartDate

`func (o *ProductionOrder) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ProductionOrder) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ProductionOrder) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *ProductionOrder) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *ProductionOrder) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *ProductionOrder) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetStatus

`func (o *ProductionOrder) GetStatus() ProductionOrderStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProductionOrder) GetStatusOk() (*ProductionOrderStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProductionOrder) SetStatus(v ProductionOrderStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProductionOrder) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTargetWarehouseId

`func (o *ProductionOrder) GetTargetWarehouseId() string`

GetTargetWarehouseId returns the TargetWarehouseId field if non-nil, zero value otherwise.

### GetTargetWarehouseIdOk

`func (o *ProductionOrder) GetTargetWarehouseIdOk() (*string, bool)`

GetTargetWarehouseIdOk returns a tuple with the TargetWarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetWarehouseId

`func (o *ProductionOrder) SetTargetWarehouseId(v string)`

SetTargetWarehouseId sets TargetWarehouseId field to given value.

### HasTargetWarehouseId

`func (o *ProductionOrder) HasTargetWarehouseId() bool`

HasTargetWarehouseId returns a boolean if a field has been set.

### SetTargetWarehouseIdNil

`func (o *ProductionOrder) SetTargetWarehouseIdNil(b bool)`

 SetTargetWarehouseIdNil sets the value for TargetWarehouseId to be an explicit nil

### UnsetTargetWarehouseId
`func (o *ProductionOrder) UnsetTargetWarehouseId()`

UnsetTargetWarehouseId ensures that no value is present for TargetWarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


