# ElsterStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertConfigured** | **bool** |  | 
**EricAvailable** | **bool** |  | 
**EricVersion** | Pointer to **NullableString** |  | [optional] 
**FeatureEnabled** | **bool** |  | 
**Hint** | **string** |  | 
**Mode** | **string** |  | 
**VendorIdConfigured** | **bool** |  | 

## Methods

### NewElsterStatus

`func NewElsterStatus(certConfigured bool, ericAvailable bool, featureEnabled bool, hint string, mode string, vendorIdConfigured bool, ) *ElsterStatus`

NewElsterStatus instantiates a new ElsterStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewElsterStatusWithDefaults

`func NewElsterStatusWithDefaults() *ElsterStatus`

NewElsterStatusWithDefaults instantiates a new ElsterStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertConfigured

`func (o *ElsterStatus) GetCertConfigured() bool`

GetCertConfigured returns the CertConfigured field if non-nil, zero value otherwise.

### GetCertConfiguredOk

`func (o *ElsterStatus) GetCertConfiguredOk() (*bool, bool)`

GetCertConfiguredOk returns a tuple with the CertConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertConfigured

`func (o *ElsterStatus) SetCertConfigured(v bool)`

SetCertConfigured sets CertConfigured field to given value.


### GetEricAvailable

`func (o *ElsterStatus) GetEricAvailable() bool`

GetEricAvailable returns the EricAvailable field if non-nil, zero value otherwise.

### GetEricAvailableOk

`func (o *ElsterStatus) GetEricAvailableOk() (*bool, bool)`

GetEricAvailableOk returns a tuple with the EricAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEricAvailable

`func (o *ElsterStatus) SetEricAvailable(v bool)`

SetEricAvailable sets EricAvailable field to given value.


### GetEricVersion

`func (o *ElsterStatus) GetEricVersion() string`

GetEricVersion returns the EricVersion field if non-nil, zero value otherwise.

### GetEricVersionOk

`func (o *ElsterStatus) GetEricVersionOk() (*string, bool)`

GetEricVersionOk returns a tuple with the EricVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEricVersion

`func (o *ElsterStatus) SetEricVersion(v string)`

SetEricVersion sets EricVersion field to given value.

### HasEricVersion

`func (o *ElsterStatus) HasEricVersion() bool`

HasEricVersion returns a boolean if a field has been set.

### SetEricVersionNil

`func (o *ElsterStatus) SetEricVersionNil(b bool)`

 SetEricVersionNil sets the value for EricVersion to be an explicit nil

### UnsetEricVersion
`func (o *ElsterStatus) UnsetEricVersion()`

UnsetEricVersion ensures that no value is present for EricVersion, not even an explicit nil
### GetFeatureEnabled

`func (o *ElsterStatus) GetFeatureEnabled() bool`

GetFeatureEnabled returns the FeatureEnabled field if non-nil, zero value otherwise.

### GetFeatureEnabledOk

`func (o *ElsterStatus) GetFeatureEnabledOk() (*bool, bool)`

GetFeatureEnabledOk returns a tuple with the FeatureEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureEnabled

`func (o *ElsterStatus) SetFeatureEnabled(v bool)`

SetFeatureEnabled sets FeatureEnabled field to given value.


### GetHint

`func (o *ElsterStatus) GetHint() string`

GetHint returns the Hint field if non-nil, zero value otherwise.

### GetHintOk

`func (o *ElsterStatus) GetHintOk() (*string, bool)`

GetHintOk returns a tuple with the Hint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHint

`func (o *ElsterStatus) SetHint(v string)`

SetHint sets Hint field to given value.


### GetMode

`func (o *ElsterStatus) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *ElsterStatus) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *ElsterStatus) SetMode(v string)`

SetMode sets Mode field to given value.


### GetVendorIdConfigured

`func (o *ElsterStatus) GetVendorIdConfigured() bool`

GetVendorIdConfigured returns the VendorIdConfigured field if non-nil, zero value otherwise.

### GetVendorIdConfiguredOk

`func (o *ElsterStatus) GetVendorIdConfiguredOk() (*bool, bool)`

GetVendorIdConfiguredOk returns a tuple with the VendorIdConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendorIdConfigured

`func (o *ElsterStatus) SetVendorIdConfigured(v bool)`

SetVendorIdConfigured sets VendorIdConfigured field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


