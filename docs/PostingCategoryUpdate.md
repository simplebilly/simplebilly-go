# PostingCategoryUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountNumber** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr03** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr04** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr49** | Pointer to **NullableString** |  | [optional] 
**CategoryType** | Pointer to [**NullablePostingCategoryType**](PostingCategoryType.md) |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**DefaultVatRate** | Pointer to **NullableInt32** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**EksCategory** | Pointer to **NullableString** |  | [optional] 
**EuVatLine** | Pointer to **NullableInt32** |  | [optional] 
**InputVatPercentage** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**IsSystem** | Pointer to **NullableBool** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**SkrVersion** | Pointer to **NullableString** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**UserModifiedSkr03** | Pointer to **NullableBool** |  | [optional] 
**UserModifiedSkr04** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewPostingCategoryUpdate

`func NewPostingCategoryUpdate() *PostingCategoryUpdate`

NewPostingCategoryUpdate instantiates a new PostingCategoryUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostingCategoryUpdateWithDefaults

`func NewPostingCategoryUpdateWithDefaults() *PostingCategoryUpdate`

NewPostingCategoryUpdateWithDefaults instantiates a new PostingCategoryUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountNumber

`func (o *PostingCategoryUpdate) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *PostingCategoryUpdate) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *PostingCategoryUpdate) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *PostingCategoryUpdate) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### SetAccountNumberNil

`func (o *PostingCategoryUpdate) SetAccountNumberNil(b bool)`

 SetAccountNumberNil sets the value for AccountNumber to be an explicit nil

### UnsetAccountNumber
`func (o *PostingCategoryUpdate) UnsetAccountNumber()`

UnsetAccountNumber ensures that no value is present for AccountNumber, not even an explicit nil
### GetAccountNumberSkr03

`func (o *PostingCategoryUpdate) GetAccountNumberSkr03() string`

GetAccountNumberSkr03 returns the AccountNumberSkr03 field if non-nil, zero value otherwise.

### GetAccountNumberSkr03Ok

`func (o *PostingCategoryUpdate) GetAccountNumberSkr03Ok() (*string, bool)`

GetAccountNumberSkr03Ok returns a tuple with the AccountNumberSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr03

`func (o *PostingCategoryUpdate) SetAccountNumberSkr03(v string)`

SetAccountNumberSkr03 sets AccountNumberSkr03 field to given value.

### HasAccountNumberSkr03

`func (o *PostingCategoryUpdate) HasAccountNumberSkr03() bool`

HasAccountNumberSkr03 returns a boolean if a field has been set.

### SetAccountNumberSkr03Nil

`func (o *PostingCategoryUpdate) SetAccountNumberSkr03Nil(b bool)`

 SetAccountNumberSkr03Nil sets the value for AccountNumberSkr03 to be an explicit nil

### UnsetAccountNumberSkr03
`func (o *PostingCategoryUpdate) UnsetAccountNumberSkr03()`

UnsetAccountNumberSkr03 ensures that no value is present for AccountNumberSkr03, not even an explicit nil
### GetAccountNumberSkr04

`func (o *PostingCategoryUpdate) GetAccountNumberSkr04() string`

GetAccountNumberSkr04 returns the AccountNumberSkr04 field if non-nil, zero value otherwise.

### GetAccountNumberSkr04Ok

`func (o *PostingCategoryUpdate) GetAccountNumberSkr04Ok() (*string, bool)`

GetAccountNumberSkr04Ok returns a tuple with the AccountNumberSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr04

`func (o *PostingCategoryUpdate) SetAccountNumberSkr04(v string)`

SetAccountNumberSkr04 sets AccountNumberSkr04 field to given value.

### HasAccountNumberSkr04

`func (o *PostingCategoryUpdate) HasAccountNumberSkr04() bool`

HasAccountNumberSkr04 returns a boolean if a field has been set.

### SetAccountNumberSkr04Nil

`func (o *PostingCategoryUpdate) SetAccountNumberSkr04Nil(b bool)`

 SetAccountNumberSkr04Nil sets the value for AccountNumberSkr04 to be an explicit nil

### UnsetAccountNumberSkr04
`func (o *PostingCategoryUpdate) UnsetAccountNumberSkr04()`

UnsetAccountNumberSkr04 ensures that no value is present for AccountNumberSkr04, not even an explicit nil
### GetAccountNumberSkr49

`func (o *PostingCategoryUpdate) GetAccountNumberSkr49() string`

GetAccountNumberSkr49 returns the AccountNumberSkr49 field if non-nil, zero value otherwise.

### GetAccountNumberSkr49Ok

`func (o *PostingCategoryUpdate) GetAccountNumberSkr49Ok() (*string, bool)`

GetAccountNumberSkr49Ok returns a tuple with the AccountNumberSkr49 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr49

`func (o *PostingCategoryUpdate) SetAccountNumberSkr49(v string)`

SetAccountNumberSkr49 sets AccountNumberSkr49 field to given value.

### HasAccountNumberSkr49

`func (o *PostingCategoryUpdate) HasAccountNumberSkr49() bool`

HasAccountNumberSkr49 returns a boolean if a field has been set.

### SetAccountNumberSkr49Nil

`func (o *PostingCategoryUpdate) SetAccountNumberSkr49Nil(b bool)`

 SetAccountNumberSkr49Nil sets the value for AccountNumberSkr49 to be an explicit nil

### UnsetAccountNumberSkr49
`func (o *PostingCategoryUpdate) UnsetAccountNumberSkr49()`

UnsetAccountNumberSkr49 ensures that no value is present for AccountNumberSkr49, not even an explicit nil
### GetCategoryType

`func (o *PostingCategoryUpdate) GetCategoryType() PostingCategoryType`

GetCategoryType returns the CategoryType field if non-nil, zero value otherwise.

### GetCategoryTypeOk

`func (o *PostingCategoryUpdate) GetCategoryTypeOk() (*PostingCategoryType, bool)`

GetCategoryTypeOk returns a tuple with the CategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryType

`func (o *PostingCategoryUpdate) SetCategoryType(v PostingCategoryType)`

SetCategoryType sets CategoryType field to given value.

### HasCategoryType

`func (o *PostingCategoryUpdate) HasCategoryType() bool`

HasCategoryType returns a boolean if a field has been set.

### SetCategoryTypeNil

`func (o *PostingCategoryUpdate) SetCategoryTypeNil(b bool)`

 SetCategoryTypeNil sets the value for CategoryType to be an explicit nil

### UnsetCategoryType
`func (o *PostingCategoryUpdate) UnsetCategoryType()`

UnsetCategoryType ensures that no value is present for CategoryType, not even an explicit nil
### GetCreatedAt

`func (o *PostingCategoryUpdate) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PostingCategoryUpdate) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PostingCategoryUpdate) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PostingCategoryUpdate) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *PostingCategoryUpdate) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *PostingCategoryUpdate) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetDefaultVatRate

`func (o *PostingCategoryUpdate) GetDefaultVatRate() int32`

GetDefaultVatRate returns the DefaultVatRate field if non-nil, zero value otherwise.

### GetDefaultVatRateOk

`func (o *PostingCategoryUpdate) GetDefaultVatRateOk() (*int32, bool)`

GetDefaultVatRateOk returns a tuple with the DefaultVatRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultVatRate

`func (o *PostingCategoryUpdate) SetDefaultVatRate(v int32)`

SetDefaultVatRate sets DefaultVatRate field to given value.

### HasDefaultVatRate

`func (o *PostingCategoryUpdate) HasDefaultVatRate() bool`

HasDefaultVatRate returns a boolean if a field has been set.

### SetDefaultVatRateNil

`func (o *PostingCategoryUpdate) SetDefaultVatRateNil(b bool)`

 SetDefaultVatRateNil sets the value for DefaultVatRate to be an explicit nil

### UnsetDefaultVatRate
`func (o *PostingCategoryUpdate) UnsetDefaultVatRate()`

UnsetDefaultVatRate ensures that no value is present for DefaultVatRate, not even an explicit nil
### GetDescription

`func (o *PostingCategoryUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PostingCategoryUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PostingCategoryUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PostingCategoryUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *PostingCategoryUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PostingCategoryUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEksCategory

`func (o *PostingCategoryUpdate) GetEksCategory() string`

GetEksCategory returns the EksCategory field if non-nil, zero value otherwise.

### GetEksCategoryOk

`func (o *PostingCategoryUpdate) GetEksCategoryOk() (*string, bool)`

GetEksCategoryOk returns a tuple with the EksCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEksCategory

`func (o *PostingCategoryUpdate) SetEksCategory(v string)`

SetEksCategory sets EksCategory field to given value.

### HasEksCategory

`func (o *PostingCategoryUpdate) HasEksCategory() bool`

HasEksCategory returns a boolean if a field has been set.

### SetEksCategoryNil

`func (o *PostingCategoryUpdate) SetEksCategoryNil(b bool)`

 SetEksCategoryNil sets the value for EksCategory to be an explicit nil

### UnsetEksCategory
`func (o *PostingCategoryUpdate) UnsetEksCategory()`

UnsetEksCategory ensures that no value is present for EksCategory, not even an explicit nil
### GetEuVatLine

`func (o *PostingCategoryUpdate) GetEuVatLine() int32`

GetEuVatLine returns the EuVatLine field if non-nil, zero value otherwise.

### GetEuVatLineOk

`func (o *PostingCategoryUpdate) GetEuVatLineOk() (*int32, bool)`

GetEuVatLineOk returns a tuple with the EuVatLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEuVatLine

`func (o *PostingCategoryUpdate) SetEuVatLine(v int32)`

SetEuVatLine sets EuVatLine field to given value.

### HasEuVatLine

`func (o *PostingCategoryUpdate) HasEuVatLine() bool`

HasEuVatLine returns a boolean if a field has been set.

### SetEuVatLineNil

`func (o *PostingCategoryUpdate) SetEuVatLineNil(b bool)`

 SetEuVatLineNil sets the value for EuVatLine to be an explicit nil

### UnsetEuVatLine
`func (o *PostingCategoryUpdate) UnsetEuVatLine()`

UnsetEuVatLine ensures that no value is present for EuVatLine, not even an explicit nil
### GetInputVatPercentage

`func (o *PostingCategoryUpdate) GetInputVatPercentage() string`

GetInputVatPercentage returns the InputVatPercentage field if non-nil, zero value otherwise.

### GetInputVatPercentageOk

`func (o *PostingCategoryUpdate) GetInputVatPercentageOk() (*string, bool)`

GetInputVatPercentageOk returns a tuple with the InputVatPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatPercentage

`func (o *PostingCategoryUpdate) SetInputVatPercentage(v string)`

SetInputVatPercentage sets InputVatPercentage field to given value.

### HasInputVatPercentage

`func (o *PostingCategoryUpdate) HasInputVatPercentage() bool`

HasInputVatPercentage returns a boolean if a field has been set.

### SetInputVatPercentageNil

`func (o *PostingCategoryUpdate) SetInputVatPercentageNil(b bool)`

 SetInputVatPercentageNil sets the value for InputVatPercentage to be an explicit nil

### UnsetInputVatPercentage
`func (o *PostingCategoryUpdate) UnsetInputVatPercentage()`

UnsetInputVatPercentage ensures that no value is present for InputVatPercentage, not even an explicit nil
### GetIsActive

`func (o *PostingCategoryUpdate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *PostingCategoryUpdate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *PostingCategoryUpdate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *PostingCategoryUpdate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *PostingCategoryUpdate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *PostingCategoryUpdate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetIsSystem

`func (o *PostingCategoryUpdate) GetIsSystem() bool`

GetIsSystem returns the IsSystem field if non-nil, zero value otherwise.

### GetIsSystemOk

`func (o *PostingCategoryUpdate) GetIsSystemOk() (*bool, bool)`

GetIsSystemOk returns a tuple with the IsSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSystem

`func (o *PostingCategoryUpdate) SetIsSystem(v bool)`

SetIsSystem sets IsSystem field to given value.

### HasIsSystem

`func (o *PostingCategoryUpdate) HasIsSystem() bool`

HasIsSystem returns a boolean if a field has been set.

### SetIsSystemNil

`func (o *PostingCategoryUpdate) SetIsSystemNil(b bool)`

 SetIsSystemNil sets the value for IsSystem to be an explicit nil

### UnsetIsSystem
`func (o *PostingCategoryUpdate) UnsetIsSystem()`

UnsetIsSystem ensures that no value is present for IsSystem, not even an explicit nil
### GetName

`func (o *PostingCategoryUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PostingCategoryUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PostingCategoryUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PostingCategoryUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *PostingCategoryUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *PostingCategoryUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSkrVersion

`func (o *PostingCategoryUpdate) GetSkrVersion() string`

GetSkrVersion returns the SkrVersion field if non-nil, zero value otherwise.

### GetSkrVersionOk

`func (o *PostingCategoryUpdate) GetSkrVersionOk() (*string, bool)`

GetSkrVersionOk returns a tuple with the SkrVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkrVersion

`func (o *PostingCategoryUpdate) SetSkrVersion(v string)`

SetSkrVersion sets SkrVersion field to given value.

### HasSkrVersion

`func (o *PostingCategoryUpdate) HasSkrVersion() bool`

HasSkrVersion returns a boolean if a field has been set.

### SetSkrVersionNil

`func (o *PostingCategoryUpdate) SetSkrVersionNil(b bool)`

 SetSkrVersionNil sets the value for SkrVersion to be an explicit nil

### UnsetSkrVersion
`func (o *PostingCategoryUpdate) UnsetSkrVersion()`

UnsetSkrVersion ensures that no value is present for SkrVersion, not even an explicit nil
### GetUpdatedAt

`func (o *PostingCategoryUpdate) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PostingCategoryUpdate) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PostingCategoryUpdate) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PostingCategoryUpdate) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *PostingCategoryUpdate) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *PostingCategoryUpdate) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetUserModifiedSkr03

`func (o *PostingCategoryUpdate) GetUserModifiedSkr03() bool`

GetUserModifiedSkr03 returns the UserModifiedSkr03 field if non-nil, zero value otherwise.

### GetUserModifiedSkr03Ok

`func (o *PostingCategoryUpdate) GetUserModifiedSkr03Ok() (*bool, bool)`

GetUserModifiedSkr03Ok returns a tuple with the UserModifiedSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserModifiedSkr03

`func (o *PostingCategoryUpdate) SetUserModifiedSkr03(v bool)`

SetUserModifiedSkr03 sets UserModifiedSkr03 field to given value.

### HasUserModifiedSkr03

`func (o *PostingCategoryUpdate) HasUserModifiedSkr03() bool`

HasUserModifiedSkr03 returns a boolean if a field has been set.

### SetUserModifiedSkr03Nil

`func (o *PostingCategoryUpdate) SetUserModifiedSkr03Nil(b bool)`

 SetUserModifiedSkr03Nil sets the value for UserModifiedSkr03 to be an explicit nil

### UnsetUserModifiedSkr03
`func (o *PostingCategoryUpdate) UnsetUserModifiedSkr03()`

UnsetUserModifiedSkr03 ensures that no value is present for UserModifiedSkr03, not even an explicit nil
### GetUserModifiedSkr04

`func (o *PostingCategoryUpdate) GetUserModifiedSkr04() bool`

GetUserModifiedSkr04 returns the UserModifiedSkr04 field if non-nil, zero value otherwise.

### GetUserModifiedSkr04Ok

`func (o *PostingCategoryUpdate) GetUserModifiedSkr04Ok() (*bool, bool)`

GetUserModifiedSkr04Ok returns a tuple with the UserModifiedSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserModifiedSkr04

`func (o *PostingCategoryUpdate) SetUserModifiedSkr04(v bool)`

SetUserModifiedSkr04 sets UserModifiedSkr04 field to given value.

### HasUserModifiedSkr04

`func (o *PostingCategoryUpdate) HasUserModifiedSkr04() bool`

HasUserModifiedSkr04 returns a boolean if a field has been set.

### SetUserModifiedSkr04Nil

`func (o *PostingCategoryUpdate) SetUserModifiedSkr04Nil(b bool)`

 SetUserModifiedSkr04Nil sets the value for UserModifiedSkr04 to be an explicit nil

### UnsetUserModifiedSkr04
`func (o *PostingCategoryUpdate) UnsetUserModifiedSkr04()`

UnsetUserModifiedSkr04 ensures that no value is present for UserModifiedSkr04, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


