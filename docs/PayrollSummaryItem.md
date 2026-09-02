# PayrollSummaryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmployeeCount** | **int32** |  | 
**Month** | **string** |  | 
**Status** | [**PayrollRunStatus**](PayrollRunStatus.md) |  | 
**TotalEmployerCost** | **string** |  | 
**TotalGross** | **string** |  | 
**TotalNet** | **string** |  | 
**Year** | **int32** |  | 

## Methods

### NewPayrollSummaryItem

`func NewPayrollSummaryItem(employeeCount int32, month string, status PayrollRunStatus, totalEmployerCost string, totalGross string, totalNet string, year int32, ) *PayrollSummaryItem`

NewPayrollSummaryItem instantiates a new PayrollSummaryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayrollSummaryItemWithDefaults

`func NewPayrollSummaryItemWithDefaults() *PayrollSummaryItem`

NewPayrollSummaryItemWithDefaults instantiates a new PayrollSummaryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployeeCount

`func (o *PayrollSummaryItem) GetEmployeeCount() int32`

GetEmployeeCount returns the EmployeeCount field if non-nil, zero value otherwise.

### GetEmployeeCountOk

`func (o *PayrollSummaryItem) GetEmployeeCountOk() (*int32, bool)`

GetEmployeeCountOk returns a tuple with the EmployeeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeCount

`func (o *PayrollSummaryItem) SetEmployeeCount(v int32)`

SetEmployeeCount sets EmployeeCount field to given value.


### GetMonth

`func (o *PayrollSummaryItem) GetMonth() string`

GetMonth returns the Month field if non-nil, zero value otherwise.

### GetMonthOk

`func (o *PayrollSummaryItem) GetMonthOk() (*string, bool)`

GetMonthOk returns a tuple with the Month field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonth

`func (o *PayrollSummaryItem) SetMonth(v string)`

SetMonth sets Month field to given value.


### GetStatus

`func (o *PayrollSummaryItem) GetStatus() PayrollRunStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PayrollSummaryItem) GetStatusOk() (*PayrollRunStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PayrollSummaryItem) SetStatus(v PayrollRunStatus)`

SetStatus sets Status field to given value.


### GetTotalEmployerCost

`func (o *PayrollSummaryItem) GetTotalEmployerCost() string`

GetTotalEmployerCost returns the TotalEmployerCost field if non-nil, zero value otherwise.

### GetTotalEmployerCostOk

`func (o *PayrollSummaryItem) GetTotalEmployerCostOk() (*string, bool)`

GetTotalEmployerCostOk returns a tuple with the TotalEmployerCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEmployerCost

`func (o *PayrollSummaryItem) SetTotalEmployerCost(v string)`

SetTotalEmployerCost sets TotalEmployerCost field to given value.


### GetTotalGross

`func (o *PayrollSummaryItem) GetTotalGross() string`

GetTotalGross returns the TotalGross field if non-nil, zero value otherwise.

### GetTotalGrossOk

`func (o *PayrollSummaryItem) GetTotalGrossOk() (*string, bool)`

GetTotalGrossOk returns a tuple with the TotalGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGross

`func (o *PayrollSummaryItem) SetTotalGross(v string)`

SetTotalGross sets TotalGross field to given value.


### GetTotalNet

`func (o *PayrollSummaryItem) GetTotalNet() string`

GetTotalNet returns the TotalNet field if non-nil, zero value otherwise.

### GetTotalNetOk

`func (o *PayrollSummaryItem) GetTotalNetOk() (*string, bool)`

GetTotalNetOk returns a tuple with the TotalNet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNet

`func (o *PayrollSummaryItem) SetTotalNet(v string)`

SetTotalNet sets TotalNet field to given value.


### GetYear

`func (o *PayrollSummaryItem) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *PayrollSummaryItem) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *PayrollSummaryItem) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


