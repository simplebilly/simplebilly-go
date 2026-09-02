# TrackOrderResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderNumber** | **string** |  | 
**OrderStatus** | **string** |  | 
**Shipments** | [**[]TrackedShipment**](TrackedShipment.md) |  | 

## Methods

### NewTrackOrderResponse

`func NewTrackOrderResponse(orderNumber string, orderStatus string, shipments []TrackedShipment, ) *TrackOrderResponse`

NewTrackOrderResponse instantiates a new TrackOrderResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackOrderResponseWithDefaults

`func NewTrackOrderResponseWithDefaults() *TrackOrderResponse`

NewTrackOrderResponseWithDefaults instantiates a new TrackOrderResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderNumber

`func (o *TrackOrderResponse) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *TrackOrderResponse) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *TrackOrderResponse) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetOrderStatus

`func (o *TrackOrderResponse) GetOrderStatus() string`

GetOrderStatus returns the OrderStatus field if non-nil, zero value otherwise.

### GetOrderStatusOk

`func (o *TrackOrderResponse) GetOrderStatusOk() (*string, bool)`

GetOrderStatusOk returns a tuple with the OrderStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderStatus

`func (o *TrackOrderResponse) SetOrderStatus(v string)`

SetOrderStatus sets OrderStatus field to given value.


### GetShipments

`func (o *TrackOrderResponse) GetShipments() []TrackedShipment`

GetShipments returns the Shipments field if non-nil, zero value otherwise.

### GetShipmentsOk

`func (o *TrackOrderResponse) GetShipmentsOk() (*[]TrackedShipment, bool)`

GetShipmentsOk returns a tuple with the Shipments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipments

`func (o *TrackOrderResponse) SetShipments(v []TrackedShipment)`

SetShipments sets Shipments field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


