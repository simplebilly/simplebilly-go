# ServiceAssignment

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

### NewServiceAssignment

`func NewServiceAssignment() *ServiceAssignment`

NewServiceAssignment instantiates a new ServiceAssignment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceAssignmentWithDefaults

`func NewServiceAssignmentWithDefaults() *ServiceAssignment`

NewServiceAssignmentWithDefaults instantiates a new ServiceAssignment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployeeId

`func (o *ServiceAssignment) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *ServiceAssignment) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *ServiceAssignment) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *ServiceAssignment) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### GetJobId

`func (o *ServiceAssignment) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ServiceAssignment) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ServiceAssignment) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ServiceAssignment) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetNotes

`func (o *ServiceAssignment) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ServiceAssignment) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ServiceAssignment) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ServiceAssignment) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ServiceAssignment) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ServiceAssignment) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetScheduledDate

`func (o *ServiceAssignment) GetScheduledDate() string`

GetScheduledDate returns the ScheduledDate field if non-nil, zero value otherwise.

### GetScheduledDateOk

`func (o *ServiceAssignment) GetScheduledDateOk() (*string, bool)`

GetScheduledDateOk returns a tuple with the ScheduledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDate

`func (o *ServiceAssignment) SetScheduledDate(v string)`

SetScheduledDate sets ScheduledDate field to given value.

### HasScheduledDate

`func (o *ServiceAssignment) HasScheduledDate() bool`

HasScheduledDate returns a boolean if a field has been set.

### GetScheduledEnd

`func (o *ServiceAssignment) GetScheduledEnd() string`

GetScheduledEnd returns the ScheduledEnd field if non-nil, zero value otherwise.

### GetScheduledEndOk

`func (o *ServiceAssignment) GetScheduledEndOk() (*string, bool)`

GetScheduledEndOk returns a tuple with the ScheduledEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledEnd

`func (o *ServiceAssignment) SetScheduledEnd(v string)`

SetScheduledEnd sets ScheduledEnd field to given value.

### HasScheduledEnd

`func (o *ServiceAssignment) HasScheduledEnd() bool`

HasScheduledEnd returns a boolean if a field has been set.

### SetScheduledEndNil

`func (o *ServiceAssignment) SetScheduledEndNil(b bool)`

 SetScheduledEndNil sets the value for ScheduledEnd to be an explicit nil

### UnsetScheduledEnd
`func (o *ServiceAssignment) UnsetScheduledEnd()`

UnsetScheduledEnd ensures that no value is present for ScheduledEnd, not even an explicit nil
### GetScheduledStart

`func (o *ServiceAssignment) GetScheduledStart() string`

GetScheduledStart returns the ScheduledStart field if non-nil, zero value otherwise.

### GetScheduledStartOk

`func (o *ServiceAssignment) GetScheduledStartOk() (*string, bool)`

GetScheduledStartOk returns a tuple with the ScheduledStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledStart

`func (o *ServiceAssignment) SetScheduledStart(v string)`

SetScheduledStart sets ScheduledStart field to given value.

### HasScheduledStart

`func (o *ServiceAssignment) HasScheduledStart() bool`

HasScheduledStart returns a boolean if a field has been set.

### SetScheduledStartNil

`func (o *ServiceAssignment) SetScheduledStartNil(b bool)`

 SetScheduledStartNil sets the value for ScheduledStart to be an explicit nil

### UnsetScheduledStart
`func (o *ServiceAssignment) UnsetScheduledStart()`

UnsetScheduledStart ensures that no value is present for ScheduledStart, not even an explicit nil
### GetStatus

`func (o *ServiceAssignment) GetStatus() ServiceAssignmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ServiceAssignment) GetStatusOk() (*ServiceAssignmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ServiceAssignment) SetStatus(v ServiceAssignmentStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ServiceAssignment) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


