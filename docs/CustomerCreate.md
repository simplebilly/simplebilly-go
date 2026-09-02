# CustomerCreate

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

### NewCustomerCreate

`func NewCustomerCreate(name string, ) *CustomerCreate`

NewCustomerCreate instantiates a new CustomerCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerCreateWithDefaults

`func NewCustomerCreateWithDefaults() *CustomerCreate`

NewCustomerCreateWithDefaults instantiates a new CustomerCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *CustomerCreate) GetAddress() interface{}`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CustomerCreate) GetAddressOk() (*interface{}, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CustomerCreate) SetAddress(v interface{})`

SetAddress sets Address field to given value.

### HasAddress

`func (o *CustomerCreate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *CustomerCreate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *CustomerCreate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetContactPerson

`func (o *CustomerCreate) GetContactPerson() string`

GetContactPerson returns the ContactPerson field if non-nil, zero value otherwise.

### GetContactPersonOk

`func (o *CustomerCreate) GetContactPersonOk() (*string, bool)`

GetContactPersonOk returns a tuple with the ContactPerson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactPerson

`func (o *CustomerCreate) SetContactPerson(v string)`

SetContactPerson sets ContactPerson field to given value.

### HasContactPerson

`func (o *CustomerCreate) HasContactPerson() bool`

HasContactPerson returns a boolean if a field has been set.

### SetContactPersonNil

`func (o *CustomerCreate) SetContactPersonNil(b bool)`

 SetContactPersonNil sets the value for ContactPerson to be an explicit nil

### UnsetContactPerson
`func (o *CustomerCreate) UnsetContactPerson()`

UnsetContactPerson ensures that no value is present for ContactPerson, not even an explicit nil
### GetEmail

`func (o *CustomerCreate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomerCreate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomerCreate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CustomerCreate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *CustomerCreate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *CustomerCreate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetExternalOrderNumber

`func (o *CustomerCreate) GetExternalOrderNumber() string`

GetExternalOrderNumber returns the ExternalOrderNumber field if non-nil, zero value otherwise.

### GetExternalOrderNumberOk

`func (o *CustomerCreate) GetExternalOrderNumberOk() (*string, bool)`

GetExternalOrderNumberOk returns a tuple with the ExternalOrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalOrderNumber

`func (o *CustomerCreate) SetExternalOrderNumber(v string)`

SetExternalOrderNumber sets ExternalOrderNumber field to given value.

### HasExternalOrderNumber

`func (o *CustomerCreate) HasExternalOrderNumber() bool`

HasExternalOrderNumber returns a boolean if a field has been set.

### SetExternalOrderNumberNil

`func (o *CustomerCreate) SetExternalOrderNumberNil(b bool)`

 SetExternalOrderNumberNil sets the value for ExternalOrderNumber to be an explicit nil

### UnsetExternalOrderNumber
`func (o *CustomerCreate) UnsetExternalOrderNumber()`

UnsetExternalOrderNumber ensures that no value is present for ExternalOrderNumber, not even an explicit nil
### GetName

`func (o *CustomerCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomerCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomerCreate) SetName(v string)`

SetName sets Name field to given value.


### GetPaymentGracePeriodDays

`func (o *CustomerCreate) GetPaymentGracePeriodDays() int32`

GetPaymentGracePeriodDays returns the PaymentGracePeriodDays field if non-nil, zero value otherwise.

### GetPaymentGracePeriodDaysOk

`func (o *CustomerCreate) GetPaymentGracePeriodDaysOk() (*int32, bool)`

GetPaymentGracePeriodDaysOk returns a tuple with the PaymentGracePeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentGracePeriodDays

`func (o *CustomerCreate) SetPaymentGracePeriodDays(v int32)`

SetPaymentGracePeriodDays sets PaymentGracePeriodDays field to given value.

### HasPaymentGracePeriodDays

`func (o *CustomerCreate) HasPaymentGracePeriodDays() bool`

HasPaymentGracePeriodDays returns a boolean if a field has been set.

### SetPaymentGracePeriodDaysNil

`func (o *CustomerCreate) SetPaymentGracePeriodDaysNil(b bool)`

 SetPaymentGracePeriodDaysNil sets the value for PaymentGracePeriodDays to be an explicit nil

### UnsetPaymentGracePeriodDays
`func (o *CustomerCreate) UnsetPaymentGracePeriodDays()`

UnsetPaymentGracePeriodDays ensures that no value is present for PaymentGracePeriodDays, not even an explicit nil
### GetPhone

`func (o *CustomerCreate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomerCreate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomerCreate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomerCreate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *CustomerCreate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *CustomerCreate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetVatId

`func (o *CustomerCreate) GetVatId() string`

GetVatId returns the VatId field if non-nil, zero value otherwise.

### GetVatIdOk

`func (o *CustomerCreate) GetVatIdOk() (*string, bool)`

GetVatIdOk returns a tuple with the VatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatId

`func (o *CustomerCreate) SetVatId(v string)`

SetVatId sets VatId field to given value.

### HasVatId

`func (o *CustomerCreate) HasVatId() bool`

HasVatId returns a boolean if a field has been set.

### SetVatIdNil

`func (o *CustomerCreate) SetVatIdNil(b bool)`

 SetVatIdNil sets the value for VatId to be an explicit nil

### UnsetVatId
`func (o *CustomerCreate) UnsetVatId()`

UnsetVatId ensures that no value is present for VatId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


