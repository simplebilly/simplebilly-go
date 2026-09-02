# InventoryCountCreate

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

### NewInventoryCountCreate

`func NewInventoryCountCreate(countDate string, countNumber string, lineItems interface{}, status InventoryCountStatus, warehouseId string, ) *InventoryCountCreate`

NewInventoryCountCreate instantiates a new InventoryCountCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryCountCreateWithDefaults

`func NewInventoryCountCreateWithDefaults() *InventoryCountCreate`

NewInventoryCountCreateWithDefaults instantiates a new InventoryCountCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountDate

`func (o *InventoryCountCreate) GetCountDate() string`

GetCountDate returns the CountDate field if non-nil, zero value otherwise.

### GetCountDateOk

`func (o *InventoryCountCreate) GetCountDateOk() (*string, bool)`

GetCountDateOk returns a tuple with the CountDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountDate

`func (o *InventoryCountCreate) SetCountDate(v string)`

SetCountDate sets CountDate field to given value.


### GetCountNumber

`func (o *InventoryCountCreate) GetCountNumber() string`

GetCountNumber returns the CountNumber field if non-nil, zero value otherwise.

### GetCountNumberOk

`func (o *InventoryCountCreate) GetCountNumberOk() (*string, bool)`

GetCountNumberOk returns a tuple with the CountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountNumber

`func (o *InventoryCountCreate) SetCountNumber(v string)`

SetCountNumber sets CountNumber field to given value.


### GetLineItems

`func (o *InventoryCountCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *InventoryCountCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *InventoryCountCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *InventoryCountCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *InventoryCountCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *InventoryCountCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *InventoryCountCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *InventoryCountCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *InventoryCountCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *InventoryCountCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *InventoryCountCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *InventoryCountCreate) GetStatus() InventoryCountStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InventoryCountCreate) GetStatusOk() (*InventoryCountStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InventoryCountCreate) SetStatus(v InventoryCountStatus)`

SetStatus sets Status field to given value.


### GetWarehouseId

`func (o *InventoryCountCreate) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *InventoryCountCreate) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *InventoryCountCreate) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


