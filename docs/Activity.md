# Activity

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

### NewActivity

`func NewActivity(activityType ActivityType, status ActivityStatus, subject string, ) *Activity`

NewActivity instantiates a new Activity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityWithDefaults

`func NewActivityWithDefaults() *Activity`

NewActivityWithDefaults instantiates a new Activity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityType

`func (o *Activity) GetActivityType() ActivityType`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *Activity) GetActivityTypeOk() (*ActivityType, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *Activity) SetActivityType(v ActivityType)`

SetActivityType sets ActivityType field to given value.


### GetAssignedTo

`func (o *Activity) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *Activity) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *Activity) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *Activity) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### SetAssignedToNil

`func (o *Activity) SetAssignedToNil(b bool)`

 SetAssignedToNil sets the value for AssignedTo to be an explicit nil

### UnsetAssignedTo
`func (o *Activity) UnsetAssignedTo()`

UnsetAssignedTo ensures that no value is present for AssignedTo, not even an explicit nil
### GetContactId

`func (o *Activity) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *Activity) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *Activity) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *Activity) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *Activity) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *Activity) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetDescription

`func (o *Activity) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Activity) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Activity) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Activity) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Activity) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Activity) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDueDate

`func (o *Activity) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *Activity) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *Activity) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *Activity) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *Activity) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *Activity) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetReminderDate

`func (o *Activity) GetReminderDate() string`

GetReminderDate returns the ReminderDate field if non-nil, zero value otherwise.

### GetReminderDateOk

`func (o *Activity) GetReminderDateOk() (*string, bool)`

GetReminderDateOk returns a tuple with the ReminderDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderDate

`func (o *Activity) SetReminderDate(v string)`

SetReminderDate sets ReminderDate field to given value.

### HasReminderDate

`func (o *Activity) HasReminderDate() bool`

HasReminderDate returns a boolean if a field has been set.

### SetReminderDateNil

`func (o *Activity) SetReminderDateNil(b bool)`

 SetReminderDateNil sets the value for ReminderDate to be an explicit nil

### UnsetReminderDate
`func (o *Activity) UnsetReminderDate()`

UnsetReminderDate ensures that no value is present for ReminderDate, not even an explicit nil
### GetStatus

`func (o *Activity) GetStatus() ActivityStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Activity) GetStatusOk() (*ActivityStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Activity) SetStatus(v ActivityStatus)`

SetStatus sets Status field to given value.


### GetSubject

`func (o *Activity) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *Activity) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *Activity) SetSubject(v string)`

SetSubject sets Subject field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


