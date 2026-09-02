# Voucher

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CategoryId** | Pointer to **NullableString** |  | [optional] 
**ContactId** | Pointer to **NullableString** | References the contact entity. | [optional] 
**ContactName** | Pointer to **NullableString** |  | [optional] 
**Currency** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**FileAttachments** | Pointer to **interface{}** |  | [optional] 
**LineItems** | Pointer to **interface{}** |  | [optional] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OpenAmount** | Pointer to **NullableString** |  | [optional] 
**PaidDate** | Pointer to **NullableString** |  | [optional] 
**PaymentStatus** | Pointer to [**NullablePaymentStatus**](PaymentStatus.md) |  | [optional] 
**TaxAmounts** | Pointer to **interface{}** |  | [optional] 
**TaxCondition** | Pointer to **NullableString** |  | [optional] 
**TotalGrossAmount** | Pointer to **NullableString** |  | [optional] 
**TotalNetAmount** | Pointer to **NullableString** |  | [optional] 
**VoucherDate** | **string** |  | 
**VoucherNumber** | Pointer to **NullableString** |  | [optional] 
**VoucherStatus** | [**VoucherStatus**](VoucherStatus.md) |  | 
**VoucherType** | [**VoucherType**](VoucherType.md) |  | 

## Methods

### NewVoucher

`func NewVoucher(currency string, voucherDate string, voucherStatus VoucherStatus, voucherType VoucherType, ) *Voucher`

NewVoucher instantiates a new Voucher object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoucherWithDefaults

`func NewVoucherWithDefaults() *Voucher`

NewVoucherWithDefaults instantiates a new Voucher object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategoryId

`func (o *Voucher) GetCategoryId() string`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *Voucher) GetCategoryIdOk() (*string, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *Voucher) SetCategoryId(v string)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *Voucher) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### SetCategoryIdNil

`func (o *Voucher) SetCategoryIdNil(b bool)`

 SetCategoryIdNil sets the value for CategoryId to be an explicit nil

### UnsetCategoryId
`func (o *Voucher) UnsetCategoryId()`

UnsetCategoryId ensures that no value is present for CategoryId, not even an explicit nil
### GetContactId

`func (o *Voucher) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *Voucher) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *Voucher) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *Voucher) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *Voucher) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *Voucher) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *Voucher) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *Voucher) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *Voucher) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *Voucher) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *Voucher) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *Voucher) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCurrency

`func (o *Voucher) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Voucher) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Voucher) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *Voucher) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Voucher) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Voucher) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Voucher) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Voucher) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Voucher) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetFileAttachments

`func (o *Voucher) GetFileAttachments() interface{}`

GetFileAttachments returns the FileAttachments field if non-nil, zero value otherwise.

### GetFileAttachmentsOk

`func (o *Voucher) GetFileAttachmentsOk() (*interface{}, bool)`

GetFileAttachmentsOk returns a tuple with the FileAttachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileAttachments

`func (o *Voucher) SetFileAttachments(v interface{})`

SetFileAttachments sets FileAttachments field to given value.

### HasFileAttachments

`func (o *Voucher) HasFileAttachments() bool`

HasFileAttachments returns a boolean if a field has been set.

### SetFileAttachmentsNil

`func (o *Voucher) SetFileAttachmentsNil(b bool)`

 SetFileAttachmentsNil sets the value for FileAttachments to be an explicit nil

### UnsetFileAttachments
`func (o *Voucher) UnsetFileAttachments()`

UnsetFileAttachments ensures that no value is present for FileAttachments, not even an explicit nil
### GetLineItems

`func (o *Voucher) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *Voucher) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *Voucher) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *Voucher) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *Voucher) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *Voucher) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetMetadata

`func (o *Voucher) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Voucher) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Voucher) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *Voucher) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *Voucher) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *Voucher) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetNotes

`func (o *Voucher) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Voucher) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Voucher) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Voucher) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *Voucher) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *Voucher) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOpenAmount

`func (o *Voucher) GetOpenAmount() string`

GetOpenAmount returns the OpenAmount field if non-nil, zero value otherwise.

### GetOpenAmountOk

`func (o *Voucher) GetOpenAmountOk() (*string, bool)`

GetOpenAmountOk returns a tuple with the OpenAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenAmount

`func (o *Voucher) SetOpenAmount(v string)`

SetOpenAmount sets OpenAmount field to given value.

### HasOpenAmount

`func (o *Voucher) HasOpenAmount() bool`

HasOpenAmount returns a boolean if a field has been set.

### SetOpenAmountNil

`func (o *Voucher) SetOpenAmountNil(b bool)`

 SetOpenAmountNil sets the value for OpenAmount to be an explicit nil

### UnsetOpenAmount
`func (o *Voucher) UnsetOpenAmount()`

UnsetOpenAmount ensures that no value is present for OpenAmount, not even an explicit nil
### GetPaidDate

`func (o *Voucher) GetPaidDate() string`

GetPaidDate returns the PaidDate field if non-nil, zero value otherwise.

### GetPaidDateOk

`func (o *Voucher) GetPaidDateOk() (*string, bool)`

GetPaidDateOk returns a tuple with the PaidDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidDate

`func (o *Voucher) SetPaidDate(v string)`

SetPaidDate sets PaidDate field to given value.

### HasPaidDate

`func (o *Voucher) HasPaidDate() bool`

HasPaidDate returns a boolean if a field has been set.

### SetPaidDateNil

`func (o *Voucher) SetPaidDateNil(b bool)`

 SetPaidDateNil sets the value for PaidDate to be an explicit nil

### UnsetPaidDate
`func (o *Voucher) UnsetPaidDate()`

UnsetPaidDate ensures that no value is present for PaidDate, not even an explicit nil
### GetPaymentStatus

`func (o *Voucher) GetPaymentStatus() PaymentStatus`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *Voucher) GetPaymentStatusOk() (*PaymentStatus, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *Voucher) SetPaymentStatus(v PaymentStatus)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *Voucher) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### SetPaymentStatusNil

`func (o *Voucher) SetPaymentStatusNil(b bool)`

 SetPaymentStatusNil sets the value for PaymentStatus to be an explicit nil

### UnsetPaymentStatus
`func (o *Voucher) UnsetPaymentStatus()`

UnsetPaymentStatus ensures that no value is present for PaymentStatus, not even an explicit nil
### GetTaxAmounts

`func (o *Voucher) GetTaxAmounts() interface{}`

GetTaxAmounts returns the TaxAmounts field if non-nil, zero value otherwise.

### GetTaxAmountsOk

`func (o *Voucher) GetTaxAmountsOk() (*interface{}, bool)`

GetTaxAmountsOk returns a tuple with the TaxAmounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmounts

`func (o *Voucher) SetTaxAmounts(v interface{})`

SetTaxAmounts sets TaxAmounts field to given value.

### HasTaxAmounts

`func (o *Voucher) HasTaxAmounts() bool`

HasTaxAmounts returns a boolean if a field has been set.

### SetTaxAmountsNil

`func (o *Voucher) SetTaxAmountsNil(b bool)`

 SetTaxAmountsNil sets the value for TaxAmounts to be an explicit nil

### UnsetTaxAmounts
`func (o *Voucher) UnsetTaxAmounts()`

UnsetTaxAmounts ensures that no value is present for TaxAmounts, not even an explicit nil
### GetTaxCondition

`func (o *Voucher) GetTaxCondition() string`

GetTaxCondition returns the TaxCondition field if non-nil, zero value otherwise.

### GetTaxConditionOk

`func (o *Voucher) GetTaxConditionOk() (*string, bool)`

GetTaxConditionOk returns a tuple with the TaxCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCondition

`func (o *Voucher) SetTaxCondition(v string)`

SetTaxCondition sets TaxCondition field to given value.

### HasTaxCondition

`func (o *Voucher) HasTaxCondition() bool`

HasTaxCondition returns a boolean if a field has been set.

### SetTaxConditionNil

`func (o *Voucher) SetTaxConditionNil(b bool)`

 SetTaxConditionNil sets the value for TaxCondition to be an explicit nil

### UnsetTaxCondition
`func (o *Voucher) UnsetTaxCondition()`

UnsetTaxCondition ensures that no value is present for TaxCondition, not even an explicit nil
### GetTotalGrossAmount

`func (o *Voucher) GetTotalGrossAmount() string`

GetTotalGrossAmount returns the TotalGrossAmount field if non-nil, zero value otherwise.

### GetTotalGrossAmountOk

`func (o *Voucher) GetTotalGrossAmountOk() (*string, bool)`

GetTotalGrossAmountOk returns a tuple with the TotalGrossAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGrossAmount

`func (o *Voucher) SetTotalGrossAmount(v string)`

SetTotalGrossAmount sets TotalGrossAmount field to given value.

### HasTotalGrossAmount

`func (o *Voucher) HasTotalGrossAmount() bool`

HasTotalGrossAmount returns a boolean if a field has been set.

### SetTotalGrossAmountNil

`func (o *Voucher) SetTotalGrossAmountNil(b bool)`

 SetTotalGrossAmountNil sets the value for TotalGrossAmount to be an explicit nil

### UnsetTotalGrossAmount
`func (o *Voucher) UnsetTotalGrossAmount()`

UnsetTotalGrossAmount ensures that no value is present for TotalGrossAmount, not even an explicit nil
### GetTotalNetAmount

`func (o *Voucher) GetTotalNetAmount() string`

GetTotalNetAmount returns the TotalNetAmount field if non-nil, zero value otherwise.

### GetTotalNetAmountOk

`func (o *Voucher) GetTotalNetAmountOk() (*string, bool)`

GetTotalNetAmountOk returns a tuple with the TotalNetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNetAmount

`func (o *Voucher) SetTotalNetAmount(v string)`

SetTotalNetAmount sets TotalNetAmount field to given value.

### HasTotalNetAmount

`func (o *Voucher) HasTotalNetAmount() bool`

HasTotalNetAmount returns a boolean if a field has been set.

### SetTotalNetAmountNil

`func (o *Voucher) SetTotalNetAmountNil(b bool)`

 SetTotalNetAmountNil sets the value for TotalNetAmount to be an explicit nil

### UnsetTotalNetAmount
`func (o *Voucher) UnsetTotalNetAmount()`

UnsetTotalNetAmount ensures that no value is present for TotalNetAmount, not even an explicit nil
### GetVoucherDate

`func (o *Voucher) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *Voucher) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *Voucher) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherNumber

`func (o *Voucher) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *Voucher) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *Voucher) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *Voucher) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### SetVoucherNumberNil

`func (o *Voucher) SetVoucherNumberNil(b bool)`

 SetVoucherNumberNil sets the value for VoucherNumber to be an explicit nil

### UnsetVoucherNumber
`func (o *Voucher) UnsetVoucherNumber()`

UnsetVoucherNumber ensures that no value is present for VoucherNumber, not even an explicit nil
### GetVoucherStatus

`func (o *Voucher) GetVoucherStatus() VoucherStatus`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *Voucher) GetVoucherStatusOk() (*VoucherStatus, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *Voucher) SetVoucherStatus(v VoucherStatus)`

SetVoucherStatus sets VoucherStatus field to given value.


### GetVoucherType

`func (o *Voucher) GetVoucherType() VoucherType`

GetVoucherType returns the VoucherType field if non-nil, zero value otherwise.

### GetVoucherTypeOk

`func (o *Voucher) GetVoucherTypeOk() (*VoucherType, bool)`

GetVoucherTypeOk returns a tuple with the VoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherType

`func (o *Voucher) SetVoucherType(v VoucherType)`

SetVoucherType sets VoucherType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


