# SupplierInvoiceCreate

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

### NewSupplierInvoiceCreate

`func NewSupplierInvoiceCreate(invoiceDate string, invoiceNumber string, lineItems interface{}, status SupplierInvoiceStatus, ) *SupplierInvoiceCreate`

NewSupplierInvoiceCreate instantiates a new SupplierInvoiceCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplierInvoiceCreateWithDefaults

`func NewSupplierInvoiceCreateWithDefaults() *SupplierInvoiceCreate`

NewSupplierInvoiceCreateWithDefaults instantiates a new SupplierInvoiceCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *SupplierInvoiceCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SupplierInvoiceCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SupplierInvoiceCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SupplierInvoiceCreate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetGoodsReceiptId

`func (o *SupplierInvoiceCreate) GetGoodsReceiptId() string`

GetGoodsReceiptId returns the GoodsReceiptId field if non-nil, zero value otherwise.

### GetGoodsReceiptIdOk

`func (o *SupplierInvoiceCreate) GetGoodsReceiptIdOk() (*string, bool)`

GetGoodsReceiptIdOk returns a tuple with the GoodsReceiptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoodsReceiptId

`func (o *SupplierInvoiceCreate) SetGoodsReceiptId(v string)`

SetGoodsReceiptId sets GoodsReceiptId field to given value.

### HasGoodsReceiptId

`func (o *SupplierInvoiceCreate) HasGoodsReceiptId() bool`

HasGoodsReceiptId returns a boolean if a field has been set.

### SetGoodsReceiptIdNil

`func (o *SupplierInvoiceCreate) SetGoodsReceiptIdNil(b bool)`

 SetGoodsReceiptIdNil sets the value for GoodsReceiptId to be an explicit nil

### UnsetGoodsReceiptId
`func (o *SupplierInvoiceCreate) UnsetGoodsReceiptId()`

UnsetGoodsReceiptId ensures that no value is present for GoodsReceiptId, not even an explicit nil
### GetInvoiceDate

`func (o *SupplierInvoiceCreate) GetInvoiceDate() string`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *SupplierInvoiceCreate) GetInvoiceDateOk() (*string, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *SupplierInvoiceCreate) SetInvoiceDate(v string)`

SetInvoiceDate sets InvoiceDate field to given value.


### GetInvoiceNumber

`func (o *SupplierInvoiceCreate) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *SupplierInvoiceCreate) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *SupplierInvoiceCreate) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### GetLineItems

`func (o *SupplierInvoiceCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *SupplierInvoiceCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *SupplierInvoiceCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *SupplierInvoiceCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *SupplierInvoiceCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *SupplierInvoiceCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SupplierInvoiceCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SupplierInvoiceCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SupplierInvoiceCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SupplierInvoiceCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SupplierInvoiceCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPurchaseOrderId

`func (o *SupplierInvoiceCreate) GetPurchaseOrderId() string`

GetPurchaseOrderId returns the PurchaseOrderId field if non-nil, zero value otherwise.

### GetPurchaseOrderIdOk

`func (o *SupplierInvoiceCreate) GetPurchaseOrderIdOk() (*string, bool)`

GetPurchaseOrderIdOk returns a tuple with the PurchaseOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrderId

`func (o *SupplierInvoiceCreate) SetPurchaseOrderId(v string)`

SetPurchaseOrderId sets PurchaseOrderId field to given value.

### HasPurchaseOrderId

`func (o *SupplierInvoiceCreate) HasPurchaseOrderId() bool`

HasPurchaseOrderId returns a boolean if a field has been set.

### SetPurchaseOrderIdNil

`func (o *SupplierInvoiceCreate) SetPurchaseOrderIdNil(b bool)`

 SetPurchaseOrderIdNil sets the value for PurchaseOrderId to be an explicit nil

### UnsetPurchaseOrderId
`func (o *SupplierInvoiceCreate) UnsetPurchaseOrderId()`

UnsetPurchaseOrderId ensures that no value is present for PurchaseOrderId, not even an explicit nil
### GetStatus

`func (o *SupplierInvoiceCreate) GetStatus() SupplierInvoiceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SupplierInvoiceCreate) GetStatusOk() (*SupplierInvoiceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SupplierInvoiceCreate) SetStatus(v SupplierInvoiceStatus)`

SetStatus sets Status field to given value.


### GetSupplierContactId

`func (o *SupplierInvoiceCreate) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *SupplierInvoiceCreate) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *SupplierInvoiceCreate) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *SupplierInvoiceCreate) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *SupplierInvoiceCreate) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *SupplierInvoiceCreate) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *SupplierInvoiceCreate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *SupplierInvoiceCreate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *SupplierInvoiceCreate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *SupplierInvoiceCreate) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *SupplierInvoiceCreate) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *SupplierInvoiceCreate) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil
### GetTotalGrossAmount

`func (o *SupplierInvoiceCreate) GetTotalGrossAmount() string`

GetTotalGrossAmount returns the TotalGrossAmount field if non-nil, zero value otherwise.

### GetTotalGrossAmountOk

`func (o *SupplierInvoiceCreate) GetTotalGrossAmountOk() (*string, bool)`

GetTotalGrossAmountOk returns a tuple with the TotalGrossAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGrossAmount

`func (o *SupplierInvoiceCreate) SetTotalGrossAmount(v string)`

SetTotalGrossAmount sets TotalGrossAmount field to given value.

### HasTotalGrossAmount

`func (o *SupplierInvoiceCreate) HasTotalGrossAmount() bool`

HasTotalGrossAmount returns a boolean if a field has been set.

### SetTotalGrossAmountNil

`func (o *SupplierInvoiceCreate) SetTotalGrossAmountNil(b bool)`

 SetTotalGrossAmountNil sets the value for TotalGrossAmount to be an explicit nil

### UnsetTotalGrossAmount
`func (o *SupplierInvoiceCreate) UnsetTotalGrossAmount()`

UnsetTotalGrossAmount ensures that no value is present for TotalGrossAmount, not even an explicit nil
### GetTotalNetAmount

`func (o *SupplierInvoiceCreate) GetTotalNetAmount() string`

GetTotalNetAmount returns the TotalNetAmount field if non-nil, zero value otherwise.

### GetTotalNetAmountOk

`func (o *SupplierInvoiceCreate) GetTotalNetAmountOk() (*string, bool)`

GetTotalNetAmountOk returns a tuple with the TotalNetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNetAmount

`func (o *SupplierInvoiceCreate) SetTotalNetAmount(v string)`

SetTotalNetAmount sets TotalNetAmount field to given value.

### HasTotalNetAmount

`func (o *SupplierInvoiceCreate) HasTotalNetAmount() bool`

HasTotalNetAmount returns a boolean if a field has been set.

### SetTotalNetAmountNil

`func (o *SupplierInvoiceCreate) SetTotalNetAmountNil(b bool)`

 SetTotalNetAmountNil sets the value for TotalNetAmount to be an explicit nil

### UnsetTotalNetAmount
`func (o *SupplierInvoiceCreate) UnsetTotalNetAmount()`

UnsetTotalNetAmount ensures that no value is present for TotalNetAmount, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


