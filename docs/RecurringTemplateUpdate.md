# RecurringTemplateUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EndDate** | Pointer to **NullableString** |  | [optional] 
**ExecutionInterval** | Pointer to **NullableString** |  | [optional] 
**ExecutionStatus** | Pointer to [**NullableExecutionStatus**](ExecutionStatus.md) |  | [optional] 
**Finalize** | Pointer to **NullableBool** |  | [optional] 
**LastExecutedAt** | Pointer to **NullableTime** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**NextExecutionAt** | Pointer to **NullableTime** |  | [optional] 
**StartDate** | Pointer to **NullableString** |  | [optional] 
**TemplateType** | Pointer to [**NullableRecurringTemplateType**](RecurringTemplateType.md) |  | [optional] 
**VoucherData** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewRecurringTemplateUpdate

`func NewRecurringTemplateUpdate() *RecurringTemplateUpdate`

NewRecurringTemplateUpdate instantiates a new RecurringTemplateUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecurringTemplateUpdateWithDefaults

`func NewRecurringTemplateUpdateWithDefaults() *RecurringTemplateUpdate`

NewRecurringTemplateUpdateWithDefaults instantiates a new RecurringTemplateUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEndDate

`func (o *RecurringTemplateUpdate) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *RecurringTemplateUpdate) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *RecurringTemplateUpdate) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *RecurringTemplateUpdate) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### SetEndDateNil

`func (o *RecurringTemplateUpdate) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *RecurringTemplateUpdate) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetExecutionInterval

`func (o *RecurringTemplateUpdate) GetExecutionInterval() string`

GetExecutionInterval returns the ExecutionInterval field if non-nil, zero value otherwise.

### GetExecutionIntervalOk

`func (o *RecurringTemplateUpdate) GetExecutionIntervalOk() (*string, bool)`

GetExecutionIntervalOk returns a tuple with the ExecutionInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionInterval

`func (o *RecurringTemplateUpdate) SetExecutionInterval(v string)`

SetExecutionInterval sets ExecutionInterval field to given value.

### HasExecutionInterval

`func (o *RecurringTemplateUpdate) HasExecutionInterval() bool`

HasExecutionInterval returns a boolean if a field has been set.

### SetExecutionIntervalNil

`func (o *RecurringTemplateUpdate) SetExecutionIntervalNil(b bool)`

 SetExecutionIntervalNil sets the value for ExecutionInterval to be an explicit nil

### UnsetExecutionInterval
`func (o *RecurringTemplateUpdate) UnsetExecutionInterval()`

UnsetExecutionInterval ensures that no value is present for ExecutionInterval, not even an explicit nil
### GetExecutionStatus

`func (o *RecurringTemplateUpdate) GetExecutionStatus() ExecutionStatus`

GetExecutionStatus returns the ExecutionStatus field if non-nil, zero value otherwise.

### GetExecutionStatusOk

`func (o *RecurringTemplateUpdate) GetExecutionStatusOk() (*ExecutionStatus, bool)`

GetExecutionStatusOk returns a tuple with the ExecutionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionStatus

`func (o *RecurringTemplateUpdate) SetExecutionStatus(v ExecutionStatus)`

SetExecutionStatus sets ExecutionStatus field to given value.

### HasExecutionStatus

`func (o *RecurringTemplateUpdate) HasExecutionStatus() bool`

HasExecutionStatus returns a boolean if a field has been set.

### SetExecutionStatusNil

`func (o *RecurringTemplateUpdate) SetExecutionStatusNil(b bool)`

 SetExecutionStatusNil sets the value for ExecutionStatus to be an explicit nil

### UnsetExecutionStatus
`func (o *RecurringTemplateUpdate) UnsetExecutionStatus()`

UnsetExecutionStatus ensures that no value is present for ExecutionStatus, not even an explicit nil
### GetFinalize

`func (o *RecurringTemplateUpdate) GetFinalize() bool`

GetFinalize returns the Finalize field if non-nil, zero value otherwise.

### GetFinalizeOk

`func (o *RecurringTemplateUpdate) GetFinalizeOk() (*bool, bool)`

GetFinalizeOk returns a tuple with the Finalize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalize

`func (o *RecurringTemplateUpdate) SetFinalize(v bool)`

SetFinalize sets Finalize field to given value.

### HasFinalize

`func (o *RecurringTemplateUpdate) HasFinalize() bool`

HasFinalize returns a boolean if a field has been set.

### SetFinalizeNil

`func (o *RecurringTemplateUpdate) SetFinalizeNil(b bool)`

 SetFinalizeNil sets the value for Finalize to be an explicit nil

### UnsetFinalize
`func (o *RecurringTemplateUpdate) UnsetFinalize()`

UnsetFinalize ensures that no value is present for Finalize, not even an explicit nil
### GetLastExecutedAt

`func (o *RecurringTemplateUpdate) GetLastExecutedAt() time.Time`

GetLastExecutedAt returns the LastExecutedAt field if non-nil, zero value otherwise.

### GetLastExecutedAtOk

`func (o *RecurringTemplateUpdate) GetLastExecutedAtOk() (*time.Time, bool)`

GetLastExecutedAtOk returns a tuple with the LastExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExecutedAt

`func (o *RecurringTemplateUpdate) SetLastExecutedAt(v time.Time)`

SetLastExecutedAt sets LastExecutedAt field to given value.

### HasLastExecutedAt

`func (o *RecurringTemplateUpdate) HasLastExecutedAt() bool`

HasLastExecutedAt returns a boolean if a field has been set.

### SetLastExecutedAtNil

`func (o *RecurringTemplateUpdate) SetLastExecutedAtNil(b bool)`

 SetLastExecutedAtNil sets the value for LastExecutedAt to be an explicit nil

### UnsetLastExecutedAt
`func (o *RecurringTemplateUpdate) UnsetLastExecutedAt()`

UnsetLastExecutedAt ensures that no value is present for LastExecutedAt, not even an explicit nil
### GetName

`func (o *RecurringTemplateUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RecurringTemplateUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RecurringTemplateUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RecurringTemplateUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *RecurringTemplateUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *RecurringTemplateUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetNextExecutionAt

`func (o *RecurringTemplateUpdate) GetNextExecutionAt() time.Time`

GetNextExecutionAt returns the NextExecutionAt field if non-nil, zero value otherwise.

### GetNextExecutionAtOk

`func (o *RecurringTemplateUpdate) GetNextExecutionAtOk() (*time.Time, bool)`

GetNextExecutionAtOk returns a tuple with the NextExecutionAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextExecutionAt

`func (o *RecurringTemplateUpdate) SetNextExecutionAt(v time.Time)`

SetNextExecutionAt sets NextExecutionAt field to given value.

### HasNextExecutionAt

`func (o *RecurringTemplateUpdate) HasNextExecutionAt() bool`

HasNextExecutionAt returns a boolean if a field has been set.

### SetNextExecutionAtNil

`func (o *RecurringTemplateUpdate) SetNextExecutionAtNil(b bool)`

 SetNextExecutionAtNil sets the value for NextExecutionAt to be an explicit nil

### UnsetNextExecutionAt
`func (o *RecurringTemplateUpdate) UnsetNextExecutionAt()`

UnsetNextExecutionAt ensures that no value is present for NextExecutionAt, not even an explicit nil
### GetStartDate

`func (o *RecurringTemplateUpdate) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *RecurringTemplateUpdate) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *RecurringTemplateUpdate) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *RecurringTemplateUpdate) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *RecurringTemplateUpdate) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *RecurringTemplateUpdate) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetTemplateType

`func (o *RecurringTemplateUpdate) GetTemplateType() RecurringTemplateType`

GetTemplateType returns the TemplateType field if non-nil, zero value otherwise.

### GetTemplateTypeOk

`func (o *RecurringTemplateUpdate) GetTemplateTypeOk() (*RecurringTemplateType, bool)`

GetTemplateTypeOk returns a tuple with the TemplateType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateType

`func (o *RecurringTemplateUpdate) SetTemplateType(v RecurringTemplateType)`

SetTemplateType sets TemplateType field to given value.

### HasTemplateType

`func (o *RecurringTemplateUpdate) HasTemplateType() bool`

HasTemplateType returns a boolean if a field has been set.

### SetTemplateTypeNil

`func (o *RecurringTemplateUpdate) SetTemplateTypeNil(b bool)`

 SetTemplateTypeNil sets the value for TemplateType to be an explicit nil

### UnsetTemplateType
`func (o *RecurringTemplateUpdate) UnsetTemplateType()`

UnsetTemplateType ensures that no value is present for TemplateType, not even an explicit nil
### GetVoucherData

`func (o *RecurringTemplateUpdate) GetVoucherData() interface{}`

GetVoucherData returns the VoucherData field if non-nil, zero value otherwise.

### GetVoucherDataOk

`func (o *RecurringTemplateUpdate) GetVoucherDataOk() (*interface{}, bool)`

GetVoucherDataOk returns a tuple with the VoucherData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherData

`func (o *RecurringTemplateUpdate) SetVoucherData(v interface{})`

SetVoucherData sets VoucherData field to given value.

### HasVoucherData

`func (o *RecurringTemplateUpdate) HasVoucherData() bool`

HasVoucherData returns a boolean if a field has been set.

### SetVoucherDataNil

`func (o *RecurringTemplateUpdate) SetVoucherDataNil(b bool)`

 SetVoucherDataNil sets the value for VoucherData to be an explicit nil

### UnsetVoucherData
`func (o *RecurringTemplateUpdate) UnsetVoucherData()`

UnsetVoucherData ensures that no value is present for VoucherData, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


