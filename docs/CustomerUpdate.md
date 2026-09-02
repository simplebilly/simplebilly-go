# CustomerUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **interface{}** |  | [optional] 
**ContactPerson** | Pointer to **NullableString** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**ExternalOrderNumber** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**PaymentGracePeriodDays** | Pointer to **NullableInt32** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**VatId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCustomerUpdate

`func NewCustomerUpdate() *CustomerUpdate`

NewCustomerUpdate instantiates a new CustomerUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerUpdateWithDefaults

`func NewCustomerUpdateWithDefaults() *CustomerUpdate`

NewCustomerUpdateWithDefaults instantiates a new CustomerUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *CustomerUpdate) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CustomerUpdate) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CustomerUpdate) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *CustomerUpdate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *CustomerUpdate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *CustomerUpdate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetContactPerson

`func (o *CustomerUpdate) GetContactPerson() string`

GetContactPerson returns the ContactPerson field if non-nil, zero value otherwise.

### GetContactPersonOk

`func (o *CustomerUpdate) GetContactPersonOk() (*string, bool)`

GetContactPersonOk returns a tuple with the ContactPerson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactPerson

`func (o *CustomerUpdate) SetContactPerson(v string)`

SetContactPerson sets ContactPerson field to given value.

### HasContactPerson

`func (o *CustomerUpdate) HasContactPerson() bool`

HasContactPerson returns a boolean if a field has been set.

### SetContactPersonNil

`func (o *CustomerUpdate) SetContactPersonNil(b bool)`

 SetContactPersonNil sets the value for ContactPerson to be an explicit nil

### UnsetContactPerson
`func (o *CustomerUpdate) UnsetContactPerson()`

UnsetContactPerson ensures that no value is present for ContactPerson, not even an explicit nil
### GetEmail

`func (o *CustomerUpdate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomerUpdate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomerUpdate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomerUpdate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *CustomerUpdate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *CustomerUpdate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetExternalOrderNumber

`func (o *CustomerUpdate) GetExternalOrderNumber() string`

GetExternalOrderNumber returns the ExternalOrderNumber field if non-nil, zero value otherwise.

### GetExternalOrderNumberOk

`func (o *CustomerUpdate) GetExternalOrderNumberOk() (*string, bool)`

GetExternalOrderNumberOk returns a tuple with the ExternalOrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalOrderNumber

`func (o *CustomerUpdate) SetExternalOrderNumber(v string)`

SetExternalOrderNumber sets ExternalOrderNumber field to given value.

### HasExternalOrderNumber

`func (o *CustomerUpdate) HasExternalOrderNumber() bool`

HasExternalOrderNumber returns a boolean if a field has been set.

### SetExternalOrderNumberNil

`func (o *CustomerUpdate) SetExternalOrderNumberNil(b bool)`

 SetExternalOrderNumberNil sets the value for ExternalOrderNumber to be an explicit nil

### UnsetExternalOrderNumber
`func (o *CustomerUpdate) UnsetExternalOrderNumber()`

UnsetExternalOrderNumber ensures that no value is present for ExternalOrderNumber, not even an explicit nil
### GetName

`func (o *CustomerUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomerUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomerUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomerUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CustomerUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CustomerUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetPaymentGracePeriodDays

`func (o *CustomerUpdate) GetPaymentGracePeriodDays() int32`

GetPaymentGracePeriodDays returns the PaymentGracePeriodDays field if non-nil, zero value otherwise.

### GetPaymentGracePeriodDaysOk

`func (o *CustomerUpdate) GetPaymentGracePeriodDaysOk() (*int32, bool)`

GetPaymentGracePeriodDaysOk returns a tuple with the PaymentGracePeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentGracePeriodDays

`func (o *CustomerUpdate) SetPaymentGracePeriodDays(v int32)`

SetPaymentGracePeriodDays sets PaymentGracePeriodDays field to given value.

### HasPaymentGracePeriodDays

`func (o *CustomerUpdate) HasPaymentGracePeriodDays() bool`

HasPaymentGracePeriodDays returns a boolean if a field has been set.

### SetPaymentGracePeriodDaysNil

`func (o *CustomerUpdate) SetPaymentGracePeriodDaysNil(b bool)`

 SetPaymentGracePeriodDaysNil sets the value for PaymentGracePeriodDays to be an explicit nil

### UnsetPaymentGracePeriodDays
`func (o *CustomerUpdate) UnsetPaymentGracePeriodDays()`

UnsetPaymentGracePeriodDays ensures that no value is present for PaymentGracePeriodDays, not even an explicit nil
### GetPhone

`func (o *CustomerUpdate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomerUpdate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomerUpdate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomerUpdate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *CustomerUpdate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *CustomerUpdate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetVatId

`func (o *CustomerUpdate) GetVatId() string`

GetVatId returns the VatId field if non-nil, zero value otherwise.

### GetVatIdOk

`func (o *CustomerUpdate) GetVatIdOk() (*string, bool)`

GetVatIdOk returns a tuple with the VatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatId

`func (o *CustomerUpdate) SetVatId(v string)`

SetVatId sets VatId field to given value.

### HasVatId

`func (o *CustomerUpdate) HasVatId() bool`

HasVatId returns a boolean if a field has been set.

### SetVatIdNil

`func (o *CustomerUpdate) SetVatIdNil(b bool)`

 SetVatIdNil sets the value for VatId to be an explicit nil

### UnsetVatId
`func (o *CustomerUpdate) UnsetVatId()`

UnsetVatId ensures that no value is present for VatId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


