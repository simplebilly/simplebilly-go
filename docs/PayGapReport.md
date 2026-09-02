# PayGapReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByJobTitle** | [**[]JobTitleGap**](JobTitleGap.md) |  | 
**DiverseCount** | **int32** |  | 
**EmployeeCount** | **int32** |  | 
**FemaleCount** | **int32** |  | 
**MaleCount** | **int32** |  | 
**MeanGapPct** | **float64** |  | 
**MedianGapPct** | **float64** |  | 
**Quartiles** | [**[]QuartileBand**](QuartileBand.md) |  | 

## Methods

### NewPayGapReport

`func NewPayGapReport(byJobTitle []JobTitleGap, diverseCount int32, employeeCount int32, femaleCount int32, maleCount int32, meanGapPct float64, medianGapPct float64, quartiles []QuartileBand, ) *PayGapReport`

NewPayGapReport instantiates a new PayGapReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayGapReportWithDefaults

`func NewPayGapReportWithDefaults() *PayGapReport`

NewPayGapReportWithDefaults instantiates a new PayGapReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetByJobTitle

`func (o *PayGapReport) GetByJobTitle() []JobTitleGap`

GetByJobTitle returns the ByJobTitle field if non-nil, zero value otherwise.

### GetByJobTitleOk

`func (o *PayGapReport) GetByJobTitleOk() (*[]JobTitleGap, bool)`

GetByJobTitleOk returns a tuple with the ByJobTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByJobTitle

`func (o *PayGapReport) SetByJobTitle(v []JobTitleGap)`

SetByJobTitle sets ByJobTitle field to given value.


### GetDiverseCount

`func (o *PayGapReport) GetDiverseCount() int32`

GetDiverseCount returns the DiverseCount field if non-nil, zero value otherwise.

### GetDiverseCountOk

`func (o *PayGapReport) GetDiverseCountOk() (*int32, bool)`

GetDiverseCountOk returns a tuple with the DiverseCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiverseCount

`func (o *PayGapReport) SetDiverseCount(v int32)`

SetDiverseCount sets DiverseCount field to given value.


### GetEmployeeCount

`func (o *PayGapReport) GetEmployeeCount() int32`

GetEmployeeCount returns the EmployeeCount field if non-nil, zero value otherwise.

### GetEmployeeCountOk

`func (o *PayGapReport) GetEmployeeCountOk() (*int32, bool)`

GetEmployeeCountOk returns a tuple with the EmployeeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeCount

`func (o *PayGapReport) SetEmployeeCount(v int32)`

SetEmployeeCount sets EmployeeCount field to given value.


### GetFemaleCount

`func (o *PayGapReport) GetFemaleCount() int32`

GetFemaleCount returns the FemaleCount field if non-nil, zero value otherwise.

### GetFemaleCountOk

`func (o *PayGapReport) GetFemaleCountOk() (*int32, bool)`

GetFemaleCountOk returns a tuple with the FemaleCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFemaleCount

`func (o *PayGapReport) SetFemaleCount(v int32)`

SetFemaleCount sets FemaleCount field to given value.


### GetMaleCount

`func (o *PayGapReport) GetMaleCount() int32`

GetMaleCount returns the MaleCount field if non-nil, zero value otherwise.

### GetMaleCountOk

`func (o *PayGapReport) GetMaleCountOk() (*int32, bool)`

GetMaleCountOk returns a tuple with the MaleCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaleCount

`func (o *PayGapReport) SetMaleCount(v int32)`

SetMaleCount sets MaleCount field to given value.


### GetMeanGapPct

`func (o *PayGapReport) GetMeanGapPct() float64`

GetMeanGapPct returns the MeanGapPct field if non-nil, zero value otherwise.

### GetMeanGapPctOk

`func (o *PayGapReport) GetMeanGapPctOk() (*float64, bool)`

GetMeanGapPctOk returns a tuple with the MeanGapPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeanGapPct

`func (o *PayGapReport) SetMeanGapPct(v float64)`

SetMeanGapPct sets MeanGapPct field to given value.


### GetMedianGapPct

`func (o *PayGapReport) GetMedianGapPct() float64`

GetMedianGapPct returns the MedianGapPct field if non-nil, zero value otherwise.

### GetMedianGapPctOk

`func (o *PayGapReport) GetMedianGapPctOk() (*float64, bool)`

GetMedianGapPctOk returns a tuple with the MedianGapPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedianGapPct

`func (o *PayGapReport) SetMedianGapPct(v float64)`

SetMedianGapPct sets MedianGapPct field to given value.


### GetQuartiles

`func (o *PayGapReport) GetQuartiles() []QuartileBand`

GetQuartiles returns the Quartiles field if non-nil, zero value otherwise.

### GetQuartilesOk

`func (o *PayGapReport) GetQuartilesOk() (*[]QuartileBand, bool)`

GetQuartilesOk returns a tuple with the Quartiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuartiles

`func (o *PayGapReport) SetQuartiles(v []QuartileBand)`

SetQuartiles sets Quartiles field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


