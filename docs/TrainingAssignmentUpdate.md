# TrainingAssignmentUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedBy** | Pointer to **NullableString** |  | [optional] 
**DueDate** | Pointer to **NullableString** |  | [optional] 
**EmployeeId** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableAssignmentStatus**](AssignmentStatus.md) |  | [optional] 
**TrainingId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTrainingAssignmentUpdate

`func NewTrainingAssignmentUpdate() *TrainingAssignmentUpdate`

NewTrainingAssignmentUpdate instantiates a new TrainingAssignmentUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrainingAssignmentUpdateWithDefaults

`func NewTrainingAssignmentUpdateWithDefaults() *TrainingAssignmentUpdate`

NewTrainingAssignmentUpdateWithDefaults instantiates a new TrainingAssignmentUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedBy

`func (o *TrainingAssignmentUpdate) GetAssignedBy() string`

GetAssignedBy returns the AssignedBy field if non-nil, zero value otherwise.

### GetAssignedByOk

`func (o *TrainingAssignmentUpdate) GetAssignedByOk() (*string, bool)`

GetAssignedByOk returns a tuple with the AssignedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedBy

`func (o *TrainingAssignmentUpdate) SetAssignedBy(v string)`

SetAssignedBy sets AssignedBy field to given value.

### HasAssignedBy

`func (o *TrainingAssignmentUpdate) HasAssignedBy() bool`

HasAssignedBy returns a boolean if a field has been set.

### SetAssignedByNil

`func (o *TrainingAssignmentUpdate) SetAssignedByNil(b bool)`

 SetAssignedByNil sets the value for AssignedBy to be an explicit nil

### UnsetAssignedBy
`func (o *TrainingAssignmentUpdate) UnsetAssignedBy()`

UnsetAssignedBy ensures that no value is present for AssignedBy, not even an explicit nil
### GetDueDate

`func (o *TrainingAssignmentUpdate) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *TrainingAssignmentUpdate) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *TrainingAssignmentUpdate) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *TrainingAssignmentUpdate) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *TrainingAssignmentUpdate) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *TrainingAssignmentUpdate) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetEmployeeId

`func (o *TrainingAssignmentUpdate) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *TrainingAssignmentUpdate) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *TrainingAssignmentUpdate) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *TrainingAssignmentUpdate) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### SetEmployeeIdNil

`func (o *TrainingAssignmentUpdate) SetEmployeeIdNil(b bool)`

 SetEmployeeIdNil sets the value for EmployeeId to be an explicit nil

### UnsetEmployeeId
`func (o *TrainingAssignmentUpdate) UnsetEmployeeId()`

UnsetEmployeeId ensures that no value is present for EmployeeId, not even an explicit nil
### GetNotes

`func (o *TrainingAssignmentUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *TrainingAssignmentUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *TrainingAssignmentUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *TrainingAssignmentUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *TrainingAssignmentUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *TrainingAssignmentUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *TrainingAssignmentUpdate) GetStatus() AssignmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TrainingAssignmentUpdate) GetStatusOk() (*AssignmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TrainingAssignmentUpdate) SetStatus(v AssignmentStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TrainingAssignmentUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *TrainingAssignmentUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *TrainingAssignmentUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetTrainingId

`func (o *TrainingAssignmentUpdate) GetTrainingId() string`

GetTrainingId returns the TrainingId field if non-nil, zero value otherwise.

### GetTrainingIdOk

`func (o *TrainingAssignmentUpdate) GetTrainingIdOk() (*string, bool)`

GetTrainingIdOk returns a tuple with the TrainingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrainingId

`func (o *TrainingAssignmentUpdate) SetTrainingId(v string)`

SetTrainingId sets TrainingId field to given value.

### HasTrainingId

`func (o *TrainingAssignmentUpdate) HasTrainingId() bool`

HasTrainingId returns a boolean if a field has been set.

### SetTrainingIdNil

`func (o *TrainingAssignmentUpdate) SetTrainingIdNil(b bool)`

 SetTrainingIdNil sets the value for TrainingId to be an explicit nil

### UnsetTrainingId
`func (o *TrainingAssignmentUpdate) UnsetTrainingId()`

UnsetTrainingId ensures that no value is present for TrainingId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


