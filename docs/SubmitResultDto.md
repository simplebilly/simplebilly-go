# SubmitResultDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Answers** | **[]int32** | Selected answer indices (required for scored builtin trainings). | 
**AssignmentId** | Pointer to **NullableString** |  | [optional] 
**Score** | **int32** | Score 0–100. Only trusted for plugin trainings without server-side scoring; builtin trainings are always re-scored from &#x60;answers&#x60;. | 
**TrainingCode** | **string** |  | 

## Methods

### NewSubmitResultDto

`func NewSubmitResultDto(answers []int32, score int32, trainingCode string, ) *SubmitResultDto`

NewSubmitResultDto instantiates a new SubmitResultDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubmitResultDtoWithDefaults

`func NewSubmitResultDtoWithDefaults() *SubmitResultDto`

NewSubmitResultDtoWithDefaults instantiates a new SubmitResultDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnswers

`func (o *SubmitResultDto) GetAnswers() []int32`

GetAnswers returns the Answers field if non-nil, zero value otherwise.

### GetAnswersOk

`func (o *SubmitResultDto) GetAnswersOk() (*[]int32, bool)`

GetAnswersOk returns a tuple with the Answers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswers

`func (o *SubmitResultDto) SetAnswers(v []int32)`

SetAnswers sets Answers field to given value.


### GetAssignmentId

`func (o *SubmitResultDto) GetAssignmentId() string`

GetAssignmentId returns the AssignmentId field if non-nil, zero value otherwise.

### GetAssignmentIdOk

`func (o *SubmitResultDto) GetAssignmentIdOk() (*string, bool)`

GetAssignmentIdOk returns a tuple with the AssignmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignmentId

`func (o *SubmitResultDto) SetAssignmentId(v string)`

SetAssignmentId sets AssignmentId field to given value.

### HasAssignmentId

`func (o *SubmitResultDto) HasAssignmentId() bool`

HasAssignmentId returns a boolean if a field has been set.

### SetAssignmentIdNil

`func (o *SubmitResultDto) SetAssignmentIdNil(b bool)`

 SetAssignmentIdNil sets the value for AssignmentId to be an explicit nil

### UnsetAssignmentId
`func (o *SubmitResultDto) UnsetAssignmentId()`

UnsetAssignmentId ensures that no value is present for AssignmentId, not even an explicit nil
### GetScore

`func (o *SubmitResultDto) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *SubmitResultDto) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *SubmitResultDto) SetScore(v int32)`

SetScore sets Score field to given value.


### GetTrainingCode

`func (o *SubmitResultDto) GetTrainingCode() string`

GetTrainingCode returns the TrainingCode field if non-nil, zero value otherwise.

### GetTrainingCodeOk

`func (o *SubmitResultDto) GetTrainingCodeOk() (*string, bool)`

GetTrainingCodeOk returns a tuple with the TrainingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrainingCode

`func (o *SubmitResultDto) SetTrainingCode(v string)`

SetTrainingCode sets TrainingCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


