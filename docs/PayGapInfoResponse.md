# PayGapInfoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmployeeId** | **string** |  | 
**FirstName** | **string** |  | 
**Gender** | Pointer to **NullableString** |  | [optional] 
**GroupMedianHourly** | Pointer to **NullableFloat64** |  | [optional] 
**GroupMedianMonthly** | Pointer to **NullableFloat64** |  | [optional] 
**GroupSize** | **int32** |  | 
**JobTitle** | **string** |  | 
**LastName** | **string** |  | 
**OverallMedianHourly** | Pointer to **NullableFloat64** |  | [optional] 
**OwnHourlyGross** | Pointer to **NullableFloat64** |  | [optional] 
**OwnMonthlyGross** | Pointer to **NullableFloat64** |  | [optional] 

## Methods

### NewPayGapInfoResponse

`func NewPayGapInfoResponse(employeeId string, firstName string, groupSize int32, jobTitle string, lastName string, ) *PayGapInfoResponse`

NewPayGapInfoResponse instantiates a new PayGapInfoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayGapInfoResponseWithDefaults

`func NewPayGapInfoResponseWithDefaults() *PayGapInfoResponse`

NewPayGapInfoResponseWithDefaults instantiates a new PayGapInfoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployeeId

`func (o *PayGapInfoResponse) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *PayGapInfoResponse) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *PayGapInfoResponse) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.


### GetFirstName

`func (o *PayGapInfoResponse) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *PayGapInfoResponse) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *PayGapInfoResponse) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetGender

`func (o *PayGapInfoResponse) GetGender() string`

GetGender returns the Gender field if non-nil, zero value otherwise.

### GetGenderOk

`func (o *PayGapInfoResponse) GetGenderOk() (*string, bool)`

GetGenderOk returns a tuple with the Gender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGender

`func (o *PayGapInfoResponse) SetGender(v string)`

SetGender sets Gender field to given value.

### HasGender

`func (o *PayGapInfoResponse) HasGender() bool`

HasGender returns a boolean if a field has been set.

### SetGenderNil

`func (o *PayGapInfoResponse) SetGenderNil(b bool)`

 SetGenderNil sets the value for Gender to be an explicit nil

### UnsetGender
`func (o *PayGapInfoResponse) UnsetGender()`

UnsetGender ensures that no value is present for Gender, not even an explicit nil
### GetGroupMedianHourly

`func (o *PayGapInfoResponse) GetGroupMedianHourly() float64`

GetGroupMedianHourly returns the GroupMedianHourly field if non-nil, zero value otherwise.

### GetGroupMedianHourlyOk

`func (o *PayGapInfoResponse) GetGroupMedianHourlyOk() (*float64, bool)`

GetGroupMedianHourlyOk returns a tuple with the GroupMedianHourly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMedianHourly

`func (o *PayGapInfoResponse) SetGroupMedianHourly(v float64)`

SetGroupMedianHourly sets GroupMedianHourly field to given value.

### HasGroupMedianHourly

`func (o *PayGapInfoResponse) HasGroupMedianHourly() bool`

HasGroupMedianHourly returns a boolean if a field has been set.

### SetGroupMedianHourlyNil

`func (o *PayGapInfoResponse) SetGroupMedianHourlyNil(b bool)`

 SetGroupMedianHourlyNil sets the value for GroupMedianHourly to be an explicit nil

### UnsetGroupMedianHourly
`func (o *PayGapInfoResponse) UnsetGroupMedianHourly()`

UnsetGroupMedianHourly ensures that no value is present for GroupMedianHourly, not even an explicit nil
### GetGroupMedianMonthly

`func (o *PayGapInfoResponse) GetGroupMedianMonthly() float64`

GetGroupMedianMonthly returns the GroupMedianMonthly field if non-nil, zero value otherwise.

### GetGroupMedianMonthlyOk

`func (o *PayGapInfoResponse) GetGroupMedianMonthlyOk() (*float64, bool)`

GetGroupMedianMonthlyOk returns a tuple with the GroupMedianMonthly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMedianMonthly

`func (o *PayGapInfoResponse) SetGroupMedianMonthly(v float64)`

SetGroupMedianMonthly sets GroupMedianMonthly field to given value.

### HasGroupMedianMonthly

`func (o *PayGapInfoResponse) HasGroupMedianMonthly() bool`

HasGroupMedianMonthly returns a boolean if a field has been set.

### SetGroupMedianMonthlyNil

`func (o *PayGapInfoResponse) SetGroupMedianMonthlyNil(b bool)`

 SetGroupMedianMonthlyNil sets the value for GroupMedianMonthly to be an explicit nil

### UnsetGroupMedianMonthly
`func (o *PayGapInfoResponse) UnsetGroupMedianMonthly()`

UnsetGroupMedianMonthly ensures that no value is present for GroupMedianMonthly, not even an explicit nil
### GetGroupSize

`func (o *PayGapInfoResponse) GetGroupSize() int32`

GetGroupSize returns the GroupSize field if non-nil, zero value otherwise.

### GetGroupSizeOk

`func (o *PayGapInfoResponse) GetGroupSizeOk() (*int32, bool)`

GetGroupSizeOk returns a tuple with the GroupSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupSize

`func (o *PayGapInfoResponse) SetGroupSize(v int32)`

SetGroupSize sets GroupSize field to given value.


### GetJobTitle

`func (o *PayGapInfoResponse) GetJobTitle() string`

GetJobTitle returns the JobTitle field if non-nil, zero value otherwise.

### GetJobTitleOk

`func (o *PayGapInfoResponse) GetJobTitleOk() (*string, bool)`

GetJobTitleOk returns a tuple with the JobTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTitle

`func (o *PayGapInfoResponse) SetJobTitle(v string)`

SetJobTitle sets JobTitle field to given value.


### GetLastName

`func (o *PayGapInfoResponse) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *PayGapInfoResponse) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *PayGapInfoResponse) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetOverallMedianHourly

`func (o *PayGapInfoResponse) GetOverallMedianHourly() float64`

GetOverallMedianHourly returns the OverallMedianHourly field if non-nil, zero value otherwise.

### GetOverallMedianHourlyOk

`func (o *PayGapInfoResponse) GetOverallMedianHourlyOk() (*float64, bool)`

GetOverallMedianHourlyOk returns a tuple with the OverallMedianHourly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverallMedianHourly

`func (o *PayGapInfoResponse) SetOverallMedianHourly(v float64)`

SetOverallMedianHourly sets OverallMedianHourly field to given value.

### HasOverallMedianHourly

`func (o *PayGapInfoResponse) HasOverallMedianHourly() bool`

HasOverallMedianHourly returns a boolean if a field has been set.

### SetOverallMedianHourlyNil

`func (o *PayGapInfoResponse) SetOverallMedianHourlyNil(b bool)`

 SetOverallMedianHourlyNil sets the value for OverallMedianHourly to be an explicit nil

### UnsetOverallMedianHourly
`func (o *PayGapInfoResponse) UnsetOverallMedianHourly()`

UnsetOverallMedianHourly ensures that no value is present for OverallMedianHourly, not even an explicit nil
### GetOwnHourlyGross

`func (o *PayGapInfoResponse) GetOwnHourlyGross() float64`

GetOwnHourlyGross returns the OwnHourlyGross field if non-nil, zero value otherwise.

### GetOwnHourlyGrossOk

`func (o *PayGapInfoResponse) GetOwnHourlyGrossOk() (*float64, bool)`

GetOwnHourlyGrossOk returns a tuple with the OwnHourlyGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnHourlyGross

`func (o *PayGapInfoResponse) SetOwnHourlyGross(v float64)`

SetOwnHourlyGross sets OwnHourlyGross field to given value.

### HasOwnHourlyGross

`func (o *PayGapInfoResponse) HasOwnHourlyGross() bool`

HasOwnHourlyGross returns a boolean if a field has been set.

### SetOwnHourlyGrossNil

`func (o *PayGapInfoResponse) SetOwnHourlyGrossNil(b bool)`

 SetOwnHourlyGrossNil sets the value for OwnHourlyGross to be an explicit nil

### UnsetOwnHourlyGross
`func (o *PayGapInfoResponse) UnsetOwnHourlyGross()`

UnsetOwnHourlyGross ensures that no value is present for OwnHourlyGross, not even an explicit nil
### GetOwnMonthlyGross

`func (o *PayGapInfoResponse) GetOwnMonthlyGross() float64`

GetOwnMonthlyGross returns the OwnMonthlyGross field if non-nil, zero value otherwise.

### GetOwnMonthlyGrossOk

`func (o *PayGapInfoResponse) GetOwnMonthlyGrossOk() (*float64, bool)`

GetOwnMonthlyGrossOk returns a tuple with the OwnMonthlyGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnMonthlyGross

`func (o *PayGapInfoResponse) SetOwnMonthlyGross(v float64)`

SetOwnMonthlyGross sets OwnMonthlyGross field to given value.

### HasOwnMonthlyGross

`func (o *PayGapInfoResponse) HasOwnMonthlyGross() bool`

HasOwnMonthlyGross returns a boolean if a field has been set.

### SetOwnMonthlyGrossNil

`func (o *PayGapInfoResponse) SetOwnMonthlyGrossNil(b bool)`

 SetOwnMonthlyGrossNil sets the value for OwnMonthlyGross to be an explicit nil

### UnsetOwnMonthlyGross
`func (o *PayGapInfoResponse) UnsetOwnMonthlyGross()`

UnsetOwnMonthlyGross ensures that no value is present for OwnMonthlyGross, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


