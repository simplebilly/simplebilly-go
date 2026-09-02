# WebhookEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attempts** | Pointer to **int32** |  | [optional] 
**Channel** | Pointer to **string** | source for inbound, target URL for outbound. | [optional] 
**Direction** | [**WebhookDirection**](WebhookDirection.md) | inbound | outbound | 
**EventType** | **string** |  | 
**LastError** | Pointer to **NullableString** |  | [optional] 
**Payload** | Pointer to **interface{}** |  | [optional] 
**Status** | Pointer to [**WebhookEventStatus**](WebhookEventStatus.md) | accepted | delivered | failed | [optional] 

## Methods

### NewWebhookEvent

`func NewWebhookEvent(direction WebhookDirection, eventType string, ) *WebhookEvent`

NewWebhookEvent instantiates a new WebhookEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookEventWithDefaults

`func NewWebhookEventWithDefaults() *WebhookEvent`

NewWebhookEventWithDefaults instantiates a new WebhookEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttempts

`func (o *WebhookEvent) GetAttempts() int32`

GetAttempts returns the Attempts field if non-nil, zero value otherwise.

### GetAttemptsOk

`func (o *WebhookEvent) GetAttemptsOk() (*int32, bool)`

GetAttemptsOk returns a tuple with the Attempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempts

`func (o *WebhookEvent) SetAttempts(v int32)`

SetAttempts sets Attempts field to given value.

### HasAttempts

`func (o *WebhookEvent) HasAttempts() bool`

HasAttempts returns a boolean if a field has been set.

### GetChannel

`func (o *WebhookEvent) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *WebhookEvent) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *WebhookEvent) SetChannel(v string)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *WebhookEvent) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetDirection

`func (o *WebhookEvent) GetDirection() WebhookDirection`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *WebhookEvent) GetDirectionOk() (*WebhookDirection, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *WebhookEvent) SetDirection(v WebhookDirection)`

SetDirection sets Direction field to given value.


### GetEventType

`func (o *WebhookEvent) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *WebhookEvent) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *WebhookEvent) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetLastError

`func (o *WebhookEvent) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *WebhookEvent) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *WebhookEvent) SetLastError(v string)`

SetLastError sets LastError field to given value.

### HasLastError

`func (o *WebhookEvent) HasLastError() bool`

HasLastError returns a boolean if a field has been set.

### SetLastErrorNil

`func (o *WebhookEvent) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *WebhookEvent) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetPayload

`func (o *WebhookEvent) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *WebhookEvent) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *WebhookEvent) SetPayload(v interface{})`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *WebhookEvent) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *WebhookEvent) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *WebhookEvent) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetStatus

`func (o *WebhookEvent) GetStatus() WebhookEventStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookEvent) GetStatusOk() (*WebhookEventStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookEvent) SetStatus(v WebhookEventStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WebhookEvent) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


