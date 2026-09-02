# TrainingAssignment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedBy** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 
**DueDate** | Pointer to **NullableString** |  | [optional] 
**EmployeeId** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**AssignmentStatus**](AssignmentStatus.md) |  | [optional] 
**TenantId** | Pointer to **string** |  | [optional] 
**TrainingId** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewTrainingAssignment

`func NewTrainingAssignment() *TrainingAssignment`

NewTrainingAssignment instantiates a new TrainingAssignment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrainingAssignmentWithDefaults

`func NewTrainingAssignmentWithDefaults() *TrainingAssignment`

NewTrainingAssignmentWithDefaults instantiates a new TrainingAssignment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedBy

`func (o *TrainingAssignment) GetAssignedBy() string`

GetAssignedBy returns the AssignedBy field if non-nil, zero value otherwise.

### GetAssignedByOk

`func (o *TrainingAssignment) GetAssignedByOk() (*string, bool)`

GetAssignedByOk returns a tuple with the AssignedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedBy

`func (o *TrainingAssignment) SetAssignedBy(v string)`

SetAssignedBy sets AssignedBy field to given value.

### HasAssignedBy

`func (o *TrainingAssignment) HasAssignedBy() bool`

HasAssignedBy returns a boolean if a field has been set.

### SetAssignedByNil

`func (o *TrainingAssignment) SetAssignedByNil(b bool)`

 SetAssignedByNil sets the value for AssignedBy to be an explicit nil

### UnsetAssignedBy
`func (o *TrainingAssignment) UnsetAssignedBy()`

UnsetAssignedBy ensures that no value is present for AssignedBy, not even an explicit nil
### GetCreatedAt

`func (o *TrainingAssignment) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TrainingAssignment) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TrainingAssignment) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TrainingAssignment) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *TrainingAssignment) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *TrainingAssignment) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *TrainingAssignment) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *TrainingAssignment) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *TrainingAssignment) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *TrainingAssignment) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetDueDate

`func (o *TrainingAssignment) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *TrainingAssignment) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *TrainingAssignment) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *TrainingAssignment) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *TrainingAssignment) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *TrainingAssignment) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetEmployeeId

`func (o *TrainingAssignment) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *TrainingAssignment) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *TrainingAssignment) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *TrainingAssignment) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### GetId

`func (o *TrainingAssignment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TrainingAssignment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TrainingAssignment) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *TrainingAssignment) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNotes

`func (o *TrainingAssignment) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *TrainingAssignment) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *TrainingAssignment) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *TrainingAssignment) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *TrainingAssignment) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *TrainingAssignment) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *TrainingAssignment) GetStatus() AssignmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TrainingAssignment) GetStatusOk() (*AssignmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TrainingAssignment) SetStatus(v AssignmentStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TrainingAssignment) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTenantId

`func (o *TrainingAssignment) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *TrainingAssignment) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *TrainingAssignment) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *TrainingAssignment) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetTrainingId

`func (o *TrainingAssignment) GetTrainingId() string`

GetTrainingId returns the TrainingId field if non-nil, zero value otherwise.

### GetTrainingIdOk

`func (o *TrainingAssignment) GetTrainingIdOk() (*string, bool)`

GetTrainingIdOk returns a tuple with the TrainingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrainingId

`func (o *TrainingAssignment) SetTrainingId(v string)`

SetTrainingId sets TrainingId field to given value.

### HasTrainingId

`func (o *TrainingAssignment) HasTrainingId() bool`

HasTrainingId returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *TrainingAssignment) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TrainingAssignment) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TrainingAssignment) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *TrainingAssignment) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *TrainingAssignment) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *TrainingAssignment) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


