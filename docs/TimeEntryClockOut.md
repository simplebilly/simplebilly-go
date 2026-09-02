# TimeEntryClockOut

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClockOut** | **time.Time** |  | 
**Hours** | Pointer to **NullableString** | Optional manual hours; when absent, derived from clock_in..clock_out. | [optional] 

## Methods

### NewTimeEntryClockOut

`func NewTimeEntryClockOut(clockOut time.Time, ) *TimeEntryClockOut`

NewTimeEntryClockOut instantiates a new TimeEntryClockOut object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeEntryClockOutWithDefaults

`func NewTimeEntryClockOutWithDefaults() *TimeEntryClockOut`

NewTimeEntryClockOutWithDefaults instantiates a new TimeEntryClockOut object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClockOut

`func (o *TimeEntryClockOut) GetClockOut() time.Time`

GetClockOut returns the ClockOut field if non-nil, zero value otherwise.

### GetClockOutOk

`func (o *TimeEntryClockOut) GetClockOutOk() (*time.Time, bool)`

GetClockOutOk returns a tuple with the ClockOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClockOut

`func (o *TimeEntryClockOut) SetClockOut(v time.Time)`

SetClockOut sets ClockOut field to given value.


### GetHours

`func (o *TimeEntryClockOut) GetHours() string`

GetHours returns the Hours field if non-nil, zero value otherwise.

### GetHoursOk

`func (o *TimeEntryClockOut) GetHoursOk() (*string, bool)`

GetHoursOk returns a tuple with the Hours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHours

`func (o *TimeEntryClockOut) SetHours(v string)`

SetHours sets Hours field to given value.

### HasHours

`func (o *TimeEntryClockOut) HasHours() bool`

HasHours returns a boolean if a field has been set.

### SetHoursNil

`func (o *TimeEntryClockOut) SetHoursNil(b bool)`

 SetHoursNil sets the value for Hours to be an explicit nil

### UnsetHours
`func (o *TimeEntryClockOut) UnsetHours()`

UnsetHours ensures that no value is present for Hours, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


