# EBilanzReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountOverview** | [**[]AccountOverview**](AccountOverview.md) |  | 
**BalanceSheet** | [**BalanceSheet**](BalanceSheet.md) |  | 
**GeneratedAt** | **string** |  | 
**IncomeStatement** | [**IncomeStatement**](IncomeStatement.md) |  | 
**Period** | **string** |  | 
**VatSummary** | [**VatSummary**](VatSummary.md) |  | 

## Methods

### NewEBilanzReport

`func NewEBilanzReport(accountOverview []AccountOverview, balanceSheet BalanceSheet, generatedAt string, incomeStatement IncomeStatement, period string, vatSummary VatSummary, ) *EBilanzReport`

NewEBilanzReport instantiates a new EBilanzReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEBilanzReportWithDefaults

`func NewEBilanzReportWithDefaults() *EBilanzReport`

NewEBilanzReportWithDefaults instantiates a new EBilanzReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountOverview

`func (o *EBilanzReport) GetAccountOverview() []AccountOverview`

GetAccountOverview returns the AccountOverview field if non-nil, zero value otherwise.

### GetAccountOverviewOk

`func (o *EBilanzReport) GetAccountOverviewOk() (*[]AccountOverview, bool)`

GetAccountOverviewOk returns a tuple with the AccountOverview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountOverview

`func (o *EBilanzReport) SetAccountOverview(v []AccountOverview)`

SetAccountOverview sets AccountOverview field to given value.


### GetBalanceSheet

`func (o *EBilanzReport) GetBalanceSheet() BalanceSheet`

GetBalanceSheet returns the BalanceSheet field if non-nil, zero value otherwise.

### GetBalanceSheetOk

`func (o *EBilanzReport) GetBalanceSheetOk() (*BalanceSheet, bool)`

GetBalanceSheetOk returns a tuple with the BalanceSheet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanceSheet

`func (o *EBilanzReport) SetBalanceSheet(v BalanceSheet)`

SetBalanceSheet sets BalanceSheet field to given value.


### GetGeneratedAt

`func (o *EBilanzReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *EBilanzReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *EBilanzReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetIncomeStatement

`func (o *EBilanzReport) GetIncomeStatement() IncomeStatement`

GetIncomeStatement returns the IncomeStatement field if non-nil, zero value otherwise.

### GetIncomeStatementOk

`func (o *EBilanzReport) GetIncomeStatementOk() (*IncomeStatement, bool)`

GetIncomeStatementOk returns a tuple with the IncomeStatement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncomeStatement

`func (o *EBilanzReport) SetIncomeStatement(v IncomeStatement)`

SetIncomeStatement sets IncomeStatement field to given value.


### GetPeriod

`func (o *EBilanzReport) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *EBilanzReport) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *EBilanzReport) SetPeriod(v string)`

SetPeriod sets Period field to given value.


### GetVatSummary

`func (o *EBilanzReport) GetVatSummary() VatSummary`

GetVatSummary returns the VatSummary field if non-nil, zero value otherwise.

### GetVatSummaryOk

`func (o *EBilanzReport) GetVatSummaryOk() (*VatSummary, bool)`

GetVatSummaryOk returns a tuple with the VatSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatSummary

`func (o *EBilanzReport) SetVatSummary(v VatSummary)`

SetVatSummary sets VatSummary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


