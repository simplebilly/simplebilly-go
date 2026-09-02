# AbsenceUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AbsenceType** | Pointer to [**NullableAbsenceType**](AbsenceType.md) | One of \&quot;vacation\&quot;, \&quot;sick\&quot;, \&quot;sabbatical\&quot;, \&quot;parental\&quot;, \&quot;other\&quot;. | [optional] 
**ApprovedAt** | Pointer to **NullableTime** |  | [optional] 
**ApprovedBy** | Pointer to **NullableString** | References the user entity. | [optional] 
**EmployeeId** | Pointer to **NullableString** | References the employee entity. | [optional] 
**EndDate** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**StartDate** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableAbsenceStatus**](AbsenceStatus.md) | One of \&quot;pending\&quot;, \&quot;approved\&quot;, \&quot;rejected\&quot;, \&quot;cancelled\&quot;. | [optional] 

## Methods

### NewAbsenceUpdate

`func NewAbsenceUpdate() *AbsenceUpdate`

NewAbsenceUpdate instantiates a new AbsenceUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAbsenceUpdateWithDefaults

`func NewAbsenceUpdateWithDefaults() *AbsenceUpdate`

NewAbsenceUpdateWithDefaults instantiates a new AbsenceUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAbsenceType

`func (o *AbsenceUpdate) GetAbsenceType() AbsenceType`

GetAbsenceType returns the AbsenceType field if non-nil, zero value otherwise.

### GetAbsenceTypeOk

`func (o *AbsenceUpdate) GetAbsenceTypeOk() (*AbsenceType, bool)`

GetAbsenceTypeOk returns a tuple with the AbsenceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbsenceType

`func (o *AbsenceUpdate) SetAbsenceType(v AbsenceType)`

SetAbsenceType sets AbsenceType field to given value.

### HasAbsenceType

`func (o *AbsenceUpdate) HasAbsenceType() bool`

HasAbsenceType returns a boolean if a field has been set.

### SetAbsenceTypeNil

`func (o *AbsenceUpdate) SetAbsenceTypeNil(b bool)`

 SetAbsenceTypeNil sets the value for AbsenceType to be an explicit nil

### UnsetAbsenceType
`func (o *AbsenceUpdate) UnsetAbsenceType()`

UnsetAbsenceType ensures that no value is present for AbsenceType, not even an explicit nil
### GetApprovedAt

`func (o *AbsenceUpdate) GetApprovedAt() time.Time`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *AbsenceUpdate) GetApprovedAtOk() (*time.Time, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *AbsenceUpdate) SetApprovedAt(v time.Time)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *AbsenceUpdate) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### SetApprovedAtNil

`func (o *AbsenceUpdate) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *AbsenceUpdate) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetApprovedBy

`func (o *AbsenceUpdate) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *AbsenceUpdate) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *AbsenceUpdate) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *AbsenceUpdate) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.

### SetApprovedByNil

`func (o *AbsenceUpdate) SetApprovedByNil(b bool)`

 SetApprovedByNil sets the value for ApprovedBy to be an explicit nil

### UnsetApprovedBy
`func (o *AbsenceUpdate) UnsetApprovedBy()`

UnsetApprovedBy ensures that no value is present for ApprovedBy, not even an explicit nil
### GetEmployeeId

`func (o *AbsenceUpdate) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *AbsenceUpdate) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *AbsenceUpdate) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *AbsenceUpdate) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### SetEmployeeIdNil

`func (o *AbsenceUpdate) SetEmployeeIdNil(b bool)`

 SetEmployeeIdNil sets the value for EmployeeId to be an explicit nil

### UnsetEmployeeId
`func (o *AbsenceUpdate) UnsetEmployeeId()`

UnsetEmployeeId ensures that no value is present for EmployeeId, not even an explicit nil
### GetEndDate

`func (o *AbsenceUpdate) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *AbsenceUpdate) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *AbsenceUpdate) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *AbsenceUpdate) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### SetEndDateNil

`func (o *AbsenceUpdate) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *AbsenceUpdate) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetNotes

`func (o *AbsenceUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *AbsenceUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *AbsenceUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *AbsenceUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *AbsenceUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *AbsenceUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStartDate

`func (o *AbsenceUpdate) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *AbsenceUpdate) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *AbsenceUpdate) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *AbsenceUpdate) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *AbsenceUpdate) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *AbsenceUpdate) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetStatus

`func (o *AbsenceUpdate) GetStatus() AbsenceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AbsenceUpdate) GetStatusOk() (*AbsenceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AbsenceUpdate) SetStatus(v AbsenceStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AbsenceUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *AbsenceUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *AbsenceUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


