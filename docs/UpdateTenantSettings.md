# UpdateTenantSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompanyType** | [**CompanyType**](CompanyType.md) |  | 
**Features** | Pointer to [**NullablePartialFeatureSettings**](PartialFeatureSettings.md) |  | [optional] 

## Methods

### NewUpdateTenantSettings

`func NewUpdateTenantSettings(companyType CompanyType, ) *UpdateTenantSettings`

NewUpdateTenantSettings instantiates a new UpdateTenantSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateTenantSettingsWithDefaults

`func NewUpdateTenantSettingsWithDefaults() *UpdateTenantSettings`

NewUpdateTenantSettingsWithDefaults instantiates a new UpdateTenantSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompanyType

`func (o *UpdateTenantSettings) GetCompanyType() CompanyType`

GetCompanyType returns the CompanyType field if non-nil, zero value otherwise.

### GetCompanyTypeOk

`func (o *UpdateTenantSettings) GetCompanyTypeOk() (*CompanyType, bool)`

GetCompanyTypeOk returns a tuple with the CompanyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyType

`func (o *UpdateTenantSettings) SetCompanyType(v CompanyType)`

SetCompanyType sets CompanyType field to given value.


### GetFeatures

`func (o *UpdateTenantSettings) GetFeatures() PartialFeatureSettings`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *UpdateTenantSettings) GetFeaturesOk() (*PartialFeatureSettings, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *UpdateTenantSettings) SetFeatures(v PartialFeatureSettings)`

SetFeatures sets Features field to given value.

### HasFeatures

`func (o *UpdateTenantSettings) HasFeatures() bool`

HasFeatures returns a boolean if a field has been set.

### SetFeaturesNil

`func (o *UpdateTenantSettings) SetFeaturesNil(b bool)`

 SetFeaturesNil sets the value for Features to be an explicit nil

### UnsetFeatures
`func (o *UpdateTenantSettings) UnsetFeatures()`

UnsetFeatures ensures that no value is present for Features, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


