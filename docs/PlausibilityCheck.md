# PlausibilityCheck

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Detail** | **string** |  | 
**Id** | **string** |  | 
**Name** | **string** |  | 
**Severity** | [**Severity**](Severity.md) |  | 
**Status** | [**CheckStatus**](CheckStatus.md) |  | 

## Methods

### NewPlausibilityCheck

`func NewPlausibilityCheck(detail string, id string, name string, severity Severity, status CheckStatus, ) *PlausibilityCheck`

NewPlausibilityCheck instantiates a new PlausibilityCheck object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlausibilityCheckWithDefaults

`func NewPlausibilityCheckWithDefaults() *PlausibilityCheck`

NewPlausibilityCheckWithDefaults instantiates a new PlausibilityCheck object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDetail

`func (o *PlausibilityCheck) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *PlausibilityCheck) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *PlausibilityCheck) SetDetail(v string)`

SetDetail sets Detail field to given value.


### GetId

`func (o *PlausibilityCheck) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PlausibilityCheck) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PlausibilityCheck) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *PlausibilityCheck) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PlausibilityCheck) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PlausibilityCheck) SetName(v string)`

SetName sets Name field to given value.


### GetSeverity

`func (o *PlausibilityCheck) GetSeverity() Severity`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *PlausibilityCheck) GetSeverityOk() (*Severity, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *PlausibilityCheck) SetSeverity(v Severity)`

SetSeverity sets Severity field to given value.


### GetStatus

`func (o *PlausibilityCheck) GetStatus() CheckStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PlausibilityCheck) GetStatusOk() (*CheckStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PlausibilityCheck) SetStatus(v CheckStatus)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


