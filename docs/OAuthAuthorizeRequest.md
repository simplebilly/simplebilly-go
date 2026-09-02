# OAuthAuthorizeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | Pointer to **interface{}** | Optional platform-specific config (e.g. Shopify &#x60;shop_domain&#x60;, &#x60;api_key&#x60;, &#x60;api_secret&#x60;) needed to build the authorization URL. | [optional] 
**Platform** | **string** |  | 
**RedirectUri** | **string** |  | 

## Methods

### NewOAuthAuthorizeRequest

`func NewOAuthAuthorizeRequest(platform string, redirectUri string, ) *OAuthAuthorizeRequest`

NewOAuthAuthorizeRequest instantiates a new OAuthAuthorizeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOAuthAuthorizeRequestWithDefaults

`func NewOAuthAuthorizeRequestWithDefaults() *OAuthAuthorizeRequest`

NewOAuthAuthorizeRequestWithDefaults instantiates a new OAuthAuthorizeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *OAuthAuthorizeRequest) GetConfig() interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *OAuthAuthorizeRequest) GetConfigOk() (*interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *OAuthAuthorizeRequest) SetConfig(v interface{})`

SetConfig sets Config field to given value.

### HasConfig

`func (o *OAuthAuthorizeRequest) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *OAuthAuthorizeRequest) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *OAuthAuthorizeRequest) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetPlatform

`func (o *OAuthAuthorizeRequest) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *OAuthAuthorizeRequest) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *OAuthAuthorizeRequest) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetRedirectUri

`func (o *OAuthAuthorizeRequest) GetRedirectUri() string`

GetRedirectUri returns the RedirectUri field if non-nil, zero value otherwise.

### GetRedirectUriOk

`func (o *OAuthAuthorizeRequest) GetRedirectUriOk() (*string, bool)`

GetRedirectUriOk returns a tuple with the RedirectUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUri

`func (o *OAuthAuthorizeRequest) SetRedirectUri(v string)`

SetRedirectUri sets RedirectUri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


