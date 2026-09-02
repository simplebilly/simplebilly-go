# IncomeStatement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpenseItems** | [**[]PnLItem**](PnLItem.md) |  | 
**NetIncome** | **string** |  | 
**RevenueItems** | [**[]PnLItem**](PnLItem.md) |  | 
**TotalExpenses** | **string** |  | 
**TotalRevenue** | **string** |  | 

## Methods

### NewIncomeStatement

`func NewIncomeStatement(expenseItems []PnLItem, netIncome string, revenueItems []PnLItem, totalExpenses string, totalRevenue string, ) *IncomeStatement`

NewIncomeStatement instantiates a new IncomeStatement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIncomeStatementWithDefaults

`func NewIncomeStatementWithDefaults() *IncomeStatement`

NewIncomeStatementWithDefaults instantiates a new IncomeStatement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpenseItems

`func (o *IncomeStatement) GetExpenseItems() []PnLItem`

GetExpenseItems returns the ExpenseItems field if non-nil, zero value otherwise.

### GetExpenseItemsOk

`func (o *IncomeStatement) GetExpenseItemsOk() (*[]PnLItem, bool)`

GetExpenseItemsOk returns a tuple with the ExpenseItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenseItems

`func (o *IncomeStatement) SetExpenseItems(v []PnLItem)`

SetExpenseItems sets ExpenseItems field to given value.


### GetNetIncome

`func (o *IncomeStatement) GetNetIncome() string`

GetNetIncome returns the NetIncome field if non-nil, zero value otherwise.

### GetNetIncomeOk

`func (o *IncomeStatement) GetNetIncomeOk() (*string, bool)`

GetNetIncomeOk returns a tuple with the NetIncome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetIncome

`func (o *IncomeStatement) SetNetIncome(v string)`

SetNetIncome sets NetIncome field to given value.


### GetRevenueItems

`func (o *IncomeStatement) GetRevenueItems() []PnLItem`

GetRevenueItems returns the RevenueItems field if non-nil, zero value otherwise.

### GetRevenueItemsOk

`func (o *IncomeStatement) GetRevenueItemsOk() (*[]PnLItem, bool)`

GetRevenueItemsOk returns a tuple with the RevenueItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenueItems

`func (o *IncomeStatement) SetRevenueItems(v []PnLItem)`

SetRevenueItems sets RevenueItems field to given value.


### GetTotalExpenses

`func (o *IncomeStatement) GetTotalExpenses() string`

GetTotalExpenses returns the TotalExpenses field if non-nil, zero value otherwise.

### GetTotalExpensesOk

`func (o *IncomeStatement) GetTotalExpensesOk() (*string, bool)`

GetTotalExpensesOk returns a tuple with the TotalExpenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalExpenses

`func (o *IncomeStatement) SetTotalExpenses(v string)`

SetTotalExpenses sets TotalExpenses field to given value.


### GetTotalRevenue

`func (o *IncomeStatement) GetTotalRevenue() string`

GetTotalRevenue returns the TotalRevenue field if non-nil, zero value otherwise.

### GetTotalRevenueOk

`func (o *IncomeStatement) GetTotalRevenueOk() (*string, bool)`

GetTotalRevenueOk returns a tuple with the TotalRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRevenue

`func (o *IncomeStatement) SetTotalRevenue(v string)`

SetTotalRevenue sets TotalRevenue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


