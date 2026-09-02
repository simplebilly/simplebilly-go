# AiSuggestionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Instructions** | Pointer to **NullableString** |  | [optional] 
**MessageBody** | Pointer to **NullableString** |  | [optional] 
**TicketId** | **string** |  | 

## Methods

### NewAiSuggestionRequest

`func NewAiSuggestionRequest(ticketId string, ) *AiSuggestionRequest`

NewAiSuggestionRequest instantiates a new AiSuggestionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiSuggestionRequestWithDefaults

`func NewAiSuggestionRequestWithDefaults() *AiSuggestionRequest`

NewAiSuggestionRequestWithDefaults instantiates a new AiSuggestionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstructions

`func (o *AiSuggestionRequest) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *AiSuggestionRequest) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *AiSuggestionRequest) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *AiSuggestionRequest) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### SetInstructionsNil

`func (o *AiSuggestionRequest) SetInstructionsNil(b bool)`

 SetInstructionsNil sets the value for Instructions to be an explicit nil

### UnsetInstructions
`func (o *AiSuggestionRequest) UnsetInstructions()`

UnsetInstructions ensures that no value is present for Instructions, not even an explicit nil
### GetMessageBody

`func (o *AiSuggestionRequest) GetMessageBody() string`

GetMessageBody returns the MessageBody field if non-nil, zero value otherwise.

### GetMessageBodyOk

`func (o *AiSuggestionRequest) GetMessageBodyOk() (*string, bool)`

GetMessageBodyOk returns a tuple with the MessageBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageBody

`func (o *AiSuggestionRequest) SetMessageBody(v string)`

SetMessageBody sets MessageBody field to given value.

### HasMessageBody

`func (o *AiSuggestionRequest) HasMessageBody() bool`

HasMessageBody returns a boolean if a field has been set.

### SetMessageBodyNil

`func (o *AiSuggestionRequest) SetMessageBodyNil(b bool)`

 SetMessageBodyNil sets the value for MessageBody to be an explicit nil

### UnsetMessageBody
`func (o *AiSuggestionRequest) UnsetMessageBody()`

UnsetMessageBody ensures that no value is present for MessageBody, not even an explicit nil
### GetTicketId

`func (o *AiSuggestionRequest) GetTicketId() string`

GetTicketId returns the TicketId field if non-nil, zero value otherwise.

### GetTicketIdOk

`func (o *AiSuggestionRequest) GetTicketIdOk() (*string, bool)`

GetTicketIdOk returns a tuple with the TicketId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTicketId

`func (o *AiSuggestionRequest) SetTicketId(v string)`

SetTicketId sets TicketId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


