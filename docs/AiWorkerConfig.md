# AiWorkerConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AutoReply** | **bool** |  | 
**CreatedAt** | **time.Time** |  | 
**Id** | **string** |  | 
**IsActive** | **bool** |  | 
**MaxToolCalls** | **int32** |  | 
**Model** | **string** |  | 
**Name** | **string** |  | 
**Provider** | **string** |  | 
**SystemPrompt** | **string** |  | 
**TenantId** | **string** |  | 
**TriggerOn** | **[]string** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewAiWorkerConfig

`func NewAiWorkerConfig(autoReply bool, createdAt time.Time, id string, isActive bool, maxToolCalls int32, model string, name string, provider string, systemPrompt string, tenantId string, triggerOn []string, ) *AiWorkerConfig`

NewAiWorkerConfig instantiates a new AiWorkerConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiWorkerConfigWithDefaults

`func NewAiWorkerConfigWithDefaults() *AiWorkerConfig`

NewAiWorkerConfigWithDefaults instantiates a new AiWorkerConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAutoReply

`func (o *AiWorkerConfig) GetAutoReply() bool`

GetAutoReply returns the AutoReply field if non-nil, zero value otherwise.

### GetAutoReplyOk

`func (o *AiWorkerConfig) GetAutoReplyOk() (*bool, bool)`

GetAutoReplyOk returns a tuple with the AutoReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoReply

`func (o *AiWorkerConfig) SetAutoReply(v bool)`

SetAutoReply sets AutoReply field to given value.


### GetCreatedAt

`func (o *AiWorkerConfig) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AiWorkerConfig) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AiWorkerConfig) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *AiWorkerConfig) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiWorkerConfig) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiWorkerConfig) SetId(v string)`

SetId sets Id field to given value.


### GetIsActive

`func (o *AiWorkerConfig) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *AiWorkerConfig) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *AiWorkerConfig) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetMaxToolCalls

`func (o *AiWorkerConfig) GetMaxToolCalls() int32`

GetMaxToolCalls returns the MaxToolCalls field if non-nil, zero value otherwise.

### GetMaxToolCallsOk

`func (o *AiWorkerConfig) GetMaxToolCallsOk() (*int32, bool)`

GetMaxToolCallsOk returns a tuple with the MaxToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxToolCalls

`func (o *AiWorkerConfig) SetMaxToolCalls(v int32)`

SetMaxToolCalls sets MaxToolCalls field to given value.


### GetModel

`func (o *AiWorkerConfig) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiWorkerConfig) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiWorkerConfig) SetModel(v string)`

SetModel sets Model field to given value.


### GetName

`func (o *AiWorkerConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiWorkerConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiWorkerConfig) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *AiWorkerConfig) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AiWorkerConfig) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AiWorkerConfig) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetSystemPrompt

`func (o *AiWorkerConfig) GetSystemPrompt() string`

GetSystemPrompt returns the SystemPrompt field if non-nil, zero value otherwise.

### GetSystemPromptOk

`func (o *AiWorkerConfig) GetSystemPromptOk() (*string, bool)`

GetSystemPromptOk returns a tuple with the SystemPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemPrompt

`func (o *AiWorkerConfig) SetSystemPrompt(v string)`

SetSystemPrompt sets SystemPrompt field to given value.


### GetTenantId

`func (o *AiWorkerConfig) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *AiWorkerConfig) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *AiWorkerConfig) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetTriggerOn

`func (o *AiWorkerConfig) GetTriggerOn() []string`

GetTriggerOn returns the TriggerOn field if non-nil, zero value otherwise.

### GetTriggerOnOk

`func (o *AiWorkerConfig) GetTriggerOnOk() (*[]string, bool)`

GetTriggerOnOk returns a tuple with the TriggerOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerOn

`func (o *AiWorkerConfig) SetTriggerOn(v []string)`

SetTriggerOn sets TriggerOn field to given value.


### GetUpdatedAt

`func (o *AiWorkerConfig) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AiWorkerConfig) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AiWorkerConfig) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *AiWorkerConfig) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *AiWorkerConfig) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *AiWorkerConfig) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


