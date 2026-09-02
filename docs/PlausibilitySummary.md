# PlausibilitySummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Errors** | **int32** |  | 
**OverallStatus** | [**CheckStatus**](CheckStatus.md) |  | 
**Passed** | **int32** |  | 
**TotalChecks** | **int32** |  | 
**Warnings** | **int32** |  | 

## Methods

### NewPlausibilitySummary

`func NewPlausibilitySummary(errors int32, overallStatus CheckStatus, passed int32, totalChecks int32, warnings int32, ) *PlausibilitySummary`

NewPlausibilitySummary instantiates a new PlausibilitySummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlausibilitySummaryWithDefaults

`func NewPlausibilitySummaryWithDefaults() *PlausibilitySummary`

NewPlausibilitySummaryWithDefaults instantiates a new PlausibilitySummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrors

`func (o *PlausibilitySummary) GetErrors() int32`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *PlausibilitySummary) GetErrorsOk() (*int32, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *PlausibilitySummary) SetErrors(v int32)`

SetErrors sets Errors field to given value.


### GetOverallStatus

`func (o *PlausibilitySummary) GetOverallStatus() CheckStatus`

GetOverallStatus returns the OverallStatus field if non-nil, zero value otherwise.

### GetOverallStatusOk

`func (o *PlausibilitySummary) GetOverallStatusOk() (*CheckStatus, bool)`

GetOverallStatusOk returns a tuple with the OverallStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverallStatus

`func (o *PlausibilitySummary) SetOverallStatus(v CheckStatus)`

SetOverallStatus sets OverallStatus field to given value.


### GetPassed

`func (o *PlausibilitySummary) GetPassed() int32`

GetPassed returns the Passed field if non-nil, zero value otherwise.

### GetPassedOk

`func (o *PlausibilitySummary) GetPassedOk() (*int32, bool)`

GetPassedOk returns a tuple with the Passed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassed

`func (o *PlausibilitySummary) SetPassed(v int32)`

SetPassed sets Passed field to given value.


### GetTotalChecks

`func (o *PlausibilitySummary) GetTotalChecks() int32`

GetTotalChecks returns the TotalChecks field if non-nil, zero value otherwise.

### GetTotalChecksOk

`func (o *PlausibilitySummary) GetTotalChecksOk() (*int32, bool)`

GetTotalChecksOk returns a tuple with the TotalChecks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalChecks

`func (o *PlausibilitySummary) SetTotalChecks(v int32)`

SetTotalChecks sets TotalChecks field to given value.


### GetWarnings

`func (o *PlausibilitySummary) GetWarnings() int32`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *PlausibilitySummary) GetWarningsOk() (*int32, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *PlausibilitySummary) SetWarnings(v int32)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


