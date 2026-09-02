# MyTrainingItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignmentId** | **string** |  | 
**CertificateId** | Pointer to **NullableString** |  | [optional] 
**Code** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**DueDate** | Pointer to **NullableString** |  | [optional] 
**LastScore** | Pointer to **NullableInt32** |  | [optional] 
**PassScore** | **int32** |  | 
**Passed** | Pointer to **NullableBool** |  | [optional] 
**Status** | [**AssignmentStatus**](AssignmentStatus.md) |  | 
**Title** | **string** |  | 
**TrainingId** | **string** |  | 
**ValidUntil** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewMyTrainingItem

`func NewMyTrainingItem(assignmentId string, code string, passScore int32, status AssignmentStatus, title string, trainingId string, ) *MyTrainingItem`

NewMyTrainingItem instantiates a new MyTrainingItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMyTrainingItemWithDefaults

`func NewMyTrainingItemWithDefaults() *MyTrainingItem`

NewMyTrainingItemWithDefaults instantiates a new MyTrainingItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignmentId

`func (o *MyTrainingItem) GetAssignmentId() string`

GetAssignmentId returns the AssignmentId field if non-nil, zero value otherwise.

### GetAssignmentIdOk

`func (o *MyTrainingItem) GetAssignmentIdOk() (*string, bool)`

GetAssignmentIdOk returns a tuple with the AssignmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignmentId

`func (o *MyTrainingItem) SetAssignmentId(v string)`

SetAssignmentId sets AssignmentId field to given value.


### GetCertificateId

`func (o *MyTrainingItem) GetCertificateId() string`

GetCertificateId returns the CertificateId field if non-nil, zero value otherwise.

### GetCertificateIdOk

`func (o *MyTrainingItem) GetCertificateIdOk() (*string, bool)`

GetCertificateIdOk returns a tuple with the CertificateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateId

`func (o *MyTrainingItem) SetCertificateId(v string)`

SetCertificateId sets CertificateId field to given value.

### HasCertificateId

`func (o *MyTrainingItem) HasCertificateId() bool`

HasCertificateId returns a boolean if a field has been set.

### SetCertificateIdNil

`func (o *MyTrainingItem) SetCertificateIdNil(b bool)`

 SetCertificateIdNil sets the value for CertificateId to be an explicit nil

### UnsetCertificateId
`func (o *MyTrainingItem) UnsetCertificateId()`

UnsetCertificateId ensures that no value is present for CertificateId, not even an explicit nil
### GetCode

`func (o *MyTrainingItem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *MyTrainingItem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *MyTrainingItem) SetCode(v string)`

SetCode sets Code field to given value.


### GetDescription

`func (o *MyTrainingItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MyTrainingItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MyTrainingItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *MyTrainingItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *MyTrainingItem) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *MyTrainingItem) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDueDate

`func (o *MyTrainingItem) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *MyTrainingItem) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *MyTrainingItem) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *MyTrainingItem) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *MyTrainingItem) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *MyTrainingItem) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetLastScore

`func (o *MyTrainingItem) GetLastScore() int32`

GetLastScore returns the LastScore field if non-nil, zero value otherwise.

### GetLastScoreOk

`func (o *MyTrainingItem) GetLastScoreOk() (*int32, bool)`

GetLastScoreOk returns a tuple with the LastScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastScore

`func (o *MyTrainingItem) SetLastScore(v int32)`

SetLastScore sets LastScore field to given value.

### HasLastScore

`func (o *MyTrainingItem) HasLastScore() bool`

HasLastScore returns a boolean if a field has been set.

### SetLastScoreNil

`func (o *MyTrainingItem) SetLastScoreNil(b bool)`

 SetLastScoreNil sets the value for LastScore to be an explicit nil

### UnsetLastScore
`func (o *MyTrainingItem) UnsetLastScore()`

UnsetLastScore ensures that no value is present for LastScore, not even an explicit nil
### GetPassScore

`func (o *MyTrainingItem) GetPassScore() int32`

GetPassScore returns the PassScore field if non-nil, zero value otherwise.

### GetPassScoreOk

`func (o *MyTrainingItem) GetPassScoreOk() (*int32, bool)`

GetPassScoreOk returns a tuple with the PassScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassScore

`func (o *MyTrainingItem) SetPassScore(v int32)`

SetPassScore sets PassScore field to given value.


### GetPassed

`func (o *MyTrainingItem) GetPassed() bool`

GetPassed returns the Passed field if non-nil, zero value otherwise.

### GetPassedOk

`func (o *MyTrainingItem) GetPassedOk() (*bool, bool)`

GetPassedOk returns a tuple with the Passed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassed

`func (o *MyTrainingItem) SetPassed(v bool)`

SetPassed sets Passed field to given value.

### HasPassed

`func (o *MyTrainingItem) HasPassed() bool`

HasPassed returns a boolean if a field has been set.

### SetPassedNil

`func (o *MyTrainingItem) SetPassedNil(b bool)`

 SetPassedNil sets the value for Passed to be an explicit nil

### UnsetPassed
`func (o *MyTrainingItem) UnsetPassed()`

UnsetPassed ensures that no value is present for Passed, not even an explicit nil
### GetStatus

`func (o *MyTrainingItem) GetStatus() AssignmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MyTrainingItem) GetStatusOk() (*AssignmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MyTrainingItem) SetStatus(v AssignmentStatus)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *MyTrainingItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *MyTrainingItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *MyTrainingItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTrainingId

`func (o *MyTrainingItem) GetTrainingId() string`

GetTrainingId returns the TrainingId field if non-nil, zero value otherwise.

### GetTrainingIdOk

`func (o *MyTrainingItem) GetTrainingIdOk() (*string, bool)`

GetTrainingIdOk returns a tuple with the TrainingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrainingId

`func (o *MyTrainingItem) SetTrainingId(v string)`

SetTrainingId sets TrainingId field to given value.


### GetValidUntil

`func (o *MyTrainingItem) GetValidUntil() time.Time`

GetValidUntil returns the ValidUntil field if non-nil, zero value otherwise.

### GetValidUntilOk

`func (o *MyTrainingItem) GetValidUntilOk() (*time.Time, bool)`

GetValidUntilOk returns a tuple with the ValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidUntil

`func (o *MyTrainingItem) SetValidUntil(v time.Time)`

SetValidUntil sets ValidUntil field to given value.

### HasValidUntil

`func (o *MyTrainingItem) HasValidUntil() bool`

HasValidUntil returns a boolean if a field has been set.

### SetValidUntilNil

`func (o *MyTrainingItem) SetValidUntilNil(b bool)`

 SetValidUntilNil sets the value for ValidUntil to be an explicit nil

### UnsetValidUntil
`func (o *MyTrainingItem) UnsetValidUntil()`

UnsetValidUntil ensures that no value is present for ValidUntil, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


