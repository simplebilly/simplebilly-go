# ProformaInvoiceUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConvertedAt** | Pointer to **NullableTime** |  | [optional] 
**ConvertedToInvoiceId** | Pointer to **NullableString** | Set when the proforma was converted into a real invoice. References the invoice entity. | [optional] 
**Currency** | Pointer to [**NullableCurrencyCode**](CurrencyCode.md) |  | [optional] 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**CustomerSnapshot** | Pointer to **interface{}** | Snapshot of the recipient at issue time (address, VAT id, …). | [optional] 
**IssueDate** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | Pointer to **NullableString** | Reference to the order/quote this proforma belongs to. | [optional] 
**PaymentDueDate** | Pointer to **NullableString** | Optional deadline the real invoice should carry after conversion. | [optional] 
**QuotationId** | Pointer to **NullableString** | References the quotation entity. | [optional] 
**Status** | Pointer to [**NullableProformaInvoiceStatus**](ProformaInvoiceStatus.md) | &#x60;draft&#x60; | &#x60;sent&#x60; | &#x60;converted&#x60;. | [optional] 
**Subtotal** | Pointer to **NullableString** |  | [optional] 
**TotalAmount** | Pointer to **NullableString** |  | [optional] 
**TotalTax** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProformaInvoiceUpdate

`func NewProformaInvoiceUpdate() *ProformaInvoiceUpdate`

NewProformaInvoiceUpdate instantiates a new ProformaInvoiceUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProformaInvoiceUpdateWithDefaults

`func NewProformaInvoiceUpdateWithDefaults() *ProformaInvoiceUpdate`

NewProformaInvoiceUpdateWithDefaults instantiates a new ProformaInvoiceUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConvertedAt

`func (o *ProformaInvoiceUpdate) GetConvertedAt() time.Time`

GetConvertedAt returns the ConvertedAt field if non-nil, zero value otherwise.

### GetConvertedAtOk

`func (o *ProformaInvoiceUpdate) GetConvertedAtOk() (*time.Time, bool)`

GetConvertedAtOk returns a tuple with the ConvertedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedAt

`func (o *ProformaInvoiceUpdate) SetConvertedAt(v time.Time)`

SetConvertedAt sets ConvertedAt field to given value.

### HasConvertedAt

`func (o *ProformaInvoiceUpdate) HasConvertedAt() bool`

HasConvertedAt returns a boolean if a field has been set.

### SetConvertedAtNil

`func (o *ProformaInvoiceUpdate) SetConvertedAtNil(b bool)`

 SetConvertedAtNil sets the value for ConvertedAt to be an explicit nil

### UnsetConvertedAt
`func (o *ProformaInvoiceUpdate) UnsetConvertedAt()`

UnsetConvertedAt ensures that no value is present for ConvertedAt, not even an explicit nil
### GetConvertedToInvoiceId

`func (o *ProformaInvoiceUpdate) GetConvertedToInvoiceId() string`

GetConvertedToInvoiceId returns the ConvertedToInvoiceId field if non-nil, zero value otherwise.

### GetConvertedToInvoiceIdOk

`func (o *ProformaInvoiceUpdate) GetConvertedToInvoiceIdOk() (*string, bool)`

GetConvertedToInvoiceIdOk returns a tuple with the ConvertedToInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedToInvoiceId

`func (o *ProformaInvoiceUpdate) SetConvertedToInvoiceId(v string)`

SetConvertedToInvoiceId sets ConvertedToInvoiceId field to given value.

### HasConvertedToInvoiceId

`func (o *ProformaInvoiceUpdate) HasConvertedToInvoiceId() bool`

HasConvertedToInvoiceId returns a boolean if a field has been set.

### SetConvertedToInvoiceIdNil

`func (o *ProformaInvoiceUpdate) SetConvertedToInvoiceIdNil(b bool)`

 SetConvertedToInvoiceIdNil sets the value for ConvertedToInvoiceId to be an explicit nil

### UnsetConvertedToInvoiceId
`func (o *ProformaInvoiceUpdate) UnsetConvertedToInvoiceId()`

UnsetConvertedToInvoiceId ensures that no value is present for ConvertedToInvoiceId, not even an explicit nil
### GetCurrency

`func (o *ProformaInvoiceUpdate) GetCurrency() CurrencyCode`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ProformaInvoiceUpdate) GetCurrencyOk() (*CurrencyCode, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ProformaInvoiceUpdate) SetCurrency(v CurrencyCode)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ProformaInvoiceUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *ProformaInvoiceUpdate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ProformaInvoiceUpdate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetCustomerId

`func (o *ProformaInvoiceUpdate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ProformaInvoiceUpdate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ProformaInvoiceUpdate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ProformaInvoiceUpdate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *ProformaInvoiceUpdate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *ProformaInvoiceUpdate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerSnapshot

`func (o *ProformaInvoiceUpdate) GetCustomerSnapshot() interface{}`

GetCustomerSnapshot returns the CustomerSnapshot field if non-nil, zero value otherwise.

### GetCustomerSnapshotOk

`func (o *ProformaInvoiceUpdate) GetCustomerSnapshotOk() (*interface{}, bool)`

GetCustomerSnapshotOk returns a tuple with the CustomerSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerSnapshot

`func (o *ProformaInvoiceUpdate) SetCustomerSnapshot(v interface{})`

SetCustomerSnapshot sets CustomerSnapshot field to given value.

### HasCustomerSnapshot

`func (o *ProformaInvoiceUpdate) HasCustomerSnapshot() bool`

HasCustomerSnapshot returns a boolean if a field has been set.

### SetCustomerSnapshotNil

`func (o *ProformaInvoiceUpdate) SetCustomerSnapshotNil(b bool)`

 SetCustomerSnapshotNil sets the value for CustomerSnapshot to be an explicit nil

### UnsetCustomerSnapshot
`func (o *ProformaInvoiceUpdate) UnsetCustomerSnapshot()`

UnsetCustomerSnapshot ensures that no value is present for CustomerSnapshot, not even an explicit nil
### GetIssueDate

`func (o *ProformaInvoiceUpdate) GetIssueDate() string`

GetIssueDate returns the IssueDate field if non-nil, zero value otherwise.

### GetIssueDateOk

`func (o *ProformaInvoiceUpdate) GetIssueDateOk() (*string, bool)`

GetIssueDateOk returns a tuple with the IssueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueDate

`func (o *ProformaInvoiceUpdate) SetIssueDate(v string)`

SetIssueDate sets IssueDate field to given value.

### HasIssueDate

`func (o *ProformaInvoiceUpdate) HasIssueDate() bool`

HasIssueDate returns a boolean if a field has been set.

### SetIssueDateNil

`func (o *ProformaInvoiceUpdate) SetIssueDateNil(b bool)`

 SetIssueDateNil sets the value for IssueDate to be an explicit nil

### UnsetIssueDate
`func (o *ProformaInvoiceUpdate) UnsetIssueDate()`

UnsetIssueDate ensures that no value is present for IssueDate, not even an explicit nil
### GetLineItems

`func (o *ProformaInvoiceUpdate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *ProformaInvoiceUpdate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *ProformaInvoiceUpdate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *ProformaInvoiceUpdate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *ProformaInvoiceUpdate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *ProformaInvoiceUpdate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *ProformaInvoiceUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ProformaInvoiceUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ProformaInvoiceUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ProformaInvoiceUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ProformaInvoiceUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ProformaInvoiceUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderNumber

`func (o *ProformaInvoiceUpdate) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ProformaInvoiceUpdate) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ProformaInvoiceUpdate) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *ProformaInvoiceUpdate) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *ProformaInvoiceUpdate) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *ProformaInvoiceUpdate) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetPaymentDueDate

`func (o *ProformaInvoiceUpdate) GetPaymentDueDate() string`

GetPaymentDueDate returns the PaymentDueDate field if non-nil, zero value otherwise.

### GetPaymentDueDateOk

`func (o *ProformaInvoiceUpdate) GetPaymentDueDateOk() (*string, bool)`

GetPaymentDueDateOk returns a tuple with the PaymentDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDueDate

`func (o *ProformaInvoiceUpdate) SetPaymentDueDate(v string)`

SetPaymentDueDate sets PaymentDueDate field to given value.

### HasPaymentDueDate

`func (o *ProformaInvoiceUpdate) HasPaymentDueDate() bool`

HasPaymentDueDate returns a boolean if a field has been set.

### SetPaymentDueDateNil

`func (o *ProformaInvoiceUpdate) SetPaymentDueDateNil(b bool)`

 SetPaymentDueDateNil sets the value for PaymentDueDate to be an explicit nil

### UnsetPaymentDueDate
`func (o *ProformaInvoiceUpdate) UnsetPaymentDueDate()`

UnsetPaymentDueDate ensures that no value is present for PaymentDueDate, not even an explicit nil
### GetQuotationId

`func (o *ProformaInvoiceUpdate) GetQuotationId() string`

GetQuotationId returns the QuotationId field if non-nil, zero value otherwise.

### GetQuotationIdOk

`func (o *ProformaInvoiceUpdate) GetQuotationIdOk() (*string, bool)`

GetQuotationIdOk returns a tuple with the QuotationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotationId

`func (o *ProformaInvoiceUpdate) SetQuotationId(v string)`

SetQuotationId sets QuotationId field to given value.

### HasQuotationId

`func (o *ProformaInvoiceUpdate) HasQuotationId() bool`

HasQuotationId returns a boolean if a field has been set.

### SetQuotationIdNil

`func (o *ProformaInvoiceUpdate) SetQuotationIdNil(b bool)`

 SetQuotationIdNil sets the value for QuotationId to be an explicit nil

### UnsetQuotationId
`func (o *ProformaInvoiceUpdate) UnsetQuotationId()`

UnsetQuotationId ensures that no value is present for QuotationId, not even an explicit nil
### GetStatus

`func (o *ProformaInvoiceUpdate) GetStatus() ProformaInvoiceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProformaInvoiceUpdate) GetStatusOk() (*ProformaInvoiceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProformaInvoiceUpdate) SetStatus(v ProformaInvoiceStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProformaInvoiceUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *ProformaInvoiceUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ProformaInvoiceUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSubtotal

`func (o *ProformaInvoiceUpdate) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *ProformaInvoiceUpdate) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *ProformaInvoiceUpdate) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.

### HasSubtotal

`func (o *ProformaInvoiceUpdate) HasSubtotal() bool`

HasSubtotal returns a boolean if a field has been set.

### SetSubtotalNil

`func (o *ProformaInvoiceUpdate) SetSubtotalNil(b bool)`

 SetSubtotalNil sets the value for Subtotal to be an explicit nil

### UnsetSubtotal
`func (o *ProformaInvoiceUpdate) UnsetSubtotal()`

UnsetSubtotal ensures that no value is present for Subtotal, not even an explicit nil
### GetTotalAmount

`func (o *ProformaInvoiceUpdate) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *ProformaInvoiceUpdate) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *ProformaInvoiceUpdate) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *ProformaInvoiceUpdate) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *ProformaInvoiceUpdate) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *ProformaInvoiceUpdate) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetTotalTax

`func (o *ProformaInvoiceUpdate) GetTotalTax() string`

GetTotalTax returns the TotalTax field if non-nil, zero value otherwise.

### GetTotalTaxOk

`func (o *ProformaInvoiceUpdate) GetTotalTaxOk() (*string, bool)`

GetTotalTaxOk returns a tuple with the TotalTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTax

`func (o *ProformaInvoiceUpdate) SetTotalTax(v string)`

SetTotalTax sets TotalTax field to given value.

### HasTotalTax

`func (o *ProformaInvoiceUpdate) HasTotalTax() bool`

HasTotalTax returns a boolean if a field has been set.

### SetTotalTaxNil

`func (o *ProformaInvoiceUpdate) SetTotalTaxNil(b bool)`

 SetTotalTaxNil sets the value for TotalTax to be an explicit nil

### UnsetTotalTax
`func (o *ProformaInvoiceUpdate) UnsetTotalTax()`

UnsetTotalTax ensures that no value is present for TotalTax, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


