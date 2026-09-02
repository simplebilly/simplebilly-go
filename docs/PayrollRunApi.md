# PayrollRunApi

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApprovedAt** | Pointer to **NullableTime** |  | [optional] 
**ApprovedBy** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**Entries** | [**[]PayrollEntryApi**](PayrollEntryApi.md) |  | 
**Month** | **int32** |  | 
**PaymentDate** | Pointer to **NullableString** |  | [optional] 
**PeriodLabel** | **string** |  | 
**RunId** | **string** |  | 
**Status** | [**PayrollRunStatus**](PayrollRunStatus.md) |  | 
**TenantId** | **string** |  | 
**TotalEmployeeCount** | **int32** |  | 
**TotalEmployerCost** | **string** |  | 
**TotalGross** | **string** |  | 
**TotalNet** | **string** |  | 
**TotalSocialSecurity** | **string** |  | 
**TotalTaxes** | **string** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**Year** | **int32** |  | 

## Methods

### NewPayrollRunApi

`func NewPayrollRunApi(createdAt time.Time, entries []PayrollEntryApi, month int32, periodLabel string, runId string, status PayrollRunStatus, tenantId string, totalEmployeeCount int32, totalEmployerCost string, totalGross string, totalNet string, totalSocialSecurity string, totalTaxes string, year int32, ) *PayrollRunApi`

NewPayrollRunApi instantiates a new PayrollRunApi object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayrollRunApiWithDefaults

`func NewPayrollRunApiWithDefaults() *PayrollRunApi`

NewPayrollRunApiWithDefaults instantiates a new PayrollRunApi object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApprovedAt

`func (o *PayrollRunApi) GetApprovedAt() time.Time`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *PayrollRunApi) GetApprovedAtOk() (*time.Time, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *PayrollRunApi) SetApprovedAt(v time.Time)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *PayrollRunApi) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### SetApprovedAtNil

`func (o *PayrollRunApi) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *PayrollRunApi) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetApprovedBy

`func (o *PayrollRunApi) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *PayrollRunApi) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *PayrollRunApi) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *PayrollRunApi) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.

### SetApprovedByNil

`func (o *PayrollRunApi) SetApprovedByNil(b bool)`

 SetApprovedByNil sets the value for ApprovedBy to be an explicit nil

### UnsetApprovedBy
`func (o *PayrollRunApi) UnsetApprovedBy()`

UnsetApprovedBy ensures that no value is present for ApprovedBy, not even an explicit nil
### GetCreatedAt

`func (o *PayrollRunApi) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PayrollRunApi) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PayrollRunApi) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetEntries

`func (o *PayrollRunApi) GetEntries() []PayrollEntryApi`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *PayrollRunApi) GetEntriesOk() (*[]PayrollEntryApi, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *PayrollRunApi) SetEntries(v []PayrollEntryApi)`

SetEntries sets Entries field to given value.


### GetMonth

`func (o *PayrollRunApi) GetMonth() int32`

GetMonth returns the Month field if non-nil, zero value otherwise.

### GetMonthOk

`func (o *PayrollRunApi) GetMonthOk() (*int32, bool)`

GetMonthOk returns a tuple with the Month field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonth

`func (o *PayrollRunApi) SetMonth(v int32)`

SetMonth sets Month field to given value.


### GetPaymentDate

`func (o *PayrollRunApi) GetPaymentDate() string`

GetPaymentDate returns the PaymentDate field if non-nil, zero value otherwise.

### GetPaymentDateOk

`func (o *PayrollRunApi) GetPaymentDateOk() (*string, bool)`

GetPaymentDateOk returns a tuple with the PaymentDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDate

`func (o *PayrollRunApi) SetPaymentDate(v string)`

SetPaymentDate sets PaymentDate field to given value.

### HasPaymentDate

`func (o *PayrollRunApi) HasPaymentDate() bool`

HasPaymentDate returns a boolean if a field has been set.

### SetPaymentDateNil

`func (o *PayrollRunApi) SetPaymentDateNil(b bool)`

 SetPaymentDateNil sets the value for PaymentDate to be an explicit nil

### UnsetPaymentDate
`func (o *PayrollRunApi) UnsetPaymentDate()`

UnsetPaymentDate ensures that no value is present for PaymentDate, not even an explicit nil
### GetPeriodLabel

`func (o *PayrollRunApi) GetPeriodLabel() string`

GetPeriodLabel returns the PeriodLabel field if non-nil, zero value otherwise.

### GetPeriodLabelOk

`func (o *PayrollRunApi) GetPeriodLabelOk() (*string, bool)`

GetPeriodLabelOk returns a tuple with the PeriodLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodLabel

`func (o *PayrollRunApi) SetPeriodLabel(v string)`

SetPeriodLabel sets PeriodLabel field to given value.


### GetRunId

`func (o *PayrollRunApi) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *PayrollRunApi) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *PayrollRunApi) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetStatus

`func (o *PayrollRunApi) GetStatus() PayrollRunStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PayrollRunApi) GetStatusOk() (*PayrollRunStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PayrollRunApi) SetStatus(v PayrollRunStatus)`

SetStatus sets Status field to given value.


### GetTenantId

`func (o *PayrollRunApi) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *PayrollRunApi) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *PayrollRunApi) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetTotalEmployeeCount

`func (o *PayrollRunApi) GetTotalEmployeeCount() int32`

GetTotalEmployeeCount returns the TotalEmployeeCount field if non-nil, zero value otherwise.

### GetTotalEmployeeCountOk

`func (o *PayrollRunApi) GetTotalEmployeeCountOk() (*int32, bool)`

GetTotalEmployeeCountOk returns a tuple with the TotalEmployeeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEmployeeCount

`func (o *PayrollRunApi) SetTotalEmployeeCount(v int32)`

SetTotalEmployeeCount sets TotalEmployeeCount field to given value.


### GetTotalEmployerCost

`func (o *PayrollRunApi) GetTotalEmployerCost() string`

GetTotalEmployerCost returns the TotalEmployerCost field if non-nil, zero value otherwise.

### GetTotalEmployerCostOk

`func (o *PayrollRunApi) GetTotalEmployerCostOk() (*string, bool)`

GetTotalEmployerCostOk returns a tuple with the TotalEmployerCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEmployerCost

`func (o *PayrollRunApi) SetTotalEmployerCost(v string)`

SetTotalEmployerCost sets TotalEmployerCost field to given value.


### GetTotalGross

`func (o *PayrollRunApi) GetTotalGross() string`

GetTotalGross returns the TotalGross field if non-nil, zero value otherwise.

### GetTotalGrossOk

`func (o *PayrollRunApi) GetTotalGrossOk() (*string, bool)`

GetTotalGrossOk returns a tuple with the TotalGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGross

`func (o *PayrollRunApi) SetTotalGross(v string)`

SetTotalGross sets TotalGross field to given value.


### GetTotalNet

`func (o *PayrollRunApi) GetTotalNet() string`

GetTotalNet returns the TotalNet field if non-nil, zero value otherwise.

### GetTotalNetOk

`func (o *PayrollRunApi) GetTotalNetOk() (*string, bool)`

GetTotalNetOk returns a tuple with the TotalNet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNet

`func (o *PayrollRunApi) SetTotalNet(v string)`

SetTotalNet sets TotalNet field to given value.


### GetTotalSocialSecurity

`func (o *PayrollRunApi) GetTotalSocialSecurity() string`

GetTotalSocialSecurity returns the TotalSocialSecurity field if non-nil, zero value otherwise.

### GetTotalSocialSecurityOk

`func (o *PayrollRunApi) GetTotalSocialSecurityOk() (*string, bool)`

GetTotalSocialSecurityOk returns a tuple with the TotalSocialSecurity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSocialSecurity

`func (o *PayrollRunApi) SetTotalSocialSecurity(v string)`

SetTotalSocialSecurity sets TotalSocialSecurity field to given value.


### GetTotalTaxes

`func (o *PayrollRunApi) GetTotalTaxes() string`

GetTotalTaxes returns the TotalTaxes field if non-nil, zero value otherwise.

### GetTotalTaxesOk

`func (o *PayrollRunApi) GetTotalTaxesOk() (*string, bool)`

GetTotalTaxesOk returns a tuple with the TotalTaxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTaxes

`func (o *PayrollRunApi) SetTotalTaxes(v string)`

SetTotalTaxes sets TotalTaxes field to given value.


### GetUpdatedAt

`func (o *PayrollRunApi) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PayrollRunApi) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PayrollRunApi) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PayrollRunApi) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *PayrollRunApi) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *PayrollRunApi) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetYear

`func (o *PayrollRunApi) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *PayrollRunApi) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *PayrollRunApi) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


