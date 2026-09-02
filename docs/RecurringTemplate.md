# RecurringTemplate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **string** |  | [readonly] 
**DeletedAt** | Pointer to **NullableString** |  | [optional] [readonly] 
**EndDate** | Pointer to **NullableString** |  | [optional] 
**ExecutionInterval** | **string** |  | 
**ExecutionStatus** | **string** |  | 
**Finalize** | **bool** |  | 
**LastExecutedAt** | Pointer to **NullableTime** |  | [optional] 
**Name** | **string** |  | 
**NextExecutionAt** | Pointer to **NullableTime** |  | [optional] 
**StartDate** | **string** |  | 
**TemplateId** | **string** |  | 
**TemplateType** | **string** |  | 
**UpdatedAt** | Pointer to **NullableString** |  | [optional] [readonly] 
**VoucherData** | **interface{}** |  | 

## Methods

### NewRecurringTemplate

`func NewRecurringTemplate(createdAt string, executionInterval string, executionStatus string, finalize bool, name string, startDate string, templateId string, templateType string, voucherData interface{}, ) *RecurringTemplate`

NewRecurringTemplate instantiates a new RecurringTemplate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecurringTemplateWithDefaults

`func NewRecurringTemplateWithDefaults() *RecurringTemplate`

NewRecurringTemplateWithDefaults instantiates a new RecurringTemplate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *RecurringTemplate) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecurringTemplate) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecurringTemplate) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *RecurringTemplate) GetDeletedAt() string`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *RecurringTemplate) GetDeletedAtOk() (*string, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *RecurringTemplate) SetDeletedAt(v string)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *RecurringTemplate) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *RecurringTemplate) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *RecurringTemplate) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetEndDate

`func (o *RecurringTemplate) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *RecurringTemplate) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *RecurringTemplate) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *RecurringTemplate) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### SetEndDateNil

`func (o *RecurringTemplate) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *RecurringTemplate) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetExecutionInterval

`func (o *RecurringTemplate) GetExecutionInterval() string`

GetExecutionInterval returns the ExecutionInterval field if non-nil, zero value otherwise.

### GetExecutionIntervalOk

`func (o *RecurringTemplate) GetExecutionIntervalOk() (*string, bool)`

GetExecutionIntervalOk returns a tuple with the ExecutionInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionInterval

`func (o *RecurringTemplate) SetExecutionInterval(v string)`

SetExecutionInterval sets ExecutionInterval field to given value.


### GetExecutionStatus

`func (o *RecurringTemplate) GetExecutionStatus() string`

GetExecutionStatus returns the ExecutionStatus field if non-nil, zero value otherwise.

### GetExecutionStatusOk

`func (o *RecurringTemplate) GetExecutionStatusOk() (*string, bool)`

GetExecutionStatusOk returns a tuple with the ExecutionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionStatus

`func (o *RecurringTemplate) SetExecutionStatus(v string)`

SetExecutionStatus sets ExecutionStatus field to given value.


### GetFinalize

`func (o *RecurringTemplate) GetFinalize() bool`

GetFinalize returns the Finalize field if non-nil, zero value otherwise.

### GetFinalizeOk

`func (o *RecurringTemplate) GetFinalizeOk() (*bool, bool)`

GetFinalizeOk returns a tuple with the Finalize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalize

`func (o *RecurringTemplate) SetFinalize(v bool)`

SetFinalize sets Finalize field to given value.


### GetLastExecutedAt

`func (o *RecurringTemplate) GetLastExecutedAt() time.Time`

GetLastExecutedAt returns the LastExecutedAt field if non-nil, zero value otherwise.

### GetLastExecutedAtOk

`func (o *RecurringTemplate) GetLastExecutedAtOk() (*time.Time, bool)`

GetLastExecutedAtOk returns a tuple with the LastExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExecutedAt

`func (o *RecurringTemplate) SetLastExecutedAt(v time.Time)`

SetLastExecutedAt sets LastExecutedAt field to given value.

### HasLastExecutedAt

`func (o *RecurringTemplate) HasLastExecutedAt() bool`

HasLastExecutedAt returns a boolean if a field has been set.

### SetLastExecutedAtNil

`func (o *RecurringTemplate) SetLastExecutedAtNil(b bool)`

 SetLastExecutedAtNil sets the value for LastExecutedAt to be an explicit nil

### UnsetLastExecutedAt
`func (o *RecurringTemplate) UnsetLastExecutedAt()`

UnsetLastExecutedAt ensures that no value is present for LastExecutedAt, not even an explicit nil
### GetName

`func (o *RecurringTemplate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RecurringTemplate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RecurringTemplate) SetName(v string)`

SetName sets Name field to given value.


### GetNextExecutionAt

`func (o *RecurringTemplate) GetNextExecutionAt() time.Time`

GetNextExecutionAt returns the NextExecutionAt field if non-nil, zero value otherwise.

### GetNextExecutionAtOk

`func (o *RecurringTemplate) GetNextExecutionAtOk() (*time.Time, bool)`

GetNextExecutionAtOk returns a tuple with the NextExecutionAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextExecutionAt

`func (o *RecurringTemplate) SetNextExecutionAt(v time.Time)`

SetNextExecutionAt sets NextExecutionAt field to given value.

### HasNextExecutionAt

`func (o *RecurringTemplate) HasNextExecutionAt() bool`

HasNextExecutionAt returns a boolean if a field has been set.

### SetNextExecutionAtNil

`func (o *RecurringTemplate) SetNextExecutionAtNil(b bool)`

 SetNextExecutionAtNil sets the value for NextExecutionAt to be an explicit nil

### UnsetNextExecutionAt
`func (o *RecurringTemplate) UnsetNextExecutionAt()`

UnsetNextExecutionAt ensures that no value is present for NextExecutionAt, not even an explicit nil
### GetStartDate

`func (o *RecurringTemplate) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *RecurringTemplate) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *RecurringTemplate) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.


### GetTemplateId

`func (o *RecurringTemplate) GetTemplateId() string`

GetTemplateId returns the TemplateId field if non-nil, zero value otherwise.

### GetTemplateIdOk

`func (o *RecurringTemplate) GetTemplateIdOk() (*string, bool)`

GetTemplateIdOk returns a tuple with the TemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateId

`func (o *RecurringTemplate) SetTemplateId(v string)`

SetTemplateId sets TemplateId field to given value.


### GetTemplateType

`func (o *RecurringTemplate) GetTemplateType() string`

GetTemplateType returns the TemplateType field if non-nil, zero value otherwise.

### GetTemplateTypeOk

`func (o *RecurringTemplate) GetTemplateTypeOk() (*string, bool)`

GetTemplateTypeOk returns a tuple with the TemplateType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateType

`func (o *RecurringTemplate) SetTemplateType(v string)`

SetTemplateType sets TemplateType field to given value.


### GetUpdatedAt

`func (o *RecurringTemplate) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RecurringTemplate) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RecurringTemplate) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *RecurringTemplate) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *RecurringTemplate) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *RecurringTemplate) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetVoucherData

`func (o *RecurringTemplate) GetVoucherData() interface{}`

GetVoucherData returns the VoucherData field if non-nil, zero value otherwise.

### GetVoucherDataOk

`func (o *RecurringTemplate) GetVoucherDataOk() (*interface{}, bool)`

GetVoucherDataOk returns a tuple with the VoucherData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoucherData

`func (o *RecurringTemplate) SetVoucherData(v interface{})`

SetVoucherData sets VoucherData field to given value.


### SetVoucherDataNil

`func (o *RecurringTemplate) SetVoucherDataNil(b bool)`

 SetVoucherDataNil sets the value for VoucherData to be an explicit nil

### UnsetVoucherData
`func (o *RecurringTemplate) UnsetVoucherData()`

UnsetVoucherData ensures that no value is present for VoucherData, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


