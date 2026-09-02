# InventoryCount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountDate** | **string** |  | 
**CountNumber** | **string** |  | 
**LineItems** | **interface{}** | JSON array of &#x60;{product_id, name, sku, expected_quantity, counted_quantity, bin_location?, batch_number?, variance}&#x60;. | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Status** | [**InventoryCountStatus**](InventoryCountStatus.md) | One of: draft | counting | reviewed | posted | 
**WarehouseId** | **string** | References the warehouse entity. | 

## Methods

### NewInventoryCount

`func NewInventoryCount(countDate string, countNumber string, lineItems interface{}, status InventoryCountStatus, warehouseId string, ) *InventoryCount`

NewInventoryCount instantiates a new InventoryCount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryCountWithDefaults

`func NewInventoryCountWithDefaults() *InventoryCount`

NewInventoryCountWithDefaults instantiates a new InventoryCount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountDate

`func (o *InventoryCount) GetCountDate() string`

GetCountDate returns the CountDate field if non-nil, zero value otherwise.

### GetCountDateOk

`func (o *InventoryCount) GetCountDateOk() (*string, bool)`

GetCountDateOk returns a tuple with the CountDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountDate

`func (o *InventoryCount) SetCountDate(v string)`

SetCountDate sets CountDate field to given value.


### GetCountNumber

`func (o *InventoryCount) GetCountNumber() string`

GetCountNumber returns the CountNumber field if non-nil, zero value otherwise.

### GetCountNumberOk

`func (o *InventoryCount) GetCountNumberOk() (*string, bool)`

GetCountNumberOk returns a tuple with the CountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountNumber

`func (o *InventoryCount) SetCountNumber(v string)`

SetCountNumber sets CountNumber field to given value.


### GetLineItems

`func (o *InventoryCount) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *InventoryCount) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *InventoryCount) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *InventoryCount) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *InventoryCount) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *InventoryCount) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *InventoryCount) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *InventoryCount) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *InventoryCount) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *InventoryCount) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *InventoryCount) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *InventoryCount) GetStatus() InventoryCountStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InventoryCount) GetStatusOk() (*InventoryCountStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InventoryCount) SetStatus(v InventoryCountStatus)`

SetStatus sets Status field to given value.


### GetWarehouseId

`func (o *InventoryCount) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *InventoryCount) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *InventoryCount) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


