# TenantSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompanyType** | [**CompanyType**](CompanyType.md) |  | 
**DpaAcceptedAt** | Pointer to **NullableTime** |  | [optional] 
**DpaAcceptedBy** | Pointer to **NullableString** |  | [optional] 
**DpaVersion** | Pointer to **NullableString** |  | [optional] 
**Features** | **interface{}** | Active feature toggles for the tenant. | 

## Methods

### NewTenantSettings

`func NewTenantSettings(companyType CompanyType, features interface{}, ) *TenantSettings`

NewTenantSettings instantiates a new TenantSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTenantSettingsWithDefaults

`func NewTenantSettingsWithDefaults() *TenantSettings`

NewTenantSettingsWithDefaults instantiates a new TenantSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompanyType

`func (o *TenantSettings) GetCompanyType() CompanyType`

GetCompanyType returns the CompanyType field if non-nil, zero value otherwise.

### GetCompanyTypeOk

`func (o *TenantSettings) GetCompanyTypeOk() (*CompanyType, bool)`

GetCompanyTypeOk returns a tuple with the CompanyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyType

`func (o *TenantSettings) SetCompanyType(v CompanyType)`

SetCompanyType sets CompanyType field to given value.


### GetDpaAcceptedAt

`func (o *TenantSettings) GetDpaAcceptedAt() time.Time`

GetDpaAcceptedAt returns the DpaAcceptedAt field if non-nil, zero value otherwise.

### GetDpaAcceptedAtOk

`func (o *TenantSettings) GetDpaAcceptedAtOk() (*time.Time, bool)`

GetDpaAcceptedAtOk returns a tuple with the DpaAcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpaAcceptedAt

`func (o *TenantSettings) SetDpaAcceptedAt(v time.Time)`

SetDpaAcceptedAt sets DpaAcceptedAt field to given value.

### HasDpaAcceptedAt

`func (o *TenantSettings) HasDpaAcceptedAt() bool`

HasDpaAcceptedAt returns a boolean if a field has been set.

### SetDpaAcceptedAtNil

`func (o *TenantSettings) SetDpaAcceptedAtNil(b bool)`

 SetDpaAcceptedAtNil sets the value for DpaAcceptedAt to be an explicit nil

### UnsetDpaAcceptedAt
`func (o *TenantSettings) UnsetDpaAcceptedAt()`

UnsetDpaAcceptedAt ensures that no value is present for DpaAcceptedAt, not even an explicit nil
### GetDpaAcceptedBy

`func (o *TenantSettings) GetDpaAcceptedBy() string`

GetDpaAcceptedBy returns the DpaAcceptedBy field if non-nil, zero value otherwise.

### GetDpaAcceptedByOk

`func (o *TenantSettings) GetDpaAcceptedByOk() (*string, bool)`

GetDpaAcceptedByOk returns a tuple with the DpaAcceptedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpaAcceptedBy

`func (o *TenantSettings) SetDpaAcceptedBy(v string)`

SetDpaAcceptedBy sets DpaAcceptedBy field to given value.

### HasDpaAcceptedBy

`func (o *TenantSettings) HasDpaAcceptedBy() bool`

HasDpaAcceptedBy returns a boolean if a field has been set.

### SetDpaAcceptedByNil

`func (o *TenantSettings) SetDpaAcceptedByNil(b bool)`

 SetDpaAcceptedByNil sets the value for DpaAcceptedBy to be an explicit nil

### UnsetDpaAcceptedBy
`func (o *TenantSettings) UnsetDpaAcceptedBy()`

UnsetDpaAcceptedBy ensures that no value is present for DpaAcceptedBy, not even an explicit nil
### GetDpaVersion

`func (o *TenantSettings) GetDpaVersion() string`

GetDpaVersion returns the DpaVersion field if non-nil, zero value otherwise.

### GetDpaVersionOk

`func (o *TenantSettings) GetDpaVersionOk() (*string, bool)`

GetDpaVersionOk returns a tuple with the DpaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpaVersion

`func (o *TenantSettings) SetDpaVersion(v string)`

SetDpaVersion sets DpaVersion field to given value.

### HasDpaVersion

`func (o *TenantSettings) HasDpaVersion() bool`

HasDpaVersion returns a boolean if a field has been set.

### SetDpaVersionNil

`func (o *TenantSettings) SetDpaVersionNil(b bool)`

 SetDpaVersionNil sets the value for DpaVersion to be an explicit nil

### UnsetDpaVersion
`func (o *TenantSettings) UnsetDpaVersion()`

UnsetDpaVersion ensures that no value is present for DpaVersion, not even an explicit nil
### GetFeatures

`func (o *TenantSettings) GetFeatures() interface{}`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *TenantSettings) GetFeaturesOk() (*interface{}, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *TenantSettings) SetFeatures(v interface{})`

SetFeatures sets Features field to given value.


### SetFeaturesNil

`func (o *TenantSettings) SetFeaturesNil(b bool)`

 SetFeaturesNil sets the value for Features to be an explicit nil

### UnsetFeatures
`func (o *TenantSettings) UnsetFeatures()`

UnsetFeatures ensures that no value is present for Features, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


