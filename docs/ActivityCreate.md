# ActivityCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivityType** | [**ActivityType**](ActivityType.md) | One of: call | email | meeting | task | note | 
**AssignedTo** | Pointer to **NullableString** | User responsible (&#x60;employee.employee_id&#x60;). | [optional] 
**ContactId** | Pointer to **NullableString** | Contact this activity belongs to (&#x60;contact.contact_id&#x60;). References the contact entity. | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**DueDate** | Pointer to **NullableString** | Follow-up / Wiedervorlage date. Open activities with a due date in the past are overdue. | [optional] 
**ReminderDate** | Pointer to **NullableString** | When to remind about the follow-up. | [optional] 
**Status** | [**ActivityStatus**](ActivityStatus.md) | One of: open | done | cancelled | 
**Subject** | **string** | Short subject line. | 

## Methods

### NewActivityCreate

`func NewActivityCreate(activityType ActivityType, status ActivityStatus, subject string, ) *ActivityCreate`

NewActivityCreate instantiates a new ActivityCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityCreateWithDefaults

`func NewActivityCreateWithDefaults() *ActivityCreate`

NewActivityCreateWithDefaults instantiates a new ActivityCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityType

`func (o *ActivityCreate) GetActivityType() ActivityType`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivityCreate) GetActivityTypeOk() (*ActivityType, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivityCreate) SetActivityType(v ActivityType)`

SetActivityType sets ActivityType field to given value.


### GetAssignedTo

`func (o *ActivityCreate) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *ActivityCreate) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *ActivityCreate) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *ActivityCreate) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### SetAssignedToNil

`func (o *ActivityCreate) SetAssignedToNil(b bool)`

 SetAssignedToNil sets the value for AssignedTo to be an explicit nil

### UnsetAssignedTo
`func (o *ActivityCreate) UnsetAssignedTo()`

UnsetAssignedTo ensures that no value is present for AssignedTo, not even an explicit nil
### GetContactId

`func (o *ActivityCreate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *ActivityCreate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *ActivityCreate) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *ActivityCreate) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *ActivityCreate) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *ActivityCreate) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetDescription

`func (o *ActivityCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ActivityCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ActivityCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ActivityCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ActivityCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ActivityCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDueDate

`func (o *ActivityCreate) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *ActivityCreate) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *ActivityCreate) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *ActivityCreate) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *ActivityCreate) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *ActivityCreate) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetReminderDate

`func (o *ActivityCreate) GetReminderDate() string`

GetReminderDate returns the ReminderDate field if non-nil, zero value otherwise.

### GetReminderDateOk

`func (o *ActivityCreate) GetReminderDateOk() (*string, bool)`

GetReminderDateOk returns a tuple with the ReminderDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderDate

`func (o *ActivityCreate) SetReminderDate(v string)`

SetReminderDate sets ReminderDate field to given value.

### HasReminderDate

`func (o *ActivityCreate) HasReminderDate() bool`

HasReminderDate returns a boolean if a field has been set.

### SetReminderDateNil

`func (o *ActivityCreate) SetReminderDateNil(b bool)`

 SetReminderDateNil sets the value for ReminderDate to be an explicit nil

### UnsetReminderDate
`func (o *ActivityCreate) UnsetReminderDate()`

UnsetReminderDate ensures that no value is present for ReminderDate, not even an explicit nil
### GetStatus

`func (o *ActivityCreate) GetStatus() ActivityStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ActivityCreate) GetStatusOk() (*ActivityStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ActivityCreate) SetStatus(v ActivityStatus)`

SetStatus sets Status field to given value.


### GetSubject

`func (o *ActivityCreate) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *ActivityCreate) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *ActivityCreate) SetSubject(v string)`

SetSubject sets Subject field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


