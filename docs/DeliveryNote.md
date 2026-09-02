# DeliveryNote

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
**Subtotal** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**TotalAmount** | Pointer to **NullableString** |  | [optional] 
**VoucherDate** | **string** |  | 
**VoucherStatus** | [**VoucherStatus**](VoucherStatus.md) |  | 

## Methods

### NewDeliveryNote

`func NewDeliveryNote(currency string, voucherDate string, voucherStatus VoucherStatus, ) *DeliveryNote`

NewDeliveryNote instantiates a new DeliveryNote object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliveryNoteWithDefaults

`func NewDeliveryNoteWithDefaults() *DeliveryNote`

NewDeliveryNoteWithDefaults instantiates a new DeliveryNote object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *DeliveryNote) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *DeliveryNote) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *DeliveryNote) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *DeliveryNote) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *DeliveryNote) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *DeliveryNote) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetContactId

`func (o *DeliveryNote) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *DeliveryNote) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *DeliveryNote) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *DeliveryNote) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *DeliveryNote) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *DeliveryNote) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetContactName

`func (o *DeliveryNote) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *DeliveryNote) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *DeliveryNote) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *DeliveryNote) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### SetContactNameNil

`func (o *DeliveryNote) SetContactNameNil(b bool)`

 SetContactNameNil sets the value for ContactName to be an explicit nil

### UnsetContactName
`func (o *DeliveryNote) UnsetContactName()`

UnsetContactName ensures that no value is present for ContactName, not even an explicit nil
### GetCurrency

`func (o *DeliveryNote) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DeliveryNote) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DeliveryNote) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDeliveryDate

`func (o *DeliveryNote) GetDeliveryDate() string`

GetDeliveryDate returns the DeliveryDate field if non-nil, zero value otherwise.

### GetDeliveryDateOk

`func (o *DeliveryNote) GetDeliveryDateOk() (*string, bool)`

GetDeliveryDateOk returns a tuple with the DeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryDate

`func (o *DeliveryNote) SetDeliveryDate(v string)`

SetDeliveryDate sets DeliveryDate field to given value.

### HasDeliveryDate

`func (o *DeliveryNote) HasDeliveryDate() bool`

HasDeliveryDate returns a boolean if a field has been set.

### SetDeliveryDateNil

`func (o *DeliveryNote) SetDeliveryDateNil(b bool)`

 SetDeliveryDateNil sets the value for DeliveryDate to be an explicit nil

### UnsetDeliveryDate
`func (o *DeliveryNote) UnsetDeliveryDate()`

UnsetDeliveryDate ensures that no value is present for DeliveryDate, not even an explicit nil
### GetDeliveryNoteNumber

`func (o *DeliveryNote) GetDeliveryNoteNumber() string`

GetDeliveryNoteNumber returns the DeliveryNoteNumber field if non-nil, zero value otherwise.

### GetDeliveryNoteNumberOk

`func (o *DeliveryNote) GetDeliveryNoteNumberOk() (*string, bool)`

GetDeliveryNoteNumberOk returns a tuple with the DeliveryNoteNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryNoteNumber

`func (o *DeliveryNote) SetDeliveryNoteNumber(v string)`

SetDeliveryNoteNumber sets DeliveryNoteNumber field to given value.

### HasDeliveryNoteNumber

`func (o *DeliveryNote) HasDeliveryNoteNumber() bool`

HasDeliveryNoteNumber returns a boolean if a field has been set.

### SetDeliveryNoteNumberNil

`func (o *DeliveryNote) SetDeliveryNoteNumberNil(b bool)`

 SetDeliveryNoteNumberNil sets the value for DeliveryNoteNumber to be an explicit nil

### UnsetDeliveryNoteNumber
`func (o *DeliveryNote) UnsetDeliveryNoteNumber()`

UnsetDeliveryNoteNumber ensures that no value is present for DeliveryNoteNumber, not even an explicit nil
### GetFiles

`func (o *DeliveryNote) GetFiles() interface{}`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *DeliveryNote) GetFilesOk() (*interface{}, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *DeliveryNote) SetFiles(v interface{})`

SetFiles sets Files field to given value.

### HasFiles

`func (o *DeliveryNote) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### SetFilesNil

`func (o *DeliveryNote) SetFilesNil(b bool)`

 SetFilesNil sets the value for Files to be an explicit nil

### UnsetFiles
`func (o *DeliveryNote) UnsetFiles()`

UnsetFiles ensures that no value is present for Files, not even an explicit nil
### GetIntroduction

`func (o *DeliveryNote) GetIntroduction() string`

GetIntroduction returns the Introduction field if non-nil, zero value otherwise.

### GetIntroductionOk

`func (o *DeliveryNote) GetIntroductionOk() (*string, bool)`

GetIntroductionOk returns a tuple with the Introduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroduction

`func (o *DeliveryNote) SetIntroduction(v string)`

SetIntroduction sets Introduction field to given value.

### HasIntroduction

`func (o *DeliveryNote) HasIntroduction() bool`

HasIntroduction returns a boolean if a field has been set.

### SetIntroductionNil

`func (o *DeliveryNote) SetIntroductionNil(b bool)`

 SetIntroductionNil sets the value for Introduction to be an explicit nil

### UnsetIntroduction
`func (o *DeliveryNote) UnsetIntroduction()`

UnsetIntroduction ensures that no value is present for Introduction, not even an explicit nil
### GetLineItems

`func (o *DeliveryNote) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *DeliveryNote) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *DeliveryNote) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *DeliveryNote) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *DeliveryNote) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *DeliveryNote) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetPrecedingSalesVoucherId

`func (o *DeliveryNote) GetPrecedingSalesVoucherId() string`

GetPrecedingSalesVoucherId returns the PrecedingSalesVoucherId field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherIdOk

`func (o *DeliveryNote) GetPrecedingSalesVoucherIdOk() (*string, bool)`

GetPrecedingSalesVoucherIdOk returns a tuple with the PrecedingSalesVoucherId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherId

`func (o *DeliveryNote) SetPrecedingSalesVoucherId(v string)`

SetPrecedingSalesVoucherId sets PrecedingSalesVoucherId field to given value.

### HasPrecedingSalesVoucherId

`func (o *DeliveryNote) HasPrecedingSalesVoucherId() bool`

HasPrecedingSalesVoucherId returns a boolean if a field has been set.

### SetPrecedingSalesVoucherIdNil

`func (o *DeliveryNote) SetPrecedingSalesVoucherIdNil(b bool)`

 SetPrecedingSalesVoucherIdNil sets the value for PrecedingSalesVoucherId to be an explicit nil

### UnsetPrecedingSalesVoucherId
`func (o *DeliveryNote) UnsetPrecedingSalesVoucherId()`

UnsetPrecedingSalesVoucherId ensures that no value is present for PrecedingSalesVoucherId, not even an explicit nil
### GetPrecedingSalesVoucherType

`func (o *DeliveryNote) GetPrecedingSalesVoucherType() PrecedingSalesVoucherType`

GetPrecedingSalesVoucherType returns the PrecedingSalesVoucherType field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherTypeOk

`func (o *DeliveryNote) GetPrecedingSalesVoucherTypeOk() (*PrecedingSalesVoucherType, bool)`

GetPrecedingSalesVoucherTypeOk returns a tuple with the PrecedingSalesVoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherType

`func (o *DeliveryNote) SetPrecedingSalesVoucherType(v PrecedingSalesVoucherType)`

SetPrecedingSalesVoucherType sets PrecedingSalesVoucherType field to given value.

### HasPrecedingSalesVoucherType

`func (o *DeliveryNote) HasPrecedingSalesVoucherType() bool`

HasPrecedingSalesVoucherType returns a boolean if a field has been set.

### SetPrecedingSalesVoucherTypeNil

`func (o *DeliveryNote) SetPrecedingSalesVoucherTypeNil(b bool)`

 SetPrecedingSalesVoucherTypeNil sets the value for PrecedingSalesVoucherType to be an explicit nil

### UnsetPrecedingSalesVoucherType
`func (o *DeliveryNote) UnsetPrecedingSalesVoucherType()`

UnsetPrecedingSalesVoucherType ensures that no value is present for PrecedingSalesVoucherType, not even an explicit nil
### GetRemark

`func (o *DeliveryNote) GetRemark() string`

GetRemark returns the Remark field if non-nil, zero value otherwise.

### GetRemarkOk

`func (o *DeliveryNote) GetRemarkOk() (*string, bool)`

GetRemarkOk returns a tuple with the Remark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemark

`func (o *DeliveryNote) SetRemark(v string)`

SetRemark sets Remark field to given value.

### HasRemark

`func (o *DeliveryNote) HasRemark() bool`

HasRemark returns a boolean if a field has been set.

### SetRemarkNil

`func (o *DeliveryNote) SetRemarkNil(b bool)`

 SetRemarkNil sets the value for Remark to be an explicit nil

### UnsetRemark
`func (o *DeliveryNote) UnsetRemark()`

UnsetRemark ensures that no value is present for Remark, not even an explicit nil
### GetShippingDate

`func (o *DeliveryNote) GetShippingDate() string`

GetShippingDate returns the ShippingDate field if non-nil, zero value otherwise.

### GetShippingDateOk

`func (o *DeliveryNote) GetShippingDateOk() (*string, bool)`

GetShippingDateOk returns a tuple with the ShippingDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingDate

`func (o *DeliveryNote) SetShippingDate(v string)`

SetShippingDate sets ShippingDate field to given value.

### HasShippingDate

`func (o *DeliveryNote) HasShippingDate() bool`

HasShippingDate returns a boolean if a field has been set.

### SetShippingDateNil

`func (o *DeliveryNote) SetShippingDateNil(b bool)`

 SetShippingDateNil sets the value for ShippingDate to be an explicit nil

### UnsetShippingDate
`func (o *DeliveryNote) UnsetShippingDate()`

UnsetShippingDate ensures that no value is present for ShippingDate, not even an explicit nil
### GetShippingMethod

`func (o *DeliveryNote) GetShippingMethod() string`

GetShippingMethod returns the ShippingMethod field if non-nil, zero value otherwise.

### GetShippingMethodOk

`func (o *DeliveryNote) GetShippingMethodOk() (*string, bool)`

GetShippingMethodOk returns a tuple with the ShippingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethod

`func (o *DeliveryNote) SetShippingMethod(v string)`

SetShippingMethod sets ShippingMethod field to given value.

### HasShippingMethod

`func (o *DeliveryNote) HasShippingMethod() bool`

HasShippingMethod returns a boolean if a field has been set.

### SetShippingMethodNil

`func (o *DeliveryNote) SetShippingMethodNil(b bool)`

 SetShippingMethodNil sets the value for ShippingMethod to be an explicit nil

### UnsetShippingMethod
`func (o *DeliveryNote) UnsetShippingMethod()`

UnsetShippingMethod ensures that no value is present for ShippingMethod, not even an explicit nil
### GetSubtotal

`func (o *DeliveryNote) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *DeliveryNote) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *DeliveryNote) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.

### HasSubtotal

`func (o *DeliveryNote) HasSubtotal() bool`

HasSubtotal returns a boolean if a field has been set.

### SetSubtotalNil

`func (o *DeliveryNote) SetSubtotalNil(b bool)`

 SetSubtotalNil sets the value for Subtotal to be an explicit nil

### UnsetSubtotal
`func (o *DeliveryNote) UnsetSubtotal()`

UnsetSubtotal ensures that no value is present for Subtotal, not even an explicit nil
### GetTitle

`func (o *DeliveryNote) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DeliveryNote) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DeliveryNote) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *DeliveryNote) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *DeliveryNote) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *DeliveryNote) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetTotalAmount

`func (o *DeliveryNote) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *DeliveryNote) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *DeliveryNote) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *DeliveryNote) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *DeliveryNote) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *DeliveryNote) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetVoucherDate

`func (o *DeliveryNote) GetVoucherDate() string`

GetVoucherDate returns the VoucherDate field if non-nil, zero value otherwise.

### GetVoucherDateOk

`func (o *DeliveryNote) GetVoucherDateOk() (*string, bool)`

GetVoucherDateOk returns a tuple with the VoucherDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherDate

`func (o *DeliveryNote) SetVoucherDate(v string)`

SetVoucherDate sets VoucherDate field to given value.


### GetVoucherStatus

`func (o *DeliveryNote) GetVoucherStatus() VoucherStatus`

GetVoucherStatus returns the VoucherStatus field if non-nil, zero value otherwise.

### GetVoucherStatusOk

`func (o *DeliveryNote) GetVoucherStatusOk() (*VoucherStatus, bool)`

GetVoucherStatusOk returns a tuple with the VoucherStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherStatus

`func (o *DeliveryNote) SetVoucherStatus(v VoucherStatus)`

SetVoucherStatus sets VoucherStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


