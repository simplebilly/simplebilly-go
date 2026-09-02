# RecurringTemplateCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EndDate** | Pointer to **NullableString** |  | [optional] 
**ExecutionInterval** | **string** |  | 
**ExecutionStatus** | [**ExecutionStatus**](ExecutionStatus.md) |  | 
**Finalize** | Pointer to **bool** |  | [optional] 
**LastExecutedAt** | Pointer to **NullableTime** |  | [optional] 
**Name** | **string** |  | 
**NextExecutionAt** | Pointer to **NullableTime** |  | [optional] 
**StartDate** | **string** |  | 
**TemplateType** | [**RecurringTemplateType**](RecurringTemplateType.md) |  | 
**VoucherData** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewRecurringTemplateCreate

`func NewRecurringTemplateCreate(executionInterval string, executionStatus ExecutionStatus, name string, startDate string, templateType RecurringTemplateType, ) *RecurringTemplateCreate`

NewRecurringTemplateCreate instantiates a new RecurringTemplateCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecurringTemplateCreateWithDefaults

`func NewRecurringTemplateCreateWithDefaults() *RecurringTemplateCreate`

NewRecurringTemplateCreateWithDefaults instantiates a new RecurringTemplateCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEndDate

`func (o *RecurringTemplateCreate) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *RecurringTemplateCreate) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *RecurringTemplateCreate) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *RecurringTemplateCreate) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### SetEndDateNil

`func (o *RecurringTemplateCreate) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *RecurringTemplateCreate) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetExecutionInterval

`func (o *RecurringTemplateCreate) GetExecutionInterval() string`

GetExecutionInterval returns the ExecutionInterval field if non-nil, zero value otherwise.

### GetExecutionIntervalOk

`func (o *RecurringTemplateCreate) GetExecutionIntervalOk() (*string, bool)`

GetExecutionIntervalOk returns a tuple with the ExecutionInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionInterval

`func (o *RecurringTemplateCreate) SetExecutionInterval(v string)`

SetExecutionInterval sets ExecutionInterval field to given value.


### GetExecutionStatus

`func (o *RecurringTemplateCreate) GetExecutionStatus() ExecutionStatus`

GetExecutionStatus returns the ExecutionStatus field if non-nil, zero value otherwise.

### GetExecutionStatusOk

`func (o *RecurringTemplateCreate) GetExecutionStatusOk() (*ExecutionStatus, bool)`

GetExecutionStatusOk returns a tuple with the ExecutionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionStatus

`func (o *RecurringTemplateCreate) SetExecutionStatus(v ExecutionStatus)`

SetExecutionStatus sets ExecutionStatus field to given value.


### GetFinalize

`func (o *RecurringTemplateCreate) GetFinalize() bool`

GetFinalize returns the Finalize field if non-nil, zero value otherwise.

### GetFinalizeOk

`func (o *RecurringTemplateCreate) GetFinalizeOk() (*bool, bool)`

GetFinalizeOk returns a tuple with the Finalize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalize

`func (o *RecurringTemplateCreate) SetFinalize(v bool)`

SetFinalize sets Finalize field to given value.

### HasFinalize

`func (o *RecurringTemplateCreate) HasFinalize() bool`

HasFinalize returns a boolean if a field has been set.

### GetLastExecutedAt

`func (o *RecurringTemplateCreate) GetLastExecutedAt() time.Time`

GetLastExecutedAt returns the LastExecutedAt field if non-nil, zero value otherwise.

### GetLastExecutedAtOk

`func (o *RecurringTemplateCreate) GetLastExecutedAtOk() (*time.Time, bool)`

GetLastExecutedAtOk returns a tuple with the LastExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExecutedAt

`func (o *RecurringTemplateCreate) SetLastExecutedAt(v time.Time)`

SetLastExecutedAt sets LastExecutedAt field to given value.

### HasLastExecutedAt

`func (o *RecurringTemplateCreate) HasLastExecutedAt() bool`

HasLastExecutedAt returns a boolean if a field has been set.

### SetLastExecutedAtNil

`func (o *RecurringTemplateCreate) SetLastExecutedAtNil(b bool)`

 SetLastExecutedAtNil sets the value for LastExecutedAt to be an explicit nil

### UnsetLastExecutedAt
`func (o *RecurringTemplateCreate) UnsetLastExecutedAt()`

UnsetLastExecutedAt ensures that no value is present for LastExecutedAt, not even an explicit nil
### GetName

`func (o *RecurringTemplateCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RecurringTemplateCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RecurringTemplateCreate) SetName(v string)`

SetName sets Name field to given value.


### GetNextExecutionAt

`func (o *RecurringTemplateCreate) GetNextExecutionAt() time.Time`

GetNextExecutionAt returns the NextExecutionAt field if non-nil, zero value otherwise.

### GetNextExecutionAtOk

`func (o *RecurringTemplateCreate) GetNextExecutionAtOk() (*time.Time, bool)`

GetNextExecutionAtOk returns a tuple with the NextExecutionAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextExecutionAt

`func (o *RecurringTemplateCreate) SetNextExecutionAt(v time.Time)`

SetNextExecutionAt sets NextExecutionAt field to given value.

### HasNextExecutionAt

`func (o *RecurringTemplateCreate) HasNextExecutionAt() bool`

HasNextExecutionAt returns a boolean if a field has been set.

### SetNextExecutionAtNil

`func (o *RecurringTemplateCreate) SetNextExecutionAtNil(b bool)`

 SetNextExecutionAtNil sets the value for NextExecutionAt to be an explicit nil

### UnsetNextExecutionAt
`func (o *RecurringTemplateCreate) UnsetNextExecutionAt()`

UnsetNextExecutionAt ensures that no value is present for NextExecutionAt, not even an explicit nil
### GetStartDate

`func (o *RecurringTemplateCreate) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *RecurringTemplateCreate) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *RecurringTemplateCreate) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.


### GetTemplateType

`func (o *RecurringTemplateCreate) GetTemplateType() RecurringTemplateType`

GetTemplateType returns the TemplateType field if non-nil, zero value otherwise.

### GetTemplateTypeOk

`func (o *RecurringTemplateCreate) GetTemplateTypeOk() (*RecurringTemplateType, bool)`

GetTemplateTypeOk returns a tuple with the TemplateType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateType

`func (o *RecurringTemplateCreate) SetTemplateType(v RecurringTemplateType)`

SetTemplateType sets TemplateType field to given value.


### GetVoucherData

`func (o *RecurringTemplateCreate) GetVoucherData() interface{}`

GetVoucherData returns the VoucherData field if non-nil, zero value otherwise.

### GetVoucherDataOk

`func (o *RecurringTemplateCreate) GetVoucherDataOk() (*interface{}, bool)`

GetVoucherDataOk returns a tuple with the VoucherData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherData

`func (o *RecurringTemplateCreate) SetVoucherData(v interface{})`

SetVoucherData sets VoucherData field to given value.

### HasVoucherData

`func (o *RecurringTemplateCreate) HasVoucherData() bool`

HasVoucherData returns a boolean if a field has been set.

### SetVoucherDataNil

`func (o *RecurringTemplateCreate) SetVoucherDataNil(b bool)`

 SetVoucherDataNil sets the value for VoucherData to be an explicit nil

### UnsetVoucherData
`func (o *RecurringTemplateCreate) UnsetVoucherData()`

UnsetVoucherData ensures that no value is present for VoucherData, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


