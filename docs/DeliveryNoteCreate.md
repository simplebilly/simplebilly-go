# DeliveryNoteCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **interface{}** |  | [optional] 
**ContactId** | Pointer to **NullableString** | References the contact entity. | [optional] 
**ContactName** | Pointer to **NullableString** |  | [optional] 
**Currency** | **string** |  | 
**DeliveryDate** | Pointer to **NullableString** |  | [optional] 
**DeliveryNoteNumber** | Pointer to **NullableString** |  | [optional] 
**Files** | Pointer to **interface{}** |  | [optional] 
**Introduction** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** |  | [optional] 
**PrecedingSalesVoucherId** | Pointer to **NullableString** | References the preceding sales voucher entity. | [optional] 
**PrecedingSalesVoucherType** | Pointer to [**NullablePrecedingSalesVoucherType**](PrecedingSalesVoucherType.md) |  | [optional] 
**Remark** | Pointer to **NullableString** |  | [optional] 
**ShippingDate** | Pointer to **NullableString** |  | [optional] 
**ShippingMethod** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**VoucherDate** | **string** |  | 
**VoucherStatus** | [**VoucherStatus**](VoucherStatus.md) |  | 

## Methods

### NewDeliveryNoteCreate

`func NewDeliveryNoteCreate(currency string, voucherDate string, voucherStatus VoucherStatus, ) *DeliveryNoteCreate`

NewDeliveryNoteCreate instantiates a new DeliveryNoteCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliveryNoteCreateWithDefaults

`func NewDeliveryNoteCreateWithDefaults() *DeliveryNoteCreate`

NewDeliveryNoteCreateWithDefaults instantiates a new DeliveryNoteCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *DeliveryNoteCreate) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *DeliveryNoteCreate) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *DeliveryNoteCreate) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *DeliveryNoteCreate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *DeliveryNoteCreate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *DeliveryNoteCreate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetContactId

`func (o *DeliveryNoteCreate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *DeliveryNoteCreate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *DeliveryNoteCreate) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *DeliveryNoteCreate) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *DeliveryNoteCreate) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *DeliveryNoteCreate) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *DeliveryNoteCreate) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *DeliveryNoteCreate) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *DeliveryNoteCreate) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *DeliveryNoteCreate) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *DeliveryNoteCreate) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *DeliveryNoteCreate) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCurrency

`func (o *DeliveryNoteCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DeliveryNoteCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DeliveryNoteCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDeliveryDate

`func (o *DeliveryNoteCreate) GetDeliveryDate() string`

GetDeliveryDate returns the DeliveryDate field if non-nil, zero value otherwise.

### GetDeliveryDateOk

`func (o *DeliveryNoteCreate) GetDeliveryDateOk() (*string, bool)`

GetDeliveryDateOk returns a tuple with the DeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryDate

`func (o *DeliveryNoteCreate) SetDeliveryDate(v string)`

SetDeliveryDate sets DeliveryDate field to given value.

### HasDeliveryDate

`func (o *DeliveryNoteCreate) HasDeliveryDate() bool`

HasDeliveryDate returns a boolean if a field has been set.

### SetDeliveryDateNil

`func (o *DeliveryNoteCreate) SetDeliveryDateNil(b bool)`

 SetDeliveryDateNil sets the value for DeliveryDate to be an explicit nil

### UnsetDeliveryDate
`func (o *DeliveryNoteCreate) UnsetDeliveryDate()`

UnsetDeliveryDate ensures that no value is present for DeliveryDate, not even an explicit nil
### GetDeliveryNoteNumber

`func (o *DeliveryNoteCreate) GetDeliveryNoteNumber() string`

GetDeliveryNoteNumber returns the DeliveryNoteNumber field if non-nil, zero value otherwise.

### GetDeliveryNoteNumberOk

`func (o *DeliveryNoteCreate) GetDeliveryNoteNumberOk() (*string, bool)`

GetDeliveryNoteNumberOk returns a tuple with the DeliveryNoteNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryNoteNumber

`func (o *DeliveryNoteCreate) SetDeliveryNoteNumber(v string)`

SetDeliveryNoteNumber sets DeliveryNoteNumber field to given value.

### HasDeliveryNoteNumber

`func (o *DeliveryNoteCreate) HasDeliveryNoteNumber() bool`

HasDeliveryNoteNumber returns a boolean if a field has been set.

### SetDeliveryNoteNumberNil

`func (o *DeliveryNoteCreate) SetDeliveryNoteNumberNil(b bool)`

 SetDeliveryNoteNumberNil sets the value for DeliveryNoteNumber to be an explicit nil

### UnsetDeliveryNoteNumber
`func (o *DeliveryNoteCreate) UnsetDeliveryNoteNumber()`

UnsetDeliveryNoteNumber ensures that no value is present for DeliveryNoteNumber, not even an explicit nil
### GetFiles

`func (o *DeliveryNoteCreate) GetFiles() interface{}`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *DeliveryNoteCreate) GetFilesOk() (*interface{}, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *DeliveryNoteCreate) SetFiles(v interface{})`

SetFiles sets Files field to given value.

### HasFiles

`func (o *DeliveryNoteCreate) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### SetFilesNil

`func (o *DeliveryNoteCreate) SetFilesNil(b bool)`

 SetFilesNil sets the value for Files to be an explicit nil

### UnsetFiles
`func (o *DeliveryNoteCreate) UnsetFiles()`

UnsetFiles ensures that no value is present for Files, not even an explicit nil
### GetIntroduction

`func (o *DeliveryNoteCreate) GetIntroduction() string`

GetIntroduction returns the Introduction field if non-nil, zero value otherwise.

### GetIntroductionOk

`func (o *DeliveryNoteCreate) GetIntroductionOk() (*string, bool)`

GetIntroductionOk returns a tuple with the Introduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroduction

`func (o *DeliveryNoteCreate) SetIntroduction(v string)`

SetIntroduction sets Introduction field to given value.

### HasIntroduction

`func (o *DeliveryNoteCreate) HasIntroduction() bool`

HasIntroduction returns a boolean if a field has been set.

### SetIntroductionNil

`func (o *DeliveryNoteCreate) SetIntroductionNil(b bool)`

 SetIntroductionNil sets the value for Introduction to be an explicit nil

### UnsetIntroduction
`func (o *DeliveryNoteCreate) UnsetIntroduction()`

UnsetIntroduction ensures that no value is present for Introduction, not even an explicit nil
### GetLineItems

`func (o *DeliveryNoteCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *DeliveryNoteCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *DeliveryNoteCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *DeliveryNoteCreate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *DeliveryNoteCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *DeliveryNoteCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetPrecedingSalesVoucherId

`func (o *DeliveryNoteCreate) GetPrecedingSalesVoucherId() string`

GetPrecedingSalesVoucherId returns the PrecedingSalesVoucherId field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherIdOk

`func (o *DeliveryNoteCreate) GetPrecedingSalesVoucherIdOk() (*string, bool)`

GetPrecedingSalesVoucherIdOk returns a tuple with the PrecedingSalesVoucherId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherId

`func (o *DeliveryNoteCreate) SetPrecedingSalesVoucherId(v string)`

SetPrecedingSalesVoucherId sets PrecedingSalesVoucherId field to given value.

### HasPrecedingSalesVoucherId

`func (o *DeliveryNoteCreate) HasPrecedingSalesVoucherId() bool`

HasPrecedingSalesVoucherId returns a boolean if a field has been set.

### SetPrecedingSalesVoucherIdNil

`func (o *DeliveryNoteCreate) SetPrecedingSalesVoucherIdNil(b bool)`

 SetPrecedingSalesVoucherIdNil sets the value for PrecedingSalesVoucherId to be an explicit nil

### UnsetPrecedingSalesVoucherId
`func (o *DeliveryNoteCreate) UnsetPrecedingSalesVoucherId()`

UnsetPrecedingSalesVoucherId ensures that no value is present for PrecedingSalesVoucherId, not even an explicit nil
### GetPrecedingSalesVoucherType

`func (o *DeliveryNoteCreate) GetPrecedingSalesVoucherType() PrecedingSalesVoucherType`

GetPrecedingSalesVoucherType returns the PrecedingSalesVoucherType field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherTypeOk

`func (o *DeliveryNoteCreate) GetPrecedingSalesVoucherTypeOk() (*PrecedingSalesVoucherType, bool)`

GetPrecedingSalesVoucherTypeOk returns a tuple with the PrecedingSalesVoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherType

`func (o *DeliveryNoteCreate) SetPrecedingSalesVoucherType(v PrecedingSalesVoucherType)`

SetPrecedingSalesVoucherType sets PrecedingSalesVoucherType field to given value.

### HasPrecedingSalesVoucherType

`func (o *DeliveryNoteCreate) HasPrecedingSalesVoucherType() bool`

HasPrecedingSalesVoucherType returns a boolean if a field has been set.

### SetPrecedingSalesVoucherTypeNil

`func (o *DeliveryNoteCreate) SetPrecedingSalesVoucherTypeNil(b bool)`

 SetPrecedingSalesVoucherTypeNil sets the value for PrecedingSalesVoucherType to be an explicit nil

### UnsetPrecedingSalesVoucherType
`func (o *DeliveryNoteCreate) UnsetPrecedingSalesVoucherType()`

UnsetPrecedingSalesVoucherType ensures that no value is present for PrecedingSalesVoucherType, not even an explicit nil
### GetRemark

`func (o *DeliveryNoteCreate) GetRemark() string`

GetRemark returns the Remark field if non-nil, zero value otherwise.

### GetRemarkOk

`func (o *DeliveryNoteCreate) GetRemarkOk() (*string, bool)`

GetRemarkOk returns a tuple with the Remark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemark

`func (o *DeliveryNoteCreate) SetRemark(v string)`

SetRemark sets Remark field to given value.

### HasRemark

`func (o *DeliveryNoteCreate) HasRemark() bool`

HasRemark returns a boolean if a field has been set.

### SetRemarkNil

`func (o *DeliveryNoteCreate) SetRemarkNil(b bool)`

 SetRemarkNil sets the value for Remark to be an explicit nil

### UnsetRemark
`func (o *DeliveryNoteCreate) UnsetRemark()`

UnsetRemark ensures that no value is present for Remark, not even an explicit nil
### GetShippingDate

`func (o *DeliveryNoteCreate) GetShippingDate() string`

GetShippingDate returns the ShippingDate field if non-nil, zero value otherwise.

### GetShippingDateOk

`func (o *DeliveryNoteCreate) GetShippingDateOk() (*string, bool)`

GetShippingDateOk returns a tuple with the ShippingDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingDate

`func (o *DeliveryNoteCreate) SetShippingDate(v string)`

SetShippingDate sets ShippingDate field to given value.

### HasShippingDate

`func (o *DeliveryNoteCreate) HasShippingDate() bool`

HasShippingDate returns a boolean if a field has been set.

### SetShippingDateNil

`func (o *DeliveryNoteCreate) SetShippingDateNil(b bool)`

 SetShippingDateNil sets the value for ShippingDate to be an explicit nil

### UnsetShippingDate
`func (o *DeliveryNoteCreate) UnsetShippingDate()`

UnsetShippingDate ensures that no value is present for ShippingDate, not even an explicit nil
### GetShippingMethod

`func (o *DeliveryNoteCreate) GetShippingMethod() string`

GetShippingMethod returns the ShippingMethod field if non-nil, zero value otherwise.

### GetShippingMethodOk

`func (o *DeliveryNoteCreate) GetShippingMethodOk() (*string, bool)`

GetShippingMethodOk returns a tuple with the ShippingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethod

`func (o *DeliveryNoteCreate) SetShippingMethod(v string)`

SetShippingMethod sets ShippingMethod field to given value.

### HasShippingMethod

`func (o *DeliveryNoteCreate) HasShippingMethod() bool`

HasShippingMethod returns a boolean if a field has been set.

### SetShippingMethodNil

`func (o *DeliveryNoteCreate) SetShippingMethodNil(b bool)`

 SetShippingMethodNil sets the value for ShippingMethod to be an explicit nil

### UnsetShippingMethod
`func (o *DeliveryNoteCreate) UnsetShippingMethod()`

UnsetShippingMethod ensures that no value is present for ShippingMethod, not even an explicit nil
### GetTitle

`func (o *DeliveryNoteCreate) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DeliveryNoteCreate) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DeliveryNoteCreate) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *DeliveryNoteCreate) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *DeliveryNoteCreate) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *DeliveryNoteCreate) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetVoucherDate

`func (o *DeliveryNoteCreate) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *DeliveryNoteCreate) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *DeliveryNoteCreate) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherStatus

`func (o *DeliveryNoteCreate) GetVoucherStatus() VoucherStatus`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *DeliveryNoteCreate) GetVoucherStatusOk() (*VoucherStatus, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *DeliveryNoteCreate) SetVoucherStatus(v VoucherStatus)`

SetVoucherStatus sets VoucherStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


