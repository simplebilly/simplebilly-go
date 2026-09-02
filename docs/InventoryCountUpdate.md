# InventoryCountUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountDate** | Pointer to **NullableString** |  | [optional] 
**CountNumber** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** | JSON array of &#x60;{product_id, name, sku, expected_quantity, counted_quantity, bin_location?, batch_number?, variance}&#x60;. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableInventoryCountStatus**](InventoryCountStatus.md) | One of: draft | counting | reviewed | posted | [optional] 
**WarehouseId** | Pointer to **NullableString** | References the warehouse entity. | [optional] 

## Methods

### NewInventoryCountUpdate

`func NewInventoryCountUpdate() *InventoryCountUpdate`

NewInventoryCountUpdate instantiates a new InventoryCountUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryCountUpdateWithDefaults

`func NewInventoryCountUpdateWithDefaults() *InventoryCountUpdate`

NewInventoryCountUpdateWithDefaults instantiates a new InventoryCountUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountDate

`func (o *InventoryCountUpdate) GetCountDate() string`

GetCountDate returns the CountDate field if non-nil, zero value otherwise.

### GetCountDateOk

`func (o *InventoryCountUpdate) GetCountDateOk() (*string, bool)`

GetCountDateOk returns a tuple with the CountDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountDate

`func (o *InventoryCountUpdate) SetCountDate(v string)`

SetCountDate sets CountDate field to given value.

### HasCountDate

`func (o *InventoryCountUpdate) HasCountDate() bool`

HasCountDate returns a boolean if a field has been set.

### SetCountDateNil

`func (o *InventoryCountUpdate) SetCountDateNil(b bool)`

 SetCountDateNil sets the value for CountDate to be an explicit nil

### UnsetCountDate
`func (o *InventoryCountUpdate) UnsetCountDate()`

UnsetCountDate ensures that no value is present for CountDate, not even an explicit nil
### GetCountNumber

`func (o *InventoryCountUpdate) GetCountNumber() string`

GetCountNumber returns the CountNumber field if non-nil, zero value otherwise.

### GetCountNumberOk

`func (o *InventoryCountUpdate) GetCountNumberOk() (*string, bool)`

GetCountNumberOk returns a tuple with the CountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountNumber

`func (o *InventoryCountUpdate) SetCountNumber(v string)`

SetCountNumber sets CountNumber field to given value.

### HasCountNumber

`func (o *InventoryCountUpdate) HasCountNumber() bool`

HasCountNumber returns a boolean if a field has been set.

### SetCountNumberNil

`func (o *InventoryCountUpdate) SetCountNumberNil(b bool)`

 SetCountNumberNil sets the value for CountNumber to be an explicit nil

### UnsetCountNumber
`func (o *InventoryCountUpdate) UnsetCountNumber()`

UnsetCountNumber ensures that no value is present for CountNumber, not even an explicit nil
### GetLineItems

`func (o *InventoryCountUpdate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *InventoryCountUpdate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *InventoryCountUpdate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *InventoryCountUpdate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *InventoryCountUpdate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *InventoryCountUpdate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *InventoryCountUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *InventoryCountUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *InventoryCountUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *InventoryCountUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *InventoryCountUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *InventoryCountUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *InventoryCountUpdate) GetStatus() InventoryCountStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InventoryCountUpdate) GetStatusOk() (*InventoryCountStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InventoryCountUpdate) SetStatus(v InventoryCountStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *InventoryCountUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *InventoryCountUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *InventoryCountUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetWarehouseId

`func (o *InventoryCountUpdate) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *InventoryCountUpdate) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *InventoryCountUpdate) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.

### HasWarehouseId

`func (o *InventoryCountUpdate) HasWarehouseId() bool`

HasWarehouseId returns a boolean if a field has been set.

### SetWarehouseIdNil

`func (o *InventoryCountUpdate) SetWarehouseIdNil(b bool)`

 SetWarehouseIdNil sets the value for WarehouseId to be an explicit nil

### UnsetWarehouseId
`func (o *InventoryCountUpdate) UnsetWarehouseId()`

UnsetWarehouseId ensures that no value is present for WarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


