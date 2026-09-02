# GoodsReceipt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GrNumber** | **string** |  | 
**LineItems** | **interface{}** | JSON array of &#x60;{product_id, name, quantity, batch_number?, expiry_date?, bin_location?}&#x60;. | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**PurchaseOrderId** | Pointer to **NullableString** | References the purchase order entity. | [optional] 
**ReceiptDate** | **string** |  | 
**SupplierContactId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** |  | [optional] 
**WarehouseId** | **string** | References the warehouse entity. | 

## Methods

### NewGoodsReceipt

`func NewGoodsReceipt(grNumber string, lineItems interface{}, receiptDate string, warehouseId string, ) *GoodsReceipt`

NewGoodsReceipt instantiates a new GoodsReceipt object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGoodsReceiptWithDefaults

`func NewGoodsReceiptWithDefaults() *GoodsReceipt`

NewGoodsReceiptWithDefaults instantiates a new GoodsReceipt object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGrNumber

`func (o *GoodsReceipt) GetGrNumber() string`

GetGrNumber returns the GrNumber field if non-nil, zero value otherwise.

### GetGrNumberOk

`func (o *GoodsReceipt) GetGrNumberOk() (*string, bool)`

GetGrNumberOk returns a tuple with the GrNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrNumber

`func (o *GoodsReceipt) SetGrNumber(v string)`

SetGrNumber sets GrNumber field to given value.


### GetLineItems

`func (o *GoodsReceipt) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *GoodsReceipt) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *GoodsReceipt) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *GoodsReceipt) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *GoodsReceipt) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *GoodsReceipt) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *GoodsReceipt) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *GoodsReceipt) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *GoodsReceipt) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *GoodsReceipt) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *GoodsReceipt) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPurchaseOrderId

`func (o *GoodsReceipt) GetPurchaseOrderId() string`

GetPurchaseOrderId returns the PurchaseOrderId field if non-nil, zero value otherwise.

### GetPurchaseOrderIdOk

`func (o *GoodsReceipt) GetPurchaseOrderIdOk() (*string, bool)`

GetPurchaseOrderIdOk returns a tuple with the PurchaseOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrderId

`func (o *GoodsReceipt) SetPurchaseOrderId(v string)`

SetPurchaseOrderId sets PurchaseOrderId field to given value.

### HasPurchaseOrderId

`func (o *GoodsReceipt) HasPurchaseOrderId() bool`

HasPurchaseOrderId returns a boolean if a field has been set.

### SetPurchaseOrderIdNil

`func (o *GoodsReceipt) SetPurchaseOrderIdNil(b bool)`

 SetPurchaseOrderIdNil sets the value for PurchaseOrderId to be an explicit nil

### UnsetPurchaseOrderId
`func (o *GoodsReceipt) UnsetPurchaseOrderId()`

UnsetPurchaseOrderId ensures that no value is present for PurchaseOrderId, not even an explicit nil
### GetReceiptDate

`func (o *GoodsReceipt) GetReceiptDate() string`

GetReceiptDate returns the ReceiptDate field if non-nil, zero value otherwise.

### GetReceiptDateOk

`func (o *GoodsReceipt) GetReceiptDateOk() (*string, bool)`

GetReceiptDateOk returns a tuple with the ReceiptDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptDate

`func (o *GoodsReceipt) SetReceiptDate(v string)`

SetReceiptDate sets ReceiptDate field to given value.


### GetSupplierContactId

`func (o *GoodsReceipt) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *GoodsReceipt) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *GoodsReceipt) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *GoodsReceipt) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *GoodsReceipt) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *GoodsReceipt) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *GoodsReceipt) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *GoodsReceipt) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *GoodsReceipt) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *GoodsReceipt) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *GoodsReceipt) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *GoodsReceipt) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil
### GetWarehouseId

`func (o *GoodsReceipt) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *GoodsReceipt) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *GoodsReceipt) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


