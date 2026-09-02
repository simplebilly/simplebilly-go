# SupplierInvoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **string** |  | [optional] 
**GoodsReceiptId** | Pointer to **NullableString** | References the goods receipt entity. | [optional] 
**InvoiceDate** | **string** |  | 
**InvoiceNumber** | **string** |  | 
**LineItems** | **interface{}** | JSON array of &#x60;{product_id, name, quantity, unitPriceNet, taxRate}&#x60;. | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**PurchaseOrderId** | Pointer to **NullableString** | References the purchase order entity. | [optional] 
**Status** | [**SupplierInvoiceStatus**](SupplierInvoiceStatus.md) | One of: draft | matched | has_variances | posted | cancelled | 
**SupplierContactId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** |  | [optional] 
**TotalGrossAmount** | Pointer to **NullableString** |  | [optional] 
**TotalNetAmount** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSupplierInvoice

`func NewSupplierInvoice(invoiceDate string, invoiceNumber string, lineItems interface{}, status SupplierInvoiceStatus, ) *SupplierInvoice`

NewSupplierInvoice instantiates a new SupplierInvoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplierInvoiceWithDefaults

`func NewSupplierInvoiceWithDefaults() *SupplierInvoice`

NewSupplierInvoiceWithDefaults instantiates a new SupplierInvoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *SupplierInvoice) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SupplierInvoice) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SupplierInvoice) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SupplierInvoice) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetGoodsReceiptId

`func (o *SupplierInvoice) GetGoodsReceiptId() string`

GetGoodsReceiptId returns the GoodsReceiptId field if non-nil, zero value otherwise.

### GetGoodsReceiptIdOk

`func (o *SupplierInvoice) GetGoodsReceiptIdOk() (*string, bool)`

GetGoodsReceiptIdOk returns a tuple with the GoodsReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoodsReceiptId

`func (o *SupplierInvoice) SetGoodsReceiptId(v string)`

SetGoodsReceiptId sets GoodsReceiptId field to given value.

### HasGoodsReceiptId

`func (o *SupplierInvoice) HasGoodsReceiptId() bool`

HasGoodsReceiptId returns a boolean if a field has been set.

### SetGoodsReceiptIdNil

`func (o *SupplierInvoice) SetGoodsReceiptIdNil(b bool)`

 SetGoodsReceiptIdNil sets the value for GoodsReceiptId to be an explicit nil

### UnsetGoodsReceiptId
`func (o *SupplierInvoice) UnsetGoodsReceiptId()`

UnsetGoodsReceiptId ensures that no value is present for GoodsReceiptId, not even an explicit nil
### GetInvoiceDate

`func (o *SupplierInvoice) GetInvoiceDate() string`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *SupplierInvoice) GetInvoiceDateOk() (*string, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *SupplierInvoice) SetInvoiceDate(v string)`

SetInvoiceDate sets InvoiceDate field to given value.


### GetInvoiceNumber

`func (o *SupplierInvoice) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *SupplierInvoice) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *SupplierInvoice) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### GetLineItems

`func (o *SupplierInvoice) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *SupplierInvoice) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *SupplierInvoice) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *SupplierInvoice) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *SupplierInvoice) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *SupplierInvoice) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SupplierInvoice) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SupplierInvoice) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SupplierInvoice) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SupplierInvoice) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SupplierInvoice) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPurchaseOrderId

`func (o *SupplierInvoice) GetPurchaseOrderId() string`

GetPurchaseOrderId returns the PurchaseOrderId field if non-nil, zero value otherwise.

### GetPurchaseOrderIdOk

`func (o *SupplierInvoice) GetPurchaseOrderIdOk() (*string, bool)`

GetPurchaseOrderIdOk returns a tuple with the PurchaseOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrderId

`func (o *SupplierInvoice) SetPurchaseOrderId(v string)`

SetPurchaseOrderId sets PurchaseOrderId field to given value.

### HasPurchaseOrderId

`func (o *SupplierInvoice) HasPurchaseOrderId() bool`

HasPurchaseOrderId returns a boolean if a field has been set.

### SetPurchaseOrderIdNil

`func (o *SupplierInvoice) SetPurchaseOrderIdNil(b bool)`

 SetPurchaseOrderIdNil sets the value for PurchaseOrderId to be an explicit nil

### UnsetPurchaseOrderId
`func (o *SupplierInvoice) UnsetPurchaseOrderId()`

UnsetPurchaseOrderId ensures that no value is present for PurchaseOrderId, not even an explicit nil
### GetStatus

`func (o *SupplierInvoice) GetStatus() SupplierInvoiceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SupplierInvoice) GetStatusOk() (*SupplierInvoiceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SupplierInvoice) SetStatus(v SupplierInvoiceStatus)`

SetStatus sets Status field to given value.


### GetSupplierContactId

`func (o *SupplierInvoice) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *SupplierInvoice) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *SupplierInvoice) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *SupplierInvoice) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *SupplierInvoice) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *SupplierInvoice) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *SupplierInvoice) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *SupplierInvoice) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *SupplierInvoice) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *SupplierInvoice) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *SupplierInvoice) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *SupplierInvoice) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil
### GetTotalGrossAmount

`func (o *SupplierInvoice) GetTotalGrossAmount() string`

GetTotalGrossAmount returns the TotalGrossAmount field if non-nil, zero value otherwise.

### GetTotalGrossAmountOk

`func (o *SupplierInvoice) GetTotalGrossAmountOk() (*string, bool)`

GetTotalGrossAmountOk returns a tuple with the TotalGrossAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGrossAmount

`func (o *SupplierInvoice) SetTotalGrossAmount(v string)`

SetTotalGrossAmount sets TotalGrossAmount field to given value.

### HasTotalGrossAmount

`func (o *SupplierInvoice) HasTotalGrossAmount() bool`

HasTotalGrossAmount returns a boolean if a field has been set.

### SetTotalGrossAmountNil

`func (o *SupplierInvoice) SetTotalGrossAmountNil(b bool)`

 SetTotalGrossAmountNil sets the value for TotalGrossAmount to be an explicit nil

### UnsetTotalGrossAmount
`func (o *SupplierInvoice) UnsetTotalGrossAmount()`

UnsetTotalGrossAmount ensures that no value is present for TotalGrossAmount, not even an explicit nil
### GetTotalNetAmount

`func (o *SupplierInvoice) GetTotalNetAmount() string`

GetTotalNetAmount returns the TotalNetAmount field if non-nil, zero value otherwise.

### GetTotalNetAmountOk

`func (o *SupplierInvoice) GetTotalNetAmountOk() (*string, bool)`

GetTotalNetAmountOk returns a tuple with the TotalNetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNetAmount

`func (o *SupplierInvoice) SetTotalNetAmount(v string)`

SetTotalNetAmount sets TotalNetAmount field to given value.

### HasTotalNetAmount

`func (o *SupplierInvoice) HasTotalNetAmount() bool`

HasTotalNetAmount returns a boolean if a field has been set.

### SetTotalNetAmountNil

`func (o *SupplierInvoice) SetTotalNetAmountNil(b bool)`

 SetTotalNetAmountNil sets the value for TotalNetAmount to be an explicit nil

### UnsetTotalNetAmount
`func (o *SupplierInvoice) UnsetTotalNetAmount()`

UnsetTotalNetAmount ensures that no value is present for TotalNetAmount, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


