# Quotation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **interface{}** |  | [optional] 
**ContactId** | Pointer to **NullableString** | References the contact entity. | [optional] 
**ContactName** | Pointer to **NullableString** |  | [optional] 
**Currency** | **string** |  | 
**ExpirationDate** | Pointer to **NullableString** |  | [optional] 
**Files** | Pointer to **interface{}** |  | [optional] 
**Introduction** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** |  | [optional] 
**PrecedingSalesVoucherId** | Pointer to **NullableString** | References the preceding sales voucher entity. | [optional] 
**PrecedingSalesVoucherType** | Pointer to [**NullablePrecedingSalesVoucherType**](PrecedingSalesVoucherType.md) |  | [optional] 
**QuotationNumber** | Pointer to **NullableString** |  | [optional] 
**Remark** | Pointer to **NullableString** |  | [optional] 
**Subtotal** | Pointer to **NullableString** |  | [optional] 
**TaxCondition** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**TotalAmount** | Pointer to **NullableString** |  | [optional] 
**TotalTax** | Pointer to **NullableString** |  | [optional] 
**VoucherDate** | **string** |  | 
**VoucherStatus** | [**VoucherStatus**](VoucherStatus.md) |  | 

## Methods

### NewQuotation

`func NewQuotation(currency string, voucherDate string, voucherStatus VoucherStatus, ) *Quotation`

NewQuotation instantiates a new Quotation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuotationWithDefaults

`func NewQuotationWithDefaults() *Quotation`

NewQuotationWithDefaults instantiates a new Quotation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *Quotation) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Quotation) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Quotation) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *Quotation) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *Quotation) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *Quotation) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetContactId

`func (o *Quotation) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *Quotation) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *Quotation) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *Quotation) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *Quotation) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *Quotation) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *Quotation) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *Quotation) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *Quotation) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *Quotation) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *Quotation) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *Quotation) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCurrency

`func (o *Quotation) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Quotation) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Quotation) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetExpirationDate

`func (o *Quotation) GetExpirationDate() string`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *Quotation) GetExpirationDateOk() (*string, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *Quotation) SetExpirationDate(v string)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *Quotation) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### SetExpirationDateNil

`func (o *Quotation) SetExpirationDateNil(b bool)`

 SetExpirationDateNil sets the value for ExpirationDate to be an explicit nil

### UnsetExpirationDate
`func (o *Quotation) UnsetExpirationDate()`

UnsetExpirationDate ensures that no value is present for ExpirationDate, not even an explicit nil
### GetFiles

`func (o *Quotation) GetFiles() interface{}`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *Quotation) GetFilesOk() (*interface{}, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *Quotation) SetFiles(v interface{})`

SetFiles sets Files field to given value.

### HasFiles

`func (o *Quotation) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### SetFilesNil

`func (o *Quotation) SetFilesNil(b bool)`

 SetFilesNil sets the value for Files to be an explicit nil

### UnsetFiles
`func (o *Quotation) UnsetFiles()`

UnsetFiles ensures that no value is present for Files, not even an explicit nil
### GetIntroduction

`func (o *Quotation) GetIntroduction() string`

GetIntroduction returns the Introduction field if non-nil, zero value otherwise.

### GetIntroductionOk

`func (o *Quotation) GetIntroductionOk() (*string, bool)`

GetIntroductionOk returns a tuple with the Introduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroduction

`func (o *Quotation) SetIntroduction(v string)`

SetIntroduction sets Introduction field to given value.

### HasIntroduction

`func (o *Quotation) HasIntroduction() bool`

HasIntroduction returns a boolean if a field has been set.

### SetIntroductionNil

`func (o *Quotation) SetIntroductionNil(b bool)`

 SetIntroductionNil sets the value for Introduction to be an explicit nil

### UnsetIntroduction
`func (o *Quotation) UnsetIntroduction()`

UnsetIntroduction ensures that no value is present for Introduction, not even an explicit nil
### GetLineItems

`func (o *Quotation) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *Quotation) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *Quotation) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *Quotation) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *Quotation) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *Quotation) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetPrecedingSalesVoucherId

`func (o *Quotation) GetPrecedingSalesVoucherId() string`

GetPrecedingSalesVoucherId returns the PrecedingSalesVoucherId field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherIdOk

`func (o *Quotation) GetPrecedingSalesVoucherIdOk() (*string, bool)`

GetPrecedingSalesVoucherIdOk returns a tuple with the PrecedingSalesVoucherId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherId

`func (o *Quotation) SetPrecedingSalesVoucherId(v string)`

SetPrecedingSalesVoucherId sets PrecedingSalesVoucherId field to given value.

### HasPrecedingSalesVoucherId

`func (o *Quotation) HasPrecedingSalesVoucherId() bool`

HasPrecedingSalesVoucherId returns a boolean if a field has been set.

### SetPrecedingSalesVoucherIdNil

`func (o *Quotation) SetPrecedingSalesVoucherIdNil(b bool)`

 SetPrecedingSalesVoucherIdNil sets the value for PrecedingSalesVoucherId to be an explicit nil

### UnsetPrecedingSalesVoucherId
`func (o *Quotation) UnsetPrecedingSalesVoucherId()`

UnsetPrecedingSalesVoucherId ensures that no value is present for PrecedingSalesVoucherId, not even an explicit nil
### GetPrecedingSalesVoucherType

`func (o *Quotation) GetPrecedingSalesVoucherType() PrecedingSalesVoucherType`

GetPrecedingSalesVoucherType returns the PrecedingSalesVoucherType field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherTypeOk

`func (o *Quotation) GetPrecedingSalesVoucherTypeOk() (*PrecedingSalesVoucherType, bool)`

GetPrecedingSalesVoucherTypeOk returns a tuple with the PrecedingSalesVoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherType

`func (o *Quotation) SetPrecedingSalesVoucherType(v PrecedingSalesVoucherType)`

SetPrecedingSalesVoucherType sets PrecedingSalesVoucherType field to given value.

### HasPrecedingSalesVoucherType

`func (o *Quotation) HasPrecedingSalesVoucherType() bool`

HasPrecedingSalesVoucherType returns a boolean if a field has been set.

### SetPrecedingSalesVoucherTypeNil

`func (o *Quotation) SetPrecedingSalesVoucherTypeNil(b bool)`

 SetPrecedingSalesVoucherTypeNil sets the value for PrecedingSalesVoucherType to be an explicit nil

### UnsetPrecedingSalesVoucherType
`func (o *Quotation) UnsetPrecedingSalesVoucherType()`

UnsetPrecedingSalesVoucherType ensures that no value is present for PrecedingSalesVoucherType, not even an explicit nil
### GetQuotationNumber

`func (o *Quotation) GetQuotationNumber() string`

GetQuotationNumber returns the QuotationNumber field if non-nil, zero value otherwise.

### GetQuotationNumberOk

`func (o *Quotation) GetQuotationNumberOk() (*string, bool)`

GetQuotationNumberOk returns a tuple with the QuotationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotationNumber

`func (o *Quotation) SetQuotationNumber(v string)`

SetQuotationNumber sets QuotationNumber field to given value.

### HasQuotationNumber

`func (o *Quotation) HasQuotationNumber() bool`

HasQuotationNumber returns a boolean if a field has been set.

### SetQuotationNumberNil

`func (o *Quotation) SetQuotationNumberNil(b bool)`

 SetQuotationNumberNil sets the value for QuotationNumber to be an explicit nil

### UnsetQuotationNumber
`func (o *Quotation) UnsetQuotationNumber()`

UnsetQuotationNumber ensures that no value is present for QuotationNumber, not even an explicit nil
### GetRemark

`func (o *Quotation) GetRemark() string`

GetRemark returns the Remark field if non-nil, zero value otherwise.

### GetRemarkOk

`func (o *Quotation) GetRemarkOk() (*string, bool)`

GetRemarkOk returns a tuple with the Remark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemark

`func (o *Quotation) SetRemark(v string)`

SetRemark sets Remark field to given value.

### HasRemark

`func (o *Quotation) HasRemark() bool`

HasRemark returns a boolean if a field has been set.

### SetRemarkNil

`func (o *Quotation) SetRemarkNil(b bool)`

 SetRemarkNil sets the value for Remark to be an explicit nil

### UnsetRemark
`func (o *Quotation) UnsetRemark()`

UnsetRemark ensures that no value is present for Remark, not even an explicit nil
### GetSubtotal

`func (o *Quotation) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *Quotation) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *Quotation) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.

### HasSubtotal

`func (o *Quotation) HasSubtotal() bool`

HasSubtotal returns a boolean if a field has been set.

### SetSubtotalNil

`func (o *Quotation) SetSubtotalNil(b bool)`

 SetSubtotalNil sets the value for Subtotal to be an explicit nil

### UnsetSubtotal
`func (o *Quotation) UnsetSubtotal()`

UnsetSubtotal ensures that no value is present for Subtotal, not even an explicit nil
### GetTaxCondition

`func (o *Quotation) GetTaxCondition() string`

GetTaxCondition returns the TaxCondition field if non-nil, zero value otherwise.

### GetTaxConditionOk

`func (o *Quotation) GetTaxConditionOk() (*string, bool)`

GetTaxConditionOk returns a tuple with the TaxCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCondition

`func (o *Quotation) SetTaxCondition(v string)`

SetTaxCondition sets TaxCondition field to given value.

### HasTaxCondition

`func (o *Quotation) HasTaxCondition() bool`

HasTaxCondition returns a boolean if a field has been set.

### SetTaxConditionNil

`func (o *Quotation) SetTaxConditionNil(b bool)`

 SetTaxConditionNil sets the value for TaxCondition to be an explicit nil

### UnsetTaxCondition
`func (o *Quotation) UnsetTaxCondition()`

UnsetTaxCondition ensures that no value is present for TaxCondition, not even an explicit nil
### GetTitle

`func (o *Quotation) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Quotation) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Quotation) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Quotation) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *Quotation) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *Quotation) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetTotalAmount

`func (o *Quotation) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *Quotation) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *Quotation) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *Quotation) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *Quotation) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *Quotation) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetTotalTax

`func (o *Quotation) GetTotalTax() string`

GetTotalTax returns the TotalTax field if non-nil, zero value otherwise.

### GetTotalTaxOk

`func (o *Quotation) GetTotalTaxOk() (*string, bool)`

GetTotalTaxOk returns a tuple with the TotalTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTax

`func (o *Quotation) SetTotalTax(v string)`

SetTotalTax sets TotalTax field to given value.

### HasTotalTax

`func (o *Quotation) HasTotalTax() bool`

HasTotalTax returns a boolean if a field has been set.

### SetTotalTaxNil

`func (o *Quotation) SetTotalTaxNil(b bool)`

 SetTotalTaxNil sets the value for TotalTax to be an explicit nil

### UnsetTotalTax
`func (o *Quotation) UnsetTotalTax()`

UnsetTotalTax ensures that no value is present for TotalTax, not even an explicit nil
### GetVoucherDate

`func (o *Quotation) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *Quotation) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *Quotation) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherStatus

`func (o *Quotation) GetVoucherStatus() VoucherStatus`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *Quotation) GetVoucherStatusOk() (*VoucherStatus, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *Quotation) SetVoucherStatus(v VoucherStatus)`

SetVoucherStatus sets VoucherStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


