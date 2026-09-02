# ProviderInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DisplayName** | **string** |  | 
**Name** | **string** |  | 
**RequiresApiKey** | **bool** |  | 
**Services** | **[]string** |  | 
**SupportsLabelCreation** | **bool** |  | 
**SupportsRateEstimation** | **bool** |  | 
**SupportsTracking** | **bool** |  | 

## Methods

### NewProviderInfo

`func NewProviderInfo(displayName string, name string, requiresApiKey bool, services []string, supportsLabelCreation bool, supportsRateEstimation bool, supportsTracking bool, ) *ProviderInfo`

NewProviderInfo instantiates a new ProviderInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProviderInfoWithDefaults

`func NewProviderInfoWithDefaults() *ProviderInfo`

NewProviderInfoWithDefaults instantiates a new ProviderInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDisplayName

`func (o *ProviderInfo) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *ProviderInfo) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *ProviderInfo) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.


### GetName

`func (o *ProviderInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProviderInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProviderInfo) SetName(v string)`

SetName sets Name field to given value.


### GetRequiresApiKey

`func (o *ProviderInfo) GetRequiresApiKey() bool`

GetRequiresApiKey returns the RequiresApiKey field if non-nil, zero value otherwise.

### GetRequiresApiKeyOk

`func (o *ProviderInfo) GetRequiresApiKeyOk() (*bool, bool)`

GetRequiresApiKeyOk returns a tuple with the RequiresApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresApiKey

`func (o *ProviderInfo) SetRequiresApiKey(v bool)`

SetRequiresApiKey sets RequiresApiKey field to given value.


### GetServices

`func (o *ProviderInfo) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *ProviderInfo) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *ProviderInfo) SetServices(v []string)`

SetServices sets Services field to given value.


### GetSupportsLabelCreation

`func (o *ProviderInfo) GetSupportsLabelCreation() bool`

GetSupportsLabelCreation returns the SupportsLabelCreation field if non-nil, zero value otherwise.

### GetSupportsLabelCreationOk

`func (o *ProviderInfo) GetSupportsLabelCreationOk() (*bool, bool)`

GetSupportsLabelCreationOk returns a tuple with the SupportsLabelCreation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsLabelCreation

`func (o *ProviderInfo) SetSupportsLabelCreation(v bool)`

SetSupportsLabelCreation sets SupportsLabelCreation field to given value.


### GetSupportsRateEstimation

`func (o *ProviderInfo) GetSupportsRateEstimation() bool`

GetSupportsRateEstimation returns the SupportsRateEstimation field if non-nil, zero value otherwise.

### GetSupportsRateEstimationOk

`func (o *ProviderInfo) GetSupportsRateEstimationOk() (*bool, bool)`

GetSupportsRateEstimationOk returns a tuple with the SupportsRateEstimation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsRateEstimation

`func (o *ProviderInfo) SetSupportsRateEstimation(v bool)`

SetSupportsRateEstimation sets SupportsRateEstimation field to given value.


### GetSupportsTracking

`func (o *ProviderInfo) GetSupportsTracking() bool`

GetSupportsTracking returns the SupportsTracking field if non-nil, zero value otherwise.

### GetSupportsTrackingOk

`func (o *ProviderInfo) GetSupportsTrackingOk() (*bool, bool)`

GetSupportsTrackingOk returns a tuple with the SupportsTracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsTracking

`func (o *ProviderInfo) SetSupportsTracking(v bool)`

SetSupportsTracking sets SupportsTracking field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


