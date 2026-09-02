# ActivityUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivityType** | Pointer to [**NullableActivityType**](ActivityType.md) | One of: call | email | meeting | task | note | [optional] 
**AssignedTo** | Pointer to **NullableString** | User responsible (&#x60;employee.employee_id&#x60;). | [optional] 
**ContactId** | Pointer to **NullableString** | Contact this activity belongs to (&#x60;contact.contact_id&#x60;). References the contact entity. | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**DueDate** | Pointer to **NullableString** | Follow-up / Wiedervorlage date. Open activities with a due date in the past are overdue. | [optional] 
**ReminderDate** | Pointer to **NullableString** | When to remind about the follow-up. | [optional] 
**Status** | Pointer to [**NullableActivityStatus**](ActivityStatus.md) | One of: open | done | cancelled | [optional] 
**Subject** | Pointer to **NullableString** | Short subject line. | [optional] 

## Methods

### NewActivityUpdate

`func NewActivityUpdate() *ActivityUpdate`

NewActivityUpdate instantiates a new ActivityUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityUpdateWithDefaults

`func NewActivityUpdateWithDefaults() *ActivityUpdate`

NewActivityUpdateWithDefaults instantiates a new ActivityUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityType

`func (o *ActivityUpdate) GetActivityType() ActivityType`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivityUpdate) GetActivityTypeOk() (*ActivityType, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivityUpdate) SetActivityType(v ActivityType)`

SetActivityType sets ActivityType field to given value.

### HasActivityType

`func (o *ActivityUpdate) HasActivityType() bool`

HasActivityType returns a boolean if a field has been set.

### SetActivityTypeNil

`func (o *ActivityUpdate) SetActivityTypeNil(b bool)`

 SetActivityTypeNil sets the value for ActivityType to be an explicit nil

### UnsetActivityType
`func (o *ActivityUpdate) UnsetActivityType()`

UnsetActivityType ensures that no value is present for ActivityType, not even an explicit nil
### GetAssignedTo

`func (o *ActivityUpdate) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *ActivityUpdate) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *ActivityUpdate) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *ActivityUpdate) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### SetAssignedToNil

`func (o *ActivityUpdate) SetAssignedToNil(b bool)`

 SetAssignedToNil sets the value for AssignedTo to be an explicit nil

### UnsetAssignedTo
`func (o *ActivityUpdate) UnsetAssignedTo()`

UnsetAssignedTo ensures that no value is present for AssignedTo, not even an explicit nil
### GetContactId

`func (o *ActivityUpdate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *ActivityUpdate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *ActivityUpdate) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *ActivityUpdate) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *ActivityUpdate) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *ActivityUpdate) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetDescription

`func (o *ActivityUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ActivityUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ActivityUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ActivityUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ActivityUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ActivityUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDueDate

`func (o *ActivityUpdate) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *ActivityUpdate) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *ActivityUpdate) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *ActivityUpdate) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *ActivityUpdate) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *ActivityUpdate) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetReminderDate

`func (o *ActivityUpdate) GetReminderDate() string`

GetReminderDate returns the ReminderDate field if non-nil, zero value otherwise.

### GetReminderDateOk

`func (o *ActivityUpdate) GetReminderDateOk() (*string, bool)`

GetReminderDateOk returns a tuple with the ReminderDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderDate

`func (o *ActivityUpdate) SetReminderDate(v string)`

SetReminderDate sets ReminderDate field to given value.

### HasReminderDate

`func (o *ActivityUpdate) HasReminderDate() bool`

HasReminderDate returns a boolean if a field has been set.

### SetReminderDateNil

`func (o *ActivityUpdate) SetReminderDateNil(b bool)`

 SetReminderDateNil sets the value for ReminderDate to be an explicit nil

### UnsetReminderDate
`func (o *ActivityUpdate) UnsetReminderDate()`

UnsetReminderDate ensures that no value is present for ReminderDate, not even an explicit nil
### GetStatus

`func (o *ActivityUpdate) GetStatus() ActivityStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ActivityUpdate) GetStatusOk() (*ActivityStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ActivityUpdate) SetStatus(v ActivityStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ActivityUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *ActivityUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ActivityUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSubject

`func (o *ActivityUpdate) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *ActivityUpdate) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *ActivityUpdate) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *ActivityUpdate) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *ActivityUpdate) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *ActivityUpdate) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


