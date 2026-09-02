# TrainingContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Contact** | [**ContactInfo**](ContactInfo.md) |  | 
**PassScore** | **int32** |  | 
**Quiz** | [**[]QuizQuestion**](QuizQuestion.md) |  | 
**Sections** | [**[]Section**](Section.md) |  | 
**Title** | **string** |  | 
**TitleEn** | **string** |  | 

## Methods

### NewTrainingContent

`func NewTrainingContent(code string, contact ContactInfo, passScore int32, quiz []QuizQuestion, sections []Section, title string, titleEn string, ) *TrainingContent`

NewTrainingContent instantiates a new TrainingContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrainingContentWithDefaults

`func NewTrainingContentWithDefaults() *TrainingContent`

NewTrainingContentWithDefaults instantiates a new TrainingContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *TrainingContent) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TrainingContent) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TrainingContent) SetCode(v string)`

SetCode sets Code field to given value.


### GetContact

`func (o *TrainingContent) GetContact() ContactInfo`

GetContact returns the Contact field if non-nil, zero value otherwise.

### GetContactOk

`func (o *TrainingContent) GetContactOk() (*ContactInfo, bool)`

GetContactOk returns a tuple with the Contact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContact

`func (o *TrainingContent) SetContact(v ContactInfo)`

SetContact sets Contact field to given value.


### GetPassScore

`func (o *TrainingContent) GetPassScore() int32`

GetPassScore returns the PassScore field if non-nil, zero value otherwise.

### GetPassScoreOk

`func (o *TrainingContent) GetPassScoreOk() (*int32, bool)`

GetPassScoreOk returns a tuple with the PassScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassScore

`func (o *TrainingContent) SetPassScore(v int32)`

SetPassScore sets PassScore field to given value.


### GetQuiz

`func (o *TrainingContent) GetQuiz() []QuizQuestion`

GetQuiz returns the Quiz field if non-nil, zero value otherwise.

### GetQuizOk

`func (o *TrainingContent) GetQuizOk() (*[]QuizQuestion, bool)`

GetQuizOk returns a tuple with the Quiz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuiz

`func (o *TrainingContent) SetQuiz(v []QuizQuestion)`

SetQuiz sets Quiz field to given value.


### GetSections

`func (o *TrainingContent) GetSections() []Section`

GetSections returns the Sections field if non-nil, zero value otherwise.

### GetSectionsOk

`func (o *TrainingContent) GetSectionsOk() (*[]Section, bool)`

GetSectionsOk returns a tuple with the Sections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSections

`func (o *TrainingContent) SetSections(v []Section)`

SetSections sets Sections field to given value.


### GetTitle

`func (o *TrainingContent) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *TrainingContent) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *TrainingContent) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTitleEn

`func (o *TrainingContent) GetTitleEn() string`

GetTitleEn returns the TitleEn field if non-nil, zero value otherwise.

### GetTitleEnOk

`func (o *TrainingContent) GetTitleEnOk() (*string, bool)`

GetTitleEnOk returns a tuple with the TitleEn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitleEn

`func (o *TrainingContent) SetTitleEn(v string)`

SetTitleEn sets TitleEn field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


