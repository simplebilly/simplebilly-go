# Budget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Category** | **string** | Posting category key (matches &#x60;category&#x60; on journal entries). | 
**MonthlyGoal** | **string** | Monthly goal amount (gross). 0 means \&quot;no goal set\&quot;. | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**Year** | **int32** | Budget year the goal applies to. | 

## Methods

### NewBudget

`func NewBudget(category string, monthlyGoal string, year int32, ) *Budget`

NewBudget instantiates a new Budget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBudgetWithDefaults

`func NewBudgetWithDefaults() *Budget`

NewBudgetWithDefaults instantiates a new Budget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategory

`func (o *Budget) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Budget) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Budget) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetMonthlyGoal

`func (o *Budget) GetMonthlyGoal() string`

GetMonthlyGoal returns the MonthlyGoal field if non-nil, zero value otherwise.

### GetMonthlyGoalOk

`func (o *Budget) GetMonthlyGoalOk() (*string, bool)`

GetMonthlyGoalOk returns a tuple with the MonthlyGoal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyGoal

`func (o *Budget) SetMonthlyGoal(v string)`

SetMonthlyGoal sets MonthlyGoal field to given value.


### GetUpdatedAt

`func (o *Budget) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Budget) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Budget) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Budget) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Budget) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Budget) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetYear

`func (o *Budget) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *Budget) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *Budget) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


