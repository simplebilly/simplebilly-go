# JobPostingUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** |  | [optional] 
**Department** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** | What the job is; markdown/HTML. | [optional] 
**EmploymentType** | Pointer to [**NullableEmploymentType**](EmploymentType.md) | full_time | part_time | contract | internship | temporary | [optional] 
**Location** | Pointer to **NullableString** |  | [optional] 
**Remote** | Pointer to **NullableBool** |  | [optional] 
**RequiredSkills** | Pointer to **interface{}** | List of required skill names (JSON array of strings). | [optional] 
**Requirements** | Pointer to **NullableString** | Structured profile of the required candidate (skills, experience). | [optional] 
**SalaryMax** | Pointer to **NullableInt32** |  | [optional] 
**SalaryMin** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to [**NullableJobPostingStatus**](JobPostingStatus.md) | draft | published | closed | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewJobPostingUpdate

`func NewJobPostingUpdate() *JobPostingUpdate`

NewJobPostingUpdate instantiates a new JobPostingUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobPostingUpdateWithDefaults

`func NewJobPostingUpdateWithDefaults() *JobPostingUpdate`

NewJobPostingUpdateWithDefaults instantiates a new JobPostingUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *JobPostingUpdate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *JobPostingUpdate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *JobPostingUpdate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *JobPostingUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *JobPostingUpdate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *JobPostingUpdate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetDepartment

`func (o *JobPostingUpdate) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *JobPostingUpdate) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *JobPostingUpdate) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *JobPostingUpdate) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### SetDepartmentNil

`func (o *JobPostingUpdate) SetDepartmentNil(b bool)`

 SetDepartmentNil sets the value for Department to be an explicit nil

### UnsetDepartment
`func (o *JobPostingUpdate) UnsetDepartment()`

UnsetDepartment ensures that no value is present for Department, not even an explicit nil
### GetDescription

`func (o *JobPostingUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JobPostingUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JobPostingUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JobPostingUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *JobPostingUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *JobPostingUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEmploymentType

`func (o *JobPostingUpdate) GetEmploymentType() EmploymentType`

GetEmploymentType returns the EmploymentType field if non-nil, zero value otherwise.

### GetEmploymentTypeOk

`func (o *JobPostingUpdate) GetEmploymentTypeOk() (*EmploymentType, bool)`

GetEmploymentTypeOk returns a tuple with the EmploymentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmploymentType

`func (o *JobPostingUpdate) SetEmploymentType(v EmploymentType)`

SetEmploymentType sets EmploymentType field to given value.

### HasEmploymentType

`func (o *JobPostingUpdate) HasEmploymentType() bool`

HasEmploymentType returns a boolean if a field has been set.

### SetEmploymentTypeNil

`func (o *JobPostingUpdate) SetEmploymentTypeNil(b bool)`

 SetEmploymentTypeNil sets the value for EmploymentType to be an explicit nil

### UnsetEmploymentType
`func (o *JobPostingUpdate) UnsetEmploymentType()`

UnsetEmploymentType ensures that no value is present for EmploymentType, not even an explicit nil
### GetLocation

`func (o *JobPostingUpdate) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *JobPostingUpdate) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *JobPostingUpdate) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *JobPostingUpdate) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *JobPostingUpdate) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *JobPostingUpdate) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetRemote

`func (o *JobPostingUpdate) GetRemote() bool`

GetRemote returns the Remote field if non-nil, zero value otherwise.

### GetRemoteOk

`func (o *JobPostingUpdate) GetRemoteOk() (*bool, bool)`

GetRemoteOk returns a tuple with the Remote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemote

`func (o *JobPostingUpdate) SetRemote(v bool)`

SetRemote sets Remote field to given value.

### HasRemote

`func (o *JobPostingUpdate) HasRemote() bool`

HasRemote returns a boolean if a field has been set.

### SetRemoteNil

`func (o *JobPostingUpdate) SetRemoteNil(b bool)`

 SetRemoteNil sets the value for Remote to be an explicit nil

### UnsetRemote
`func (o *JobPostingUpdate) UnsetRemote()`

UnsetRemote ensures that no value is present for Remote, not even an explicit nil
### GetRequiredSkills

`func (o *JobPostingUpdate) GetRequiredSkills() interface{}`

GetRequiredSkills returns the RequiredSkills field if non-nil, zero value otherwise.

### GetRequiredSkillsOk

`func (o *JobPostingUpdate) GetRequiredSkillsOk() (*interface{}, bool)`

GetRequiredSkillsOk returns a tuple with the RequiredSkills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredSkills

`func (o *JobPostingUpdate) SetRequiredSkills(v interface{})`

SetRequiredSkills sets RequiredSkills field to given value.

### HasRequiredSkills

`func (o *JobPostingUpdate) HasRequiredSkills() bool`

HasRequiredSkills returns a boolean if a field has been set.

### SetRequiredSkillsNil

`func (o *JobPostingUpdate) SetRequiredSkillsNil(b bool)`

 SetRequiredSkillsNil sets the value for RequiredSkills to be an explicit nil

### UnsetRequiredSkills
`func (o *JobPostingUpdate) UnsetRequiredSkills()`

UnsetRequiredSkills ensures that no value is present for RequiredSkills, not even an explicit nil
### GetRequirements

`func (o *JobPostingUpdate) GetRequirements() string`

GetRequirements returns the Requirements field if non-nil, zero value otherwise.

### GetRequirementsOk

`func (o *JobPostingUpdate) GetRequirementsOk() (*string, bool)`

GetRequirementsOk returns a tuple with the Requirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirements

`func (o *JobPostingUpdate) SetRequirements(v string)`

SetRequirements sets Requirements field to given value.

### HasRequirements

`func (o *JobPostingUpdate) HasRequirements() bool`

HasRequirements returns a boolean if a field has been set.

### SetRequirementsNil

`func (o *JobPostingUpdate) SetRequirementsNil(b bool)`

 SetRequirementsNil sets the value for Requirements to be an explicit nil

### UnsetRequirements
`func (o *JobPostingUpdate) UnsetRequirements()`

UnsetRequirements ensures that no value is present for Requirements, not even an explicit nil
### GetSalaryMax

`func (o *JobPostingUpdate) GetSalaryMax() int32`

GetSalaryMax returns the SalaryMax field if non-nil, zero value otherwise.

### GetSalaryMaxOk

`func (o *JobPostingUpdate) GetSalaryMaxOk() (*int32, bool)`

GetSalaryMaxOk returns a tuple with the SalaryMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalaryMax

`func (o *JobPostingUpdate) SetSalaryMax(v int32)`

SetSalaryMax sets SalaryMax field to given value.

### HasSalaryMax

`func (o *JobPostingUpdate) HasSalaryMax() bool`

HasSalaryMax returns a boolean if a field has been set.

### SetSalaryMaxNil

`func (o *JobPostingUpdate) SetSalaryMaxNil(b bool)`

 SetSalaryMaxNil sets the value for SalaryMax to be an explicit nil

### UnsetSalaryMax
`func (o *JobPostingUpdate) UnsetSalaryMax()`

UnsetSalaryMax ensures that no value is present for SalaryMax, not even an explicit nil
### GetSalaryMin

`func (o *JobPostingUpdate) GetSalaryMin() int32`

GetSalaryMin returns the SalaryMin field if non-nil, zero value otherwise.

### GetSalaryMinOk

`func (o *JobPostingUpdate) GetSalaryMinOk() (*int32, bool)`

GetSalaryMinOk returns a tuple with the SalaryMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalaryMin

`func (o *JobPostingUpdate) SetSalaryMin(v int32)`

SetSalaryMin sets SalaryMin field to given value.

### HasSalaryMin

`func (o *JobPostingUpdate) HasSalaryMin() bool`

HasSalaryMin returns a boolean if a field has been set.

### SetSalaryMinNil

`func (o *JobPostingUpdate) SetSalaryMinNil(b bool)`

 SetSalaryMinNil sets the value for SalaryMin to be an explicit nil

### UnsetSalaryMin
`func (o *JobPostingUpdate) UnsetSalaryMin()`

UnsetSalaryMin ensures that no value is present for SalaryMin, not even an explicit nil
### GetStatus

`func (o *JobPostingUpdate) GetStatus() JobPostingStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JobPostingUpdate) GetStatusOk() (*JobPostingStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JobPostingUpdate) SetStatus(v JobPostingStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *JobPostingUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *JobPostingUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *JobPostingUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetTitle

`func (o *JobPostingUpdate) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *JobPostingUpdate) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *JobPostingUpdate) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *JobPostingUpdate) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *JobPostingUpdate) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *JobPostingUpdate) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


