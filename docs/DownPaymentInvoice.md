# DownPaymentInvoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactId** | Pointer to **NullableString** |  | [optional] 
**ContactName** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **string** |  | [readonly] 
**Currency** | **string** |  | 
**Id** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**PaidAmount** | **string** |  | 
**TotalAmount** | **string** |  | 
**VoucherDate** | **string** |  | 
**VoucherNumber** | Pointer to **NullableString** |  | [optional] 
**VoucherStatus** | **string** |  | 

## Methods

### NewDownPaymentInvoice

`func NewDownPaymentInvoice(createdAt string, currency string, id string, paidAmount string, totalAmount string, voucherDate string, voucherStatus string, ) *DownPaymentInvoice`

NewDownPaymentInvoice instantiates a new DownPaymentInvoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDownPaymentInvoiceWithDefaults

`func NewDownPaymentInvoiceWithDefaults() *DownPaymentInvoice`

NewDownPaymentInvoiceWithDefaults instantiates a new DownPaymentInvoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactId

`func (o *DownPaymentInvoice) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *DownPaymentInvoice) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *DownPaymentInvoice) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *DownPaymentInvoice) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *DownPaymentInvoice) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *DownPaymentInvoice) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *DownPaymentInvoice) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *DownPaymentInvoice) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *DownPaymentInvoice) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *DownPaymentInvoice) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *DownPaymentInvoice) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *DownPaymentInvoice) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCreatedAt

`func (o *DownPaymentInvoice) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DownPaymentInvoice) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DownPaymentInvoice) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrency

`func (o *DownPaymentInvoice) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DownPaymentInvoice) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DownPaymentInvoice) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetId

`func (o *DownPaymentInvoice) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DownPaymentInvoice) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DownPaymentInvoice) SetId(v string)`

SetId sets Id field to given value.


### GetNotes

`func (o *DownPaymentInvoice) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *DownPaymentInvoice) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *DownPaymentInvoice) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *DownPaymentInvoice) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *DownPaymentInvoice) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *DownPaymentInvoice) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPaidAmount

`func (o *DownPaymentInvoice) GetPaidAmount() string`

GetPaidAmount returns the PaidAmount field if non-nil, zero value otherwise.

### GetPaidAmountOk

`func (o *DownPaymentInvoice) GetPaidAmountOk() (*string, bool)`

GetPaidAmountOk returns a tuple with the PaidAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAmount

`func (o *DownPaymentInvoice) SetPaidAmount(v string)`

SetPaidAmount sets PaidAmount field to given value.


### GetTotalAmount

`func (o *DownPaymentInvoice) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *DownPaymentInvoice) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *DownPaymentInvoice) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetVoucherDate

`func (o *DownPaymentInvoice) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *DownPaymentInvoice) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *DownPaymentInvoice) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherNumber

`func (o *DownPaymentInvoice) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *DownPaymentInvoice) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *DownPaymentInvoice) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *DownPaymentInvoice) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### SetVoucherNumberNil

`func (o *DownPaymentInvoice) SetVoucherNumberNil(b bool)`

 SetVoucherNumberNil sets the value for VoucherNumber to be an explicit nil

### UnsetVoucherNumber
`func (o *DownPaymentInvoice) UnsetVoucherNumber()`

UnsetVoucherNumber ensures that no value is present for VoucherNumber, not even an explicit nil
### GetVoucherStatus

`func (o *DownPaymentInvoice) GetVoucherStatus() string`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *DownPaymentInvoice) GetVoucherStatusOk() (*string, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *DownPaymentInvoice) SetVoucherStatus(v string)`

SetVoucherStatus sets VoucherStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


