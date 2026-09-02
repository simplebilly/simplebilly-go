# ProformaInvoiceCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConvertedAt** | Pointer to **NullableTime** |  | [optional] 
**ConvertedToInvoiceId** | Pointer to **NullableString** | Set when the proforma was converted into a real invoice. References the invoice entity. | [optional] 
**Currency** | [**CurrencyCode**](CurrencyCode.md) |  | 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**CustomerSnapshot** | Pointer to **interface{}** | Snapshot of the recipient at issue time (address, VAT id, …). | [optional] 
**IssueDate** | **string** |  | 
**LineItems** | **interface{}** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | Pointer to **NullableString** | Reference to the order/quote this proforma belongs to. | [optional] 
**PaymentDueDate** | Pointer to **NullableString** | Optional deadline the real invoice should carry after conversion. | [optional] 
**QuotationId** | Pointer to **NullableString** | References the quotation entity. | [optional] 
**Status** | [**ProformaInvoiceStatus**](ProformaInvoiceStatus.md) | &#x60;draft&#x60; | &#x60;sent&#x60; | &#x60;converted&#x60;. | 
**Subtotal** | **string** |  | 
**TotalAmount** | **string** |  | 
**TotalTax** | **string** |  | 

## Methods

### NewProformaInvoiceCreate

`func NewProformaInvoiceCreate(currency CurrencyCode, issueDate string, lineItems interface{}, status ProformaInvoiceStatus, subtotal string, totalAmount string, totalTax string, ) *ProformaInvoiceCreate`

NewProformaInvoiceCreate instantiates a new ProformaInvoiceCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProformaInvoiceCreateWithDefaults

`func NewProformaInvoiceCreateWithDefaults() *ProformaInvoiceCreate`

NewProformaInvoiceCreateWithDefaults instantiates a new ProformaInvoiceCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConvertedAt

`func (o *ProformaInvoiceCreate) GetConvertedAt() time.Time`

GetConvertedAt returns the ConvertedAt field if non-nil, zero value otherwise.

### GetConvertedAtOk

`func (o *ProformaInvoiceCreate) GetConvertedAtOk() (*time.Time, bool)`

GetConvertedAtOk returns a tuple with the ConvertedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedAt

`func (o *ProformaInvoiceCreate) SetConvertedAt(v time.Time)`

SetConvertedAt sets ConvertedAt field to given value.

### HasConvertedAt

`func (o *ProformaInvoiceCreate) HasConvertedAt() bool`

HasConvertedAt returns a boolean if a field has been set.

### SetConvertedAtNil

`func (o *ProformaInvoiceCreate) SetConvertedAtNil(b bool)`

 SetConvertedAtNil sets the value for ConvertedAt to be an explicit nil

### UnsetConvertedAt
`func (o *ProformaInvoiceCreate) UnsetConvertedAt()`

UnsetConvertedAt ensures that no value is present for ConvertedAt, not even an explicit nil
### GetConvertedToInvoiceId

`func (o *ProformaInvoiceCreate) GetConvertedToInvoiceId() string`

GetConvertedToInvoiceId returns the ConvertedToInvoiceId field if non-nil, zero value otherwise.

### GetConvertedToInvoiceIdOk

`func (o *ProformaInvoiceCreate) GetConvertedToInvoiceIdOk() (*string, bool)`

GetConvertedToInvoiceIdOk returns a tuple with the ConvertedToInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedToInvoiceId

`func (o *ProformaInvoiceCreate) SetConvertedToInvoiceId(v string)`

SetConvertedToInvoiceId sets ConvertedToInvoiceId field to given value.

### HasConvertedToInvoiceId

`func (o *ProformaInvoiceCreate) HasConvertedToInvoiceId() bool`

HasConvertedToInvoiceId returns a boolean if a field has been set.

### SetConvertedToInvoiceIdNil

`func (o *ProformaInvoiceCreate) SetConvertedToInvoiceIdNil(b bool)`

 SetConvertedToInvoiceIdNil sets the value for ConvertedToInvoiceId to be an explicit nil

### UnsetConvertedToInvoiceId
`func (o *ProformaInvoiceCreate) UnsetConvertedToInvoiceId()`

UnsetConvertedToInvoiceId ensures that no value is present for ConvertedToInvoiceId, not even an explicit nil
### GetCurrency

`func (o *ProformaInvoiceCreate) GetCurrency() CurrencyCode`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ProformaInvoiceCreate) GetCurrencyOk() (*CurrencyCode, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ProformaInvoiceCreate) SetCurrency(v CurrencyCode)`

SetCurrency sets Currency field to given value.


### GetCustomerId

`func (o *ProformaInvoiceCreate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ProformaInvoiceCreate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ProformaInvoiceCreate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ProformaInvoiceCreate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *ProformaInvoiceCreate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *ProformaInvoiceCreate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerSnapshot

`func (o *ProformaInvoiceCreate) GetCustomerSnapshot() interface{}`

GetCustomerSnapshot returns the CustomerSnapshot field if non-nil, zero value otherwise.

### GetCustomerSnapshotOk

`func (o *ProformaInvoiceCreate) GetCustomerSnapshotOk() (*interface{}, bool)`

GetCustomerSnapshotOk returns a tuple with the CustomerSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerSnapshot

`func (o *ProformaInvoiceCreate) SetCustomerSnapshot(v interface{})`

SetCustomerSnapshot sets CustomerSnapshot field to given value.

### HasCustomerSnapshot

`func (o *ProformaInvoiceCreate) HasCustomerSnapshot() bool`

HasCustomerSnapshot returns a boolean if a field has been set.

### SetCustomerSnapshotNil

`func (o *ProformaInvoiceCreate) SetCustomerSnapshotNil(b bool)`

 SetCustomerSnapshotNil sets the value for CustomerSnapshot to be an explicit nil

### UnsetCustomerSnapshot
`func (o *ProformaInvoiceCreate) UnsetCustomerSnapshot()`

UnsetCustomerSnapshot ensures that no value is present for CustomerSnapshot, not even an explicit nil
### GetIssueDate

`func (o *ProformaInvoiceCreate) GetIssueDate() string`

GetIssueDate returns the IssueDate field if non-nil, zero value otherwise.

### GetIssueDateOk

`func (o *ProformaInvoiceCreate) GetIssueDateOk() (*string, bool)`

GetIssueDateOk returns a tuple with the IssueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueDate

`func (o *ProformaInvoiceCreate) SetIssueDate(v string)`

SetIssueDate sets IssueDate field to given value.


### GetLineItems

`func (o *ProformaInvoiceCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *ProformaInvoiceCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *ProformaInvoiceCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *ProformaInvoiceCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *ProformaInvoiceCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *ProformaInvoiceCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ProformaInvoiceCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ProformaInvoiceCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ProformaInvoiceCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ProformaInvoiceCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ProformaInvoiceCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderNumber

`func (o *ProformaInvoiceCreate) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ProformaInvoiceCreate) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ProformaInvoiceCreate) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *ProformaInvoiceCreate) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *ProformaInvoiceCreate) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *ProformaInvoiceCreate) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetPaymentDueDate

`func (o *ProformaInvoiceCreate) GetPaymentDueDate() string`

GetPaymentDueDate returns the PaymentDueDate field if non-nil, zero value otherwise.

### GetPaymentDueDateOk

`func (o *ProformaInvoiceCreate) GetPaymentDueDateOk() (*string, bool)`

GetPaymentDueDateOk returns a tuple with the PaymentDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDueDate

`func (o *ProformaInvoiceCreate) SetPaymentDueDate(v string)`

SetPaymentDueDate sets PaymentDueDate field to given value.

### HasPaymentDueDate

`func (o *ProformaInvoiceCreate) HasPaymentDueDate() bool`

HasPaymentDueDate returns a boolean if a field has been set.

### SetPaymentDueDateNil

`func (o *ProformaInvoiceCreate) SetPaymentDueDateNil(b bool)`

 SetPaymentDueDateNil sets the value for PaymentDueDate to be an explicit nil

### UnsetPaymentDueDate
`func (o *ProformaInvoiceCreate) UnsetPaymentDueDate()`

UnsetPaymentDueDate ensures that no value is present for PaymentDueDate, not even an explicit nil
### GetQuotationId

`func (o *ProformaInvoiceCreate) GetQuotationId() string`

GetQuotationId returns the QuotationId field if non-nil, zero value otherwise.

### GetQuotationIdOk

`func (o *ProformaInvoiceCreate) GetQuotationIdOk() (*string, bool)`

GetQuotationIdOk returns a tuple with the QuotationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotationId

`func (o *ProformaInvoiceCreate) SetQuotationId(v string)`

SetQuotationId sets QuotationId field to given value.

### HasQuotationId

`func (o *ProformaInvoiceCreate) HasQuotationId() bool`

HasQuotationId returns a boolean if a field has been set.

### SetQuotationIdNil

`func (o *ProformaInvoiceCreate) SetQuotationIdNil(b bool)`

 SetQuotationIdNil sets the value for QuotationId to be an explicit nil

### UnsetQuotationId
`func (o *ProformaInvoiceCreate) UnsetQuotationId()`

UnsetQuotationId ensures that no value is present for QuotationId, not even an explicit nil
### GetStatus

`func (o *ProformaInvoiceCreate) GetStatus() ProformaInvoiceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProformaInvoiceCreate) GetStatusOk() (*ProformaInvoiceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProformaInvoiceCreate) SetStatus(v ProformaInvoiceStatus)`

SetStatus sets Status field to given value.


### GetSubtotal

`func (o *ProformaInvoiceCreate) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *ProformaInvoiceCreate) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *ProformaInvoiceCreate) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.


### GetTotalAmount

`func (o *ProformaInvoiceCreate) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *ProformaInvoiceCreate) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *ProformaInvoiceCreate) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetTotalTax

`func (o *ProformaInvoiceCreate) GetTotalTax() string`

GetTotalTax returns the TotalTax field if non-nil, zero value otherwise.

### GetTotalTaxOk

`func (o *ProformaInvoiceCreate) GetTotalTaxOk() (*string, bool)`

GetTotalTaxOk returns a tuple with the TotalTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTax

`func (o *ProformaInvoiceCreate) SetTotalTax(v string)`

SetTotalTax sets TotalTax field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


