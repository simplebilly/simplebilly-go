# PayrollSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | **string** |  | 
**HourlyGross** | Pointer to **NullableString** |  | [optional] 
**Id** | **string** |  | 
**JobTitle** | **string** |  | 
**LastName** | **string** |  | 
**MonthlySalary** | Pointer to **NullableString** |  | [optional] 
**Months** | [**[]PayrollMonth**](PayrollMonth.md) |  | 
**WeeklyHours** | Pointer to **NullableString** |  | [optional] 
**Year** | **int32** |  | 

## Methods

### NewPayrollSummary

`func NewPayrollSummary(firstName string, id string, jobTitle string, lastName string, months []PayrollMonth, year int32, ) *PayrollSummary`

NewPayrollSummary instantiates a new PayrollSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayrollSummaryWithDefaults

`func NewPayrollSummaryWithDefaults() *PayrollSummary`

NewPayrollSummaryWithDefaults instantiates a new PayrollSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *PayrollSummary) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *PayrollSummary) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *PayrollSummary) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetHourlyGross

`func (o *PayrollSummary) GetHourlyGross() string`

GetHourlyGross returns the HourlyGross field if non-nil, zero value otherwise.

### GetHourlyGrossOk

`func (o *PayrollSummary) GetHourlyGrossOk() (*string, bool)`

GetHourlyGrossOk returns a tuple with the HourlyGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourlyGross

`func (o *PayrollSummary) SetHourlyGross(v string)`

SetHourlyGross sets HourlyGross field to given value.

### HasHourlyGross

`func (o *PayrollSummary) HasHourlyGross() bool`

HasHourlyGross returns a boolean if a field has been set.

### SetHourlyGrossNil

`func (o *PayrollSummary) SetHourlyGrossNil(b bool)`

 SetHourlyGrossNil sets the value for HourlyGross to be an explicit nil

### UnsetHourlyGross
`func (o *PayrollSummary) UnsetHourlyGross()`

UnsetHourlyGross ensures that no value is present for HourlyGross, not even an explicit nil
### GetId

`func (o *PayrollSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PayrollSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PayrollSummary) SetId(v string)`

SetId sets Id field to given value.


### GetJobTitle

`func (o *PayrollSummary) GetJobTitle() string`

GetJobTitle returns the JobTitle field if non-nil, zero value otherwise.

### GetJobTitleOk

`func (o *PayrollSummary) GetJobTitleOk() (*string, bool)`

GetJobTitleOk returns a tuple with the JobTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTitle

`func (o *PayrollSummary) SetJobTitle(v string)`

SetJobTitle sets JobTitle field to given value.


### GetLastName

`func (o *PayrollSummary) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *PayrollSummary) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *PayrollSummary) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetMonthlySalary

`func (o *PayrollSummary) GetMonthlySalary() string`

GetMonthlySalary returns the MonthlySalary field if non-nil, zero value otherwise.

### GetMonthlySalaryOk

`func (o *PayrollSummary) GetMonthlySalaryOk() (*string, bool)`

GetMonthlySalaryOk returns a tuple with the MonthlySalary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlySalary

`func (o *PayrollSummary) SetMonthlySalary(v string)`

SetMonthlySalary sets MonthlySalary field to given value.

### HasMonthlySalary

`func (o *PayrollSummary) HasMonthlySalary() bool`

HasMonthlySalary returns a boolean if a field has been set.

### SetMonthlySalaryNil

`func (o *PayrollSummary) SetMonthlySalaryNil(b bool)`

 SetMonthlySalaryNil sets the value for MonthlySalary to be an explicit nil

### UnsetMonthlySalary
`func (o *PayrollSummary) UnsetMonthlySalary()`

UnsetMonthlySalary ensures that no value is present for MonthlySalary, not even an explicit nil
### GetMonths

`func (o *PayrollSummary) GetMonths() []PayrollMonth`

GetMonths returns the Months field if non-nil, zero value otherwise.

### GetMonthsOk

`func (o *PayrollSummary) GetMonthsOk() (*[]PayrollMonth, bool)`

GetMonthsOk returns a tuple with the Months field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonths

`func (o *PayrollSummary) SetMonths(v []PayrollMonth)`

SetMonths sets Months field to given value.


### GetWeeklyHours

`func (o *PayrollSummary) GetWeeklyHours() string`

GetWeeklyHours returns the WeeklyHours field if non-nil, zero value otherwise.

### GetWeeklyHoursOk

`func (o *PayrollSummary) GetWeeklyHoursOk() (*string, bool)`

GetWeeklyHoursOk returns a tuple with the WeeklyHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyHours

`func (o *PayrollSummary) SetWeeklyHours(v string)`

SetWeeklyHours sets WeeklyHours field to given value.

### HasWeeklyHours

`func (o *PayrollSummary) HasWeeklyHours() bool`

HasWeeklyHours returns a boolean if a field has been set.

### SetWeeklyHoursNil

`func (o *PayrollSummary) SetWeeklyHoursNil(b bool)`

 SetWeeklyHoursNil sets the value for WeeklyHours to be an explicit nil

### UnsetWeeklyHours
`func (o *PayrollSummary) UnsetWeeklyHours()`

UnsetWeeklyHours ensures that no value is present for WeeklyHours, not even an explicit nil
### GetYear

`func (o *PayrollSummary) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *PayrollSummary) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *PayrollSummary) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


