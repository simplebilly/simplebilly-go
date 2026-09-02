# GatewayOAuthAuthorizeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GatewayType** | **string** |  | 
**RedirectUri** | **string** |  | 

## Methods

### NewGatewayOAuthAuthorizeRequest

`func NewGatewayOAuthAuthorizeRequest(gatewayType string, redirectUri string, ) *GatewayOAuthAuthorizeRequest`

NewGatewayOAuthAuthorizeRequest instantiates a new GatewayOAuthAuthorizeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGatewayOAuthAuthorizeRequestWithDefaults

`func NewGatewayOAuthAuthorizeRequestWithDefaults() *GatewayOAuthAuthorizeRequest`

NewGatewayOAuthAuthorizeRequestWithDefaults instantiates a new GatewayOAuthAuthorizeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGatewayType

`func (o *GatewayOAuthAuthorizeRequest) GetGatewayType() string`

GetGatewayType returns the GatewayType field if non-nil, zero value otherwise.

### GetGatewayTypeOk

`func (o *GatewayOAuthAuthorizeRequest) GetGatewayTypeOk() (*string, bool)`

GetGatewayTypeOk returns a tuple with the GatewayType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayType

`func (o *GatewayOAuthAuthorizeRequest) SetGatewayType(v string)`

SetGatewayType sets GatewayType field to given value.


### GetRedirectUri

`func (o *GatewayOAuthAuthorizeRequest) GetRedirectUri() string`

GetRedirectUri returns the RedirectUri field if non-nil, zero value otherwise.

### GetRedirectUriOk

`func (o *GatewayOAuthAuthorizeRequest) GetRedirectUriOk() (*string, bool)`

GetRedirectUriOk returns a tuple with the RedirectUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUri

`func (o *GatewayOAuthAuthorizeRequest) SetRedirectUri(v string)`

SetRedirectUri sets RedirectUri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


