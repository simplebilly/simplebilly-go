# TrackingInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | **string** |  | 
**EstimatedDelivery** | Pointer to **NullableString** |  | [optional] 
**Events** | [**[]TrackingEvent**](TrackingEvent.md) |  | 
**RawResponse** | Pointer to **interface{}** |  | [optional] 
**Status** | **string** |  | 
**TrackingNumber** | **string** |  | 

## Methods

### NewTrackingInfo

`func NewTrackingInfo(carrier string, events []TrackingEvent, status string, trackingNumber string, ) *TrackingInfo`

NewTrackingInfo instantiates a new TrackingInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingInfoWithDefaults

`func NewTrackingInfoWithDefaults() *TrackingInfo`

NewTrackingInfoWithDefaults instantiates a new TrackingInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *TrackingInfo) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *TrackingInfo) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *TrackingInfo) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.


### GetEstimatedDelivery

`func (o *TrackingInfo) GetEstimatedDelivery() string`

GetEstimatedDelivery returns the EstimatedDelivery field if non-nil, zero value otherwise.

### GetEstimatedDeliveryOk

`func (o *TrackingInfo) GetEstimatedDeliveryOk() (*string, bool)`

GetEstimatedDeliveryOk returns a tuple with the EstimatedDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedDelivery

`func (o *TrackingInfo) SetEstimatedDelivery(v string)`

SetEstimatedDelivery sets EstimatedDelivery field to given value.

### HasEstimatedDelivery

`func (o *TrackingInfo) HasEstimatedDelivery() bool`

HasEstimatedDelivery returns a boolean if a field has been set.

### SetEstimatedDeliveryNil

`func (o *TrackingInfo) SetEstimatedDeliveryNil(b bool)`

 SetEstimatedDeliveryNil sets the value for EstimatedDelivery to be an explicit nil

### UnsetEstimatedDelivery
`func (o *TrackingInfo) UnsetEstimatedDelivery()`

UnsetEstimatedDelivery ensures that no value is present for EstimatedDelivery, not even an explicit nil
### GetEvents

`func (o *TrackingInfo) GetEvents() []TrackingEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *TrackingInfo) GetEventsOk() (*[]TrackingEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *TrackingInfo) SetEvents(v []TrackingEvent)`

SetEvents sets Events field to given value.


### GetRawResponse

`func (o *TrackingInfo) GetRawResponse() interface{}`

GetRawResponse returns the RawResponse field if non-nil, zero value otherwise.

### GetRawResponseOk

`func (o *TrackingInfo) GetRawResponseOk() (*interface{}, bool)`

GetRawResponseOk returns a tuple with the RawResponse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawResponse

`func (o *TrackingInfo) SetRawResponse(v interface{})`

SetRawResponse sets RawResponse field to given value.

### HasRawResponse

`func (o *TrackingInfo) HasRawResponse() bool`

HasRawResponse returns a boolean if a field has been set.

### SetRawResponseNil

`func (o *TrackingInfo) SetRawResponseNil(b bool)`

 SetRawResponseNil sets the value for RawResponse to be an explicit nil

### UnsetRawResponse
`func (o *TrackingInfo) UnsetRawResponse()`

UnsetRawResponse ensures that no value is present for RawResponse, not even an explicit nil
### GetStatus

`func (o *TrackingInfo) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TrackingInfo) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TrackingInfo) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTrackingNumber

`func (o *TrackingInfo) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *TrackingInfo) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *TrackingInfo) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


