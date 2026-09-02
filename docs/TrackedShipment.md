# TrackedShipment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | **string** |  | 
**Events** | [**[]TrackingEvent**](TrackingEvent.md) |  | 
**LabelUrl** | Pointer to **NullableString** |  | [optional] 
**Status** | **string** |  | 
**TrackingNumber** | Pointer to **NullableString** |  | [optional] 
**TrackingUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTrackedShipment

`func NewTrackedShipment(carrier string, events []TrackingEvent, status string, ) *TrackedShipment`

NewTrackedShipment instantiates a new TrackedShipment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackedShipmentWithDefaults

`func NewTrackedShipmentWithDefaults() *TrackedShipment`

NewTrackedShipmentWithDefaults instantiates a new TrackedShipment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *TrackedShipment) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *TrackedShipment) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *TrackedShipment) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.


### GetEvents

`func (o *TrackedShipment) GetEvents() []TrackingEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *TrackedShipment) GetEventsOk() (*[]TrackingEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *TrackedShipment) SetEvents(v []TrackingEvent)`

SetEvents sets Events field to given value.


### GetLabelUrl

`func (o *TrackedShipment) GetLabelUrl() string`

GetLabelUrl returns the LabelUrl field if non-nil, zero value otherwise.

### GetLabelUrlOk

`func (o *TrackedShipment) GetLabelUrlOk() (*string, bool)`

GetLabelUrlOk returns a tuple with the LabelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelUrl

`func (o *TrackedShipment) SetLabelUrl(v string)`

SetLabelUrl sets LabelUrl field to given value.

### HasLabelUrl

`func (o *TrackedShipment) HasLabelUrl() bool`

HasLabelUrl returns a boolean if a field has been set.

### SetLabelUrlNil

`func (o *TrackedShipment) SetLabelUrlNil(b bool)`

 SetLabelUrlNil sets the value for LabelUrl to be an explicit nil

### UnsetLabelUrl
`func (o *TrackedShipment) UnsetLabelUrl()`

UnsetLabelUrl ensures that no value is present for LabelUrl, not even an explicit nil
### GetStatus

`func (o *TrackedShipment) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TrackedShipment) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TrackedShipment) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTrackingNumber

`func (o *TrackedShipment) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *TrackedShipment) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *TrackedShipment) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *TrackedShipment) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### SetTrackingNumberNil

`func (o *TrackedShipment) SetTrackingNumberNil(b bool)`

 SetTrackingNumberNil sets the value for TrackingNumber to be an explicit nil

### UnsetTrackingNumber
`func (o *TrackedShipment) UnsetTrackingNumber()`

UnsetTrackingNumber ensures that no value is present for TrackingNumber, not even an explicit nil
### GetTrackingUrl

`func (o *TrackedShipment) GetTrackingUrl() string`

GetTrackingUrl returns the TrackingUrl field if non-nil, zero value otherwise.

### GetTrackingUrlOk

`func (o *TrackedShipment) GetTrackingUrlOk() (*string, bool)`

GetTrackingUrlOk returns a tuple with the TrackingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingUrl

`func (o *TrackedShipment) SetTrackingUrl(v string)`

SetTrackingUrl sets TrackingUrl field to given value.

### HasTrackingUrl

`func (o *TrackedShipment) HasTrackingUrl() bool`

HasTrackingUrl returns a boolean if a field has been set.

### SetTrackingUrlNil

`func (o *TrackedShipment) SetTrackingUrlNil(b bool)`

 SetTrackingUrlNil sets the value for TrackingUrl to be an explicit nil

### UnsetTrackingUrl
`func (o *TrackedShipment) UnsetTrackingUrl()`

UnsetTrackingUrl ensures that no value is present for TrackingUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


