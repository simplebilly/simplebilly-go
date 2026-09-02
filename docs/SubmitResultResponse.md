# SubmitResultResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertificateId** | Pointer to **NullableString** |  | [optional] 
**CompletionId** | **string** |  | 
**PassScore** | **int32** |  | 
**Passed** | **bool** |  | 
**Score** | **int32** |  | 
**ValidUntil** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewSubmitResultResponse

`func NewSubmitResultResponse(completionId string, passScore int32, passed bool, score int32, ) *SubmitResultResponse`

NewSubmitResultResponse instantiates a new SubmitResultResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubmitResultResponseWithDefaults

`func NewSubmitResultResponseWithDefaults() *SubmitResultResponse`

NewSubmitResultResponseWithDefaults instantiates a new SubmitResultResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificateId

`func (o *SubmitResultResponse) GetCertificateId() string`

GetCertificateId returns the CertificateId field if non-nil, zero value otherwise.

### GetCertificateIdOk

`func (o *SubmitResultResponse) GetCertificateIdOk() (*string, bool)`

GetCertificateIdOk returns a tuple with the CertificateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateId

`func (o *SubmitResultResponse) SetCertificateId(v string)`

SetCertificateId sets CertificateId field to given value.

### HasCertificateId

`func (o *SubmitResultResponse) HasCertificateId() bool`

HasCertificateId returns a boolean if a field has been set.

### SetCertificateIdNil

`func (o *SubmitResultResponse) SetCertificateIdNil(b bool)`

 SetCertificateIdNil sets the value for CertificateId to be an explicit nil

### UnsetCertificateId
`func (o *SubmitResultResponse) UnsetCertificateId()`

UnsetCertificateId ensures that no value is present for CertificateId, not even an explicit nil
### GetCompletionId

`func (o *SubmitResultResponse) GetCompletionId() string`

GetCompletionId returns the CompletionId field if non-nil, zero value otherwise.

### GetCompletionIdOk

`func (o *SubmitResultResponse) GetCompletionIdOk() (*string, bool)`

GetCompletionIdOk returns a tuple with the CompletionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletionId

`func (o *SubmitResultResponse) SetCompletionId(v string)`

SetCompletionId sets CompletionId field to given value.


### GetPassScore

`func (o *SubmitResultResponse) GetPassScore() int32`

GetPassScore returns the PassScore field if non-nil, zero value otherwise.

### GetPassScoreOk

`func (o *SubmitResultResponse) GetPassScoreOk() (*int32, bool)`

GetPassScoreOk returns a tuple with the PassScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassScore

`func (o *SubmitResultResponse) SetPassScore(v int32)`

SetPassScore sets PassScore field to given value.


### GetPassed

`func (o *SubmitResultResponse) GetPassed() bool`

GetPassed returns the Passed field if non-nil, zero value otherwise.

### GetPassedOk

`func (o *SubmitResultResponse) GetPassedOk() (*bool, bool)`

GetPassedOk returns a tuple with the Passed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassed

`func (o *SubmitResultResponse) SetPassed(v bool)`

SetPassed sets Passed field to given value.


### GetScore

`func (o *SubmitResultResponse) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *SubmitResultResponse) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *SubmitResultResponse) SetScore(v int32)`

SetScore sets Score field to given value.


### GetValidUntil

`func (o *SubmitResultResponse) GetValidUntil() time.Time`

GetValidUntil returns the ValidUntil field if non-nil, zero value otherwise.

### GetValidUntilOk

`func (o *SubmitResultResponse) GetValidUntilOk() (*time.Time, bool)`

GetValidUntilOk returns a tuple with the ValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidUntil

`func (o *SubmitResultResponse) SetValidUntil(v time.Time)`

SetValidUntil sets ValidUntil field to given value.

### HasValidUntil

`func (o *SubmitResultResponse) HasValidUntil() bool`

HasValidUntil returns a boolean if a field has been set.

### SetValidUntilNil

`func (o *SubmitResultResponse) SetValidUntilNil(b bool)`

 SetValidUntilNil sets the value for ValidUntil to be an explicit nil

### UnsetValidUntil
`func (o *SubmitResultResponse) UnsetValidUntil()`

UnsetValidUntil ensures that no value is present for ValidUntil, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


