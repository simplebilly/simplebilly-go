# SendMessageDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | **string** |  | 
**IsInternal** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewSendMessageDto

`func NewSendMessageDto(body string, ) *SendMessageDto`

NewSendMessageDto instantiates a new SendMessageDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendMessageDtoWithDefaults

`func NewSendMessageDtoWithDefaults() *SendMessageDto`

NewSendMessageDtoWithDefaults instantiates a new SendMessageDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *SendMessageDto) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SendMessageDto) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SendMessageDto) SetBody(v string)`

SetBody sets Body field to given value.


### GetIsInternal

`func (o *SendMessageDto) GetIsInternal() bool`

GetIsInternal returns the IsInternal field if non-nil, zero value otherwise.

### GetIsInternalOk

`func (o *SendMessageDto) GetIsInternalOk() (*bool, bool)`

GetIsInternalOk returns a tuple with the IsInternal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsInternal

`func (o *SendMessageDto) SetIsInternal(v bool)`

SetIsInternal sets IsInternal field to given value.

### HasIsInternal

`func (o *SendMessageDto) HasIsInternal() bool`

HasIsInternal returns a boolean if a field has been set.

### SetIsInternalNil

`func (o *SendMessageDto) SetIsInternalNil(b bool)`

 SetIsInternalNil sets the value for IsInternal to be an explicit nil

### UnsetIsInternal
`func (o *SendMessageDto) UnsetIsInternal()`

UnsetIsInternal ensures that no value is present for IsInternal, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


