# QuotationCreate

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
**TaxCondition** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**VoucherDate** | **string** |  | 
**VoucherStatus** | [**VoucherStatus**](VoucherStatus.md) |  | 

## Methods

### NewQuotationCreate

`func NewQuotationCreate(currency string, voucherDate string, voucherStatus VoucherStatus, ) *QuotationCreate`

NewQuotationCreate instantiates a new QuotationCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuotationCreateWithDefaults

`func NewQuotationCreateWithDefaults() *QuotationCreate`

NewQuotationCreateWithDefaults instantiates a new QuotationCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *QuotationCreate) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *QuotationCreate) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *QuotationCreate) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *QuotationCreate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *QuotationCreate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *QuotationCreate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetContactId

`func (o *QuotationCreate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *QuotationCreate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *QuotationCreate) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *QuotationCreate) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *QuotationCreate) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *QuotationCreate) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *QuotationCreate) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *QuotationCreate) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *QuotationCreate) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *QuotationCreate) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *QuotationCreate) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *QuotationCreate) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCurrency

`func (o *QuotationCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *QuotationCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *QuotationCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetExpirationDate

`func (o *QuotationCreate) GetExpirationDate() string`

GetExpirationDate returns the ExpirationDate field if non-nil, zero value otherwise.

### GetExpirationDateOk

`func (o *QuotationCreate) GetExpirationDateOk() (*string, bool)`

GetExpirationDateOk returns a tuple with the ExpirationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDate

`func (o *QuotationCreate) SetExpirationDate(v string)`

SetExpirationDate sets ExpirationDate field to given value.

### HasExpirationDate

`func (o *QuotationCreate) HasExpirationDate() bool`

HasExpirationDate returns a boolean if a field has been set.

### SetExpirationDateNil

`func (o *QuotationCreate) SetExpirationDateNil(b bool)`

 SetExpirationDateNil sets the value for ExpirationDate to be an explicit nil

### UnsetExpirationDate
`func (o *QuotationCreate) UnsetExpirationDate()`

UnsetExpirationDate ensures that no value is present for ExpirationDate, not even an explicit nil
### GetFiles

`func (o *QuotationCreate) GetFiles() interface{}`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *QuotationCreate) GetFilesOk() (*interface{}, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *QuotationCreate) SetFiles(v interface{})`

SetFiles sets Files field to given value.

### HasFiles

`func (o *QuotationCreate) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### SetFilesNil

`func (o *QuotationCreate) SetFilesNil(b bool)`

 SetFilesNil sets the value for Files to be an explicit nil

### UnsetFiles
`func (o *QuotationCreate) UnsetFiles()`

UnsetFiles ensures that no value is present for Files, not even an explicit nil
### GetIntroduction

`func (o *QuotationCreate) GetIntroduction() string`

GetIntroduction returns the Introduction field if non-nil, zero value otherwise.

### GetIntroductionOk

`func (o *QuotationCreate) GetIntroductionOk() (*string, bool)`

GetIntroductionOk returns a tuple with the Introduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroduction

`func (o *QuotationCreate) SetIntroduction(v string)`

SetIntroduction sets Introduction field to given value.

### HasIntroduction

`func (o *QuotationCreate) HasIntroduction() bool`

HasIntroduction returns a boolean if a field has been set.

### SetIntroductionNil

`func (o *QuotationCreate) SetIntroductionNil(b bool)`

 SetIntroductionNil sets the value for Introduction to be an explicit nil

### UnsetIntroduction
`func (o *QuotationCreate) UnsetIntroduction()`

UnsetIntroduction ensures that no value is present for Introduction, not even an explicit nil
### GetLineItems

`func (o *QuotationCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *QuotationCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *QuotationCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *QuotationCreate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *QuotationCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *QuotationCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetPrecedingSalesVoucherId

`func (o *QuotationCreate) GetPrecedingSalesVoucherId() string`

GetPrecedingSalesVoucherId returns the PrecedingSalesVoucherId field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherIdOk

`func (o *QuotationCreate) GetPrecedingSalesVoucherIdOk() (*string, bool)`

GetPrecedingSalesVoucherIdOk returns a tuple with the PrecedingSalesVoucherId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherId

`func (o *QuotationCreate) SetPrecedingSalesVoucherId(v string)`

SetPrecedingSalesVoucherId sets PrecedingSalesVoucherId field to given value.

### HasPrecedingSalesVoucherId

`func (o *QuotationCreate) HasPrecedingSalesVoucherId() bool`

HasPrecedingSalesVoucherId returns a boolean if a field has been set.

### SetPrecedingSalesVoucherIdNil

`func (o *QuotationCreate) SetPrecedingSalesVoucherIdNil(b bool)`

 SetPrecedingSalesVoucherIdNil sets the value for PrecedingSalesVoucherId to be an explicit nil

### UnsetPrecedingSalesVoucherId
`func (o *QuotationCreate) UnsetPrecedingSalesVoucherId()`

UnsetPrecedingSalesVoucherId ensures that no value is present for PrecedingSalesVoucherId, not even an explicit nil
### GetPrecedingSalesVoucherType

`func (o *QuotationCreate) GetPrecedingSalesVoucherType() PrecedingSalesVoucherType`

GetPrecedingSalesVoucherType returns the PrecedingSalesVoucherType field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherTypeOk

`func (o *QuotationCreate) GetPrecedingSalesVoucherTypeOk() (*PrecedingSalesVoucherType, bool)`

GetPrecedingSalesVoucherTypeOk returns a tuple with the PrecedingSalesVoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherType

`func (o *QuotationCreate) SetPrecedingSalesVoucherType(v PrecedingSalesVoucherType)`

SetPrecedingSalesVoucherType sets PrecedingSalesVoucherType field to given value.

### HasPrecedingSalesVoucherType

`func (o *QuotationCreate) HasPrecedingSalesVoucherType() bool`

HasPrecedingSalesVoucherType returns a boolean if a field has been set.

### SetPrecedingSalesVoucherTypeNil

`func (o *QuotationCreate) SetPrecedingSalesVoucherTypeNil(b bool)`

 SetPrecedingSalesVoucherTypeNil sets the value for PrecedingSalesVoucherType to be an explicit nil

### UnsetPrecedingSalesVoucherType
`func (o *QuotationCreate) UnsetPrecedingSalesVoucherType()`

UnsetPrecedingSalesVoucherType ensures that no value is present for PrecedingSalesVoucherType, not even an explicit nil
### GetQuotationNumber

`func (o *QuotationCreate) GetQuotationNumber() string`

GetQuotationNumber returns the QuotationNumber field if non-nil, zero value otherwise.

### GetQuotationNumberOk

`func (o *QuotationCreate) GetQuotationNumberOk() (*string, bool)`

GetQuotationNumberOk returns a tuple with the QuotationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotationNumber

`func (o *QuotationCreate) SetQuotationNumber(v string)`

SetQuotationNumber sets QuotationNumber field to given value.

### HasQuotationNumber

`func (o *QuotationCreate) HasQuotationNumber() bool`

HasQuotationNumber returns a boolean if a field has been set.

### SetQuotationNumberNil

`func (o *QuotationCreate) SetQuotationNumberNil(b bool)`

 SetQuotationNumberNil sets the value for QuotationNumber to be an explicit nil

### UnsetQuotationNumber
`func (o *QuotationCreate) UnsetQuotationNumber()`

UnsetQuotationNumber ensures that no value is present for QuotationNumber, not even an explicit nil
### GetRemark

`func (o *QuotationCreate) GetRemark() string`

GetRemark returns the Remark field if non-nil, zero value otherwise.

### GetRemarkOk

`func (o *QuotationCreate) GetRemarkOk() (*string, bool)`

GetRemarkOk returns a tuple with the Remark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemark

`func (o *QuotationCreate) SetRemark(v string)`

SetRemark sets Remark field to given value.

### HasRemark

`func (o *QuotationCreate) HasRemark() bool`

HasRemark returns a boolean if a field has been set.

### SetRemarkNil

`func (o *QuotationCreate) SetRemarkNil(b bool)`

 SetRemarkNil sets the value for Remark to be an explicit nil

### UnsetRemark
`func (o *QuotationCreate) UnsetRemark()`

UnsetRemark ensures that no value is present for Remark, not even an explicit nil
### GetTaxCondition

`func (o *QuotationCreate) GetTaxCondition() string`

GetTaxCondition returns the TaxCondition field if non-nil, zero value otherwise.

### GetTaxConditionOk

`func (o *QuotationCreate) GetTaxConditionOk() (*string, bool)`

GetTaxConditionOk returns a tuple with the TaxCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCondition

`func (o *QuotationCreate) SetTaxCondition(v string)`

SetTaxCondition sets TaxCondition field to given value.

### HasTaxCondition

`func (o *QuotationCreate) HasTaxCondition() bool`

HasTaxCondition returns a boolean if a field has been set.

### SetTaxConditionNil

`func (o *QuotationCreate) SetTaxConditionNil(b bool)`

 SetTaxConditionNil sets the value for TaxCondition to be an explicit nil

### UnsetTaxCondition
`func (o *QuotationCreate) UnsetTaxCondition()`

UnsetTaxCondition ensures that no value is present for TaxCondition, not even an explicit nil
### GetTitle

`func (o *QuotationCreate) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *QuotationCreate) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *QuotationCreate) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *QuotationCreate) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *QuotationCreate) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *QuotationCreate) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetVoucherDate

`func (o *QuotationCreate) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *QuotationCreate) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *QuotationCreate) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherStatus

`func (o *QuotationCreate) GetVoucherStatus() VoucherStatus`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *QuotationCreate) GetVoucherStatusOk() (*VoucherStatus, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *QuotationCreate) SetVoucherStatus(v VoucherStatus)`

SetVoucherStatus sets VoucherStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


