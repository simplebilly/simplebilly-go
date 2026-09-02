# CustomerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnnualVolume** | **int32** |  | 
**IsRegistered** | **bool** |  | 

## Methods

### NewCustomerInfo

`func NewCustomerInfo(annualVolume int32, isRegistered bool, ) *CustomerInfo`

NewCustomerInfo instantiates a new CustomerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerInfoWithDefaults

`func NewCustomerInfoWithDefaults() *CustomerInfo`

NewCustomerInfoWithDefaults instantiates a new CustomerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnnualVolume

`func (o *CustomerInfo) GetAnnualVolume() int32`

GetAnnualVolume returns the AnnualVolume field if non-nil, zero value otherwise.

### GetAnnualVolumeOk

`func (o *CustomerInfo) GetAnnualVolumeOk() (*int32, bool)`

GetAnnualVolumeOk returns a tuple with the AnnualVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnualVolume

`func (o *CustomerInfo) SetAnnualVolume(v int32)`

SetAnnualVolume sets AnnualVolume field to given value.


### GetIsRegistered

`func (o *CustomerInfo) GetIsRegistered() bool`

GetIsRegistered returns the IsRegistered field if non-nil, zero value otherwise.

### GetIsRegisteredOk

`func (o *CustomerInfo) GetIsRegisteredOk() (*bool, bool)`

GetIsRegisteredOk returns a tuple with the IsRegistered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRegistered

`func (o *CustomerInfo) SetIsRegistered(v bool)`

SetIsRegistered sets IsRegistered field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


