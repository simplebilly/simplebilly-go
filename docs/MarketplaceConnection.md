# MarketplaceConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | **interface{}** |  | 
**ConnectionId** | **string** |  | 
**ConnectorType** | [**ConnectorType**](ConnectorType.md) |  | 
**CreatedAt** | **time.Time** |  | 
**IsActive** | **bool** |  | 
**Label** | **string** |  | 
**LastSyncAt** | Pointer to **NullableTime** |  | [optional] 
**Platform** | **string** |  | 
**PlatformUserId** | Pointer to **NullableString** |  | [optional] 
**Scopes** | Pointer to **NullableString** |  | [optional] 
**ShopDomain** | Pointer to **NullableString** |  | [optional] 
**ShopName** | Pointer to **NullableString** |  | [optional] 
**SyncStatus** | Pointer to **NullableString** |  | [optional] 
**TenantId** | **string** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewMarketplaceConnection

`func NewMarketplaceConnection(config interface{}, connectionId string, connectorType ConnectorType, createdAt time.Time, isActive bool, label string, platform string, tenantId string, ) *MarketplaceConnection`

NewMarketplaceConnection instantiates a new MarketplaceConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMarketplaceConnectionWithDefaults

`func NewMarketplaceConnectionWithDefaults() *MarketplaceConnection`

NewMarketplaceConnectionWithDefaults instantiates a new MarketplaceConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *MarketplaceConnection) GetConfig() interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *MarketplaceConnection) GetConfigOk() (*interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *MarketplaceConnection) SetConfig(v interface{})`

SetConfig sets Config field to given value.


### SetConfigNil

`func (o *MarketplaceConnection) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *MarketplaceConnection) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetConnectionId

`func (o *MarketplaceConnection) GetConnectionId() string`

GetConnectionId returns the ConnectionId field if non-nil, zero value otherwise.

### GetConnectionIdOk

`func (o *MarketplaceConnection) GetConnectionIdOk() (*string, bool)`

GetConnectionIdOk returns a tuple with the ConnectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionId

`func (o *MarketplaceConnection) SetConnectionId(v string)`

SetConnectionId sets ConnectionId field to given value.


### GetConnectorType

`func (o *MarketplaceConnection) GetConnectorType() ConnectorType`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *MarketplaceConnection) GetConnectorTypeOk() (*ConnectorType, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *MarketplaceConnection) SetConnectorType(v ConnectorType)`

SetConnectorType sets ConnectorType field to given value.


### GetCreatedAt

`func (o *MarketplaceConnection) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MarketplaceConnection) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MarketplaceConnection) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetIsActive

`func (o *MarketplaceConnection) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *MarketplaceConnection) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *MarketplaceConnection) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetLabel

`func (o *MarketplaceConnection) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *MarketplaceConnection) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *MarketplaceConnection) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetLastSyncAt

`func (o *MarketplaceConnection) GetLastSyncAt() time.Time`

GetLastSyncAt returns the LastSyncAt field if non-nil, zero value otherwise.

### GetLastSyncAtOk

`func (o *MarketplaceConnection) GetLastSyncAtOk() (*time.Time, bool)`

GetLastSyncAtOk returns a tuple with the LastSyncAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncAt

`func (o *MarketplaceConnection) SetLastSyncAt(v time.Time)`

SetLastSyncAt sets LastSyncAt field to given value.

### HasLastSyncAt

`func (o *MarketplaceConnection) HasLastSyncAt() bool`

HasLastSyncAt returns a boolean if a field has been set.

### SetLastSyncAtNil

`func (o *MarketplaceConnection) SetLastSyncAtNil(b bool)`

 SetLastSyncAtNil sets the value for LastSyncAt to be an explicit nil

### UnsetLastSyncAt
`func (o *MarketplaceConnection) UnsetLastSyncAt()`

UnsetLastSyncAt ensures that no value is present for LastSyncAt, not even an explicit nil
### GetPlatform

`func (o *MarketplaceConnection) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *MarketplaceConnection) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *MarketplaceConnection) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetPlatformUserId

`func (o *MarketplaceConnection) GetPlatformUserId() string`

GetPlatformUserId returns the PlatformUserId field if non-nil, zero value otherwise.

### GetPlatformUserIdOk

`func (o *MarketplaceConnection) GetPlatformUserIdOk() (*string, bool)`

GetPlatformUserIdOk returns a tuple with the PlatformUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformUserId

`func (o *MarketplaceConnection) SetPlatformUserId(v string)`

SetPlatformUserId sets PlatformUserId field to given value.

### HasPlatformUserId

`func (o *MarketplaceConnection) HasPlatformUserId() bool`

HasPlatformUserId returns a boolean if a field has been set.

### SetPlatformUserIdNil

`func (o *MarketplaceConnection) SetPlatformUserIdNil(b bool)`

 SetPlatformUserIdNil sets the value for PlatformUserId to be an explicit nil

### UnsetPlatformUserId
`func (o *MarketplaceConnection) UnsetPlatformUserId()`

UnsetPlatformUserId ensures that no value is present for PlatformUserId, not even an explicit nil
### GetScopes

`func (o *MarketplaceConnection) GetScopes() string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *MarketplaceConnection) GetScopesOk() (*string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *MarketplaceConnection) SetScopes(v string)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *MarketplaceConnection) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### SetScopesNil

`func (o *MarketplaceConnection) SetScopesNil(b bool)`

 SetScopesNil sets the value for Scopes to be an explicit nil

### UnsetScopes
`func (o *MarketplaceConnection) UnsetScopes()`

UnsetScopes ensures that no value is present for Scopes, not even an explicit nil
### GetShopDomain

`func (o *MarketplaceConnection) GetShopDomain() string`

GetShopDomain returns the ShopDomain field if non-nil, zero value otherwise.

### GetShopDomainOk

`func (o *MarketplaceConnection) GetShopDomainOk() (*string, bool)`

GetShopDomainOk returns a tuple with the ShopDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShopDomain

`func (o *MarketplaceConnection) SetShopDomain(v string)`

SetShopDomain sets ShopDomain field to given value.

### HasShopDomain

`func (o *MarketplaceConnection) HasShopDomain() bool`

HasShopDomain returns a boolean if a field has been set.

### SetShopDomainNil

`func (o *MarketplaceConnection) SetShopDomainNil(b bool)`

 SetShopDomainNil sets the value for ShopDomain to be an explicit nil

### UnsetShopDomain
`func (o *MarketplaceConnection) UnsetShopDomain()`

UnsetShopDomain ensures that no value is present for ShopDomain, not even an explicit nil
### GetShopName

`func (o *MarketplaceConnection) GetShopName() string`

GetShopName returns the ShopName field if non-nil, zero value otherwise.

### GetShopNameOk

`func (o *MarketplaceConnection) GetShopNameOk() (*string, bool)`

GetShopNameOk returns a tuple with the ShopName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShopName

`func (o *MarketplaceConnection) SetShopName(v string)`

SetShopName sets ShopName field to given value.

### HasShopName

`func (o *MarketplaceConnection) HasShopName() bool`

HasShopName returns a boolean if a field has been set.

### SetShopNameNil

`func (o *MarketplaceConnection) SetShopNameNil(b bool)`

 SetShopNameNil sets the value for ShopName to be an explicit nil

### UnsetShopName
`func (o *MarketplaceConnection) UnsetShopName()`

UnsetShopName ensures that no value is present for ShopName, not even an explicit nil
### GetSyncStatus

`func (o *MarketplaceConnection) GetSyncStatus() string`

GetSyncStatus returns the SyncStatus field if non-nil, zero value otherwise.

### GetSyncStatusOk

`func (o *MarketplaceConnection) GetSyncStatusOk() (*string, bool)`

GetSyncStatusOk returns a tuple with the SyncStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncStatus

`func (o *MarketplaceConnection) SetSyncStatus(v string)`

SetSyncStatus sets SyncStatus field to given value.

### HasSyncStatus

`func (o *MarketplaceConnection) HasSyncStatus() bool`

HasSyncStatus returns a boolean if a field has been set.

### SetSyncStatusNil

`func (o *MarketplaceConnection) SetSyncStatusNil(b bool)`

 SetSyncStatusNil sets the value for SyncStatus to be an explicit nil

### UnsetSyncStatus
`func (o *MarketplaceConnection) UnsetSyncStatus()`

UnsetSyncStatus ensures that no value is present for SyncStatus, not even an explicit nil
### GetTenantId

`func (o *MarketplaceConnection) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *MarketplaceConnection) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *MarketplaceConnection) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetUpdatedAt

`func (o *MarketplaceConnection) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *MarketplaceConnection) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *MarketplaceConnection) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *MarketplaceConnection) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *MarketplaceConnection) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *MarketplaceConnection) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


