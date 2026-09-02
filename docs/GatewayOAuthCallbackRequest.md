# GatewayOAuthCallbackRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**GatewayType** | **string** |  | 
**RedirectUri** | **string** |  | 
**State** | **string** |  | 

## Methods

### NewGatewayOAuthCallbackRequest

`func NewGatewayOAuthCallbackRequest(code string, gatewayType string, redirectUri string, state string, ) *GatewayOAuthCallbackRequest`

NewGatewayOAuthCallbackRequest instantiates a new GatewayOAuthCallbackRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGatewayOAuthCallbackRequestWithDefaults

`func NewGatewayOAuthCallbackRequestWithDefaults() *GatewayOAuthCallbackRequest`

NewGatewayOAuthCallbackRequestWithDefaults instantiates a new GatewayOAuthCallbackRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *GatewayOAuthCallbackRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *GatewayOAuthCallbackRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *GatewayOAuthCallbackRequest) SetCode(v string)`

SetCode sets Code field to given value.


### GetGatewayType

`func (o *GatewayOAuthCallbackRequest) GetGatewayType() string`

GetGatewayType returns the GatewayType field if non-nil, zero value otherwise.

### GetGatewayTypeOk

`func (o *GatewayOAuthCallbackRequest) GetGatewayTypeOk() (*string, bool)`

GetGatewayTypeOk returns a tuple with the GatewayType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayType

`func (o *GatewayOAuthCallbackRequest) SetGatewayType(v string)`

SetGatewayType sets GatewayType field to given value.


### GetRedirectUri

`func (o *GatewayOAuthCallbackRequest) GetRedirectUri() string`

GetRedirectUri returns the RedirectUri field if non-nil, zero value otherwise.

### GetRedirectUriOk

`func (o *GatewayOAuthCallbackRequest) GetRedirectUriOk() (*string, bool)`

GetRedirectUriOk returns a tuple with the RedirectUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUri

`func (o *GatewayOAuthCallbackRequest) SetRedirectUri(v string)`

SetRedirectUri sets RedirectUri field to given value.


### GetState

`func (o *GatewayOAuthCallbackRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *GatewayOAuthCallbackRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *GatewayOAuthCallbackRequest) SetState(v string)`

SetState sets State field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


