# AutomationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AutomationKey** | **string** |  | 
**Config** | **interface{}** |  | 
**DefaultDay** | Pointer to **NullableInt32** |  | [optional] 
**Description** | **string** |  | 
**Enabled** | **bool** |  | 
**Kind** | **string** |  | 
**LastRunAt** | Pointer to **NullableTime** |  | [optional] 
**NextRunAt** | Pointer to **NullableTime** |  | [optional] 
**ScheduleKind** | **string** |  | 

## Methods

### NewAutomationDto

`func NewAutomationDto(automationKey string, config interface{}, description string, enabled bool, kind string, scheduleKind string, ) *AutomationDto`

NewAutomationDto instantiates a new AutomationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAutomationDtoWithDefaults

`func NewAutomationDtoWithDefaults() *AutomationDto`

NewAutomationDtoWithDefaults instantiates a new AutomationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAutomationKey

`func (o *AutomationDto) GetAutomationKey() string`

GetAutomationKey returns the AutomationKey field if non-nil, zero value otherwise.

### GetAutomationKeyOk

`func (o *AutomationDto) GetAutomationKeyOk() (*string, bool)`

GetAutomationKeyOk returns a tuple with the AutomationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomationKey

`func (o *AutomationDto) SetAutomationKey(v string)`

SetAutomationKey sets AutomationKey field to given value.


### GetConfig

`func (o *AutomationDto) GetConfig() interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *AutomationDto) GetConfigOk() (*interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *AutomationDto) SetConfig(v interface{})`

SetConfig sets Config field to given value.


### SetConfigNil

`func (o *AutomationDto) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *AutomationDto) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetDefaultDay

`func (o *AutomationDto) GetDefaultDay() int32`

GetDefaultDay returns the DefaultDay field if non-nil, zero value otherwise.

### GetDefaultDayOk

`func (o *AutomationDto) GetDefaultDayOk() (*int32, bool)`

GetDefaultDayOk returns a tuple with the DefaultDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultDay

`func (o *AutomationDto) SetDefaultDay(v int32)`

SetDefaultDay sets DefaultDay field to given value.

### HasDefaultDay

`func (o *AutomationDto) HasDefaultDay() bool`

HasDefaultDay returns a boolean if a field has been set.

### SetDefaultDayNil

`func (o *AutomationDto) SetDefaultDayNil(b bool)`

 SetDefaultDayNil sets the value for DefaultDay to be an explicit nil

### UnsetDefaultDay
`func (o *AutomationDto) UnsetDefaultDay()`

UnsetDefaultDay ensures that no value is present for DefaultDay, not even an explicit nil
### GetDescription

`func (o *AutomationDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AutomationDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AutomationDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEnabled

`func (o *AutomationDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AutomationDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AutomationDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetKind

`func (o *AutomationDto) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AutomationDto) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AutomationDto) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLastRunAt

`func (o *AutomationDto) GetLastRunAt() time.Time`

GetLastRunAt returns the LastRunAt field if non-nil, zero value otherwise.

### GetLastRunAtOk

`func (o *AutomationDto) GetLastRunAtOk() (*time.Time, bool)`

GetLastRunAtOk returns a tuple with the LastRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRunAt

`func (o *AutomationDto) SetLastRunAt(v time.Time)`

SetLastRunAt sets LastRunAt field to given value.

### HasLastRunAt

`func (o *AutomationDto) HasLastRunAt() bool`

HasLastRunAt returns a boolean if a field has been set.

### SetLastRunAtNil

`func (o *AutomationDto) SetLastRunAtNil(b bool)`

 SetLastRunAtNil sets the value for LastRunAt to be an explicit nil

### UnsetLastRunAt
`func (o *AutomationDto) UnsetLastRunAt()`

UnsetLastRunAt ensures that no value is present for LastRunAt, not even an explicit nil
### GetNextRunAt

`func (o *AutomationDto) GetNextRunAt() time.Time`

GetNextRunAt returns the NextRunAt field if non-nil, zero value otherwise.

### GetNextRunAtOk

`func (o *AutomationDto) GetNextRunAtOk() (*time.Time, bool)`

GetNextRunAtOk returns a tuple with the NextRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextRunAt

`func (o *AutomationDto) SetNextRunAt(v time.Time)`

SetNextRunAt sets NextRunAt field to given value.

### HasNextRunAt

`func (o *AutomationDto) HasNextRunAt() bool`

HasNextRunAt returns a boolean if a field has been set.

### SetNextRunAtNil

`func (o *AutomationDto) SetNextRunAtNil(b bool)`

 SetNextRunAtNil sets the value for NextRunAt to be an explicit nil

### UnsetNextRunAt
`func (o *AutomationDto) UnsetNextRunAt()`

UnsetNextRunAt ensures that no value is present for NextRunAt, not even an explicit nil
### GetScheduleKind

`func (o *AutomationDto) GetScheduleKind() string`

GetScheduleKind returns the ScheduleKind field if non-nil, zero value otherwise.

### GetScheduleKindOk

`func (o *AutomationDto) GetScheduleKindOk() (*string, bool)`

GetScheduleKindOk returns a tuple with the ScheduleKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleKind

`func (o *AutomationDto) SetScheduleKind(v string)`

SetScheduleKind sets ScheduleKind field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


