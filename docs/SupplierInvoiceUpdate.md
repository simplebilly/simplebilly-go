# SupplierInvoiceUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** |  | [optional] 
**GoodsReceiptId** | Pointer to **NullableString** | References the goods receipt entity. | [optional] 
**InvoiceDate** | Pointer to **NullableString** |  | [optional] 
**InvoiceNumber** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** | JSON array of &#x60;{product_id, name, quantity, unitPriceNet, taxRate}&#x60;. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**PurchaseOrderId** | Pointer to **NullableString** | References the purchase order entity. | [optional] 
**Status** | Pointer to [**NullableSupplierInvoiceStatus**](SupplierInvoiceStatus.md) | One of: draft | matched | has_variances | posted | cancelled | [optional] 
**SupplierContactId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** |  | [optional] 
**TotalGrossAmount** | Pointer to **NullableString** |  | [optional] 
**TotalNetAmount** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSupplierInvoiceUpdate

`func NewSupplierInvoiceUpdate() *SupplierInvoiceUpdate`

NewSupplierInvoiceUpdate instantiates a new SupplierInvoiceUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplierInvoiceUpdateWithDefaults

`func NewSupplierInvoiceUpdateWithDefaults() *SupplierInvoiceUpdate`

NewSupplierInvoiceUpdateWithDefaults instantiates a new SupplierInvoiceUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *SupplierInvoiceUpdate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SupplierInvoiceUpdate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SupplierInvoiceUpdate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SupplierInvoiceUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *SupplierInvoiceUpdate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *SupplierInvoiceUpdate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetGoodsReceiptId

`func (o *SupplierInvoiceUpdate) GetGoodsReceiptId() string`

GetGoodsReceiptId returns the GoodsReceiptId field if non-nil, zero value otherwise.

### GetGoodsReceiptIdOk

`func (o *SupplierInvoiceUpdate) GetGoodsReceiptIdOk() (*string, bool)`

GetGoodsReceiptIdOk returns a tuple with the GoodsReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoodsReceiptId

`func (o *SupplierInvoiceUpdate) SetGoodsReceiptId(v string)`

SetGoodsReceiptId sets GoodsReceiptId field to given value.

### HasGoodsReceiptId

`func (o *SupplierInvoiceUpdate) HasGoodsReceiptId() bool`

HasGoodsReceiptId returns a boolean if a field has been set.

### SetGoodsReceiptIdNil

`func (o *SupplierInvoiceUpdate) SetGoodsReceiptIdNil(b bool)`

 SetGoodsReceiptIdNil sets the value for GoodsReceiptId to be an explicit nil

### UnsetGoodsReceiptId
`func (o *SupplierInvoiceUpdate) UnsetGoodsReceiptId()`

UnsetGoodsReceiptId ensures that no value is present for GoodsReceiptId, not even an explicit nil
### GetInvoiceDate

`func (o *SupplierInvoiceUpdate) GetInvoiceDate() string`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *SupplierInvoiceUpdate) GetInvoiceDateOk() (*string, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *SupplierInvoiceUpdate) SetInvoiceDate(v string)`

SetInvoiceDate sets InvoiceDate field to given value.

### HasInvoiceDate

`func (o *SupplierInvoiceUpdate) HasInvoiceDate() bool`

HasInvoiceDate returns a boolean if a field has been set.

### SetInvoiceDateNil

`func (o *SupplierInvoiceUpdate) SetInvoiceDateNil(b bool)`

 SetInvoiceDateNil sets the value for InvoiceDate to be an explicit nil

### UnsetInvoiceDate
`func (o *SupplierInvoiceUpdate) UnsetInvoiceDate()`

UnsetInvoiceDate ensures that no value is present for InvoiceDate, not even an explicit nil
### GetInvoiceNumber

`func (o *SupplierInvoiceUpdate) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *SupplierInvoiceUpdate) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *SupplierInvoiceUpdate) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *SupplierInvoiceUpdate) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### SetInvoiceNumberNil

`func (o *SupplierInvoiceUpdate) SetInvoiceNumberNil(b bool)`

 SetInvoiceNumberNil sets the value for InvoiceNumber to be an explicit nil

### UnsetInvoiceNumber
`func (o *SupplierInvoiceUpdate) UnsetInvoiceNumber()`

UnsetInvoiceNumber ensures that no value is present for InvoiceNumber, not even an explicit nil
### GetLineItems

`func (o *SupplierInvoiceUpdate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *SupplierInvoiceUpdate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *SupplierInvoiceUpdate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *SupplierInvoiceUpdate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *SupplierInvoiceUpdate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *SupplierInvoiceUpdate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *SupplierInvoiceUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SupplierInvoiceUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SupplierInvoiceUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SupplierInvoiceUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SupplierInvoiceUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SupplierInvoiceUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPurchaseOrderId

`func (o *SupplierInvoiceUpdate) GetPurchaseOrderId() string`

GetPurchaseOrderId returns the PurchaseOrderId field if non-nil, zero value otherwise.

### GetPurchaseOrderIdOk

`func (o *SupplierInvoiceUpdate) GetPurchaseOrderIdOk() (*string, bool)`

GetPurchaseOrderIdOk returns a tuple with the PurchaseOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrderId

`func (o *SupplierInvoiceUpdate) SetPurchaseOrderId(v string)`

SetPurchaseOrderId sets PurchaseOrderId field to given value.

### HasPurchaseOrderId

`func (o *SupplierInvoiceUpdate) HasPurchaseOrderId() bool`

HasPurchaseOrderId returns a boolean if a field has been set.

### SetPurchaseOrderIdNil

`func (o *SupplierInvoiceUpdate) SetPurchaseOrderIdNil(b bool)`

 SetPurchaseOrderIdNil sets the value for PurchaseOrderId to be an explicit nil

### UnsetPurchaseOrderId
`func (o *SupplierInvoiceUpdate) UnsetPurchaseOrderId()`

UnsetPurchaseOrderId ensures that no value is present for PurchaseOrderId, not even an explicit nil
### GetStatus

`func (o *SupplierInvoiceUpdate) GetStatus() SupplierInvoiceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SupplierInvoiceUpdate) GetStatusOk() (*SupplierInvoiceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SupplierInvoiceUpdate) SetStatus(v SupplierInvoiceStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SupplierInvoiceUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *SupplierInvoiceUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *SupplierInvoiceUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSupplierContactId

`func (o *SupplierInvoiceUpdate) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *SupplierInvoiceUpdate) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *SupplierInvoiceUpdate) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *SupplierInvoiceUpdate) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *SupplierInvoiceUpdate) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *SupplierInvoiceUpdate) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *SupplierInvoiceUpdate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *SupplierInvoiceUpdate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *SupplierInvoiceUpdate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *SupplierInvoiceUpdate) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *SupplierInvoiceUpdate) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *SupplierInvoiceUpdate) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil
### GetTotalGrossAmount

`func (o *SupplierInvoiceUpdate) GetTotalGrossAmount() string`

GetTotalGrossAmount returns the TotalGrossAmount field if non-nil, zero value otherwise.

### GetTotalGrossAmountOk

`func (o *SupplierInvoiceUpdate) GetTotalGrossAmountOk() (*string, bool)`

GetTotalGrossAmountOk returns a tuple with the TotalGrossAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGrossAmount

`func (o *SupplierInvoiceUpdate) SetTotalGrossAmount(v string)`

SetTotalGrossAmount sets TotalGrossAmount field to given value.

### HasTotalGrossAmount

`func (o *SupplierInvoiceUpdate) HasTotalGrossAmount() bool`

HasTotalGrossAmount returns a boolean if a field has been set.

### SetTotalGrossAmountNil

`func (o *SupplierInvoiceUpdate) SetTotalGrossAmountNil(b bool)`

 SetTotalGrossAmountNil sets the value for TotalGrossAmount to be an explicit nil

### UnsetTotalGrossAmount
`func (o *SupplierInvoiceUpdate) UnsetTotalGrossAmount()`

UnsetTotalGrossAmount ensures that no value is present for TotalGrossAmount, not even an explicit nil
### GetTotalNetAmount

`func (o *SupplierInvoiceUpdate) GetTotalNetAmount() string`

GetTotalNetAmount returns the TotalNetAmount field if non-nil, zero value otherwise.

### GetTotalNetAmountOk

`func (o *SupplierInvoiceUpdate) GetTotalNetAmountOk() (*string, bool)`

GetTotalNetAmountOk returns a tuple with the TotalNetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNetAmount

`func (o *SupplierInvoiceUpdate) SetTotalNetAmount(v string)`

SetTotalNetAmount sets TotalNetAmount field to given value.

### HasTotalNetAmount

`func (o *SupplierInvoiceUpdate) HasTotalNetAmount() bool`

HasTotalNetAmount returns a boolean if a field has been set.

### SetTotalNetAmountNil

`func (o *SupplierInvoiceUpdate) SetTotalNetAmountNil(b bool)`

 SetTotalNetAmountNil sets the value for TotalNetAmount to be an explicit nil

### UnsetTotalNetAmount
`func (o *SupplierInvoiceUpdate) UnsetTotalNetAmount()`

UnsetTotalNetAmount ensures that no value is present for TotalNetAmount, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


