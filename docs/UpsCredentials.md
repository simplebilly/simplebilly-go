# UpsCredentials

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientId** | **string** | OAuth 2.0 client credentials from developer.ups.com. | 
**ClientSecret** | **string** |  | 
**ShipperNumber** | Pointer to **NullableString** | UPS account number; required for label creation, optional for rates/tracking. | [optional] 

## Methods

### NewUpsCredentials

`func NewUpsCredentials(clientId string, clientSecret string, ) *UpsCredentials`

NewUpsCredentials instantiates a new UpsCredentials object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpsCredentialsWithDefaults

`func NewUpsCredentialsWithDefaults() *UpsCredentials`

NewUpsCredentialsWithDefaults instantiates a new UpsCredentials object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientId

`func (o *UpsCredentials) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *UpsCredentials) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *UpsCredentials) SetClientId(v string)`

SetClientId sets ClientId field to given value.


### GetClientSecret

`func (o *UpsCredentials) GetClientSecret() string`

GetClientSecret returns the ClientSecret field if non-nil, zero value otherwise.

### GetClientSecretOk

`func (o *UpsCredentials) GetClientSecretOk() (*string, bool)`

GetClientSecretOk returns a tuple with the ClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSecret

`func (o *UpsCredentials) SetClientSecret(v string)`

SetClientSecret sets ClientSecret field to given value.


### GetShipperNumber

`func (o *UpsCredentials) GetShipperNumber() string`

GetShipperNumber returns the ShipperNumber field if non-nil, zero value otherwise.

### GetShipperNumberOk

`func (o *UpsCredentials) GetShipperNumberOk() (*string, bool)`

GetShipperNumberOk returns a tuple with the ShipperNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipperNumber

`func (o *UpsCredentials) SetShipperNumber(v string)`

SetShipperNumber sets ShipperNumber field to given value.

### HasShipperNumber

`func (o *UpsCredentials) HasShipperNumber() bool`

HasShipperNumber returns a boolean if a field has been set.

### SetShipperNumberNil

`func (o *UpsCredentials) SetShipperNumberNil(b bool)`

 SetShipperNumberNil sets the value for ShipperNumber to be an explicit nil

### UnsetShipperNumber
`func (o *UpsCredentials) UnsetShipperNumber()`

UnsetShipperNumber ensures that no value is present for ShipperNumber, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


