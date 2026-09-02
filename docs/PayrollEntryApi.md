# PayrollEntryApi

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvEmployee** | **string** |  | 
**AvEmployer** | **string** |  | 
**ChurchTaxAmount** | **string** |  | 
**Employee** | Pointer to [**NullableEmployee**](Employee.md) |  | [optional] 
**EmployeeId** | **string** |  | 
**EntryId** | **string** |  | 
**ExtraPaymentReason** | Pointer to **NullableString** |  | [optional] 
**ExtraPayments** | **string** |  | 
**GrossSalary** | **string** |  | 
**KvEmployee** | **string** |  | 
**KvEmployer** | **string** |  | 
**Lohnsteuer** | **string** |  | 
**NetSalary** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**PvEmployee** | **string** |  | 
**PvEmployer** | **string** |  | 
**RunId** | **string** |  | 
**RvEmployee** | **string** |  | 
**RvEmployer** | **string** |  | 
**SickDays** | **int32** |  | 
**Soli** | **string** |  | 
**Status** | [**PayrollRunStatus**](PayrollRunStatus.md) |  | 
**TotalDeductions** | **string** |  | 
**TotalEmployerCost** | **string** |  | 
**VacationDaysUsed** | **int32** |  | 

## Methods

### NewPayrollEntryApi

`func NewPayrollEntryApi(avEmployee string, avEmployer string, churchTaxAmount string, employeeId string, entryId string, extraPayments string, grossSalary string, kvEmployee string, kvEmployer string, lohnsteuer string, netSalary string, pvEmployee string, pvEmployer string, runId string, rvEmployee string, rvEmployer string, sickDays int32, soli string, status PayrollRunStatus, totalDeductions string, totalEmployerCost string, vacationDaysUsed int32, ) *PayrollEntryApi`

NewPayrollEntryApi instantiates a new PayrollEntryApi object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayrollEntryApiWithDefaults

`func NewPayrollEntryApiWithDefaults() *PayrollEntryApi`

NewPayrollEntryApiWithDefaults instantiates a new PayrollEntryApi object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvEmployee

`func (o *PayrollEntryApi) GetAvEmployee() string`

GetAvEmployee returns the AvEmployee field if non-nil, zero value otherwise.

### GetAvEmployeeOk

`func (o *PayrollEntryApi) GetAvEmployeeOk() (*string, bool)`

GetAvEmployeeOk returns a tuple with the AvEmployee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvEmployee

`func (o *PayrollEntryApi) SetAvEmployee(v string)`

SetAvEmployee sets AvEmployee field to given value.


### GetAvEmployer

`func (o *PayrollEntryApi) GetAvEmployer() string`

GetAvEmployer returns the AvEmployer field if non-nil, zero value otherwise.

### GetAvEmployerOk

`func (o *PayrollEntryApi) GetAvEmployerOk() (*string, bool)`

GetAvEmployerOk returns a tuple with the AvEmployer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvEmployer

`func (o *PayrollEntryApi) SetAvEmployer(v string)`

SetAvEmployer sets AvEmployer field to given value.


### GetChurchTaxAmount

`func (o *PayrollEntryApi) GetChurchTaxAmount() string`

GetChurchTaxAmount returns the ChurchTaxAmount field if non-nil, zero value otherwise.

### GetChurchTaxAmountOk

`func (o *PayrollEntryApi) GetChurchTaxAmountOk() (*string, bool)`

GetChurchTaxAmountOk returns a tuple with the ChurchTaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChurchTaxAmount

`func (o *PayrollEntryApi) SetChurchTaxAmount(v string)`

SetChurchTaxAmount sets ChurchTaxAmount field to given value.


### GetEmployee

`func (o *PayrollEntryApi) GetEmployee() Employee`

GetEmployee returns the Employee field if non-nil, zero value otherwise.

### GetEmployeeOk

`func (o *PayrollEntryApi) GetEmployeeOk() (*Employee, bool)`

GetEmployeeOk returns a tuple with the Employee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployee

`func (o *PayrollEntryApi) SetEmployee(v Employee)`

SetEmployee sets Employee field to given value.

### HasEmployee

`func (o *PayrollEntryApi) HasEmployee() bool`

HasEmployee returns a boolean if a field has been set.

### SetEmployeeNil

`func (o *PayrollEntryApi) SetEmployeeNil(b bool)`

 SetEmployeeNil sets the value for Employee to be an explicit nil

### UnsetEmployee
`func (o *PayrollEntryApi) UnsetEmployee()`

UnsetEmployee ensures that no value is present for Employee, not even an explicit nil
### GetEmployeeId

`func (o *PayrollEntryApi) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *PayrollEntryApi) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *PayrollEntryApi) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.


### GetEntryId

`func (o *PayrollEntryApi) GetEntryId() string`

GetEntryId returns the EntryId field if non-nil, zero value otherwise.

### GetEntryIdOk

`func (o *PayrollEntryApi) GetEntryIdOk() (*string, bool)`

GetEntryIdOk returns a tuple with the EntryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryId

`func (o *PayrollEntryApi) SetEntryId(v string)`

SetEntryId sets EntryId field to given value.


### GetExtraPaymentReason

`func (o *PayrollEntryApi) GetExtraPaymentReason() string`

GetExtraPaymentReason returns the ExtraPaymentReason field if non-nil, zero value otherwise.

### GetExtraPaymentReasonOk

`func (o *PayrollEntryApi) GetExtraPaymentReasonOk() (*string, bool)`

GetExtraPaymentReasonOk returns a tuple with the ExtraPaymentReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraPaymentReason

`func (o *PayrollEntryApi) SetExtraPaymentReason(v string)`

SetExtraPaymentReason sets ExtraPaymentReason field to given value.

### HasExtraPaymentReason

`func (o *PayrollEntryApi) HasExtraPaymentReason() bool`

HasExtraPaymentReason returns a boolean if a field has been set.

### SetExtraPaymentReasonNil

`func (o *PayrollEntryApi) SetExtraPaymentReasonNil(b bool)`

 SetExtraPaymentReasonNil sets the value for ExtraPaymentReason to be an explicit nil

### UnsetExtraPaymentReason
`func (o *PayrollEntryApi) UnsetExtraPaymentReason()`

UnsetExtraPaymentReason ensures that no value is present for ExtraPaymentReason, not even an explicit nil
### GetExtraPayments

`func (o *PayrollEntryApi) GetExtraPayments() string`

GetExtraPayments returns the ExtraPayments field if non-nil, zero value otherwise.

### GetExtraPaymentsOk

`func (o *PayrollEntryApi) GetExtraPaymentsOk() (*string, bool)`

GetExtraPaymentsOk returns a tuple with the ExtraPayments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraPayments

`func (o *PayrollEntryApi) SetExtraPayments(v string)`

SetExtraPayments sets ExtraPayments field to given value.


### GetGrossSalary

`func (o *PayrollEntryApi) GetGrossSalary() string`

GetGrossSalary returns the GrossSalary field if non-nil, zero value otherwise.

### GetGrossSalaryOk

`func (o *PayrollEntryApi) GetGrossSalaryOk() (*string, bool)`

GetGrossSalaryOk returns a tuple with the GrossSalary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrossSalary

`func (o *PayrollEntryApi) SetGrossSalary(v string)`

SetGrossSalary sets GrossSalary field to given value.


### GetKvEmployee

`func (o *PayrollEntryApi) GetKvEmployee() string`

GetKvEmployee returns the KvEmployee field if non-nil, zero value otherwise.

### GetKvEmployeeOk

`func (o *PayrollEntryApi) GetKvEmployeeOk() (*string, bool)`

GetKvEmployeeOk returns a tuple with the KvEmployee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKvEmployee

`func (o *PayrollEntryApi) SetKvEmployee(v string)`

SetKvEmployee sets KvEmployee field to given value.


### GetKvEmployer

`func (o *PayrollEntryApi) GetKvEmployer() string`

GetKvEmployer returns the KvEmployer field if non-nil, zero value otherwise.

### GetKvEmployerOk

`func (o *PayrollEntryApi) GetKvEmployerOk() (*string, bool)`

GetKvEmployerOk returns a tuple with the KvEmployer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKvEmployer

`func (o *PayrollEntryApi) SetKvEmployer(v string)`

SetKvEmployer sets KvEmployer field to given value.


### GetLohnsteuer

`func (o *PayrollEntryApi) GetLohnsteuer() string`

GetLohnsteuer returns the Lohnsteuer field if non-nil, zero value otherwise.

### GetLohnsteuerOk

`func (o *PayrollEntryApi) GetLohnsteuerOk() (*string, bool)`

GetLohnsteuerOk returns a tuple with the Lohnsteuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLohnsteuer

`func (o *PayrollEntryApi) SetLohnsteuer(v string)`

SetLohnsteuer sets Lohnsteuer field to given value.


### GetNetSalary

`func (o *PayrollEntryApi) GetNetSalary() string`

GetNetSalary returns the NetSalary field if non-nil, zero value otherwise.

### GetNetSalaryOk

`func (o *PayrollEntryApi) GetNetSalaryOk() (*string, bool)`

GetNetSalaryOk returns a tuple with the NetSalary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetSalary

`func (o *PayrollEntryApi) SetNetSalary(v string)`

SetNetSalary sets NetSalary field to given value.


### GetNotes

`func (o *PayrollEntryApi) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *PayrollEntryApi) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *PayrollEntryApi) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *PayrollEntryApi) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *PayrollEntryApi) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *PayrollEntryApi) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPvEmployee

`func (o *PayrollEntryApi) GetPvEmployee() string`

GetPvEmployee returns the PvEmployee field if non-nil, zero value otherwise.

### GetPvEmployeeOk

`func (o *PayrollEntryApi) GetPvEmployeeOk() (*string, bool)`

GetPvEmployeeOk returns a tuple with the PvEmployee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPvEmployee

`func (o *PayrollEntryApi) SetPvEmployee(v string)`

SetPvEmployee sets PvEmployee field to given value.


### GetPvEmployer

`func (o *PayrollEntryApi) GetPvEmployer() string`

GetPvEmployer returns the PvEmployer field if non-nil, zero value otherwise.

### GetPvEmployerOk

`func (o *PayrollEntryApi) GetPvEmployerOk() (*string, bool)`

GetPvEmployerOk returns a tuple with the PvEmployer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPvEmployer

`func (o *PayrollEntryApi) SetPvEmployer(v string)`

SetPvEmployer sets PvEmployer field to given value.


### GetRunId

`func (o *PayrollEntryApi) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *PayrollEntryApi) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *PayrollEntryApi) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetRvEmployee

`func (o *PayrollEntryApi) GetRvEmployee() string`

GetRvEmployee returns the RvEmployee field if non-nil, zero value otherwise.

### GetRvEmployeeOk

`func (o *PayrollEntryApi) GetRvEmployeeOk() (*string, bool)`

GetRvEmployeeOk returns a tuple with the RvEmployee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRvEmployee

`func (o *PayrollEntryApi) SetRvEmployee(v string)`

SetRvEmployee sets RvEmployee field to given value.


### GetRvEmployer

`func (o *PayrollEntryApi) GetRvEmployer() string`

GetRvEmployer returns the RvEmployer field if non-nil, zero value otherwise.

### GetRvEmployerOk

`func (o *PayrollEntryApi) GetRvEmployerOk() (*string, bool)`

GetRvEmployerOk returns a tuple with the RvEmployer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRvEmployer

`func (o *PayrollEntryApi) SetRvEmployer(v string)`

SetRvEmployer sets RvEmployer field to given value.


### GetSickDays

`func (o *PayrollEntryApi) GetSickDays() int32`

GetSickDays returns the SickDays field if non-nil, zero value otherwise.

### GetSickDaysOk

`func (o *PayrollEntryApi) GetSickDaysOk() (*int32, bool)`

GetSickDaysOk returns a tuple with the SickDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSickDays

`func (o *PayrollEntryApi) SetSickDays(v int32)`

SetSickDays sets SickDays field to given value.


### GetSoli

`func (o *PayrollEntryApi) GetSoli() string`

GetSoli returns the Soli field if non-nil, zero value otherwise.

### GetSoliOk

`func (o *PayrollEntryApi) GetSoliOk() (*string, bool)`

GetSoliOk returns a tuple with the Soli field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoli

`func (o *PayrollEntryApi) SetSoli(v string)`

SetSoli sets Soli field to given value.


### GetStatus

`func (o *PayrollEntryApi) GetStatus() PayrollRunStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PayrollEntryApi) GetStatusOk() (*PayrollRunStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PayrollEntryApi) SetStatus(v PayrollRunStatus)`

SetStatus sets Status field to given value.


### GetTotalDeductions

`func (o *PayrollEntryApi) GetTotalDeductions() string`

GetTotalDeductions returns the TotalDeductions field if non-nil, zero value otherwise.

### GetTotalDeductionsOk

`func (o *PayrollEntryApi) GetTotalDeductionsOk() (*string, bool)`

GetTotalDeductionsOk returns a tuple with the TotalDeductions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalDeductions

`func (o *PayrollEntryApi) SetTotalDeductions(v string)`

SetTotalDeductions sets TotalDeductions field to given value.


### GetTotalEmployerCost

`func (o *PayrollEntryApi) GetTotalEmployerCost() string`

GetTotalEmployerCost returns the TotalEmployerCost field if non-nil, zero value otherwise.

### GetTotalEmployerCostOk

`func (o *PayrollEntryApi) GetTotalEmployerCostOk() (*string, bool)`

GetTotalEmployerCostOk returns a tuple with the TotalEmployerCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEmployerCost

`func (o *PayrollEntryApi) SetTotalEmployerCost(v string)`

SetTotalEmployerCost sets TotalEmployerCost field to given value.


### GetVacationDaysUsed

`func (o *PayrollEntryApi) GetVacationDaysUsed() int32`

GetVacationDaysUsed returns the VacationDaysUsed field if non-nil, zero value otherwise.

### GetVacationDaysUsedOk

`func (o *PayrollEntryApi) GetVacationDaysUsedOk() (*int32, bool)`

GetVacationDaysUsedOk returns a tuple with the VacationDaysUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVacationDaysUsed

`func (o *PayrollEntryApi) SetVacationDaysUsed(v int32)`

SetVacationDaysUsed sets VacationDaysUsed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


