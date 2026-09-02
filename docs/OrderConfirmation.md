# OrderConfirmation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **interface{}** |  | [optional] 
**ConfirmationNumber** | Pointer to **NullableString** |  | [optional] 
**ContactId** | Pointer to **NullableString** | References the contact entity. | [optional] 
**ContactName** | Pointer to **NullableString** |  | [optional] 
**Currency** | **string** |  | 
**Files** | Pointer to **interface{}** |  | [optional] 
**Introduction** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** |  | [optional] 
**PrecedingSalesVoucherId** | Pointer to **NullableString** | References the preceding sales voucher entity. | [optional] 
**PrecedingSalesVoucherType** | Pointer to [**NullablePrecedingSalesVoucherType**](PrecedingSalesVoucherType.md) |  | [optional] 
**Remark** | Pointer to **NullableString** |  | [optional] 
**Subtotal** | Pointer to **NullableString** |  | [optional] 
**TaxCondition** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**TotalAmount** | Pointer to **NullableString** |  | [optional] 
**TotalTax** | Pointer to **NullableString** |  | [optional] 
**VoucherDate** | **string** |  | 
**VoucherStatus** | [**VoucherStatus**](VoucherStatus.md) |  | 

## Methods

### NewOrderConfirmation

`func NewOrderConfirmation(currency string, voucherDate string, voucherStatus VoucherStatus, ) *OrderConfirmation`

NewOrderConfirmation instantiates a new OrderConfirmation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderConfirmationWithDefaults

`func NewOrderConfirmationWithDefaults() *OrderConfirmation`

NewOrderConfirmationWithDefaults instantiates a new OrderConfirmation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *OrderConfirmation) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *OrderConfirmation) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *OrderConfirmation) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *OrderConfirmation) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *OrderConfirmation) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *OrderConfirmation) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetConfirmationNumber

`func (o *OrderConfirmation) GetConfirmationNumber() string`

GetConfirmationNumber returns the ConfirmationNumber field if non-nil, zero value otherwise.

### GetConfirmationNumberOk

`func (o *OrderConfirmation) GetConfirmationNumberOk() (*string, bool)`

GetConfirmationNumberOk returns a tuple with the ConfirmationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmationNumber

`func (o *OrderConfirmation) SetConfirmationNumber(v string)`

SetConfirmationNumber sets ConfirmationNumber field to given value.

### HasConfirmationNumber

`func (o *OrderConfirmation) HasConfirmationNumber() bool`

HasConfirmationNumber returns a boolean if a field has been set.

### SetConfirmationNumberNil

`func (o *OrderConfirmation) SetConfirmationNumberNil(b bool)`

 SetConfirmationNumberNil sets the value for ConfirmationNumber to be an explicit nil

### UnsetConfirmationNumber
`func (o *OrderConfirmation) UnsetConfirmationNumber()`

UnsetConfirmationNumber ensures that no value is present for ConfirmationNumber, not even an explicit nil
### GetContactId

`func (o *OrderConfirmation) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *OrderConfirmation) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *OrderConfirmation) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *OrderConfirmation) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *OrderConfirmation) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *OrderConfirmation) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *OrderConfirmation) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *OrderConfirmation) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *OrderConfirmation) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *OrderConfirmation) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *OrderConfirmation) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *OrderConfirmation) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCurrency

`func (o *OrderConfirmation) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *OrderConfirmation) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *OrderConfirmation) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetFiles

`func (o *OrderConfirmation) GetFiles() interface{}`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *OrderConfirmation) GetFilesOk() (*interface{}, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *OrderConfirmation) SetFiles(v interface{})`

SetFiles sets Files field to given value.

### HasFiles

`func (o *OrderConfirmation) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### SetFilesNil

`func (o *OrderConfirmation) SetFilesNil(b bool)`

 SetFilesNil sets the value for Files to be an explicit nil

### UnsetFiles
`func (o *OrderConfirmation) UnsetFiles()`

UnsetFiles ensures that no value is present for Files, not even an explicit nil
### GetIntroduction

`func (o *OrderConfirmation) GetIntroduction() string`

GetIntroduction returns the Introduction field if non-nil, zero value otherwise.

### GetIntroductionOk

`func (o *OrderConfirmation) GetIntroductionOk() (*string, bool)`

GetIntroductionOk returns a tuple with the Introduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroduction

`func (o *OrderConfirmation) SetIntroduction(v string)`

SetIntroduction sets Introduction field to given value.

### HasIntroduction

`func (o *OrderConfirmation) HasIntroduction() bool`

HasIntroduction returns a boolean if a field has been set.

### SetIntroductionNil

`func (o *OrderConfirmation) SetIntroductionNil(b bool)`

 SetIntroductionNil sets the value for Introduction to be an explicit nil

### UnsetIntroduction
`func (o *OrderConfirmation) UnsetIntroduction()`

UnsetIntroduction ensures that no value is present for Introduction, not even an explicit nil
### GetLineItems

`func (o *OrderConfirmation) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *OrderConfirmation) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *OrderConfirmation) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *OrderConfirmation) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *OrderConfirmation) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *OrderConfirmation) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetPrecedingSalesVoucherId

`func (o *OrderConfirmation) GetPrecedingSalesVoucherId() string`

GetPrecedingSalesVoucherId returns the PrecedingSalesVoucherId field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherIdOk

`func (o *OrderConfirmation) GetPrecedingSalesVoucherIdOk() (*string, bool)`

GetPrecedingSalesVoucherIdOk returns a tuple with the PrecedingSalesVoucherId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherId

`func (o *OrderConfirmation) SetPrecedingSalesVoucherId(v string)`

SetPrecedingSalesVoucherId sets PrecedingSalesVoucherId field to given value.

### HasPrecedingSalesVoucherId

`func (o *OrderConfirmation) HasPrecedingSalesVoucherId() bool`

HasPrecedingSalesVoucherId returns a boolean if a field has been set.

### SetPrecedingSalesVoucherIdNil

`func (o *OrderConfirmation) SetPrecedingSalesVoucherIdNil(b bool)`

 SetPrecedingSalesVoucherIdNil sets the value for PrecedingSalesVoucherId to be an explicit nil

### UnsetPrecedingSalesVoucherId
`func (o *OrderConfirmation) UnsetPrecedingSalesVoucherId()`

UnsetPrecedingSalesVoucherId ensures that no value is present for PrecedingSalesVoucherId, not even an explicit nil
### GetPrecedingSalesVoucherType

`func (o *OrderConfirmation) GetPrecedingSalesVoucherType() PrecedingSalesVoucherType`

GetPrecedingSalesVoucherType returns the PrecedingSalesVoucherType field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherTypeOk

`func (o *OrderConfirmation) GetPrecedingSalesVoucherTypeOk() (*PrecedingSalesVoucherType, bool)`

GetPrecedingSalesVoucherTypeOk returns a tuple with the PrecedingSalesVoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherType

`func (o *OrderConfirmation) SetPrecedingSalesVoucherType(v PrecedingSalesVoucherType)`

SetPrecedingSalesVoucherType sets PrecedingSalesVoucherType field to given value.

### HasPrecedingSalesVoucherType

`func (o *OrderConfirmation) HasPrecedingSalesVoucherType() bool`

HasPrecedingSalesVoucherType returns a boolean if a field has been set.

### SetPrecedingSalesVoucherTypeNil

`func (o *OrderConfirmation) SetPrecedingSalesVoucherTypeNil(b bool)`

 SetPrecedingSalesVoucherTypeNil sets the value for PrecedingSalesVoucherType to be an explicit nil

### UnsetPrecedingSalesVoucherType
`func (o *OrderConfirmation) UnsetPrecedingSalesVoucherType()`

UnsetPrecedingSalesVoucherType ensures that no value is present for PrecedingSalesVoucherType, not even an explicit nil
### GetRemark

`func (o *OrderConfirmation) GetRemark() string`

GetRemark returns the Remark field if non-nil, zero value otherwise.

### GetRemarkOk

`func (o *OrderConfirmation) GetRemarkOk() (*string, bool)`

GetRemarkOk returns a tuple with the Remark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemark

`func (o *OrderConfirmation) SetRemark(v string)`

SetRemark sets Remark field to given value.

### HasRemark

`func (o *OrderConfirmation) HasRemark() bool`

HasRemark returns a boolean if a field has been set.

### SetRemarkNil

`func (o *OrderConfirmation) SetRemarkNil(b bool)`

 SetRemarkNil sets the value for Remark to be an explicit nil

### UnsetRemark
`func (o *OrderConfirmation) UnsetRemark()`

UnsetRemark ensures that no value is present for Remark, not even an explicit nil
### GetSubtotal

`func (o *OrderConfirmation) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *OrderConfirmation) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *OrderConfirmation) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.

### HasSubtotal

`func (o *OrderConfirmation) HasSubtotal() bool`

HasSubtotal returns a boolean if a field has been set.

### SetSubtotalNil

`func (o *OrderConfirmation) SetSubtotalNil(b bool)`

 SetSubtotalNil sets the value for Subtotal to be an explicit nil

### UnsetSubtotal
`func (o *OrderConfirmation) UnsetSubtotal()`

UnsetSubtotal ensures that no value is present for Subtotal, not even an explicit nil
### GetTaxCondition

`func (o *OrderConfirmation) GetTaxCondition() string`

GetTaxCondition returns the TaxCondition field if non-nil, zero value otherwise.

### GetTaxConditionOk

`func (o *OrderConfirmation) GetTaxConditionOk() (*string, bool)`

GetTaxConditionOk returns a tuple with the TaxCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCondition

`func (o *OrderConfirmation) SetTaxCondition(v string)`

SetTaxCondition sets TaxCondition field to given value.

### HasTaxCondition

`func (o *OrderConfirmation) HasTaxCondition() bool`

HasTaxCondition returns a boolean if a field has been set.

### SetTaxConditionNil

`func (o *OrderConfirmation) SetTaxConditionNil(b bool)`

 SetTaxConditionNil sets the value for TaxCondition to be an explicit nil

### UnsetTaxCondition
`func (o *OrderConfirmation) UnsetTaxCondition()`

UnsetTaxCondition ensures that no value is present for TaxCondition, not even an explicit nil
### GetTitle

`func (o *OrderConfirmation) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *OrderConfirmation) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *OrderConfirmation) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *OrderConfirmation) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *OrderConfirmation) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *OrderConfirmation) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetTotalAmount

`func (o *OrderConfirmation) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *OrderConfirmation) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *OrderConfirmation) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *OrderConfirmation) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *OrderConfirmation) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *OrderConfirmation) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetTotalTax

`func (o *OrderConfirmation) GetTotalTax() string`

GetTotalTax returns the TotalTax field if non-nil, zero value otherwise.

### GetTotalTaxOk

`func (o *OrderConfirmation) GetTotalTaxOk() (*string, bool)`

GetTotalTaxOk returns a tuple with the TotalTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTax

`func (o *OrderConfirmation) SetTotalTax(v string)`

SetTotalTax sets TotalTax field to given value.

### HasTotalTax

`func (o *OrderConfirmation) HasTotalTax() bool`

HasTotalTax returns a boolean if a field has been set.

### SetTotalTaxNil

`func (o *OrderConfirmation) SetTotalTaxNil(b bool)`

 SetTotalTaxNil sets the value for TotalTax to be an explicit nil

### UnsetTotalTax
`func (o *OrderConfirmation) UnsetTotalTax()`

UnsetTotalTax ensures that no value is present for TotalTax, not even an explicit nil
### GetVoucherDate

`func (o *OrderConfirmation) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *OrderConfirmation) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *OrderConfirmation) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherStatus

`func (o *OrderConfirmation) GetVoucherStatus() VoucherStatus`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *OrderConfirmation) GetVoucherStatusOk() (*VoucherStatus, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *OrderConfirmation) SetVoucherStatus(v VoucherStatus)`

SetVoucherStatus sets VoucherStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


