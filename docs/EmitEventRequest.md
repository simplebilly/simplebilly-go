# EmitEventRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventType** | **string** |  | 
**Payload** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewEmitEventRequest

`func NewEmitEventRequest(eventType string, ) *EmitEventRequest`

NewEmitEventRequest instantiates a new EmitEventRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmitEventRequestWithDefaults

`func NewEmitEventRequestWithDefaults() *EmitEventRequest`

NewEmitEventRequestWithDefaults instantiates a new EmitEventRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventType

`func (o *EmitEventRequest) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *EmitEventRequest) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *EmitEventRequest) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetPayload

`func (o *EmitEventRequest) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *EmitEventRequest) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *EmitEventRequest) SetPayload(v interface{})`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *EmitEventRequest) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *EmitEventRequest) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *EmitEventRequest) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


