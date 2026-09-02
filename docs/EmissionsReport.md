# EmissionsReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByCategory** | [**[]CategoryTotal**](CategoryTotal.md) |  | 
**ByScope** | [**[]ScopeTotal**](ScopeTotal.md) |  | 
**ByYear** | [**[]YearTotal**](YearTotal.md) |  | 
**DataQuality** | [**DataQuality**](DataQuality.md) |  | 
**IntensityPerEmployee** | Pointer to **NullableFloat64** |  | [optional] 
**IntensityPerRevenueMio** | Pointer to **NullableFloat64** | tCO2e per million EUR net revenue. | [optional] 
**NetRevenue** | Pointer to **NullableFloat64** | Sum of paid/sent/partially-paid invoices (EUR net) in the year. | [optional] 
**SpendBasedEstimateTco2e** | Pointer to **NullableFloat64** | Spend-based estimate from bookkeeping payments (EXIOBASE factor). | [optional] 
**Targets** | [**[]TargetProgress**](TargetProgress.md) |  | 
**TotalTco2e** | **string** |  | 

## Methods

### NewEmissionsReport

`func NewEmissionsReport(byCategory []CategoryTotal, byScope []ScopeTotal, byYear []YearTotal, dataQuality DataQuality, targets []TargetProgress, totalTco2e string, ) *EmissionsReport`

NewEmissionsReport instantiates a new EmissionsReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmissionsReportWithDefaults

`func NewEmissionsReportWithDefaults() *EmissionsReport`

NewEmissionsReportWithDefaults instantiates a new EmissionsReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetByCategory

`func (o *EmissionsReport) GetByCategory() []CategoryTotal`

GetByCategory returns the ByCategory field if non-nil, zero value otherwise.

### GetByCategoryOk

`func (o *EmissionsReport) GetByCategoryOk() (*[]CategoryTotal, bool)`

GetByCategoryOk returns a tuple with the ByCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByCategory

`func (o *EmissionsReport) SetByCategory(v []CategoryTotal)`

SetByCategory sets ByCategory field to given value.


### GetByScope

`func (o *EmissionsReport) GetByScope() []ScopeTotal`

GetByScope returns the ByScope field if non-nil, zero value otherwise.

### GetByScopeOk

`func (o *EmissionsReport) GetByScopeOk() (*[]ScopeTotal, bool)`

GetByScopeOk returns a tuple with the ByScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByScope

`func (o *EmissionsReport) SetByScope(v []ScopeTotal)`

SetByScope sets ByScope field to given value.


### GetByYear

`func (o *EmissionsReport) GetByYear() []YearTotal`

GetByYear returns the ByYear field if non-nil, zero value otherwise.

### GetByYearOk

`func (o *EmissionsReport) GetByYearOk() (*[]YearTotal, bool)`

GetByYearOk returns a tuple with the ByYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByYear

`func (o *EmissionsReport) SetByYear(v []YearTotal)`

SetByYear sets ByYear field to given value.


### GetDataQuality

`func (o *EmissionsReport) GetDataQuality() DataQuality`

GetDataQuality returns the DataQuality field if non-nil, zero value otherwise.

### GetDataQualityOk

`func (o *EmissionsReport) GetDataQualityOk() (*DataQuality, bool)`

GetDataQualityOk returns a tuple with the DataQuality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataQuality

`func (o *EmissionsReport) SetDataQuality(v DataQuality)`

SetDataQuality sets DataQuality field to given value.


### GetIntensityPerEmployee

`func (o *EmissionsReport) GetIntensityPerEmployee() float64`

GetIntensityPerEmployee returns the IntensityPerEmployee field if non-nil, zero value otherwise.

### GetIntensityPerEmployeeOk

`func (o *EmissionsReport) GetIntensityPerEmployeeOk() (*float64, bool)`

GetIntensityPerEmployeeOk returns a tuple with the IntensityPerEmployee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntensityPerEmployee

`func (o *EmissionsReport) SetIntensityPerEmployee(v float64)`

SetIntensityPerEmployee sets IntensityPerEmployee field to given value.

### HasIntensityPerEmployee

`func (o *EmissionsReport) HasIntensityPerEmployee() bool`

HasIntensityPerEmployee returns a boolean if a field has been set.

### SetIntensityPerEmployeeNil

`func (o *EmissionsReport) SetIntensityPerEmployeeNil(b bool)`

 SetIntensityPerEmployeeNil sets the value for IntensityPerEmployee to be an explicit nil

### UnsetIntensityPerEmployee
`func (o *EmissionsReport) UnsetIntensityPerEmployee()`

UnsetIntensityPerEmployee ensures that no value is present for IntensityPerEmployee, not even an explicit nil
### GetIntensityPerRevenueMio

`func (o *EmissionsReport) GetIntensityPerRevenueMio() float64`

GetIntensityPerRevenueMio returns the IntensityPerRevenueMio field if non-nil, zero value otherwise.

### GetIntensityPerRevenueMioOk

`func (o *EmissionsReport) GetIntensityPerRevenueMioOk() (*float64, bool)`

GetIntensityPerRevenueMioOk returns a tuple with the IntensityPerRevenueMio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntensityPerRevenueMio

`func (o *EmissionsReport) SetIntensityPerRevenueMio(v float64)`

SetIntensityPerRevenueMio sets IntensityPerRevenueMio field to given value.

### HasIntensityPerRevenueMio

`func (o *EmissionsReport) HasIntensityPerRevenueMio() bool`

HasIntensityPerRevenueMio returns a boolean if a field has been set.

### SetIntensityPerRevenueMioNil

`func (o *EmissionsReport) SetIntensityPerRevenueMioNil(b bool)`

 SetIntensityPerRevenueMioNil sets the value for IntensityPerRevenueMio to be an explicit nil

### UnsetIntensityPerRevenueMio
`func (o *EmissionsReport) UnsetIntensityPerRevenueMio()`

UnsetIntensityPerRevenueMio ensures that no value is present for IntensityPerRevenueMio, not even an explicit nil
### GetNetRevenue

`func (o *EmissionsReport) GetNetRevenue() float64`

GetNetRevenue returns the NetRevenue field if non-nil, zero value otherwise.

### GetNetRevenueOk

`func (o *EmissionsReport) GetNetRevenueOk() (*float64, bool)`

GetNetRevenueOk returns a tuple with the NetRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetRevenue

`func (o *EmissionsReport) SetNetRevenue(v float64)`

SetNetRevenue sets NetRevenue field to given value.

### HasNetRevenue

`func (o *EmissionsReport) HasNetRevenue() bool`

HasNetRevenue returns a boolean if a field has been set.

### SetNetRevenueNil

`func (o *EmissionsReport) SetNetRevenueNil(b bool)`

 SetNetRevenueNil sets the value for NetRevenue to be an explicit nil

### UnsetNetRevenue
`func (o *EmissionsReport) UnsetNetRevenue()`

UnsetNetRevenue ensures that no value is present for NetRevenue, not even an explicit nil
### GetSpendBasedEstimateTco2e

`func (o *EmissionsReport) GetSpendBasedEstimateTco2e() float64`

GetSpendBasedEstimateTco2e returns the SpendBasedEstimateTco2e field if non-nil, zero value otherwise.

### GetSpendBasedEstimateTco2eOk

`func (o *EmissionsReport) GetSpendBasedEstimateTco2eOk() (*float64, bool)`

GetSpendBasedEstimateTco2eOk returns a tuple with the SpendBasedEstimateTco2e field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpendBasedEstimateTco2e

`func (o *EmissionsReport) SetSpendBasedEstimateTco2e(v float64)`

SetSpendBasedEstimateTco2e sets SpendBasedEstimateTco2e field to given value.

### HasSpendBasedEstimateTco2e

`func (o *EmissionsReport) HasSpendBasedEstimateTco2e() bool`

HasSpendBasedEstimateTco2e returns a boolean if a field has been set.

### SetSpendBasedEstimateTco2eNil

`func (o *EmissionsReport) SetSpendBasedEstimateTco2eNil(b bool)`

 SetSpendBasedEstimateTco2eNil sets the value for SpendBasedEstimateTco2e to be an explicit nil

### UnsetSpendBasedEstimateTco2e
`func (o *EmissionsReport) UnsetSpendBasedEstimateTco2e()`

UnsetSpendBasedEstimateTco2e ensures that no value is present for SpendBasedEstimateTco2e, not even an explicit nil
### GetTargets

`func (o *EmissionsReport) GetTargets() []TargetProgress`

GetTargets returns the Targets field if non-nil, zero value otherwise.

### GetTargetsOk

`func (o *EmissionsReport) GetTargetsOk() (*[]TargetProgress, bool)`

GetTargetsOk returns a tuple with the Targets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargets

`func (o *EmissionsReport) SetTargets(v []TargetProgress)`

SetTargets sets Targets field to given value.


### GetTotalTco2e

`func (o *EmissionsReport) GetTotalTco2e() string`

GetTotalTco2e returns the TotalTco2e field if non-nil, zero value otherwise.

### GetTotalTco2eOk

`func (o *EmissionsReport) GetTotalTco2eOk() (*string, bool)`

GetTotalTco2eOk returns a tuple with the TotalTco2e field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTco2e

`func (o *EmissionsReport) SetTotalTco2e(v string)`

SetTotalTco2e sets TotalTco2e field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


