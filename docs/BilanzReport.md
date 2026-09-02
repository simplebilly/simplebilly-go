# BilanzReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Aktiva** | [**[]BilanzItem**](BilanzItem.md) |  | 
**Balanced** | **bool** |  | 
**GeneratedAt** | **string** |  | 
**Passiva** | [**[]BilanzItem**](BilanzItem.md) |  | 
**Period** | **string** |  | 
**TotalAktiva** | **string** |  | 
**TotalPassiva** | **string** |  | 

## Methods

### NewBilanzReport

`func NewBilanzReport(aktiva []BilanzItem, balanced bool, generatedAt string, passiva []BilanzItem, period string, totalAktiva string, totalPassiva string, ) *BilanzReport`

NewBilanzReport instantiates a new BilanzReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBilanzReportWithDefaults

`func NewBilanzReportWithDefaults() *BilanzReport`

NewBilanzReportWithDefaults instantiates a new BilanzReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAktiva

`func (o *BilanzReport) GetAktiva() []BilanzItem`

GetAktiva returns the Aktiva field if non-nil, zero value otherwise.

### GetAktivaOk

`func (o *BilanzReport) GetAktivaOk() (*[]BilanzItem, bool)`

GetAktivaOk returns a tuple with the Aktiva field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAktiva

`func (o *BilanzReport) SetAktiva(v []BilanzItem)`

SetAktiva sets Aktiva field to given value.


### GetBalanced

`func (o *BilanzReport) GetBalanced() bool`

GetBalanced returns the Balanced field if non-nil, zero value otherwise.

### GetBalancedOk

`func (o *BilanzReport) GetBalancedOk() (*bool, bool)`

GetBalancedOk returns a tuple with the Balanced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanced

`func (o *BilanzReport) SetBalanced(v bool)`

SetBalanced sets Balanced field to given value.


### GetGeneratedAt

`func (o *BilanzReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *BilanzReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *BilanzReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPassiva

`func (o *BilanzReport) GetPassiva() []BilanzItem`

GetPassiva returns the Passiva field if non-nil, zero value otherwise.

### GetPassivaOk

`func (o *BilanzReport) GetPassivaOk() (*[]BilanzItem, bool)`

GetPassivaOk returns a tuple with the Passiva field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassiva

`func (o *BilanzReport) SetPassiva(v []BilanzItem)`

SetPassiva sets Passiva field to given value.


### GetPeriod

`func (o *BilanzReport) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *BilanzReport) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *BilanzReport) SetPeriod(v string)`

SetPeriod sets Period field to given value.


### GetTotalAktiva

`func (o *BilanzReport) GetTotalAktiva() string`

GetTotalAktiva returns the TotalAktiva field if non-nil, zero value otherwise.

### GetTotalAktivaOk

`func (o *BilanzReport) GetTotalAktivaOk() (*string, bool)`

GetTotalAktivaOk returns a tuple with the TotalAktiva field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAktiva

`func (o *BilanzReport) SetTotalAktiva(v string)`

SetTotalAktiva sets TotalAktiva field to given value.


### GetTotalPassiva

`func (o *BilanzReport) GetTotalPassiva() string`

GetTotalPassiva returns the TotalPassiva field if non-nil, zero value otherwise.

### GetTotalPassivaOk

`func (o *BilanzReport) GetTotalPassivaOk() (*string, bool)`

GetTotalPassivaOk returns a tuple with the TotalPassiva field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPassiva

`func (o *BilanzReport) SetTotalPassiva(v string)`

SetTotalPassiva sets TotalPassiva field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


