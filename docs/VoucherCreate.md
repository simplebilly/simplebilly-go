# VoucherCreate

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

### NewVoucherCreate

`func NewVoucherCreate(currency string, voucherDate string, voucherStatus VoucherStatus, voucherType VoucherType, ) *VoucherCreate`

NewVoucherCreate instantiates a new VoucherCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoucherCreateWithDefaults

`func NewVoucherCreateWithDefaults() *VoucherCreate`

NewVoucherCreateWithDefaults instantiates a new VoucherCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategoryId

`func (o *VoucherCreate) GetCategoryId() string`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *VoucherCreate) GetCategoryIdOk() (*string, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *VoucherCreate) SetCategoryId(v string)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *VoucherCreate) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### SetCategoryIdNil

`func (o *VoucherCreate) SetCategoryIdNil(b bool)`

 SetCategoryIdNil sets the value for CategoryId to be an explicit nil

### UnsetCategoryId
`func (o *VoucherCreate) UnsetCategoryId()`

UnsetCategoryId ensures that no value is present for CategoryId, not even an explicit nil
### GetContactId

`func (o *VoucherCreate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *VoucherCreate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *VoucherCreate) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *VoucherCreate) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *VoucherCreate) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *VoucherCreate) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *VoucherCreate) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *VoucherCreate) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *VoucherCreate) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *VoucherCreate) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *VoucherCreate) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *VoucherCreate) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCurrency

`func (o *VoucherCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *VoucherCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *VoucherCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *VoucherCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *VoucherCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *VoucherCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *VoucherCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *VoucherCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *VoucherCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetFileAttachments

`func (o *VoucherCreate) GetFileAttachments() interface{}`

GetFileAttachments returns the FileAttachments field if non-nil, zero value otherwise.

### GetFileAttachmentsOk

`func (o *VoucherCreate) GetFileAttachmentsOk() (*interface{}, bool)`

GetFileAttachmentsOk returns a tuple with the FileAttachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileAttachments

`func (o *VoucherCreate) SetFileAttachments(v interface{})`

SetFileAttachments sets FileAttachments field to given value.

### HasFileAttachments

`func (o *VoucherCreate) HasFileAttachments() bool`

HasFileAttachments returns a boolean if a field has been set.

### SetFileAttachmentsNil

`func (o *VoucherCreate) SetFileAttachmentsNil(b bool)`

 SetFileAttachmentsNil sets the value for FileAttachments to be an explicit nil

### UnsetFileAttachments
`func (o *VoucherCreate) UnsetFileAttachments()`

UnsetFileAttachments ensures that no value is present for FileAttachments, not even an explicit nil
### GetLineItems

`func (o *VoucherCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *VoucherCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *VoucherCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *VoucherCreate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *VoucherCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *VoucherCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetMetadata

`func (o *VoucherCreate) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *VoucherCreate) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *VoucherCreate) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *VoucherCreate) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *VoucherCreate) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *VoucherCreate) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetNotes

`func (o *VoucherCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *VoucherCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *VoucherCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *VoucherCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *VoucherCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *VoucherCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOpenAmount

`func (o *VoucherCreate) GetOpenAmount() string`

GetOpenAmount returns the OpenAmount field if non-nil, zero value otherwise.

### GetOpenAmountOk

`func (o *VoucherCreate) GetOpenAmountOk() (*string, bool)`

GetOpenAmountOk returns a tuple with the OpenAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenAmount

`func (o *VoucherCreate) SetOpenAmount(v string)`

SetOpenAmount sets OpenAmount field to given value.

### HasOpenAmount

`func (o *VoucherCreate) HasOpenAmount() bool`

HasOpenAmount returns a boolean if a field has been set.

### SetOpenAmountNil

`func (o *VoucherCreate) SetOpenAmountNil(b bool)`

 SetOpenAmountNil sets the value for OpenAmount to be an explicit nil

### UnsetOpenAmount
`func (o *VoucherCreate) UnsetOpenAmount()`

UnsetOpenAmount ensures that no value is present for OpenAmount, not even an explicit nil
### GetPaidDate

`func (o *VoucherCreate) GetPaidDate() string`

GetPaidDate returns the PaidDate field if non-nil, zero value otherwise.

### GetPaidDateOk

`func (o *VoucherCreate) GetPaidDateOk() (*string, bool)`

GetPaidDateOk returns a tuple with the PaidDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidDate

`func (o *VoucherCreate) SetPaidDate(v string)`

SetPaidDate sets PaidDate field to given value.

### HasPaidDate

`func (o *VoucherCreate) HasPaidDate() bool`

HasPaidDate returns a boolean if a field has been set.

### SetPaidDateNil

`func (o *VoucherCreate) SetPaidDateNil(b bool)`

 SetPaidDateNil sets the value for PaidDate to be an explicit nil

### UnsetPaidDate
`func (o *VoucherCreate) UnsetPaidDate()`

UnsetPaidDate ensures that no value is present for PaidDate, not even an explicit nil
### GetPaymentStatus

`func (o *VoucherCreate) GetPaymentStatus() PaymentStatus`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *VoucherCreate) GetPaymentStatusOk() (*PaymentStatus, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *VoucherCreate) SetPaymentStatus(v PaymentStatus)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *VoucherCreate) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### SetPaymentStatusNil

`func (o *VoucherCreate) SetPaymentStatusNil(b bool)`

 SetPaymentStatusNil sets the value for PaymentStatus to be an explicit nil

### UnsetPaymentStatus
`func (o *VoucherCreate) UnsetPaymentStatus()`

UnsetPaymentStatus ensures that no value is present for PaymentStatus, not even an explicit nil
### GetTaxAmounts

`func (o *VoucherCreate) GetTaxAmounts() interface{}`

GetTaxAmounts returns the TaxAmounts field if non-nil, zero value otherwise.

### GetTaxAmountsOk

`func (o *VoucherCreate) GetTaxAmountsOk() (*interface{}, bool)`

GetTaxAmountsOk returns a tuple with the TaxAmounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmounts

`func (o *VoucherCreate) SetTaxAmounts(v interface{})`

SetTaxAmounts sets TaxAmounts field to given value.

### HasTaxAmounts

`func (o *VoucherCreate) HasTaxAmounts() bool`

HasTaxAmounts returns a boolean if a field has been set.

### SetTaxAmountsNil

`func (o *VoucherCreate) SetTaxAmountsNil(b bool)`

 SetTaxAmountsNil sets the value for TaxAmounts to be an explicit nil

### UnsetTaxAmounts
`func (o *VoucherCreate) UnsetTaxAmounts()`

UnsetTaxAmounts ensures that no value is present for TaxAmounts, not even an explicit nil
### GetTaxCondition

`func (o *VoucherCreate) GetTaxCondition() string`

GetTaxCondition returns the TaxCondition field if non-nil, zero value otherwise.

### GetTaxConditionOk

`func (o *VoucherCreate) GetTaxConditionOk() (*string, bool)`

GetTaxConditionOk returns a tuple with the TaxCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCondition

`func (o *VoucherCreate) SetTaxCondition(v string)`

SetTaxCondition sets TaxCondition field to given value.

### HasTaxCondition

`func (o *VoucherCreate) HasTaxCondition() bool`

HasTaxCondition returns a boolean if a field has been set.

### SetTaxConditionNil

`func (o *VoucherCreate) SetTaxConditionNil(b bool)`

 SetTaxConditionNil sets the value for TaxCondition to be an explicit nil

### UnsetTaxCondition
`func (o *VoucherCreate) UnsetTaxCondition()`

UnsetTaxCondition ensures that no value is present for TaxCondition, not even an explicit nil
### GetTotalGrossAmount

`func (o *VoucherCreate) GetTotalGrossAmount() string`

GetTotalGrossAmount returns the TotalGrossAmount field if non-nil, zero value otherwise.

### GetTotalGrossAmountOk

`func (o *VoucherCreate) GetTotalGrossAmountOk() (*string, bool)`

GetTotalGrossAmountOk returns a tuple with the TotalGrossAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGrossAmount

`func (o *VoucherCreate) SetTotalGrossAmount(v string)`

SetTotalGrossAmount sets TotalGrossAmount field to given value.

### HasTotalGrossAmount

`func (o *VoucherCreate) HasTotalGrossAmount() bool`

HasTotalGrossAmount returns a boolean if a field has been set.

### SetTotalGrossAmountNil

`func (o *VoucherCreate) SetTotalGrossAmountNil(b bool)`

 SetTotalGrossAmountNil sets the value for TotalGrossAmount to be an explicit nil

### UnsetTotalGrossAmount
`func (o *VoucherCreate) UnsetTotalGrossAmount()`

UnsetTotalGrossAmount ensures that no value is present for TotalGrossAmount, not even an explicit nil
### GetTotalNetAmount

`func (o *VoucherCreate) GetTotalNetAmount() string`

GetTotalNetAmount returns the TotalNetAmount field if non-nil, zero value otherwise.

### GetTotalNetAmountOk

`func (o *VoucherCreate) GetTotalNetAmountOk() (*string, bool)`

GetTotalNetAmountOk returns a tuple with the TotalNetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNetAmount

`func (o *VoucherCreate) SetTotalNetAmount(v string)`

SetTotalNetAmount sets TotalNetAmount field to given value.

### HasTotalNetAmount

`func (o *VoucherCreate) HasTotalNetAmount() bool`

HasTotalNetAmount returns a boolean if a field has been set.

### SetTotalNetAmountNil

`func (o *VoucherCreate) SetTotalNetAmountNil(b bool)`

 SetTotalNetAmountNil sets the value for TotalNetAmount to be an explicit nil

### UnsetTotalNetAmount
`func (o *VoucherCreate) UnsetTotalNetAmount()`

UnsetTotalNetAmount ensures that no value is present for TotalNetAmount, not even an explicit nil
### GetVoucherDate

`func (o *VoucherCreate) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *VoucherCreate) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *VoucherCreate) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherNumber

`func (o *VoucherCreate) GetVoucherNumber() string`

GetVoucherNumber returns the VoucherNumber field if non-nil, zero value otherwise.

### GetVoucherNumberOk

`func (o *VoucherCreate) GetVoucherNumberOk() (*string, bool)`

GetVoucherNumberOk returns a tuple with the VoucherNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherNumber

`func (o *VoucherCreate) SetVoucherNumber(v string)`

SetVoucherNumber sets VoucherNumber field to given value.

### HasVoucherNumber

`func (o *VoucherCreate) HasVoucherNumber() bool`

HasVoucherNumber returns a boolean if a field has been set.

### SetVoucherNumberNil

`func (o *VoucherCreate) SetVoucherNumberNil(b bool)`

 SetVoucherNumberNil sets the value for VoucherNumber to be an explicit nil

### UnsetVoucherNumber
`func (o *VoucherCreate) UnsetVoucherNumber()`

UnsetVoucherNumber ensures that no value is present for VoucherNumber, not even an explicit nil
### GetVoucherStatus

`func (o *VoucherCreate) GetVoucherStatus() VoucherStatus`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *VoucherCreate) GetVoucherStatusOk() (*VoucherStatus, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *VoucherCreate) SetVoucherStatus(v VoucherStatus)`

SetVoucherStatus sets VoucherStatus field to given value.


### GetVoucherType

`func (o *VoucherCreate) GetVoucherType() VoucherType`

GetVoucherType returns the VoucherType field if non-nil, zero value otherwise.

### GetVoucherTypeOk

`func (o *VoucherCreate) GetVoucherTypeOk() (*VoucherType, bool)`

GetVoucherTypeOk returns a tuple with the VoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherType

`func (o *VoucherCreate) SetVoucherType(v VoucherType)`

SetVoucherType sets VoucherType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


