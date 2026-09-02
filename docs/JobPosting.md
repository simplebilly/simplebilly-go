# JobPosting

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** |  | [optional] 
**Department** | Pointer to **NullableString** |  | [optional] 
**Description** | **string** | What the job is; markdown/HTML. | 
**EmploymentType** | Pointer to [**NullableEmploymentType**](EmploymentType.md) | full_time | part_time | contract | internship | temporary | [optional] 
**Location** | Pointer to **NullableString** |  | [optional] 
**Remote** | **bool** |  | 
**RequiredSkills** | **interface{}** | List of required skill names (JSON array of strings). | 
**Requirements** | Pointer to **NullableString** | Structured profile of the required candidate (skills, experience). | [optional] 
**SalaryMax** | Pointer to **NullableInt32** |  | [optional] 
**SalaryMin** | Pointer to **NullableInt32** |  | [optional] 
**Status** | [**JobPostingStatus**](JobPostingStatus.md) | draft | published | closed | 
**Title** | **string** |  | 

## Methods

### NewJobPosting

`func NewJobPosting(description string, remote bool, requiredSkills interface{}, status JobPostingStatus, title string, ) *JobPosting`

NewJobPosting instantiates a new JobPosting object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobPostingWithDefaults

`func NewJobPostingWithDefaults() *JobPosting`

NewJobPostingWithDefaults instantiates a new JobPosting object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *JobPosting) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *JobPosting) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *JobPosting) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *JobPosting) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *JobPosting) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *JobPosting) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetDepartment

`func (o *JobPosting) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *JobPosting) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *JobPosting) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *JobPosting) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### SetDepartmentNil

`func (o *JobPosting) SetDepartmentNil(b bool)`

 SetDepartmentNil sets the value for Department to be an explicit nil

### UnsetDepartment
`func (o *JobPosting) UnsetDepartment()`

UnsetDepartment ensures that no value is present for Department, not even an explicit nil
### GetDescription

`func (o *JobPosting) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JobPosting) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JobPosting) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEmploymentType

`func (o *JobPosting) GetEmploymentType() EmploymentType`

GetEmploymentType returns the EmploymentType field if non-nil, zero value otherwise.

### GetEmploymentTypeOk

`func (o *JobPosting) GetEmploymentTypeOk() (*EmploymentType, bool)`

GetEmploymentTypeOk returns a tuple with the EmploymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmploymentType

`func (o *JobPosting) SetEmploymentType(v EmploymentType)`

SetEmploymentType sets EmploymentType field to given value.

### HasEmploymentType

`func (o *JobPosting) HasEmploymentType() bool`

HasEmploymentType returns a boolean if a field has been set.

### SetEmploymentTypeNil

`func (o *JobPosting) SetEmploymentTypeNil(b bool)`

 SetEmploymentTypeNil sets the value for EmploymentType to be an explicit nil

### UnsetEmploymentType
`func (o *JobPosting) UnsetEmploymentType()`

UnsetEmploymentType ensures that no value is present for EmploymentType, not even an explicit nil
### GetLocation

`func (o *JobPosting) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *JobPosting) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *JobPosting) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *JobPosting) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *JobPosting) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *JobPosting) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetRemote

`func (o *JobPosting) GetRemote() bool`

GetRemote returns the Remote field if non-nil, zero value otherwise.

### GetRemoteOk

`func (o *JobPosting) GetRemoteOk() (*bool, bool)`

GetRemoteOk returns a tuple with the Remote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemote

`func (o *JobPosting) SetRemote(v bool)`

SetRemote sets Remote field to given value.


### GetRequiredSkills

`func (o *JobPosting) GetRequiredSkills() interface{}`

GetRequiredSkills returns the RequiredSkills field if non-nil, zero value otherwise.

### GetRequiredSkillsOk

`func (o *JobPosting) GetRequiredSkillsOk() (*interface{}, bool)`

GetRequiredSkillsOk returns a tuple with the RequiredSkills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredSkills

`func (o *JobPosting) SetRequiredSkills(v interface{})`

SetRequiredSkills sets RequiredSkills field to given value.


### SetRequiredSkillsNil

`func (o *JobPosting) SetRequiredSkillsNil(b bool)`

 SetRequiredSkillsNil sets the value for RequiredSkills to be an explicit nil

### UnsetRequiredSkills
`func (o *JobPosting) UnsetRequiredSkills()`

UnsetRequiredSkills ensures that no value is present for RequiredSkills, not even an explicit nil
### GetRequirements

`func (o *JobPosting) GetRequirements() string`

GetRequirements returns the Requirements field if non-nil, zero value otherwise.

### GetRequirementsOk

`func (o *JobPosting) GetRequirementsOk() (*string, bool)`

GetRequirementsOk returns a tuple with the Requirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirements

`func (o *JobPosting) SetRequirements(v string)`

SetRequirements sets Requirements field to given value.

### HasRequirements

`func (o *JobPosting) HasRequirements() bool`

HasRequirements returns a boolean if a field has been set.

### SetRequirementsNil

`func (o *JobPosting) SetRequirementsNil(b bool)`

 SetRequirementsNil sets the value for Requirements to be an explicit nil

### UnsetRequirements
`func (o *JobPosting) UnsetRequirements()`

UnsetRequirements ensures that no value is present for Requirements, not even an explicit nil
### GetSalaryMax

`func (o *JobPosting) GetSalaryMax() int32`

GetSalaryMax returns the SalaryMax field if non-nil, zero value otherwise.

### GetSalaryMaxOk

`func (o *JobPosting) GetSalaryMaxOk() (*int32, bool)`

GetSalaryMaxOk returns a tuple with the SalaryMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalaryMax

`func (o *JobPosting) SetSalaryMax(v int32)`

SetSalaryMax sets SalaryMax field to given value.

### HasSalaryMax

`func (o *JobPosting) HasSalaryMax() bool`

HasSalaryMax returns a boolean if a field has been set.

### SetSalaryMaxNil

`func (o *JobPosting) SetSalaryMaxNil(b bool)`

 SetSalaryMaxNil sets the value for SalaryMax to be an explicit nil

### UnsetSalaryMax
`func (o *JobPosting) UnsetSalaryMax()`

UnsetSalaryMax ensures that no value is present for SalaryMax, not even an explicit nil
### GetSalaryMin

`func (o *JobPosting) GetSalaryMin() int32`

GetSalaryMin returns the SalaryMin field if non-nil, zero value otherwise.

### GetSalaryMinOk

`func (o *JobPosting) GetSalaryMinOk() (*int32, bool)`

GetSalaryMinOk returns a tuple with the SalaryMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalaryMin

`func (o *JobPosting) SetSalaryMin(v int32)`

SetSalaryMin sets SalaryMin field to given value.

### HasSalaryMin

`func (o *JobPosting) HasSalaryMin() bool`

HasSalaryMin returns a boolean if a field has been set.

### SetSalaryMinNil

`func (o *JobPosting) SetSalaryMinNil(b bool)`

 SetSalaryMinNil sets the value for SalaryMin to be an explicit nil

### UnsetSalaryMin
`func (o *JobPosting) UnsetSalaryMin()`

UnsetSalaryMin ensures that no value is present for SalaryMin, not even an explicit nil
### GetStatus

`func (o *JobPosting) GetStatus() JobPostingStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JobPosting) GetStatusOk() (*JobPostingStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JobPosting) SetStatus(v JobPostingStatus)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *JobPosting) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *JobPosting) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *JobPosting) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


