# AiSuggestion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Confidence** | **float64** |  | 
**Reasoning** | **string** |  | 
**SuggestedPriority** | Pointer to **NullableString** |  | [optional] 
**SuggestedReply** | **string** |  | 
**SuggestedStatus** | Pointer to **NullableString** |  | [optional] 
**ToolCalls** | **[]string** |  | 

## Methods

### NewAiSuggestion

`func NewAiSuggestion(confidence float64, reasoning string, suggestedReply string, toolCalls []string, ) *AiSuggestion`

NewAiSuggestion instantiates a new AiSuggestion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiSuggestionWithDefaults

`func NewAiSuggestionWithDefaults() *AiSuggestion`

NewAiSuggestionWithDefaults instantiates a new AiSuggestion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfidence

`func (o *AiSuggestion) GetConfidence() float64`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *AiSuggestion) GetConfidenceOk() (*float64, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *AiSuggestion) SetConfidence(v float64)`

SetConfidence sets Confidence field to given value.


### GetReasoning

`func (o *AiSuggestion) GetReasoning() string`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *AiSuggestion) GetReasoningOk() (*string, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *AiSuggestion) SetReasoning(v string)`

SetReasoning sets Reasoning field to given value.


### GetSuggestedPriority

`func (o *AiSuggestion) GetSuggestedPriority() string`

GetSuggestedPriority returns the SuggestedPriority field if non-nil, zero value otherwise.

### GetSuggestedPriorityOk

`func (o *AiSuggestion) GetSuggestedPriorityOk() (*string, bool)`

GetSuggestedPriorityOk returns a tuple with the SuggestedPriority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedPriority

`func (o *AiSuggestion) SetSuggestedPriority(v string)`

SetSuggestedPriority sets SuggestedPriority field to given value.

### HasSuggestedPriority

`func (o *AiSuggestion) HasSuggestedPriority() bool`

HasSuggestedPriority returns a boolean if a field has been set.

### SetSuggestedPriorityNil

`func (o *AiSuggestion) SetSuggestedPriorityNil(b bool)`

 SetSuggestedPriorityNil sets the value for SuggestedPriority to be an explicit nil

### UnsetSuggestedPriority
`func (o *AiSuggestion) UnsetSuggestedPriority()`

UnsetSuggestedPriority ensures that no value is present for SuggestedPriority, not even an explicit nil
### GetSuggestedReply

`func (o *AiSuggestion) GetSuggestedReply() string`

GetSuggestedReply returns the SuggestedReply field if non-nil, zero value otherwise.

### GetSuggestedReplyOk

`func (o *AiSuggestion) GetSuggestedReplyOk() (*string, bool)`

GetSuggestedReplyOk returns a tuple with the SuggestedReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedReply

`func (o *AiSuggestion) SetSuggestedReply(v string)`

SetSuggestedReply sets SuggestedReply field to given value.


### GetSuggestedStatus

`func (o *AiSuggestion) GetSuggestedStatus() string`

GetSuggestedStatus returns the SuggestedStatus field if non-nil, zero value otherwise.

### GetSuggestedStatusOk

`func (o *AiSuggestion) GetSuggestedStatusOk() (*string, bool)`

GetSuggestedStatusOk returns a tuple with the SuggestedStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedStatus

`func (o *AiSuggestion) SetSuggestedStatus(v string)`

SetSuggestedStatus sets SuggestedStatus field to given value.

### HasSuggestedStatus

`func (o *AiSuggestion) HasSuggestedStatus() bool`

HasSuggestedStatus returns a boolean if a field has been set.

### SetSuggestedStatusNil

`func (o *AiSuggestion) SetSuggestedStatusNil(b bool)`

 SetSuggestedStatusNil sets the value for SuggestedStatus to be an explicit nil

### UnsetSuggestedStatus
`func (o *AiSuggestion) UnsetSuggestedStatus()`

UnsetSuggestedStatus ensures that no value is present for SuggestedStatus, not even an explicit nil
### GetToolCalls

`func (o *AiSuggestion) GetToolCalls() []string`

GetToolCalls returns the ToolCalls field if non-nil, zero value otherwise.

### GetToolCallsOk

`func (o *AiSuggestion) GetToolCallsOk() (*[]string, bool)`

GetToolCallsOk returns a tuple with the ToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCalls

`func (o *AiSuggestion) SetToolCalls(v []string)`

SetToolCalls sets ToolCalls field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


