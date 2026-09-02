# BudgetGoalRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MonthlyGoal** | **string** | Monthly goal amount (gross). 0 means \&quot;no goal\&quot; (fallback to default). | 
**Year** | **int32** | Budget year the goal applies to. | 

## Methods

### NewBudgetGoalRequest

`func NewBudgetGoalRequest(monthlyGoal string, year int32, ) *BudgetGoalRequest`

NewBudgetGoalRequest instantiates a new BudgetGoalRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBudgetGoalRequestWithDefaults

`func NewBudgetGoalRequestWithDefaults() *BudgetGoalRequest`

NewBudgetGoalRequestWithDefaults instantiates a new BudgetGoalRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMonthlyGoal

`func (o *BudgetGoalRequest) GetMonthlyGoal() string`

GetMonthlyGoal returns the MonthlyGoal field if non-nil, zero value otherwise.

### GetMonthlyGoalOk

`func (o *BudgetGoalRequest) GetMonthlyGoalOk() (*string, bool)`

GetMonthlyGoalOk returns a tuple with the MonthlyGoal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyGoal

`func (o *BudgetGoalRequest) SetMonthlyGoal(v string)`

SetMonthlyGoal sets MonthlyGoal field to given value.


### GetYear

`func (o *BudgetGoalRequest) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *BudgetGoalRequest) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *BudgetGoalRequest) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


