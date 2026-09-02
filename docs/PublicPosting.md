# PublicPosting

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** |  | [optional] 
**Description** | **string** |  | 
**EmploymentType** | Pointer to **NullableString** |  | [optional] 
**Id** | **string** |  | 
**Location** | Pointer to **NullableString** |  | [optional] 
**Remote** | **bool** |  | 
**RequiredSkills** | **[]string** |  | 
**Requirements** | Pointer to **NullableString** |  | [optional] 
**SalaryMax** | Pointer to **NullableInt32** |  | [optional] 
**SalaryMin** | Pointer to **NullableInt32** |  | [optional] 
**Title** | **string** |  | 

## Methods

### NewPublicPosting

`func NewPublicPosting(description string, id string, remote bool, requiredSkills []string, title string, ) *PublicPosting`

NewPublicPosting instantiates a new PublicPosting object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicPostingWithDefaults

`func NewPublicPostingWithDefaults() *PublicPosting`

NewPublicPostingWithDefaults instantiates a new PublicPosting object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *PublicPosting) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *PublicPosting) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *PublicPosting) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *PublicPosting) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *PublicPosting) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *PublicPosting) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetDescription

`func (o *PublicPosting) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PublicPosting) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PublicPosting) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEmploymentType

`func (o *PublicPosting) GetEmploymentType() string`

GetEmploymentType returns the EmploymentType field if non-nil, zero value otherwise.

### GetEmploymentTypeOk

`func (o *PublicPosting) GetEmploymentTypeOk() (*string, bool)`

GetEmploymentTypeOk returns a tuple with the EmploymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmploymentType

`func (o *PublicPosting) SetEmploymentType(v string)`

SetEmploymentType sets EmploymentType field to given value.

### HasEmploymentType

`func (o *PublicPosting) HasEmploymentType() bool`

HasEmploymentType returns a boolean if a field has been set.

### SetEmploymentTypeNil

`func (o *PublicPosting) SetEmploymentTypeNil(b bool)`

 SetEmploymentTypeNil sets the value for EmploymentType to be an explicit nil

### UnsetEmploymentType
`func (o *PublicPosting) UnsetEmploymentType()`

UnsetEmploymentType ensures that no value is present for EmploymentType, not even an explicit nil
### GetId

`func (o *PublicPosting) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PublicPosting) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PublicPosting) SetId(v string)`

SetId sets Id field to given value.


### GetLocation

`func (o *PublicPosting) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *PublicPosting) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *PublicPosting) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *PublicPosting) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *PublicPosting) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *PublicPosting) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetRemote

`func (o *PublicPosting) GetRemote() bool`

GetRemote returns the Remote field if non-nil, zero value otherwise.

### GetRemoteOk

`func (o *PublicPosting) GetRemoteOk() (*bool, bool)`

GetRemoteOk returns a tuple with the Remote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemote

`func (o *PublicPosting) SetRemote(v bool)`

SetRemote sets Remote field to given value.


### GetRequiredSkills

`func (o *PublicPosting) GetRequiredSkills() []string`

GetRequiredSkills returns the RequiredSkills field if non-nil, zero value otherwise.

### GetRequiredSkillsOk

`func (o *PublicPosting) GetRequiredSkillsOk() (*[]string, bool)`

GetRequiredSkillsOk returns a tuple with the RequiredSkills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredSkills

`func (o *PublicPosting) SetRequiredSkills(v []string)`

SetRequiredSkills sets RequiredSkills field to given value.


### GetRequirements

`func (o *PublicPosting) GetRequirements() string`

GetRequirements returns the Requirements field if non-nil, zero value otherwise.

### GetRequirementsOk

`func (o *PublicPosting) GetRequirementsOk() (*string, bool)`

GetRequirementsOk returns a tuple with the Requirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirements

`func (o *PublicPosting) SetRequirements(v string)`

SetRequirements sets Requirements field to given value.

### HasRequirements

`func (o *PublicPosting) HasRequirements() bool`

HasRequirements returns a boolean if a field has been set.

### SetRequirementsNil

`func (o *PublicPosting) SetRequirementsNil(b bool)`

 SetRequirementsNil sets the value for Requirements to be an explicit nil

### UnsetRequirements
`func (o *PublicPosting) UnsetRequirements()`

UnsetRequirements ensures that no value is present for Requirements, not even an explicit nil
### GetSalaryMax

`func (o *PublicPosting) GetSalaryMax() int32`

GetSalaryMax returns the SalaryMax field if non-nil, zero value otherwise.

### GetSalaryMaxOk

`func (o *PublicPosting) GetSalaryMaxOk() (*int32, bool)`

GetSalaryMaxOk returns a tuple with the SalaryMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalaryMax

`func (o *PublicPosting) SetSalaryMax(v int32)`

SetSalaryMax sets SalaryMax field to given value.

### HasSalaryMax

`func (o *PublicPosting) HasSalaryMax() bool`

HasSalaryMax returns a boolean if a field has been set.

### SetSalaryMaxNil

`func (o *PublicPosting) SetSalaryMaxNil(b bool)`

 SetSalaryMaxNil sets the value for SalaryMax to be an explicit nil

### UnsetSalaryMax
`func (o *PublicPosting) UnsetSalaryMax()`

UnsetSalaryMax ensures that no value is present for SalaryMax, not even an explicit nil
### GetSalaryMin

`func (o *PublicPosting) GetSalaryMin() int32`

GetSalaryMin returns the SalaryMin field if non-nil, zero value otherwise.

### GetSalaryMinOk

`func (o *PublicPosting) GetSalaryMinOk() (*int32, bool)`

GetSalaryMinOk returns a tuple with the SalaryMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalaryMin

`func (o *PublicPosting) SetSalaryMin(v int32)`

SetSalaryMin sets SalaryMin field to given value.

### HasSalaryMin

`func (o *PublicPosting) HasSalaryMin() bool`

HasSalaryMin returns a boolean if a field has been set.

### SetSalaryMinNil

`func (o *PublicPosting) SetSalaryMinNil(b bool)`

 SetSalaryMinNil sets the value for SalaryMin to be an explicit nil

### UnsetSalaryMin
`func (o *PublicPosting) UnsetSalaryMin()`

UnsetSalaryMin ensures that no value is present for SalaryMin, not even an explicit nil
### GetTitle

`func (o *PublicPosting) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PublicPosting) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PublicPosting) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


