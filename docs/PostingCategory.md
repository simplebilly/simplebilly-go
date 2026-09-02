# PostingCategory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountNumber** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr03** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr04** | Pointer to **NullableString** |  | [optional] 
**AccountNumberSkr49** | Pointer to **NullableString** |  | [optional] 
**CategoryId** | **string** |  | 
**DefaultVatRate** | **int32** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**EksCategory** | Pointer to **NullableString** |  | [optional] 
**IsActive** | **bool** |  | 
**IsSystem** | **bool** |  | 
**Name** | **string** |  | 
**SkrVersion** | **string** |  | 
**Type** | **string** |  | 

## Methods

### NewPostingCategory

`func NewPostingCategory(categoryId string, defaultVatRate int32, isActive bool, isSystem bool, name string, skrVersion string, type_ string, ) *PostingCategory`

NewPostingCategory instantiates a new PostingCategory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostingCategoryWithDefaults

`func NewPostingCategoryWithDefaults() *PostingCategory`

NewPostingCategoryWithDefaults instantiates a new PostingCategory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountNumber

`func (o *PostingCategory) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *PostingCategory) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *PostingCategory) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *PostingCategory) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### SetAccountNumberNil

`func (o *PostingCategory) SetAccountNumberNil(b bool)`

 SetAccountNumberNil sets the value for AccountNumber to be an explicit nil

### UnsetAccountNumber
`func (o *PostingCategory) UnsetAccountNumber()`

UnsetAccountNumber ensures that no value is present for AccountNumber, not even an explicit nil
### GetAccountNumberSkr03

`func (o *PostingCategory) GetAccountNumberSkr03() string`

GetAccountNumberSkr03 returns the AccountNumberSkr03 field if non-nil, zero value otherwise.

### GetAccountNumberSkr03Ok

`func (o *PostingCategory) GetAccountNumberSkr03Ok() (*string, bool)`

GetAccountNumberSkr03Ok returns a tuple with the AccountNumberSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr03

`func (o *PostingCategory) SetAccountNumberSkr03(v string)`

SetAccountNumberSkr03 sets AccountNumberSkr03 field to given value.

### HasAccountNumberSkr03

`func (o *PostingCategory) HasAccountNumberSkr03() bool`

HasAccountNumberSkr03 returns a boolean if a field has been set.

### SetAccountNumberSkr03Nil

`func (o *PostingCategory) SetAccountNumberSkr03Nil(b bool)`

 SetAccountNumberSkr03Nil sets the value for AccountNumberSkr03 to be an explicit nil

### UnsetAccountNumberSkr03
`func (o *PostingCategory) UnsetAccountNumberSkr03()`

UnsetAccountNumberSkr03 ensures that no value is present for AccountNumberSkr03, not even an explicit nil
### GetAccountNumberSkr04

`func (o *PostingCategory) GetAccountNumberSkr04() string`

GetAccountNumberSkr04 returns the AccountNumberSkr04 field if non-nil, zero value otherwise.

### GetAccountNumberSkr04Ok

`func (o *PostingCategory) GetAccountNumberSkr04Ok() (*string, bool)`

GetAccountNumberSkr04Ok returns a tuple with the AccountNumberSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr04

`func (o *PostingCategory) SetAccountNumberSkr04(v string)`

SetAccountNumberSkr04 sets AccountNumberSkr04 field to given value.

### HasAccountNumberSkr04

`func (o *PostingCategory) HasAccountNumberSkr04() bool`

HasAccountNumberSkr04 returns a boolean if a field has been set.

### SetAccountNumberSkr04Nil

`func (o *PostingCategory) SetAccountNumberSkr04Nil(b bool)`

 SetAccountNumberSkr04Nil sets the value for AccountNumberSkr04 to be an explicit nil

### UnsetAccountNumberSkr04
`func (o *PostingCategory) UnsetAccountNumberSkr04()`

UnsetAccountNumberSkr04 ensures that no value is present for AccountNumberSkr04, not even an explicit nil
### GetAccountNumberSkr49

`func (o *PostingCategory) GetAccountNumberSkr49() string`

GetAccountNumberSkr49 returns the AccountNumberSkr49 field if non-nil, zero value otherwise.

### GetAccountNumberSkr49Ok

`func (o *PostingCategory) GetAccountNumberSkr49Ok() (*string, bool)`

GetAccountNumberSkr49Ok returns a tuple with the AccountNumberSkr49 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumberSkr49

`func (o *PostingCategory) SetAccountNumberSkr49(v string)`

SetAccountNumberSkr49 sets AccountNumberSkr49 field to given value.

### HasAccountNumberSkr49

`func (o *PostingCategory) HasAccountNumberSkr49() bool`

HasAccountNumberSkr49 returns a boolean if a field has been set.

### SetAccountNumberSkr49Nil

`func (o *PostingCategory) SetAccountNumberSkr49Nil(b bool)`

 SetAccountNumberSkr49Nil sets the value for AccountNumberSkr49 to be an explicit nil

### UnsetAccountNumberSkr49
`func (o *PostingCategory) UnsetAccountNumberSkr49()`

UnsetAccountNumberSkr49 ensures that no value is present for AccountNumberSkr49, not even an explicit nil
### GetCategoryId

`func (o *PostingCategory) GetCategoryId() string`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *PostingCategory) GetCategoryIdOk() (*string, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *PostingCategory) SetCategoryId(v string)`

SetCategoryId sets CategoryId field to given value.


### GetDefaultVatRate

`func (o *PostingCategory) GetDefaultVatRate() int32`

GetDefaultVatRate returns the DefaultVatRate field if non-nil, zero value otherwise.

### GetDefaultVatRateOk

`func (o *PostingCategory) GetDefaultVatRateOk() (*int32, bool)`

GetDefaultVatRateOk returns a tuple with the DefaultVatRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultVatRate

`func (o *PostingCategory) SetDefaultVatRate(v int32)`

SetDefaultVatRate sets DefaultVatRate field to given value.


### GetDescription

`func (o *PostingCategory) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PostingCategory) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PostingCategory) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PostingCategory) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *PostingCategory) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PostingCategory) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEksCategory

`func (o *PostingCategory) GetEksCategory() string`

GetEksCategory returns the EksCategory field if non-nil, zero value otherwise.

### GetEksCategoryOk

`func (o *PostingCategory) GetEksCategoryOk() (*string, bool)`

GetEksCategoryOk returns a tuple with the EksCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEksCategory

`func (o *PostingCategory) SetEksCategory(v string)`

SetEksCategory sets EksCategory field to given value.

### HasEksCategory

`func (o *PostingCategory) HasEksCategory() bool`

HasEksCategory returns a boolean if a field has been set.

### SetEksCategoryNil

`func (o *PostingCategory) SetEksCategoryNil(b bool)`

 SetEksCategoryNil sets the value for EksCategory to be an explicit nil

### UnsetEksCategory
`func (o *PostingCategory) UnsetEksCategory()`

UnsetEksCategory ensures that no value is present for EksCategory, not even an explicit nil
### GetIsActive

`func (o *PostingCategory) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *PostingCategory) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *PostingCategory) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetIsSystem

`func (o *PostingCategory) GetIsSystem() bool`

GetIsSystem returns the IsSystem field if non-nil, zero value otherwise.

### GetIsSystemOk

`func (o *PostingCategory) GetIsSystemOk() (*bool, bool)`

GetIsSystemOk returns a tuple with the IsSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSystem

`func (o *PostingCategory) SetIsSystem(v bool)`

SetIsSystem sets IsSystem field to given value.


### GetName

`func (o *PostingCategory) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PostingCategory) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PostingCategory) SetName(v string)`

SetName sets Name field to given value.


### GetSkrVersion

`func (o *PostingCategory) GetSkrVersion() string`

GetSkrVersion returns the SkrVersion field if non-nil, zero value otherwise.

### GetSkrVersionOk

`func (o *PostingCategory) GetSkrVersionOk() (*string, bool)`

GetSkrVersionOk returns a tuple with the SkrVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkrVersion

`func (o *PostingCategory) SetSkrVersion(v string)`

SetSkrVersion sets SkrVersion field to given value.


### GetType

`func (o *PostingCategory) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PostingCategory) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PostingCategory) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


