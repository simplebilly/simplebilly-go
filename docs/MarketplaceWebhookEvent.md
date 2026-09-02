# MarketplaceWebhookEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionId** | **string** | References the marketplace connection entity. | 
**EventBody** | Pointer to **interface{}** |  | [optional] 
**EventType** | **string** |  | 
**Headers** | Pointer to **interface{}** |  | [optional] 
**Platform** | **string** |  | 
**Processed** | Pointer to **bool** |  | [optional] 
**ProcessingError** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewMarketplaceWebhookEvent

`func NewMarketplaceWebhookEvent(connectionId string, eventType string, platform string, ) *MarketplaceWebhookEvent`

NewMarketplaceWebhookEvent instantiates a new MarketplaceWebhookEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMarketplaceWebhookEventWithDefaults

`func NewMarketplaceWebhookEventWithDefaults() *MarketplaceWebhookEvent`

NewMarketplaceWebhookEventWithDefaults instantiates a new MarketplaceWebhookEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionId

`func (o *MarketplaceWebhookEvent) GetConnectionId() string`

GetConnectionId returns the ConnectionId field if non-nil, zero value otherwise.

### GetConnectionIdOk

`func (o *MarketplaceWebhookEvent) GetConnectionIdOk() (*string, bool)`

GetConnectionIdOk returns a tuple with the ConnectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionId

`func (o *MarketplaceWebhookEvent) SetConnectionId(v string)`

SetConnectionId sets ConnectionId field to given value.


### GetEventBody

`func (o *MarketplaceWebhookEvent) GetEventBody() interface{}`

GetEventBody returns the EventBody field if non-nil, zero value otherwise.

### GetEventBodyOk

`func (o *MarketplaceWebhookEvent) GetEventBodyOk() (*interface{}, bool)`

GetEventBodyOk returns a tuple with the EventBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventBody

`func (o *MarketplaceWebhookEvent) SetEventBody(v interface{})`

SetEventBody sets EventBody field to given value.

### HasEventBody

`func (o *MarketplaceWebhookEvent) HasEventBody() bool`

HasEventBody returns a boolean if a field has been set.

### SetEventBodyNil

`func (o *MarketplaceWebhookEvent) SetEventBodyNil(b bool)`

 SetEventBodyNil sets the value for EventBody to be an explicit nil

### UnsetEventBody
`func (o *MarketplaceWebhookEvent) UnsetEventBody()`

UnsetEventBody ensures that no value is present for EventBody, not even an explicit nil
### GetEventType

`func (o *MarketplaceWebhookEvent) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *MarketplaceWebhookEvent) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *MarketplaceWebhookEvent) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetHeaders

`func (o *MarketplaceWebhookEvent) GetHeaders() interface{}`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *MarketplaceWebhookEvent) GetHeadersOk() (*interface{}, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *MarketplaceWebhookEvent) SetHeaders(v interface{})`

SetHeaders sets Headers field to given value.

### HasHeaders

`func (o *MarketplaceWebhookEvent) HasHeaders() bool`

HasHeaders returns a boolean if a field has been set.

### SetHeadersNil

`func (o *MarketplaceWebhookEvent) SetHeadersNil(b bool)`

 SetHeadersNil sets the value for Headers to be an explicit nil

### UnsetHeaders
`func (o *MarketplaceWebhookEvent) UnsetHeaders()`

UnsetHeaders ensures that no value is present for Headers, not even an explicit nil
### GetPlatform

`func (o *MarketplaceWebhookEvent) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *MarketplaceWebhookEvent) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *MarketplaceWebhookEvent) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetProcessed

`func (o *MarketplaceWebhookEvent) GetProcessed() bool`

GetProcessed returns the Processed field if non-nil, zero value otherwise.

### GetProcessedOk

`func (o *MarketplaceWebhookEvent) GetProcessedOk() (*bool, bool)`

GetProcessedOk returns a tuple with the Processed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessed

`func (o *MarketplaceWebhookEvent) SetProcessed(v bool)`

SetProcessed sets Processed field to given value.

### HasProcessed

`func (o *MarketplaceWebhookEvent) HasProcessed() bool`

HasProcessed returns a boolean if a field has been set.

### GetProcessingError

`func (o *MarketplaceWebhookEvent) GetProcessingError() string`

GetProcessingError returns the ProcessingError field if non-nil, zero value otherwise.

### GetProcessingErrorOk

`func (o *MarketplaceWebhookEvent) GetProcessingErrorOk() (*string, bool)`

GetProcessingErrorOk returns a tuple with the ProcessingError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingError

`func (o *MarketplaceWebhookEvent) SetProcessingError(v string)`

SetProcessingError sets ProcessingError field to given value.

### HasProcessingError

`func (o *MarketplaceWebhookEvent) HasProcessingError() bool`

HasProcessingError returns a boolean if a field has been set.

### SetProcessingErrorNil

`func (o *MarketplaceWebhookEvent) SetProcessingErrorNil(b bool)`

 SetProcessingErrorNil sets the value for ProcessingError to be an explicit nil

### UnsetProcessingError
`func (o *MarketplaceWebhookEvent) UnsetProcessingError()`

UnsetProcessingError ensures that no value is present for ProcessingError, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


