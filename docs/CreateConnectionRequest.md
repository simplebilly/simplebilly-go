# CreateConnectionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | Pointer to **NullableString** |  | [optional] 
**ApiSecret** | Pointer to **NullableString** |  | [optional] 
**Config** | Pointer to **interface{}** |  | [optional] 
**Label** | **string** |  | 
**Platform** | **string** |  | 
**ShopDomain** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateConnectionRequest

`func NewCreateConnectionRequest(label string, platform string, ) *CreateConnectionRequest`

NewCreateConnectionRequest instantiates a new CreateConnectionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateConnectionRequestWithDefaults

`func NewCreateConnectionRequestWithDefaults() *CreateConnectionRequest`

NewCreateConnectionRequestWithDefaults instantiates a new CreateConnectionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKey

`func (o *CreateConnectionRequest) GetApiKey() string`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *CreateConnectionRequest) GetApiKeyOk() (*string, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *CreateConnectionRequest) SetApiKey(v string)`

SetApiKey sets ApiKey field to given value.

### HasApiKey

`func (o *CreateConnectionRequest) HasApiKey() bool`

HasApiKey returns a boolean if a field has been set.

### SetApiKeyNil

`func (o *CreateConnectionRequest) SetApiKeyNil(b bool)`

 SetApiKeyNil sets the value for ApiKey to be an explicit nil

### UnsetApiKey
`func (o *CreateConnectionRequest) UnsetApiKey()`

UnsetApiKey ensures that no value is present for ApiKey, not even an explicit nil
### GetApiSecret

`func (o *CreateConnectionRequest) GetApiSecret() string`

GetApiSecret returns the ApiSecret field if non-nil, zero value otherwise.

### GetApiSecretOk

`func (o *CreateConnectionRequest) GetApiSecretOk() (*string, bool)`

GetApiSecretOk returns a tuple with the ApiSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiSecret

`func (o *CreateConnectionRequest) SetApiSecret(v string)`

SetApiSecret sets ApiSecret field to given value.

### HasApiSecret

`func (o *CreateConnectionRequest) HasApiSecret() bool`

HasApiSecret returns a boolean if a field has been set.

### SetApiSecretNil

`func (o *CreateConnectionRequest) SetApiSecretNil(b bool)`

 SetApiSecretNil sets the value for ApiSecret to be an explicit nil

### UnsetApiSecret
`func (o *CreateConnectionRequest) UnsetApiSecret()`

UnsetApiSecret ensures that no value is present for ApiSecret, not even an explicit nil
### GetConfig

`func (o *CreateConnectionRequest) GetConfig() interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateConnectionRequest) GetConfigOk() (*interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateConnectionRequest) SetConfig(v interface{})`

SetConfig sets Config field to given value.

### HasConfig

`func (o *CreateConnectionRequest) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *CreateConnectionRequest) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *CreateConnectionRequest) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetLabel

`func (o *CreateConnectionRequest) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateConnectionRequest) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateConnectionRequest) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetPlatform

`func (o *CreateConnectionRequest) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *CreateConnectionRequest) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *CreateConnectionRequest) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetShopDomain

`func (o *CreateConnectionRequest) GetShopDomain() string`

GetShopDomain returns the ShopDomain field if non-nil, zero value otherwise.

### GetShopDomainOk

`func (o *CreateConnectionRequest) GetShopDomainOk() (*string, bool)`

GetShopDomainOk returns a tuple with the ShopDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShopDomain

`func (o *CreateConnectionRequest) SetShopDomain(v string)`

SetShopDomain sets ShopDomain field to given value.

### HasShopDomain

`func (o *CreateConnectionRequest) HasShopDomain() bool`

HasShopDomain returns a boolean if a field has been set.

### SetShopDomainNil

`func (o *CreateConnectionRequest) SetShopDomainNil(b bool)`

 SetShopDomainNil sets the value for ShopDomain to be an explicit nil

### UnsetShopDomain
`func (o *CreateConnectionRequest) UnsetShopDomain()`

UnsetShopDomain ensures that no value is present for ShopDomain, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


