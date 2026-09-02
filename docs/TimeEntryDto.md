# TimeEntryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClockIn** | Pointer to **NullableTime** |  | [optional] 
**ClockOut** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**Date** | **string** |  | 
**EmployeeId** | **string** |  | 
**Hours** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**TimeEntryId** | **string** |  | 

## Methods

### NewTimeEntryDto

`func NewTimeEntryDto(createdAt time.Time, date string, employeeId string, timeEntryId string, ) *TimeEntryDto`

NewTimeEntryDto instantiates a new TimeEntryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeEntryDtoWithDefaults

`func NewTimeEntryDtoWithDefaults() *TimeEntryDto`

NewTimeEntryDtoWithDefaults instantiates a new TimeEntryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClockIn

`func (o *TimeEntryDto) GetClockIn() time.Time`

GetClockIn returns the ClockIn field if non-nil, zero value otherwise.

### GetClockInOk

`func (o *TimeEntryDto) GetClockInOk() (*time.Time, bool)`

GetClockInOk returns a tuple with the ClockIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClockIn

`func (o *TimeEntryDto) SetClockIn(v time.Time)`

SetClockIn sets ClockIn field to given value.

### HasClockIn

`func (o *TimeEntryDto) HasClockIn() bool`

HasClockIn returns a boolean if a field has been set.

### SetClockInNil

`func (o *TimeEntryDto) SetClockInNil(b bool)`

 SetClockInNil sets the value for ClockIn to be an explicit nil

### UnsetClockIn
`func (o *TimeEntryDto) UnsetClockIn()`

UnsetClockIn ensures that no value is present for ClockIn, not even an explicit nil
### GetClockOut

`func (o *TimeEntryDto) GetClockOut() time.Time`

GetClockOut returns the ClockOut field if non-nil, zero value otherwise.

### GetClockOutOk

`func (o *TimeEntryDto) GetClockOutOk() (*time.Time, bool)`

GetClockOutOk returns a tuple with the ClockOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClockOut

`func (o *TimeEntryDto) SetClockOut(v time.Time)`

SetClockOut sets ClockOut field to given value.

### HasClockOut

`func (o *TimeEntryDto) HasClockOut() bool`

HasClockOut returns a boolean if a field has been set.

### SetClockOutNil

`func (o *TimeEntryDto) SetClockOutNil(b bool)`

 SetClockOutNil sets the value for ClockOut to be an explicit nil

### UnsetClockOut
`func (o *TimeEntryDto) UnsetClockOut()`

UnsetClockOut ensures that no value is present for ClockOut, not even an explicit nil
### GetCreatedAt

`func (o *TimeEntryDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TimeEntryDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TimeEntryDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDate

`func (o *TimeEntryDto) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *TimeEntryDto) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *TimeEntryDto) SetDate(v string)`

SetDate sets Date field to given value.


### GetEmployeeId

`func (o *TimeEntryDto) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *TimeEntryDto) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *TimeEntryDto) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.


### GetHours

`func (o *TimeEntryDto) GetHours() string`

GetHours returns the Hours field if non-nil, zero value otherwise.

### GetHoursOk

`func (o *TimeEntryDto) GetHoursOk() (*string, bool)`

GetHoursOk returns a tuple with the Hours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHours

`func (o *TimeEntryDto) SetHours(v string)`

SetHours sets Hours field to given value.

### HasHours

`func (o *TimeEntryDto) HasHours() bool`

HasHours returns a boolean if a field has been set.

### SetHoursNil

`func (o *TimeEntryDto) SetHoursNil(b bool)`

 SetHoursNil sets the value for Hours to be an explicit nil

### UnsetHours
`func (o *TimeEntryDto) UnsetHours()`

UnsetHours ensures that no value is present for Hours, not even an explicit nil
### GetNotes

`func (o *TimeEntryDto) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *TimeEntryDto) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *TimeEntryDto) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *TimeEntryDto) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *TimeEntryDto) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *TimeEntryDto) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetTimeEntryId

`func (o *TimeEntryDto) GetTimeEntryId() string`

GetTimeEntryId returns the TimeEntryId field if non-nil, zero value otherwise.

### GetTimeEntryIdOk

`func (o *TimeEntryDto) GetTimeEntryIdOk() (*string, bool)`

GetTimeEntryIdOk returns a tuple with the TimeEntryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeEntryId

`func (o *TimeEntryDto) SetTimeEntryId(v string)`

SetTimeEntryId sets TimeEntryId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


