# Customer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **interface{}** |  | [optional] 
**ContactPerson** | Pointer to **NullableString** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**ExternalOrderNumber** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**PaymentGracePeriodDays** | Pointer to **NullableInt32** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**VatId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCustomer

`func NewCustomer(name string, ) *Customer`

NewCustomer instantiates a new Customer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerWithDefaults

`func NewCustomerWithDefaults() *Customer`

NewCustomerWithDefaults instantiates a new Customer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *Customer) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Customer) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Customer) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *Customer) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *Customer) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *Customer) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetContactPerson

`func (o *Customer) GetContactPerson() string`

GetContactPerson returns the ContactPerson field if non-nil, zero value otherwise.

### GetContactPersonOk

`func (o *Customer) GetContactPersonOk() (*string, bool)`

GetContactPersonOk returns a tuple with the ContactPerson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactPerson

`func (o *Customer) SetContactPerson(v string)`

SetContactPerson sets ContactPerson field to given value.

### HasContactPerson

`func (o *Customer) HasContactPerson() bool`

HasContactPerson returns a boolean if a field has been set.

### SetContactPersonNil

`func (o *Customer) SetContactPersonNil(b bool)`

 SetContactPersonNil sets the value for ContactPerson to be an explicit nil

### UnsetContactPerson
`func (o *Customer) UnsetContactPerson()`

UnsetContactPerson ensures that no value is present for ContactPerson, not even an explicit nil
### GetEmail

`func (o *Customer) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Customer) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Customer) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *Customer) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *Customer) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *Customer) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetExternalOrderNumber

`func (o *Customer) GetExternalOrderNumber() string`

GetExternalOrderNumber returns the ExternalOrderNumber field if non-nil, zero value otherwise.

### GetExternalOrderNumberOk

`func (o *Customer) GetExternalOrderNumberOk() (*string, bool)`

GetExternalOrderNumberOk returns a tuple with the ExternalOrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalOrderNumber

`func (o *Customer) SetExternalOrderNumber(v string)`

SetExternalOrderNumber sets ExternalOrderNumber field to given value.

### HasExternalOrderNumber

`func (o *Customer) HasExternalOrderNumber() bool`

HasExternalOrderNumber returns a boolean if a field has been set.

### SetExternalOrderNumberNil

`func (o *Customer) SetExternalOrderNumberNil(b bool)`

 SetExternalOrderNumberNil sets the value for ExternalOrderNumber to be an explicit nil

### UnsetExternalOrderNumber
`func (o *Customer) UnsetExternalOrderNumber()`

UnsetExternalOrderNumber ensures that no value is present for ExternalOrderNumber, not even an explicit nil
### GetName

`func (o *Customer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Customer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Customer) SetName(v string)`

SetName sets Name field to given value.


### GetPaymentGracePeriodDays

`func (o *Customer) GetPaymentGracePeriodDays() int32`

GetPaymentGracePeriodDays returns the PaymentGracePeriodDays field if non-nil, zero value otherwise.

### GetPaymentGracePeriodDaysOk

`func (o *Customer) GetPaymentGracePeriodDaysOk() (*int32, bool)`

GetPaymentGracePeriodDaysOk returns a tuple with the PaymentGracePeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentGracePeriodDays

`func (o *Customer) SetPaymentGracePeriodDays(v int32)`

SetPaymentGracePeriodDays sets PaymentGracePeriodDays field to given value.

### HasPaymentGracePeriodDays

`func (o *Customer) HasPaymentGracePeriodDays() bool`

HasPaymentGracePeriodDays returns a boolean if a field has been set.

### SetPaymentGracePeriodDaysNil

`func (o *Customer) SetPaymentGracePeriodDaysNil(b bool)`

 SetPaymentGracePeriodDaysNil sets the value for PaymentGracePeriodDays to be an explicit nil

### UnsetPaymentGracePeriodDays
`func (o *Customer) UnsetPaymentGracePeriodDays()`

UnsetPaymentGracePeriodDays ensures that no value is present for PaymentGracePeriodDays, not even an explicit nil
### GetPhone

`func (o *Customer) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *Customer) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *Customer) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *Customer) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *Customer) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *Customer) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetVatId

`func (o *Customer) GetVatId() string`

GetVatId returns the VatId field if non-nil, zero value otherwise.

### GetVatIdOk

`func (o *Customer) GetVatIdOk() (*string, bool)`

GetVatIdOk returns a tuple with the VatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatId

`func (o *Customer) SetVatId(v string)`

SetVatId sets VatId field to given value.

### HasVatId

`func (o *Customer) HasVatId() bool`

HasVatId returns a boolean if a field has been set.

### SetVatIdNil

`func (o *Customer) SetVatIdNil(b bool)`

 SetVatIdNil sets the value for VatId to be an explicit nil

### UnsetVatId
`func (o *Customer) UnsetVatId()`

UnsetVatId ensures that no value is present for VatId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


