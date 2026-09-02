# RateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Customer** | Pointer to [**NullableCustomerInfo**](CustomerInfo.md) |  | [optional] 
**Packages** | [**[]Package**](Package.md) |  | 
**Recipient** | [**Address**](Address.md) |  | 
**Sender** | [**Address**](Address.md) |  | 

## Methods

### NewRateRequest

`func NewRateRequest(packages []Package, recipient Address, sender Address, ) *RateRequest`

NewRateRequest instantiates a new RateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRateRequestWithDefaults

`func NewRateRequestWithDefaults() *RateRequest`

NewRateRequestWithDefaults instantiates a new RateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomer

`func (o *RateRequest) GetCustomer() CustomerInfo`

GetCustomer returns the Customer field if non-nil, zero value otherwise.

### GetCustomerOk

`func (o *RateRequest) GetCustomerOk() (*CustomerInfo, bool)`

GetCustomerOk returns a tuple with the Customer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomer

`func (o *RateRequest) SetCustomer(v CustomerInfo)`

SetCustomer sets Customer field to given value.

### HasCustomer

`func (o *RateRequest) HasCustomer() bool`

HasCustomer returns a boolean if a field has been set.

### SetCustomerNil

`func (o *RateRequest) SetCustomerNil(b bool)`

 SetCustomerNil sets the value for Customer to be an explicit nil

### UnsetCustomer
`func (o *RateRequest) UnsetCustomer()`

UnsetCustomer ensures that no value is present for Customer, not even an explicit nil
### GetPackages

`func (o *RateRequest) GetPackages() []Package`

GetPackages returns the Packages field if non-nil, zero value otherwise.

### GetPackagesOk

`func (o *RateRequest) GetPackagesOk() (*[]Package, bool)`

GetPackagesOk returns a tuple with the Packages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackages

`func (o *RateRequest) SetPackages(v []Package)`

SetPackages sets Packages field to given value.


### GetRecipient

`func (o *RateRequest) GetRecipient() Address`

GetRecipient returns the Recipient field if non-nil, zero value otherwise.

### GetRecipientOk

`func (o *RateRequest) GetRecipientOk() (*Address, bool)`

GetRecipientOk returns a tuple with the Recipient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipient

`func (o *RateRequest) SetRecipient(v Address)`

SetRecipient sets Recipient field to given value.


### GetSender

`func (o *RateRequest) GetSender() Address`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *RateRequest) GetSenderOk() (*Address, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *RateRequest) SetSender(v Address)`

SetSender sets Sender field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


