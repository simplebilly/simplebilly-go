# Model

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BackupCodes** | **[]string** |  | 
**CreatedAt** | **time.Time** |  | 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 
**Email** | **string** |  | 
**EmailVerified** | **bool** |  | 
**Id** | **string** |  | 
**IsActive** | **bool** |  | 
**IsTotpEnabled** | **bool** |  | 
**LastLogin** | Pointer to **NullableTime** |  | [optional] 
**Name** | **string** |  | 
**OauthId** | Pointer to **NullableString** |  | [optional] 
**OauthProvider** | Pointer to **NullableString** |  | [optional] 
**PasswordChangedAt** | Pointer to **NullableTime** | Set on password change; auth/refresh tokens issued before this timestamp are rejected by the auth middleware. | [optional] 
**PasswordHash** | **string** |  | 
**Picture** | Pointer to **NullableString** |  | [optional] 
**PrivacyAcceptedAt** | Pointer to **NullableTime** | When the user accepted the data privacy policy (GDPR consent record). | [optional] 
**TotpSecret** | Pointer to **NullableString** |  | [optional] 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewModel

`func NewModel(backupCodes []string, createdAt time.Time, email string, emailVerified bool, id string, isActive bool, isTotpEnabled bool, name string, passwordHash string, updatedAt time.Time, ) *Model`

NewModel instantiates a new Model object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelWithDefaults

`func NewModelWithDefaults() *Model`

NewModelWithDefaults instantiates a new Model object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackupCodes

`func (o *Model) GetBackupCodes() []string`

GetBackupCodes returns the BackupCodes field if non-nil, zero value otherwise.

### GetBackupCodesOk

`func (o *Model) GetBackupCodesOk() (*[]string, bool)`

GetBackupCodesOk returns a tuple with the BackupCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupCodes

`func (o *Model) SetBackupCodes(v []string)`

SetBackupCodes sets BackupCodes field to given value.


### GetCreatedAt

`func (o *Model) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Model) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Model) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *Model) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *Model) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *Model) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *Model) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *Model) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *Model) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetEmail

`func (o *Model) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Model) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Model) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetEmailVerified

`func (o *Model) GetEmailVerified() bool`

GetEmailVerified returns the EmailVerified field if non-nil, zero value otherwise.

### GetEmailVerifiedOk

`func (o *Model) GetEmailVerifiedOk() (*bool, bool)`

GetEmailVerifiedOk returns a tuple with the EmailVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailVerified

`func (o *Model) SetEmailVerified(v bool)`

SetEmailVerified sets EmailVerified field to given value.


### GetId

`func (o *Model) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Model) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Model) SetId(v string)`

SetId sets Id field to given value.


### GetIsActive

`func (o *Model) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *Model) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *Model) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetIsTotpEnabled

`func (o *Model) GetIsTotpEnabled() bool`

GetIsTotpEnabled returns the IsTotpEnabled field if non-nil, zero value otherwise.

### GetIsTotpEnabledOk

`func (o *Model) GetIsTotpEnabledOk() (*bool, bool)`

GetIsTotpEnabledOk returns a tuple with the IsTotpEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTotpEnabled

`func (o *Model) SetIsTotpEnabled(v bool)`

SetIsTotpEnabled sets IsTotpEnabled field to given value.


### GetLastLogin

`func (o *Model) GetLastLogin() time.Time`

GetLastLogin returns the LastLogin field if non-nil, zero value otherwise.

### GetLastLoginOk

`func (o *Model) GetLastLoginOk() (*time.Time, bool)`

GetLastLoginOk returns a tuple with the LastLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLogin

`func (o *Model) SetLastLogin(v time.Time)`

SetLastLogin sets LastLogin field to given value.

### HasLastLogin

`func (o *Model) HasLastLogin() bool`

HasLastLogin returns a boolean if a field has been set.

### SetLastLoginNil

`func (o *Model) SetLastLoginNil(b bool)`

 SetLastLoginNil sets the value for LastLogin to be an explicit nil

### UnsetLastLogin
`func (o *Model) UnsetLastLogin()`

UnsetLastLogin ensures that no value is present for LastLogin, not even an explicit nil
### GetName

`func (o *Model) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Model) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Model) SetName(v string)`

SetName sets Name field to given value.


### GetOauthId

`func (o *Model) GetOauthId() string`

GetOauthId returns the OauthId field if non-nil, zero value otherwise.

### GetOauthIdOk

`func (o *Model) GetOauthIdOk() (*string, bool)`

GetOauthIdOk returns a tuple with the OauthId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthId

`func (o *Model) SetOauthId(v string)`

SetOauthId sets OauthId field to given value.

### HasOauthId

`func (o *Model) HasOauthId() bool`

HasOauthId returns a boolean if a field has been set.

### SetOauthIdNil

`func (o *Model) SetOauthIdNil(b bool)`

 SetOauthIdNil sets the value for OauthId to be an explicit nil

### UnsetOauthId
`func (o *Model) UnsetOauthId()`

UnsetOauthId ensures that no value is present for OauthId, not even an explicit nil
### GetOauthProvider

`func (o *Model) GetOauthProvider() string`

GetOauthProvider returns the OauthProvider field if non-nil, zero value otherwise.

### GetOauthProviderOk

`func (o *Model) GetOauthProviderOk() (*string, bool)`

GetOauthProviderOk returns a tuple with the OauthProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthProvider

`func (o *Model) SetOauthProvider(v string)`

SetOauthProvider sets OauthProvider field to given value.

### HasOauthProvider

`func (o *Model) HasOauthProvider() bool`

HasOauthProvider returns a boolean if a field has been set.

### SetOauthProviderNil

`func (o *Model) SetOauthProviderNil(b bool)`

 SetOauthProviderNil sets the value for OauthProvider to be an explicit nil

### UnsetOauthProvider
`func (o *Model) UnsetOauthProvider()`

UnsetOauthProvider ensures that no value is present for OauthProvider, not even an explicit nil
### GetPasswordChangedAt

`func (o *Model) GetPasswordChangedAt() time.Time`

GetPasswordChangedAt returns the PasswordChangedAt field if non-nil, zero value otherwise.

### GetPasswordChangedAtOk

`func (o *Model) GetPasswordChangedAtOk() (*time.Time, bool)`

GetPasswordChangedAtOk returns a tuple with the PasswordChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordChangedAt

`func (o *Model) SetPasswordChangedAt(v time.Time)`

SetPasswordChangedAt sets PasswordChangedAt field to given value.

### HasPasswordChangedAt

`func (o *Model) HasPasswordChangedAt() bool`

HasPasswordChangedAt returns a boolean if a field has been set.

### SetPasswordChangedAtNil

`func (o *Model) SetPasswordChangedAtNil(b bool)`

 SetPasswordChangedAtNil sets the value for PasswordChangedAt to be an explicit nil

### UnsetPasswordChangedAt
`func (o *Model) UnsetPasswordChangedAt()`

UnsetPasswordChangedAt ensures that no value is present for PasswordChangedAt, not even an explicit nil
### GetPasswordHash

`func (o *Model) GetPasswordHash() string`

GetPasswordHash returns the PasswordHash field if non-nil, zero value otherwise.

### GetPasswordHashOk

`func (o *Model) GetPasswordHashOk() (*string, bool)`

GetPasswordHashOk returns a tuple with the PasswordHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordHash

`func (o *Model) SetPasswordHash(v string)`

SetPasswordHash sets PasswordHash field to given value.


### GetPicture

`func (o *Model) GetPicture() string`

GetPicture returns the Picture field if non-nil, zero value otherwise.

### GetPictureOk

`func (o *Model) GetPictureOk() (*string, bool)`

GetPictureOk returns a tuple with the Picture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPicture

`func (o *Model) SetPicture(v string)`

SetPicture sets Picture field to given value.

### HasPicture

`func (o *Model) HasPicture() bool`

HasPicture returns a boolean if a field has been set.

### SetPictureNil

`func (o *Model) SetPictureNil(b bool)`

 SetPictureNil sets the value for Picture to be an explicit nil

### UnsetPicture
`func (o *Model) UnsetPicture()`

UnsetPicture ensures that no value is present for Picture, not even an explicit nil
### GetPrivacyAcceptedAt

`func (o *Model) GetPrivacyAcceptedAt() time.Time`

GetPrivacyAcceptedAt returns the PrivacyAcceptedAt field if non-nil, zero value otherwise.

### GetPrivacyAcceptedAtOk

`func (o *Model) GetPrivacyAcceptedAtOk() (*time.Time, bool)`

GetPrivacyAcceptedAtOk returns a tuple with the PrivacyAcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyAcceptedAt

`func (o *Model) SetPrivacyAcceptedAt(v time.Time)`

SetPrivacyAcceptedAt sets PrivacyAcceptedAt field to given value.

### HasPrivacyAcceptedAt

`func (o *Model) HasPrivacyAcceptedAt() bool`

HasPrivacyAcceptedAt returns a boolean if a field has been set.

### SetPrivacyAcceptedAtNil

`func (o *Model) SetPrivacyAcceptedAtNil(b bool)`

 SetPrivacyAcceptedAtNil sets the value for PrivacyAcceptedAt to be an explicit nil

### UnsetPrivacyAcceptedAt
`func (o *Model) UnsetPrivacyAcceptedAt()`

UnsetPrivacyAcceptedAt ensures that no value is present for PrivacyAcceptedAt, not even an explicit nil
### GetTotpSecret

`func (o *Model) GetTotpSecret() string`

GetTotpSecret returns the TotpSecret field if non-nil, zero value otherwise.

### GetTotpSecretOk

`func (o *Model) GetTotpSecretOk() (*string, bool)`

GetTotpSecretOk returns a tuple with the TotpSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpSecret

`func (o *Model) SetTotpSecret(v string)`

SetTotpSecret sets TotpSecret field to given value.

### HasTotpSecret

`func (o *Model) HasTotpSecret() bool`

HasTotpSecret returns a boolean if a field has been set.

### SetTotpSecretNil

`func (o *Model) SetTotpSecretNil(b bool)`

 SetTotpSecretNil sets the value for TotpSecret to be an explicit nil

### UnsetTotpSecret
`func (o *Model) UnsetTotpSecret()`

UnsetTotpSecret ensures that no value is present for TotpSecret, not even an explicit nil
### GetUpdatedAt

`func (o *Model) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Model) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Model) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


