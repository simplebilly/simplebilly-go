# ServiceAssignmentUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmployeeId** | Pointer to **NullableString** | References the employees entity. | [optional] 
**JobId** | Pointer to **NullableString** | References the service_jobs entity. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**ScheduledDate** | Pointer to **NullableString** | Work day the assignment is scheduled for. | [optional] 
**ScheduledEnd** | Pointer to **NullableString** | Planned end time of the assignment. | [optional] 
**ScheduledStart** | Pointer to **NullableString** | Planned start time of the assignment. | [optional] 
**Status** | Pointer to [**NullableServiceAssignmentStatus**](ServiceAssignmentStatus.md) | Assignment lifecycle status: \&quot;planned\&quot;, \&quot;confirmed\&quot;, \&quot;en_route\&quot;, \&quot;in_progress\&quot;, \&quot;completed\&quot; or \&quot;cancelled\&quot;. | [optional] 

## Methods

### NewServiceAssignmentUpdate

`func NewServiceAssignmentUpdate() *ServiceAssignmentUpdate`

NewServiceAssignmentUpdate instantiates a new ServiceAssignmentUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceAssignmentUpdateWithDefaults

`func NewServiceAssignmentUpdateWithDefaults() *ServiceAssignmentUpdate`

NewServiceAssignmentUpdateWithDefaults instantiates a new ServiceAssignmentUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployeeId

`func (o *ServiceAssignmentUpdate) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *ServiceAssignmentUpdate) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *ServiceAssignmentUpdate) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *ServiceAssignmentUpdate) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### SetEmployeeIdNil

`func (o *ServiceAssignmentUpdate) SetEmployeeIdNil(b bool)`

 SetEmployeeIdNil sets the value for EmployeeId to be an explicit nil

### UnsetEmployeeId
`func (o *ServiceAssignmentUpdate) UnsetEmployeeId()`

UnsetEmployeeId ensures that no value is present for EmployeeId, not even an explicit nil
### GetJobId

`func (o *ServiceAssignmentUpdate) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ServiceAssignmentUpdate) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ServiceAssignmentUpdate) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ServiceAssignmentUpdate) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### SetJobIdNil

`func (o *ServiceAssignmentUpdate) SetJobIdNil(b bool)`

 SetJobIdNil sets the value for JobId to be an explicit nil

### UnsetJobId
`func (o *ServiceAssignmentUpdate) UnsetJobId()`

UnsetJobId ensures that no value is present for JobId, not even an explicit nil
### GetNotes

`func (o *ServiceAssignmentUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ServiceAssignmentUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ServiceAssignmentUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ServiceAssignmentUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ServiceAssignmentUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ServiceAssignmentUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetScheduledDate

`func (o *ServiceAssignmentUpdate) GetScheduledDate() string`

GetScheduledDate returns the ScheduledDate field if non-nil, zero value otherwise.

### GetScheduledDateOk

`func (o *ServiceAssignmentUpdate) GetScheduledDateOk() (*string, bool)`

GetScheduledDateOk returns a tuple with the ScheduledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDate

`func (o *ServiceAssignmentUpdate) SetScheduledDate(v string)`

SetScheduledDate sets ScheduledDate field to given value.

### HasScheduledDate

`func (o *ServiceAssignmentUpdate) HasScheduledDate() bool`

HasScheduledDate returns a boolean if a field has been set.

### SetScheduledDateNil

`func (o *ServiceAssignmentUpdate) SetScheduledDateNil(b bool)`

 SetScheduledDateNil sets the value for ScheduledDate to be an explicit nil

### UnsetScheduledDate
`func (o *ServiceAssignmentUpdate) UnsetScheduledDate()`

UnsetScheduledDate ensures that no value is present for ScheduledDate, not even an explicit nil
### GetScheduledEnd

`func (o *ServiceAssignmentUpdate) GetScheduledEnd() string`

GetScheduledEnd returns the ScheduledEnd field if non-nil, zero value otherwise.

### GetScheduledEndOk

`func (o *ServiceAssignmentUpdate) GetScheduledEndOk() (*string, bool)`

GetScheduledEndOk returns a tuple with the ScheduledEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledEnd

`func (o *ServiceAssignmentUpdate) SetScheduledEnd(v string)`

SetScheduledEnd sets ScheduledEnd field to given value.

### HasScheduledEnd

`func (o *ServiceAssignmentUpdate) HasScheduledEnd() bool`

HasScheduledEnd returns a boolean if a field has been set.

### SetScheduledEndNil

`func (o *ServiceAssignmentUpdate) SetScheduledEndNil(b bool)`

 SetScheduledEndNil sets the value for ScheduledEnd to be an explicit nil

### UnsetScheduledEnd
`func (o *ServiceAssignmentUpdate) UnsetScheduledEnd()`

UnsetScheduledEnd ensures that no value is present for ScheduledEnd, not even an explicit nil
### GetScheduledStart

`func (o *ServiceAssignmentUpdate) GetScheduledStart() string`

GetScheduledStart returns the ScheduledStart field if non-nil, zero value otherwise.

### GetScheduledStartOk

`func (o *ServiceAssignmentUpdate) GetScheduledStartOk() (*string, bool)`

GetScheduledStartOk returns a tuple with the ScheduledStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledStart

`func (o *ServiceAssignmentUpdate) SetScheduledStart(v string)`

SetScheduledStart sets ScheduledStart field to given value.

### HasScheduledStart

`func (o *ServiceAssignmentUpdate) HasScheduledStart() bool`

HasScheduledStart returns a boolean if a field has been set.

### SetScheduledStartNil

`func (o *ServiceAssignmentUpdate) SetScheduledStartNil(b bool)`

 SetScheduledStartNil sets the value for ScheduledStart to be an explicit nil

### UnsetScheduledStart
`func (o *ServiceAssignmentUpdate) UnsetScheduledStart()`

UnsetScheduledStart ensures that no value is present for ScheduledStart, not even an explicit nil
### GetStatus

`func (o *ServiceAssignmentUpdate) GetStatus() ServiceAssignmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ServiceAssignmentUpdate) GetStatusOk() (*ServiceAssignmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ServiceAssignmentUpdate) SetStatus(v ServiceAssignmentStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ServiceAssignmentUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *ServiceAssignmentUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ServiceAssignmentUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


