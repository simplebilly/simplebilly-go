# JobApplication

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CvFile** | Pointer to **NullableString** | Relative path of the stored CV file under the upload dir. | [optional] 
**CvText** | Pointer to **NullableString** | Extracted CV text, used for match-scoring. | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**MatchReason** | Pointer to **NullableString** |  | [optional] 
**MatchScore** | Pointer to **NullableInt32** | 0-100 LLM match score against the posting&#39;s required profile. | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**PostingId** | Pointer to **NullableString** | References the job_posting entity. | [optional] 
**Source** | **string** | website | email | board | 
**Status** | [**ApplicationStatus**](ApplicationStatus.md) | new | reviewing | interview | hired | rejected | 

## Methods

### NewJobApplication

`func NewJobApplication(source string, status ApplicationStatus, ) *JobApplication`

NewJobApplication instantiates a new JobApplication object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobApplicationWithDefaults

`func NewJobApplicationWithDefaults() *JobApplication`

NewJobApplicationWithDefaults instantiates a new JobApplication object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCvFile

`func (o *JobApplication) GetCvFile() string`

GetCvFile returns the CvFile field if non-nil, zero value otherwise.

### GetCvFileOk

`func (o *JobApplication) GetCvFileOk() (*string, bool)`

GetCvFileOk returns a tuple with the CvFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCvFile

`func (o *JobApplication) SetCvFile(v string)`

SetCvFile sets CvFile field to given value.

### HasCvFile

`func (o *JobApplication) HasCvFile() bool`

HasCvFile returns a boolean if a field has been set.

### SetCvFileNil

`func (o *JobApplication) SetCvFileNil(b bool)`

 SetCvFileNil sets the value for CvFile to be an explicit nil

### UnsetCvFile
`func (o *JobApplication) UnsetCvFile()`

UnsetCvFile ensures that no value is present for CvFile, not even an explicit nil
### GetCvText

`func (o *JobApplication) GetCvText() string`

GetCvText returns the CvText field if non-nil, zero value otherwise.

### GetCvTextOk

`func (o *JobApplication) GetCvTextOk() (*string, bool)`

GetCvTextOk returns a tuple with the CvText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCvText

`func (o *JobApplication) SetCvText(v string)`

SetCvText sets CvText field to given value.

### HasCvText

`func (o *JobApplication) HasCvText() bool`

HasCvText returns a boolean if a field has been set.

### SetCvTextNil

`func (o *JobApplication) SetCvTextNil(b bool)`

 SetCvTextNil sets the value for CvText to be an explicit nil

### UnsetCvText
`func (o *JobApplication) UnsetCvText()`

UnsetCvText ensures that no value is present for CvText, not even an explicit nil
### GetEmail

`func (o *JobApplication) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *JobApplication) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *JobApplication) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *JobApplication) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *JobApplication) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *JobApplication) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetMatchReason

`func (o *JobApplication) GetMatchReason() string`

GetMatchReason returns the MatchReason field if non-nil, zero value otherwise.

### GetMatchReasonOk

`func (o *JobApplication) GetMatchReasonOk() (*string, bool)`

GetMatchReasonOk returns a tuple with the MatchReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchReason

`func (o *JobApplication) SetMatchReason(v string)`

SetMatchReason sets MatchReason field to given value.

### HasMatchReason

`func (o *JobApplication) HasMatchReason() bool`

HasMatchReason returns a boolean if a field has been set.

### SetMatchReasonNil

`func (o *JobApplication) SetMatchReasonNil(b bool)`

 SetMatchReasonNil sets the value for MatchReason to be an explicit nil

### UnsetMatchReason
`func (o *JobApplication) UnsetMatchReason()`

UnsetMatchReason ensures that no value is present for MatchReason, not even an explicit nil
### GetMatchScore

`func (o *JobApplication) GetMatchScore() int32`

GetMatchScore returns the MatchScore field if non-nil, zero value otherwise.

### GetMatchScoreOk

`func (o *JobApplication) GetMatchScoreOk() (*int32, bool)`

GetMatchScoreOk returns a tuple with the MatchScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchScore

`func (o *JobApplication) SetMatchScore(v int32)`

SetMatchScore sets MatchScore field to given value.

### HasMatchScore

`func (o *JobApplication) HasMatchScore() bool`

HasMatchScore returns a boolean if a field has been set.

### SetMatchScoreNil

`func (o *JobApplication) SetMatchScoreNil(b bool)`

 SetMatchScoreNil sets the value for MatchScore to be an explicit nil

### UnsetMatchScore
`func (o *JobApplication) UnsetMatchScore()`

UnsetMatchScore ensures that no value is present for MatchScore, not even an explicit nil
### GetName

`func (o *JobApplication) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *JobApplication) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *JobApplication) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *JobApplication) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *JobApplication) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *JobApplication) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetPhone

`func (o *JobApplication) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *JobApplication) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *JobApplication) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *JobApplication) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *JobApplication) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *JobApplication) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetPostingId

`func (o *JobApplication) GetPostingId() string`

GetPostingId returns the PostingId field if non-nil, zero value otherwise.

### GetPostingIdOk

`func (o *JobApplication) GetPostingIdOk() (*string, bool)`

GetPostingIdOk returns a tuple with the PostingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostingId

`func (o *JobApplication) SetPostingId(v string)`

SetPostingId sets PostingId field to given value.

### HasPostingId

`func (o *JobApplication) HasPostingId() bool`

HasPostingId returns a boolean if a field has been set.

### SetPostingIdNil

`func (o *JobApplication) SetPostingIdNil(b bool)`

 SetPostingIdNil sets the value for PostingId to be an explicit nil

### UnsetPostingId
`func (o *JobApplication) UnsetPostingId()`

UnsetPostingId ensures that no value is present for PostingId, not even an explicit nil
### GetSource

`func (o *JobApplication) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *JobApplication) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *JobApplication) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *JobApplication) GetStatus() ApplicationStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JobApplication) GetStatusOk() (*ApplicationStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JobApplication) SetStatus(v ApplicationStatus)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


