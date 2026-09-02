# SuitabilityRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerAnnualVolume** | Pointer to **NullableInt32** |  | [optional] 
**Items** | [**[]CartItemInput**](CartItemInput.md) |  | 
**Recipient** | [**Address**](Address.md) |  | 
**Sender** | [**Address**](Address.md) |  | 

## Methods

### NewSuitabilityRequest

`func NewSuitabilityRequest(items []CartItemInput, recipient Address, sender Address, ) *SuitabilityRequest`

NewSuitabilityRequest instantiates a new SuitabilityRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuitabilityRequestWithDefaults

`func NewSuitabilityRequestWithDefaults() *SuitabilityRequest`

NewSuitabilityRequestWithDefaults instantiates a new SuitabilityRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerAnnualVolume

`func (o *SuitabilityRequest) GetCustomerAnnualVolume() int32`

GetCustomerAnnualVolume returns the CustomerAnnualVolume field if non-nil, zero value otherwise.

### GetCustomerAnnualVolumeOk

`func (o *SuitabilityRequest) GetCustomerAnnualVolumeOk() (*int32, bool)`

GetCustomerAnnualVolumeOk returns a tuple with the CustomerAnnualVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAnnualVolume

`func (o *SuitabilityRequest) SetCustomerAnnualVolume(v int32)`

SetCustomerAnnualVolume sets CustomerAnnualVolume field to given value.

### HasCustomerAnnualVolume

`func (o *SuitabilityRequest) HasCustomerAnnualVolume() bool`

HasCustomerAnnualVolume returns a boolean if a field has been set.

### SetCustomerAnnualVolumeNil

`func (o *SuitabilityRequest) SetCustomerAnnualVolumeNil(b bool)`

 SetCustomerAnnualVolumeNil sets the value for CustomerAnnualVolume to be an explicit nil

### UnsetCustomerAnnualVolume
`func (o *SuitabilityRequest) UnsetCustomerAnnualVolume()`

UnsetCustomerAnnualVolume ensures that no value is present for CustomerAnnualVolume, not even an explicit nil
### GetItems

`func (o *SuitabilityRequest) GetItems() []CartItemInput`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SuitabilityRequest) GetItemsOk() (*[]CartItemInput, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SuitabilityRequest) SetItems(v []CartItemInput)`

SetItems sets Items field to given value.


### GetRecipient

`func (o *SuitabilityRequest) GetRecipient() Address`

GetRecipient returns the Recipient field if non-nil, zero value otherwise.

### GetRecipientOk

`func (o *SuitabilityRequest) GetRecipientOk() (*Address, bool)`

GetRecipientOk returns a tuple with the Recipient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipient

`func (o *SuitabilityRequest) SetRecipient(v Address)`

SetRecipient sets Recipient field to given value.


### GetSender

`func (o *SuitabilityRequest) GetSender() Address`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SuitabilityRequest) GetSenderOk() (*Address, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SuitabilityRequest) SetSender(v Address)`

SetSender sets Sender field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


