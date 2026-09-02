# GuVReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Expenses** | [**[]GuVItem**](GuVItem.md) |  | 
**GeneratedAt** | **string** |  | 
**NetIncome** | **string** |  | 
**Period** | **string** |  | 
**Revenue** | [**[]GuVItem**](GuVItem.md) |  | 
**TotalExpenses** | **string** |  | 
**TotalRevenue** | **string** |  | 

## Methods

### NewGuVReport

`func NewGuVReport(expenses []GuVItem, generatedAt string, netIncome string, period string, revenue []GuVItem, totalExpenses string, totalRevenue string, ) *GuVReport`

NewGuVReport instantiates a new GuVReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGuVReportWithDefaults

`func NewGuVReportWithDefaults() *GuVReport`

NewGuVReportWithDefaults instantiates a new GuVReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpenses

`func (o *GuVReport) GetExpenses() []GuVItem`

GetExpenses returns the Expenses field if non-nil, zero value otherwise.

### GetExpensesOk

`func (o *GuVReport) GetExpensesOk() (*[]GuVItem, bool)`

GetExpensesOk returns a tuple with the Expenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenses

`func (o *GuVReport) SetExpenses(v []GuVItem)`

SetExpenses sets Expenses field to given value.


### GetGeneratedAt

`func (o *GuVReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *GuVReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *GuVReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetNetIncome

`func (o *GuVReport) GetNetIncome() string`

GetNetIncome returns the NetIncome field if non-nil, zero value otherwise.

### GetNetIncomeOk

`func (o *GuVReport) GetNetIncomeOk() (*string, bool)`

GetNetIncomeOk returns a tuple with the NetIncome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetIncome

`func (o *GuVReport) SetNetIncome(v string)`

SetNetIncome sets NetIncome field to given value.


### GetPeriod

`func (o *GuVReport) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *GuVReport) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *GuVReport) SetPeriod(v string)`

SetPeriod sets Period field to given value.


### GetRevenue

`func (o *GuVReport) GetRevenue() []GuVItem`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *GuVReport) GetRevenueOk() (*[]GuVItem, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *GuVReport) SetRevenue(v []GuVItem)`

SetRevenue sets Revenue field to given value.


### GetTotalExpenses

`func (o *GuVReport) GetTotalExpenses() string`

GetTotalExpenses returns the TotalExpenses field if non-nil, zero value otherwise.

### GetTotalExpensesOk

`func (o *GuVReport) GetTotalExpensesOk() (*string, bool)`

GetTotalExpensesOk returns a tuple with the TotalExpenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalExpenses

`func (o *GuVReport) SetTotalExpenses(v string)`

SetTotalExpenses sets TotalExpenses field to given value.


### GetTotalRevenue

`func (o *GuVReport) GetTotalRevenue() string`

GetTotalRevenue returns the TotalRevenue field if non-nil, zero value otherwise.

### GetTotalRevenueOk

`func (o *GuVReport) GetTotalRevenueOk() (*string, bool)`

GetTotalRevenueOk returns a tuple with the TotalRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRevenue

`func (o *GuVReport) SetTotalRevenue(v string)`

SetTotalRevenue sets TotalRevenue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


