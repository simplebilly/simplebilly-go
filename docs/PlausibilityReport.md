# PlausibilityReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checks** | [**[]PlausibilityCheck**](PlausibilityCheck.md) |  | 
**GeneratedAt** | **string** |  | 
**Summary** | [**PlausibilitySummary**](PlausibilitySummary.md) |  | 

## Methods

### NewPlausibilityReport

`func NewPlausibilityReport(checks []PlausibilityCheck, generatedAt string, summary PlausibilitySummary, ) *PlausibilityReport`

NewPlausibilityReport instantiates a new PlausibilityReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlausibilityReportWithDefaults

`func NewPlausibilityReportWithDefaults() *PlausibilityReport`

NewPlausibilityReportWithDefaults instantiates a new PlausibilityReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecks

`func (o *PlausibilityReport) GetChecks() []PlausibilityCheck`

GetChecks returns the Checks field if non-nil, zero value otherwise.

### GetChecksOk

`func (o *PlausibilityReport) GetChecksOk() (*[]PlausibilityCheck, bool)`

GetChecksOk returns a tuple with the Checks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecks

`func (o *PlausibilityReport) SetChecks(v []PlausibilityCheck)`

SetChecks sets Checks field to given value.


### GetGeneratedAt

`func (o *PlausibilityReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *PlausibilityReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *PlausibilityReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetSummary

`func (o *PlausibilityReport) GetSummary() PlausibilitySummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *PlausibilityReport) GetSummaryOk() (*PlausibilitySummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *PlausibilityReport) SetSummary(v PlausibilitySummary)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


