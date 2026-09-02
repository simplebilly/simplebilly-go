# PostingCategoryCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountNumber** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr03** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr04** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr49** | Pointer to **NullableString** |  | [optional] 
**CategoryType** | [**PostingCategoryType**](PostingCategoryType.md) |  | 
**CreatedAt** | **time.Time** |  | 
**DefaultVatRate** | **int32** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**EksCategory** | Pointer to **NullableString** |  | [optional] 
**EuVatLine** | Pointer to **NullableInt32** |  | [optional] 
**InputVatPercentage** | **string** |  | 
**IsActive** | **bool** |  | 
**IsSystem** | **bool** |  | 
**Name** | **string** |  | 
**SkrVersion** | **string** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**UserModifiedSkr03** | **bool** |  | 
**UserModifiedSkr04** | **bool** |  | 

## Methods

### NewPostingCategoryCreate

`func NewPostingCategoryCreate(categoryType PostingCategoryType, createdAt time.Time, defaultVatRate int32, inputVatPercentage string, isActive bool, isSystem bool, name string, skrVersion string, userModifiedSkr03 bool, userModifiedSkr04 bool, ) *PostingCategoryCreate`

NewPostingCategoryCreate instantiates a new PostingCategoryCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostingCategoryCreateWithDefaults

`func NewPostingCategoryCreateWithDefaults() *PostingCategoryCreate`

NewPostingCategoryCreateWithDefaults instantiates a new PostingCategoryCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountNumber

`func (o *PostingCategoryCreate) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *PostingCategoryCreate) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *PostingCategoryCreate) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *PostingCategoryCreate) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### SetAccountNumberNil

`func (o *PostingCategoryCreate) SetAccountNumberNil(b bool)`

 SetAccountNumberNil sets the value for AccountNumber to be an explicit nil

### UnsetAccountNumber
`func (o *PostingCategoryCreate) UnsetAccountNumber()`

UnsetAccountNumber ensures that no value is present for AccountNumber, not even an explicit nil
### GetAccountNumberSkr03

`func (o *PostingCategoryCreate) GetAccountNumberSkr03() string`

GetAccountNumberSkr03 returns the AccountNumberSkr03 field if non-nil, zero value otherwise.

### GetAccountNumberSkr03Ok

`func (o *PostingCategoryCreate) GetAccountNumberSkr03Ok() (*string, bool)`

GetAccountNumberSkr03Ok returns a tuple with the AccountNumberSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr03

`func (o *PostingCategoryCreate) SetAccountNumberSkr03(v string)`

SetAccountNumberSkr03 sets AccountNumberSkr03 field to given value.

### HasAccountNumberSkr03

`func (o *PostingCategoryCreate) HasAccountNumberSkr03() bool`

HasAccountNumberSkr03 returns a boolean if a field has been set.

### SetAccountNumberSkr03Nil

`func (o *PostingCategoryCreate) SetAccountNumberSkr03Nil(b bool)`

 SetAccountNumberSkr03Nil sets the value for AccountNumberSkr03 to be an explicit nil

### UnsetAccountNumberSkr03
`func (o *PostingCategoryCreate) UnsetAccountNumberSkr03()`

UnsetAccountNumberSkr03 ensures that no value is present for AccountNumberSkr03, not even an explicit nil
### GetAccountNumberSkr04

`func (o *PostingCategoryCreate) GetAccountNumberSkr04() string`

GetAccountNumberSkr04 returns the AccountNumberSkr04 field if non-nil, zero value otherwise.

### GetAccountNumberSkr04Ok

`func (o *PostingCategoryCreate) GetAccountNumberSkr04Ok() (*string, bool)`

GetAccountNumberSkr04Ok returns a tuple with the AccountNumberSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr04

`func (o *PostingCategoryCreate) SetAccountNumberSkr04(v string)`

SetAccountNumberSkr04 sets AccountNumberSkr04 field to given value.

### HasAccountNumberSkr04

`func (o *PostingCategoryCreate) HasAccountNumberSkr04() bool`

HasAccountNumberSkr04 returns a boolean if a field has been set.

### SetAccountNumberSkr04Nil

`func (o *PostingCategoryCreate) SetAccountNumberSkr04Nil(b bool)`

 SetAccountNumberSkr04Nil sets the value for AccountNumberSkr04 to be an explicit nil

### UnsetAccountNumberSkr04
`func (o *PostingCategoryCreate) UnsetAccountNumberSkr04()`

UnsetAccountNumberSkr04 ensures that no value is present for AccountNumberSkr04, not even an explicit nil
### GetAccountNumberSkr49

`func (o *PostingCategoryCreate) GetAccountNumberSkr49() string`

GetAccountNumberSkr49 returns the AccountNumberSkr49 field if non-nil, zero value otherwise.

### GetAccountNumberSkr49Ok

`func (o *PostingCategoryCreate) GetAccountNumberSkr49Ok() (*string, bool)`

GetAccountNumberSkr49Ok returns a tuple with the AccountNumberSkr49 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr49

`func (o *PostingCategoryCreate) SetAccountNumberSkr49(v string)`

SetAccountNumberSkr49 sets AccountNumberSkr49 field to given value.

### HasAccountNumberSkr49

`func (o *PostingCategoryCreate) HasAccountNumberSkr49() bool`

HasAccountNumberSkr49 returns a boolean if a field has been set.

### SetAccountNumberSkr49Nil

`func (o *PostingCategoryCreate) SetAccountNumberSkr49Nil(b bool)`

 SetAccountNumberSkr49Nil sets the value for AccountNumberSkr49 to be an explicit nil

### UnsetAccountNumberSkr49
`func (o *PostingCategoryCreate) UnsetAccountNumberSkr49()`

UnsetAccountNumberSkr49 ensures that no value is present for AccountNumberSkr49, not even an explicit nil
### GetCategoryType

`func (o *PostingCategoryCreate) GetCategoryType() PostingCategoryType`

GetCategoryType returns the CategoryType field if non-nil, zero value otherwise.

### GetCategoryTypeOk

`func (o *PostingCategoryCreate) GetCategoryTypeOk() (*PostingCategoryType, bool)`

GetCategoryTypeOk returns a tuple with the CategoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryType

`func (o *PostingCategoryCreate) SetCategoryType(v PostingCategoryType)`

SetCategoryType sets CategoryType field to given value.


### GetCreatedAt

`func (o *PostingCategoryCreate) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PostingCategoryCreate) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PostingCategoryCreate) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDefaultVatRate

`func (o *PostingCategoryCreate) GetDefaultVatRate() int32`

GetDefaultVatRate returns the DefaultVatRate field if non-nil, zero value otherwise.

### GetDefaultVatRateOk

`func (o *PostingCategoryCreate) GetDefaultVatRateOk() (*int32, bool)`

GetDefaultVatRateOk returns a tuple with the DefaultVatRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultVatRate

`func (o *PostingCategoryCreate) SetDefaultVatRate(v int32)`

SetDefaultVatRate sets DefaultVatRate field to given value.


### GetDescription

`func (o *PostingCategoryCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PostingCategoryCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PostingCategoryCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PostingCategoryCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *PostingCategoryCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PostingCategoryCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEksCategory

`func (o *PostingCategoryCreate) GetEksCategory() string`

GetEksCategory returns the EksCategory field if non-nil, zero value otherwise.

### GetEksCategoryOk

`func (o *PostingCategoryCreate) GetEksCategoryOk() (*string, bool)`

GetEksCategoryOk returns a tuple with the EksCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEksCategory

`func (o *PostingCategoryCreate) SetEksCategory(v string)`

SetEksCategory sets EksCategory field to given value.

### HasEksCategory

`func (o *PostingCategoryCreate) HasEksCategory() bool`

HasEksCategory returns a boolean if a field has been set.

### SetEksCategoryNil

`func (o *PostingCategoryCreate) SetEksCategoryNil(b bool)`

 SetEksCategoryNil sets the value for EksCategory to be an explicit nil

### UnsetEksCategory
`func (o *PostingCategoryCreate) UnsetEksCategory()`

UnsetEksCategory ensures that no value is present for EksCategory, not even an explicit nil
### GetEuVatLine

`func (o *PostingCategoryCreate) GetEuVatLine() int32`

GetEuVatLine returns the EuVatLine field if non-nil, zero value otherwise.

### GetEuVatLineOk

`func (o *PostingCategoryCreate) GetEuVatLineOk() (*int32, bool)`

GetEuVatLineOk returns a tuple with the EuVatLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEuVatLine

`func (o *PostingCategoryCreate) SetEuVatLine(v int32)`

SetEuVatLine sets EuVatLine field to given value.

### HasEuVatLine

`func (o *PostingCategoryCreate) HasEuVatLine() bool`

HasEuVatLine returns a boolean if a field has been set.

### SetEuVatLineNil

`func (o *PostingCategoryCreate) SetEuVatLineNil(b bool)`

 SetEuVatLineNil sets the value for EuVatLine to be an explicit nil

### UnsetEuVatLine
`func (o *PostingCategoryCreate) UnsetEuVatLine()`

UnsetEuVatLine ensures that no value is present for EuVatLine, not even an explicit nil
### GetInputVatPercentage

`func (o *PostingCategoryCreate) GetInputVatPercentage() string`

GetInputVatPercentage returns the InputVatPercentage field if non-nil, zero value otherwise.

### GetInputVatPercentageOk

`func (o *PostingCategoryCreate) GetInputVatPercentageOk() (*string, bool)`

GetInputVatPercentageOk returns a tuple with the InputVatPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatPercentage

`func (o *PostingCategoryCreate) SetInputVatPercentage(v string)`

SetInputVatPercentage sets InputVatPercentage field to given value.


### GetIsActive

`func (o *PostingCategoryCreate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *PostingCategoryCreate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *PostingCategoryCreate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetIsSystem

`func (o *PostingCategoryCreate) GetIsSystem() bool`

GetIsSystem returns the IsSystem field if non-nil, zero value otherwise.

### GetIsSystemOk

`func (o *PostingCategoryCreate) GetIsSystemOk() (*bool, bool)`

GetIsSystemOk returns a tuple with the IsSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSystem

`func (o *PostingCategoryCreate) SetIsSystem(v bool)`

SetIsSystem sets IsSystem field to given value.


### GetName

`func (o *PostingCategoryCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PostingCategoryCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PostingCategoryCreate) SetName(v string)`

SetName sets Name field to given value.


### GetSkrVersion

`func (o *PostingCategoryCreate) GetSkrVersion() string`

GetSkrVersion returns the SkrVersion field if non-nil, zero value otherwise.

### GetSkrVersionOk

`func (o *PostingCategoryCreate) GetSkrVersionOk() (*string, bool)`

GetSkrVersionOk returns a tuple with the SkrVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkrVersion

`func (o *PostingCategoryCreate) SetSkrVersion(v string)`

SetSkrVersion sets SkrVersion field to given value.


### GetUpdatedAt

`func (o *PostingCategoryCreate) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PostingCategoryCreate) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PostingCategoryCreate) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PostingCategoryCreate) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *PostingCategoryCreate) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *PostingCategoryCreate) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetUserModifiedSkr03

`func (o *PostingCategoryCreate) GetUserModifiedSkr03() bool`

GetUserModifiedSkr03 returns the UserModifiedSkr03 field if non-nil, zero value otherwise.

### GetUserModifiedSkr03Ok

`func (o *PostingCategoryCreate) GetUserModifiedSkr03Ok() (*bool, bool)`

GetUserModifiedSkr03Ok returns a tuple with the UserModifiedSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserModifiedSkr03

`func (o *PostingCategoryCreate) SetUserModifiedSkr03(v bool)`

SetUserModifiedSkr03 sets UserModifiedSkr03 field to given value.


### GetUserModifiedSkr04

`func (o *PostingCategoryCreate) GetUserModifiedSkr04() bool`

GetUserModifiedSkr04 returns the UserModifiedSkr04 field if non-nil, zero value otherwise.

### GetUserModifiedSkr04Ok

`func (o *PostingCategoryCreate) GetUserModifiedSkr04Ok() (*bool, bool)`

GetUserModifiedSkr04Ok returns a tuple with the UserModifiedSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserModifiedSkr04

`func (o *PostingCategoryCreate) SetUserModifiedSkr04(v bool)`

SetUserModifiedSkr04 sets UserModifiedSkr04 field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


