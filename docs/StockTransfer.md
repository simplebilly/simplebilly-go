# StockTransfer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineItems** | **interface{}** | JSON array of &#x60;{product_id, name, quantity, batch_number?}&#x60;. | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**SourceWarehouseId** | **string** | References the warehouse entity. | 
**Status** | [**StockTransferStatus**](StockTransferStatus.md) | One of: draft | completed | cancelled | 
**TargetWarehouseId** | **string** | References the warehouse entity. | 
**TransferDate** | **string** |  | 
**TransferNumber** | **string** |  | 

## Methods

### NewStockTransfer

`func NewStockTransfer(lineItems interface{}, sourceWarehouseId string, status StockTransferStatus, targetWarehouseId string, transferDate string, transferNumber string, ) *StockTransfer`

NewStockTransfer instantiates a new StockTransfer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStockTransferWithDefaults

`func NewStockTransferWithDefaults() *StockTransfer`

NewStockTransferWithDefaults instantiates a new StockTransfer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineItems

`func (o *StockTransfer) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *StockTransfer) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *StockTransfer) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *StockTransfer) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *StockTransfer) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *StockTransfer) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *StockTransfer) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *StockTransfer) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *StockTransfer) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *StockTransfer) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *StockTransfer) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetSourceWarehouseId

`func (o *StockTransfer) GetSourceWarehouseId() string`

GetSourceWarehouseId returns the SourceWarehouseId field if non-nil, zero value otherwise.

### GetSourceWarehouseIdOk

`func (o *StockTransfer) GetSourceWarehouseIdOk() (*string, bool)`

GetSourceWarehouseIdOk returns a tuple with the SourceWarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceWarehouseId

`func (o *StockTransfer) SetSourceWarehouseId(v string)`

SetSourceWarehouseId sets SourceWarehouseId field to given value.


### GetStatus

`func (o *StockTransfer) GetStatus() StockTransferStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StockTransfer) GetStatusOk() (*StockTransferStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StockTransfer) SetStatus(v StockTransferStatus)`

SetStatus sets Status field to given value.


### GetTargetWarehouseId

`func (o *StockTransfer) GetTargetWarehouseId() string`

GetTargetWarehouseId returns the TargetWarehouseId field if non-nil, zero value otherwise.

### GetTargetWarehouseIdOk

`func (o *StockTransfer) GetTargetWarehouseIdOk() (*string, bool)`

GetTargetWarehouseIdOk returns a tuple with the TargetWarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetWarehouseId

`func (o *StockTransfer) SetTargetWarehouseId(v string)`

SetTargetWarehouseId sets TargetWarehouseId field to given value.


### GetTransferDate

`func (o *StockTransfer) GetTransferDate() string`

GetTransferDate returns the TransferDate field if non-nil, zero value otherwise.

### GetTransferDateOk

`func (o *StockTransfer) GetTransferDateOk() (*string, bool)`

GetTransferDateOk returns a tuple with the TransferDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferDate

`func (o *StockTransfer) SetTransferDate(v string)`

SetTransferDate sets TransferDate field to given value.


### GetTransferNumber

`func (o *StockTransfer) GetTransferNumber() string`

GetTransferNumber returns the TransferNumber field if non-nil, zero value otherwise.

### GetTransferNumberOk

`func (o *StockTransfer) GetTransferNumberOk() (*string, bool)`

GetTransferNumberOk returns a tuple with the TransferNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferNumber

`func (o *StockTransfer) SetTransferNumber(v string)`

SetTransferNumber sets TransferNumber field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


