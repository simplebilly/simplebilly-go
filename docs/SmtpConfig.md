# SmtpConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Encryption** | [**SmtpEncryption**](SmtpEncryption.md) |  | 
**FromAddress** | **string** |  | 
**FromName** | Pointer to **NullableString** |  | [optional] 
**Host** | **string** |  | 
**Password** | **string** |  | 
**Port** | **int32** |  | 
**TimeoutSeconds** | Pointer to **NullableInt64** |  | [optional] 
**Username** | **string** |  | 

## Methods

### NewSmtpConfig

`func NewSmtpConfig(encryption SmtpEncryption, fromAddress string, host string, password string, port int32, username string, ) *SmtpConfig`

NewSmtpConfig instantiates a new SmtpConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmtpConfigWithDefaults

`func NewSmtpConfigWithDefaults() *SmtpConfig`

NewSmtpConfigWithDefaults instantiates a new SmtpConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEncryption

`func (o *SmtpConfig) GetEncryption() SmtpEncryption`

GetEncryption returns the Encryption field if non-nil, zero value otherwise.

### GetEncryptionOk

`func (o *SmtpConfig) GetEncryptionOk() (*SmtpEncryption, bool)`

GetEncryptionOk returns a tuple with the Encryption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryption

`func (o *SmtpConfig) SetEncryption(v SmtpEncryption)`

SetEncryption sets Encryption field to given value.


### GetFromAddress

`func (o *SmtpConfig) GetFromAddress() string`

GetFromAddress returns the FromAddress field if non-nil, zero value otherwise.

### GetFromAddressOk

`func (o *SmtpConfig) GetFromAddressOk() (*string, bool)`

GetFromAddressOk returns a tuple with the FromAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromAddress

`func (o *SmtpConfig) SetFromAddress(v string)`

SetFromAddress sets FromAddress field to given value.


### GetFromName

`func (o *SmtpConfig) GetFromName() string`

GetFromName returns the FromName field if non-nil, zero value otherwise.

### GetFromNameOk

`func (o *SmtpConfig) GetFromNameOk() (*string, bool)`

GetFromNameOk returns a tuple with the FromName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromName

`func (o *SmtpConfig) SetFromName(v string)`

SetFromName sets FromName field to given value.

### HasFromName

`func (o *SmtpConfig) HasFromName() bool`

HasFromName returns a boolean if a field has been set.

### SetFromNameNil

`func (o *SmtpConfig) SetFromNameNil(b bool)`

 SetFromNameNil sets the value for FromName to be an explicit nil

### UnsetFromName
`func (o *SmtpConfig) UnsetFromName()`

UnsetFromName ensures that no value is present for FromName, not even an explicit nil
### GetHost

`func (o *SmtpConfig) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *SmtpConfig) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *SmtpConfig) SetHost(v string)`

SetHost sets Host field to given value.


### GetPassword

`func (o *SmtpConfig) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *SmtpConfig) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *SmtpConfig) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetPort

`func (o *SmtpConfig) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *SmtpConfig) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *SmtpConfig) SetPort(v int32)`

SetPort sets Port field to given value.


### GetTimeoutSeconds

`func (o *SmtpConfig) GetTimeoutSeconds() int64`

GetTimeoutSeconds returns the TimeoutSeconds field if non-nil, zero value otherwise.

### GetTimeoutSecondsOk

`func (o *SmtpConfig) GetTimeoutSecondsOk() (*int64, bool)`

GetTimeoutSecondsOk returns a tuple with the TimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeoutSeconds

`func (o *SmtpConfig) SetTimeoutSeconds(v int64)`

SetTimeoutSeconds sets TimeoutSeconds field to given value.

### HasTimeoutSeconds

`func (o *SmtpConfig) HasTimeoutSeconds() bool`

HasTimeoutSeconds returns a boolean if a field has been set.

### SetTimeoutSecondsNil

`func (o *SmtpConfig) SetTimeoutSecondsNil(b bool)`

 SetTimeoutSecondsNil sets the value for TimeoutSeconds to be an explicit nil

### UnsetTimeoutSeconds
`func (o *SmtpConfig) UnsetTimeoutSeconds()`

UnsetTimeoutSeconds ensures that no value is present for TimeoutSeconds, not even an explicit nil
### GetUsername

`func (o *SmtpConfig) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *SmtpConfig) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *SmtpConfig) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


