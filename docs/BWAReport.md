# BWAReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Expenses** | [**BWAExpenses**](BWAExpenses.md) |  | 
**GeneratedAt** | **string** |  | 
**Period** | **string** |  | 
**Revenue** | [**BWARevenue**](BWARevenue.md) |  | 
**Summary** | [**BWASummary**](BWASummary.md) |  | 

## Methods

### NewBWAReport

`func NewBWAReport(expenses BWAExpenses, generatedAt string, period string, revenue BWARevenue, summary BWASummary, ) *BWAReport`

NewBWAReport instantiates a new BWAReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBWAReportWithDefaults

`func NewBWAReportWithDefaults() *BWAReport`

NewBWAReportWithDefaults instantiates a new BWAReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpenses

`func (o *BWAReport) GetExpenses() BWAExpenses`

GetExpenses returns the Expenses field if non-nil, zero value otherwise.

### GetExpensesOk

`func (o *BWAReport) GetExpensesOk() (*BWAExpenses, bool)`

GetExpensesOk returns a tuple with the Expenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpenses

`func (o *BWAReport) SetExpenses(v BWAExpenses)`

SetExpenses sets Expenses field to given value.


### GetGeneratedAt

`func (o *BWAReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *BWAReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *BWAReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *BWAReport) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *BWAReport) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *BWAReport) SetPeriod(v string)`

SetPeriod sets Period field to given value.


### GetRevenue

`func (o *BWAReport) GetRevenue() BWARevenue`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *BWAReport) GetRevenueOk() (*BWARevenue, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *BWAReport) SetRevenue(v BWARevenue)`

SetRevenue sets Revenue field to given value.


### GetSummary

`func (o *BWAReport) GetSummary() BWASummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *BWAReport) GetSummaryOk() (*BWASummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *BWAReport) SetSummary(v BWASummary)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


