# ServiceAssignmentCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmployeeId** | Pointer to **string** | References the employees entity. | [optional] 
**JobId** | Pointer to **string** | References the service_jobs entity. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**ScheduledDate** | Pointer to **string** | Work day the assignment is scheduled for. | [optional] 
**ScheduledEnd** | Pointer to **NullableString** | Planned end time of the assignment. | [optional] 
**ScheduledStart** | Pointer to **NullableString** | Planned start time of the assignment. | [optional] 
**Status** | Pointer to [**ServiceAssignmentStatus**](ServiceAssignmentStatus.md) | Assignment lifecycle status: \&quot;planned\&quot;, \&quot;confirmed\&quot;, \&quot;en_route\&quot;, \&quot;in_progress\&quot;, \&quot;completed\&quot; or \&quot;cancelled\&quot;. | [optional] 

## Methods

### NewServiceAssignmentCreate

`func NewServiceAssignmentCreate() *ServiceAssignmentCreate`

NewServiceAssignmentCreate instantiates a new ServiceAssignmentCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceAssignmentCreateWithDefaults

`func NewServiceAssignmentCreateWithDefaults() *ServiceAssignmentCreate`

NewServiceAssignmentCreateWithDefaults instantiates a new ServiceAssignmentCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployeeId

`func (o *ServiceAssignmentCreate) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *ServiceAssignmentCreate) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *ServiceAssignmentCreate) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *ServiceAssignmentCreate) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### GetJobId

`func (o *ServiceAssignmentCreate) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ServiceAssignmentCreate) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ServiceAssignmentCreate) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ServiceAssignmentCreate) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetNotes

`func (o *ServiceAssignmentCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ServiceAssignmentCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ServiceAssignmentCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ServiceAssignmentCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ServiceAssignmentCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ServiceAssignmentCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetScheduledDate

`func (o *ServiceAssignmentCreate) GetScheduledDate() string`

GetScheduledDate returns the ScheduledDate field if non-nil, zero value otherwise.

### GetScheduledDateOk

`func (o *ServiceAssignmentCreate) GetScheduledDateOk() (*string, bool)`

GetScheduledDateOk returns a tuple with the ScheduledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDate

`func (o *ServiceAssignmentCreate) SetScheduledDate(v string)`

SetScheduledDate sets ScheduledDate field to given value.

### HasScheduledDate

`func (o *ServiceAssignmentCreate) HasScheduledDate() bool`

HasScheduledDate returns a boolean if a field has been set.

### GetScheduledEnd

`func (o *ServiceAssignmentCreate) GetScheduledEnd() string`

GetScheduledEnd returns the ScheduledEnd field if non-nil, zero value otherwise.

### GetScheduledEndOk

`func (o *ServiceAssignmentCreate) GetScheduledEndOk() (*string, bool)`

GetScheduledEndOk returns a tuple with the ScheduledEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledEnd

`func (o *ServiceAssignmentCreate) SetScheduledEnd(v string)`

SetScheduledEnd sets ScheduledEnd field to given value.

### HasScheduledEnd

`func (o *ServiceAssignmentCreate) HasScheduledEnd() bool`

HasScheduledEnd returns a boolean if a field has been set.

### SetScheduledEndNil

`func (o *ServiceAssignmentCreate) SetScheduledEndNil(b bool)`

 SetScheduledEndNil sets the value for ScheduledEnd to be an explicit nil

### UnsetScheduledEnd
`func (o *ServiceAssignmentCreate) UnsetScheduledEnd()`

UnsetScheduledEnd ensures that no value is present for ScheduledEnd, not even an explicit nil
### GetScheduledStart

`func (o *ServiceAssignmentCreate) GetScheduledStart() string`

GetScheduledStart returns the ScheduledStart field if non-nil, zero value otherwise.

### GetScheduledStartOk

`func (o *ServiceAssignmentCreate) GetScheduledStartOk() (*string, bool)`

GetScheduledStartOk returns a tuple with the ScheduledStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledStart

`func (o *ServiceAssignmentCreate) SetScheduledStart(v string)`

SetScheduledStart sets ScheduledStart field to given value.

### HasScheduledStart

`func (o *ServiceAssignmentCreate) HasScheduledStart() bool`

HasScheduledStart returns a boolean if a field has been set.

### SetScheduledStartNil

`func (o *ServiceAssignmentCreate) SetScheduledStartNil(b bool)`

 SetScheduledStartNil sets the value for ScheduledStart to be an explicit nil

### UnsetScheduledStart
`func (o *ServiceAssignmentCreate) UnsetScheduledStart()`

UnsetScheduledStart ensures that no value is present for ScheduledStart, not even an explicit nil
### GetStatus

`func (o *ServiceAssignmentCreate) GetStatus() ServiceAssignmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ServiceAssignmentCreate) GetStatusOk() (*ServiceAssignmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ServiceAssignmentCreate) SetStatus(v ServiceAssignmentStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ServiceAssignmentCreate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


