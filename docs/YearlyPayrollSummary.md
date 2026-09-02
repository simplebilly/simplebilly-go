# YearlyPayrollSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvgEmployeeCount** | **int32** |  | 
**Months** | [**[]PayrollSummaryItem**](PayrollSummaryItem.md) |  | 
**Year** | **int32** |  | 
**YearlyEmployerCost** | **string** |  | 
**YearlyGross** | **string** |  | 
**YearlyNet** | **string** |  | 

## Methods

### NewYearlyPayrollSummary

`func NewYearlyPayrollSummary(avgEmployeeCount int32, months []PayrollSummaryItem, year int32, yearlyEmployerCost string, yearlyGross string, yearlyNet string, ) *YearlyPayrollSummary`

NewYearlyPayrollSummary instantiates a new YearlyPayrollSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewYearlyPayrollSummaryWithDefaults

`func NewYearlyPayrollSummaryWithDefaults() *YearlyPayrollSummary`

NewYearlyPayrollSummaryWithDefaults instantiates a new YearlyPayrollSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvgEmployeeCount

`func (o *YearlyPayrollSummary) GetAvgEmployeeCount() int32`

GetAvgEmployeeCount returns the AvgEmployeeCount field if non-nil, zero value otherwise.

### GetAvgEmployeeCountOk

`func (o *YearlyPayrollSummary) GetAvgEmployeeCountOk() (*int32, bool)`

GetAvgEmployeeCountOk returns a tuple with the AvgEmployeeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEmployeeCount

`func (o *YearlyPayrollSummary) SetAvgEmployeeCount(v int32)`

SetAvgEmployeeCount sets AvgEmployeeCount field to given value.


### GetMonths

`func (o *YearlyPayrollSummary) GetMonths() []PayrollSummaryItem`

GetMonths returns the Months field if non-nil, zero value otherwise.

### GetMonthsOk

`func (o *YearlyPayrollSummary) GetMonthsOk() (*[]PayrollSummaryItem, bool)`

GetMonthsOk returns a tuple with the Months field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonths

`func (o *YearlyPayrollSummary) SetMonths(v []PayrollSummaryItem)`

SetMonths sets Months field to given value.


### GetYear

`func (o *YearlyPayrollSummary) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *YearlyPayrollSummary) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *YearlyPayrollSummary) SetYear(v int32)`

SetYear sets Year field to given value.


### GetYearlyEmployerCost

`func (o *YearlyPayrollSummary) GetYearlyEmployerCost() string`

GetYearlyEmployerCost returns the YearlyEmployerCost field if non-nil, zero value otherwise.

### GetYearlyEmployerCostOk

`func (o *YearlyPayrollSummary) GetYearlyEmployerCostOk() (*string, bool)`

GetYearlyEmployerCostOk returns a tuple with the YearlyEmployerCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearlyEmployerCost

`func (o *YearlyPayrollSummary) SetYearlyEmployerCost(v string)`

SetYearlyEmployerCost sets YearlyEmployerCost field to given value.


### GetYearlyGross

`func (o *YearlyPayrollSummary) GetYearlyGross() string`

GetYearlyGross returns the YearlyGross field if non-nil, zero value otherwise.

### GetYearlyGrossOk

`func (o *YearlyPayrollSummary) GetYearlyGrossOk() (*string, bool)`

GetYearlyGrossOk returns a tuple with the YearlyGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearlyGross

`func (o *YearlyPayrollSummary) SetYearlyGross(v string)`

SetYearlyGross sets YearlyGross field to given value.


### GetYearlyNet

`func (o *YearlyPayrollSummary) GetYearlyNet() string`

GetYearlyNet returns the YearlyNet field if non-nil, zero value otherwise.

### GetYearlyNetOk

`func (o *YearlyPayrollSummary) GetYearlyNetOk() (*string, bool)`

GetYearlyNetOk returns a tuple with the YearlyNet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearlyNet

`func (o *YearlyPayrollSummary) SetYearlyNet(v string)`

SetYearlyNet sets YearlyNet field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


