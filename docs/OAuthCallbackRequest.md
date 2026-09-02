# OAuthCallbackRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Config** | Pointer to **interface{}** |  | [optional] 
**ConnectionId** | Pointer to **NullableString** |  | [optional] 
**Platform** | **string** |  | 
**ShopDomain** | Pointer to **NullableString** |  | [optional] 
**State** | **string** |  | 

## Methods

### NewOAuthCallbackRequest

`func NewOAuthCallbackRequest(code string, platform string, state string, ) *OAuthCallbackRequest`

NewOAuthCallbackRequest instantiates a new OAuthCallbackRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOAuthCallbackRequestWithDefaults

`func NewOAuthCallbackRequestWithDefaults() *OAuthCallbackRequest`

NewOAuthCallbackRequestWithDefaults instantiates a new OAuthCallbackRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *OAuthCallbackRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *OAuthCallbackRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *OAuthCallbackRequest) SetCode(v string)`

SetCode sets Code field to given value.


### GetConfig

`func (o *OAuthCallbackRequest) GetConfig() interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *OAuthCallbackRequest) GetConfigOk() (*interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *OAuthCallbackRequest) SetConfig(v interface{})`

SetConfig sets Config field to given value.

### HasConfig

`func (o *OAuthCallbackRequest) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *OAuthCallbackRequest) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *OAuthCallbackRequest) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetConnectionId

`func (o *OAuthCallbackRequest) GetConnectionId() string`

GetConnectionId returns the ConnectionId field if non-nil, zero value otherwise.

### GetConnectionIdOk

`func (o *OAuthCallbackRequest) GetConnectionIdOk() (*string, bool)`

GetConnectionIdOk returns a tuple with the ConnectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionId

`func (o *OAuthCallbackRequest) SetConnectionId(v string)`

SetConnectionId sets ConnectionId field to given value.

### HasConnectionId

`func (o *OAuthCallbackRequest) HasConnectionId() bool`

HasConnectionId returns a boolean if a field has been set.

### SetConnectionIdNil

`func (o *OAuthCallbackRequest) SetConnectionIdNil(b bool)`

 SetConnectionIdNil sets the value for ConnectionId to be an explicit nil

### UnsetConnectionId
`func (o *OAuthCallbackRequest) UnsetConnectionId()`

UnsetConnectionId ensures that no value is present for ConnectionId, not even an explicit nil
### GetPlatform

`func (o *OAuthCallbackRequest) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *OAuthCallbackRequest) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *OAuthCallbackRequest) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetShopDomain

`func (o *OAuthCallbackRequest) GetShopDomain() string`

GetShopDomain returns the ShopDomain field if non-nil, zero value otherwise.

### GetShopDomainOk

`func (o *OAuthCallbackRequest) GetShopDomainOk() (*string, bool)`

GetShopDomainOk returns a tuple with the ShopDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShopDomain

`func (o *OAuthCallbackRequest) SetShopDomain(v string)`

SetShopDomain sets ShopDomain field to given value.

### HasShopDomain

`func (o *OAuthCallbackRequest) HasShopDomain() bool`

HasShopDomain returns a boolean if a field has been set.

### SetShopDomainNil

`func (o *OAuthCallbackRequest) SetShopDomainNil(b bool)`

 SetShopDomainNil sets the value for ShopDomain to be an explicit nil

### UnsetShopDomain
`func (o *OAuthCallbackRequest) UnsetShopDomain()`

UnsetShopDomain ensures that no value is present for ShopDomain, not even an explicit nil
### GetState

`func (o *OAuthCallbackRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *OAuthCallbackRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *OAuthCallbackRequest) SetState(v string)`

SetState sets State field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


