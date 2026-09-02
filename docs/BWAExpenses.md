# BWAExpenses

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpenseBreakdown** | [**[]ExpenseItem**](ExpenseItem.md) |  | 
**TotalExpenses** | **string** |  | 

## Methods

### NewBWAExpenses

`func NewBWAExpenses(expenseBreakdown []ExpenseItem, totalExpenses string, ) *BWAExpenses`

NewBWAExpenses instantiates a new BWAExpenses object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBWAExpensesWithDefaults

`func NewBWAExpensesWithDefaults() *BWAExpenses`

NewBWAExpensesWithDefaults instantiates a new BWAExpenses object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpenseBreakdown

`func (o *BWAExpenses) GetExpenseBreakdown() []ExpenseItem`

GetExpenseBreakdown returns the ExpenseBreakdown field if non-nil, zero value otherwise.

### GetExpenseBreakdownOk

`func (o *BWAExpenses) GetExpenseBreakdownOk() (*[]ExpenseItem, bool)`

GetExpenseBreakdownOk returns a tuple with the ExpenseBreakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseBreakdown

`func (o *BWAExpenses) SetExpenseBreakdown(v []ExpenseItem)`

SetExpenseBreakdown sets ExpenseBreakdown field to given value.


### GetTotalExpenses

`func (o *BWAExpenses) GetTotalExpenses() string`

GetTotalExpenses returns the TotalExpenses field if non-nil, zero value otherwise.

### GetTotalExpensesOk

`func (o *BWAExpenses) GetTotalExpensesOk() (*string, bool)`

GetTotalExpensesOk returns a tuple with the TotalExpenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalExpenses

`func (o *BWAExpenses) SetTotalExpenses(v string)`

SetTotalExpenses sets TotalExpenses field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


