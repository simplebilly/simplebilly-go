# AiConfigDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AutoReply** | Pointer to **NullableBool** |  | [optional] 
**MaxToolCalls** | Pointer to **NullableInt32** |  | [optional] 
**Model** | **string** |  | 
**Name** | **string** |  | 
**Provider** | **string** |  | 
**SystemPrompt** | Pointer to **NullableString** |  | [optional] 
**TriggerOn** | Pointer to **[]string** |  | [optional] 

## Methods

### NewAiConfigDto

`func NewAiConfigDto(model string, name string, provider string, ) *AiConfigDto`

NewAiConfigDto instantiates a new AiConfigDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiConfigDtoWithDefaults

`func NewAiConfigDtoWithDefaults() *AiConfigDto`

NewAiConfigDtoWithDefaults instantiates a new AiConfigDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAutoReply

`func (o *AiConfigDto) GetAutoReply() bool`

GetAutoReply returns the AutoReply field if non-nil, zero value otherwise.

### GetAutoReplyOk

`func (o *AiConfigDto) GetAutoReplyOk() (*bool, bool)`

GetAutoReplyOk returns a tuple with the AutoReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoReply

`func (o *AiConfigDto) SetAutoReply(v bool)`

SetAutoReply sets AutoReply field to given value.

### HasAutoReply

`func (o *AiConfigDto) HasAutoReply() bool`

HasAutoReply returns a boolean if a field has been set.

### SetAutoReplyNil

`func (o *AiConfigDto) SetAutoReplyNil(b bool)`

 SetAutoReplyNil sets the value for AutoReply to be an explicit nil

### UnsetAutoReply
`func (o *AiConfigDto) UnsetAutoReply()`

UnsetAutoReply ensures that no value is present for AutoReply, not even an explicit nil
### GetMaxToolCalls

`func (o *AiConfigDto) GetMaxToolCalls() int32`

GetMaxToolCalls returns the MaxToolCalls field if non-nil, zero value otherwise.

### GetMaxToolCallsOk

`func (o *AiConfigDto) GetMaxToolCallsOk() (*int32, bool)`

GetMaxToolCallsOk returns a tuple with the MaxToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxToolCalls

`func (o *AiConfigDto) SetMaxToolCalls(v int32)`

SetMaxToolCalls sets MaxToolCalls field to given value.

### HasMaxToolCalls

`func (o *AiConfigDto) HasMaxToolCalls() bool`

HasMaxToolCalls returns a boolean if a field has been set.

### SetMaxToolCallsNil

`func (o *AiConfigDto) SetMaxToolCallsNil(b bool)`

 SetMaxToolCallsNil sets the value for MaxToolCalls to be an explicit nil

### UnsetMaxToolCalls
`func (o *AiConfigDto) UnsetMaxToolCalls()`

UnsetMaxToolCalls ensures that no value is present for MaxToolCalls, not even an explicit nil
### GetModel

`func (o *AiConfigDto) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiConfigDto) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiConfigDto) SetModel(v string)`

SetModel sets Model field to given value.


### GetName

`func (o *AiConfigDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiConfigDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiConfigDto) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *AiConfigDto) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AiConfigDto) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AiConfigDto) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetSystemPrompt

`func (o *AiConfigDto) GetSystemPrompt() string`

GetSystemPrompt returns the SystemPrompt field if non-nil, zero value otherwise.

### GetSystemPromptOk

`func (o *AiConfigDto) GetSystemPromptOk() (*string, bool)`

GetSystemPromptOk returns a tuple with the SystemPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemPrompt

`func (o *AiConfigDto) SetSystemPrompt(v string)`

SetSystemPrompt sets SystemPrompt field to given value.

### HasSystemPrompt

`func (o *AiConfigDto) HasSystemPrompt() bool`

HasSystemPrompt returns a boolean if a field has been set.

### SetSystemPromptNil

`func (o *AiConfigDto) SetSystemPromptNil(b bool)`

 SetSystemPromptNil sets the value for SystemPrompt to be an explicit nil

### UnsetSystemPrompt
`func (o *AiConfigDto) UnsetSystemPrompt()`

UnsetSystemPrompt ensures that no value is present for SystemPrompt, not even an explicit nil
### GetTriggerOn

`func (o *AiConfigDto) GetTriggerOn() []string`

GetTriggerOn returns the TriggerOn field if non-nil, zero value otherwise.

### GetTriggerOnOk

`func (o *AiConfigDto) GetTriggerOnOk() (*[]string, bool)`

GetTriggerOnOk returns a tuple with the TriggerOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerOn

`func (o *AiConfigDto) SetTriggerOn(v []string)`

SetTriggerOn sets TriggerOn field to given value.

### HasTriggerOn

`func (o *AiConfigDto) HasTriggerOn() bool`

HasTriggerOn returns a boolean if a field has been set.

### SetTriggerOnNil

`func (o *AiConfigDto) SetTriggerOnNil(b bool)`

 SetTriggerOnNil sets the value for TriggerOn to be an explicit nil

### UnsetTriggerOn
`func (o *AiConfigDto) UnsetTriggerOn()`

UnsetTriggerOn ensures that no value is present for TriggerOn, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


