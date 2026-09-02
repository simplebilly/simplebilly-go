# TotpSetupResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BackupCodes** | **[]string** |  | 
**QrCodeUrl** | **string** |  | 
**Secret** | **string** |  | 

## Methods

### NewTotpSetupResponse

`func NewTotpSetupResponse(backupCodes []string, qrCodeUrl string, secret string, ) *TotpSetupResponse`

NewTotpSetupResponse instantiates a new TotpSetupResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTotpSetupResponseWithDefaults

`func NewTotpSetupResponseWithDefaults() *TotpSetupResponse`

NewTotpSetupResponseWithDefaults instantiates a new TotpSetupResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackupCodes

`func (o *TotpSetupResponse) GetBackupCodes() []string`

GetBackupCodes returns the BackupCodes field if non-nil, zero value otherwise.

### GetBackupCodesOk

`func (o *TotpSetupResponse) GetBackupCodesOk() (*[]string, bool)`

GetBackupCodesOk returns a tuple with the BackupCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupCodes

`func (o *TotpSetupResponse) SetBackupCodes(v []string)`

SetBackupCodes sets BackupCodes field to given value.


### GetQrCodeUrl

`func (o *TotpSetupResponse) GetQrCodeUrl() string`

GetQrCodeUrl returns the QrCodeUrl field if non-nil, zero value otherwise.

### GetQrCodeUrlOk

`func (o *TotpSetupResponse) GetQrCodeUrlOk() (*string, bool)`

GetQrCodeUrlOk returns a tuple with the QrCodeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeUrl

`func (o *TotpSetupResponse) SetQrCodeUrl(v string)`

SetQrCodeUrl sets QrCodeUrl field to given value.


### GetSecret

`func (o *TotpSetupResponse) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *TotpSetupResponse) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *TotpSetupResponse) SetSecret(v string)`

SetSecret sets Secret field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


