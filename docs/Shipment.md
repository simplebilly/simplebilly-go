# Shipment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveredAt** | Pointer to **NullableTime** |  | [optional] 
**LabelUrl** | Pointer to **NullableString** |  | [optional] 
**LineItemsShipment** | Pointer to **interface{}** |  | [optional] 
**OrderId** | **string** | References the order entity. | 
**RecipientAddress** | Pointer to **interface{}** |  | [optional] 
**ShipmentDate** | **string** |  | 
**ShippingCarrier** | **string** |  | 
**ShippingCost** | Pointer to **NullableString** |  | [optional] 
**ShippingMethod** | Pointer to **NullableString** |  | [optional] 
**SignedBy** | Pointer to **NullableString** |  | [optional] 
**Status** | **string** |  | 
**TrackingEvents** | Pointer to **interface{}** | Latest carrier tracking events (from the live tracking API). | [optional] 
**TrackingNumber** | Pointer to **NullableString** |  | [optional] 
**TrackingUrl** | Pointer to **NullableString** |  | [optional] 
**WeightKg** | Pointer to **NullableFloat64** |  | [optional] 

## Methods

### NewShipment

`func NewShipment(orderId string, shipmentDate string, shippingCarrier string, status string, ) *Shipment`

NewShipment instantiates a new Shipment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShipmentWithDefaults

`func NewShipmentWithDefaults() *Shipment`

NewShipmentWithDefaults instantiates a new Shipment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveredAt

`func (o *Shipment) GetDeliveredAt() time.Time`

GetDeliveredAt returns the DeliveredAt field if non-nil, zero value otherwise.

### GetDeliveredAtOk

`func (o *Shipment) GetDeliveredAtOk() (*time.Time, bool)`

GetDeliveredAtOk returns a tuple with the DeliveredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveredAt

`func (o *Shipment) SetDeliveredAt(v time.Time)`

SetDeliveredAt sets DeliveredAt field to given value.

### HasDeliveredAt

`func (o *Shipment) HasDeliveredAt() bool`

HasDeliveredAt returns a boolean if a field has been set.

### SetDeliveredAtNil

`func (o *Shipment) SetDeliveredAtNil(b bool)`

 SetDeliveredAtNil sets the value for DeliveredAt to be an explicit nil

### UnsetDeliveredAt
`func (o *Shipment) UnsetDeliveredAt()`

UnsetDeliveredAt ensures that no value is present for DeliveredAt, not even an explicit nil
### GetLabelUrl

`func (o *Shipment) GetLabelUrl() string`

GetLabelUrl returns the LabelUrl field if non-nil, zero value otherwise.

### GetLabelUrlOk

`func (o *Shipment) GetLabelUrlOk() (*string, bool)`

GetLabelUrlOk returns a tuple with the LabelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelUrl

`func (o *Shipment) SetLabelUrl(v string)`

SetLabelUrl sets LabelUrl field to given value.

### HasLabelUrl

`func (o *Shipment) HasLabelUrl() bool`

HasLabelUrl returns a boolean if a field has been set.

### SetLabelUrlNil

`func (o *Shipment) SetLabelUrlNil(b bool)`

 SetLabelUrlNil sets the value for LabelUrl to be an explicit nil

### UnsetLabelUrl
`func (o *Shipment) UnsetLabelUrl()`

UnsetLabelUrl ensures that no value is present for LabelUrl, not even an explicit nil
### GetLineItemsShipment

`func (o *Shipment) GetLineItemsShipment() interface{}`

GetLineItemsShipment returns the LineItemsShipment field if non-nil, zero value otherwise.

### GetLineItemsShipmentOk

`func (o *Shipment) GetLineItemsShipmentOk() (*interface{}, bool)`

GetLineItemsShipmentOk returns a tuple with the LineItemsShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemsShipment

`func (o *Shipment) SetLineItemsShipment(v interface{})`

SetLineItemsShipment sets LineItemsShipment field to given value.

### HasLineItemsShipment

`func (o *Shipment) HasLineItemsShipment() bool`

HasLineItemsShipment returns a boolean if a field has been set.

### SetLineItemsShipmentNil

`func (o *Shipment) SetLineItemsShipmentNil(b bool)`

 SetLineItemsShipmentNil sets the value for LineItemsShipment to be an explicit nil

### UnsetLineItemsShipment
`func (o *Shipment) UnsetLineItemsShipment()`

UnsetLineItemsShipment ensures that no value is present for LineItemsShipment, not even an explicit nil
### GetOrderId

`func (o *Shipment) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *Shipment) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *Shipment) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.


### GetRecipientAddress

`func (o *Shipment) GetRecipientAddress() interface{}`

GetRecipientAddress returns the RecipientAddress field if non-nil, zero value otherwise.

### GetRecipientAddressOk

`func (o *Shipment) GetRecipientAddressOk() (*interface{}, bool)`

GetRecipientAddressOk returns a tuple with the RecipientAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientAddress

`func (o *Shipment) SetRecipientAddress(v interface{})`

SetRecipientAddress sets RecipientAddress field to given value.

### HasRecipientAddress

`func (o *Shipment) HasRecipientAddress() bool`

HasRecipientAddress returns a boolean if a field has been set.

### SetRecipientAddressNil

`func (o *Shipment) SetRecipientAddressNil(b bool)`

 SetRecipientAddressNil sets the value for RecipientAddress to be an explicit nil

### UnsetRecipientAddress
`func (o *Shipment) UnsetRecipientAddress()`

UnsetRecipientAddress ensures that no value is present for RecipientAddress, not even an explicit nil
### GetShipmentDate

`func (o *Shipment) GetShipmentDate() string`

GetShipmentDate returns the ShipmentDate field if non-nil, zero value otherwise.

### GetShipmentDateOk

`func (o *Shipment) GetShipmentDateOk() (*string, bool)`

GetShipmentDateOk returns a tuple with the ShipmentDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentDate

`func (o *Shipment) SetShipmentDate(v string)`

SetShipmentDate sets ShipmentDate field to given value.


### GetShippingCarrier

`func (o *Shipment) GetShippingCarrier() string`

GetShippingCarrier returns the ShippingCarrier field if non-nil, zero value otherwise.

### GetShippingCarrierOk

`func (o *Shipment) GetShippingCarrierOk() (*string, bool)`

GetShippingCarrierOk returns a tuple with the ShippingCarrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingCarrier

`func (o *Shipment) SetShippingCarrier(v string)`

SetShippingCarrier sets ShippingCarrier field to given value.


### GetShippingCost

`func (o *Shipment) GetShippingCost() string`

GetShippingCost returns the ShippingCost field if non-nil, zero value otherwise.

### GetShippingCostOk

`func (o *Shipment) GetShippingCostOk() (*string, bool)`

GetShippingCostOk returns a tuple with the ShippingCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingCost

`func (o *Shipment) SetShippingCost(v string)`

SetShippingCost sets ShippingCost field to given value.

### HasShippingCost

`func (o *Shipment) HasShippingCost() bool`

HasShippingCost returns a boolean if a field has been set.

### SetShippingCostNil

`func (o *Shipment) SetShippingCostNil(b bool)`

 SetShippingCostNil sets the value for ShippingCost to be an explicit nil

### UnsetShippingCost
`func (o *Shipment) UnsetShippingCost()`

UnsetShippingCost ensures that no value is present for ShippingCost, not even an explicit nil
### GetShippingMethod

`func (o *Shipment) GetShippingMethod() string`

GetShippingMethod returns the ShippingMethod field if non-nil, zero value otherwise.

### GetShippingMethodOk

`func (o *Shipment) GetShippingMethodOk() (*string, bool)`

GetShippingMethodOk returns a tuple with the ShippingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethod

`func (o *Shipment) SetShippingMethod(v string)`

SetShippingMethod sets ShippingMethod field to given value.

### HasShippingMethod

`func (o *Shipment) HasShippingMethod() bool`

HasShippingMethod returns a boolean if a field has been set.

### SetShippingMethodNil

`func (o *Shipment) SetShippingMethodNil(b bool)`

 SetShippingMethodNil sets the value for ShippingMethod to be an explicit nil

### UnsetShippingMethod
`func (o *Shipment) UnsetShippingMethod()`

UnsetShippingMethod ensures that no value is present for ShippingMethod, not even an explicit nil
### GetSignedBy

`func (o *Shipment) GetSignedBy() string`

GetSignedBy returns the SignedBy field if non-nil, zero value otherwise.

### GetSignedByOk

`func (o *Shipment) GetSignedByOk() (*string, bool)`

GetSignedByOk returns a tuple with the SignedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignedBy

`func (o *Shipment) SetSignedBy(v string)`

SetSignedBy sets SignedBy field to given value.

### HasSignedBy

`func (o *Shipment) HasSignedBy() bool`

HasSignedBy returns a boolean if a field has been set.

### SetSignedByNil

`func (o *Shipment) SetSignedByNil(b bool)`

 SetSignedByNil sets the value for SignedBy to be an explicit nil

### UnsetSignedBy
`func (o *Shipment) UnsetSignedBy()`

UnsetSignedBy ensures that no value is present for SignedBy, not even an explicit nil
### GetStatus

`func (o *Shipment) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Shipment) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Shipment) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTrackingEvents

`func (o *Shipment) GetTrackingEvents() interface{}`

GetTrackingEvents returns the TrackingEvents field if non-nil, zero value otherwise.

### GetTrackingEventsOk

`func (o *Shipment) GetTrackingEventsOk() (*interface{}, bool)`

GetTrackingEventsOk returns a tuple with the TrackingEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingEvents

`func (o *Shipment) SetTrackingEvents(v interface{})`

SetTrackingEvents sets TrackingEvents field to given value.

### HasTrackingEvents

`func (o *Shipment) HasTrackingEvents() bool`

HasTrackingEvents returns a boolean if a field has been set.

### SetTrackingEventsNil

`func (o *Shipment) SetTrackingEventsNil(b bool)`

 SetTrackingEventsNil sets the value for TrackingEvents to be an explicit nil

### UnsetTrackingEvents
`func (o *Shipment) UnsetTrackingEvents()`

UnsetTrackingEvents ensures that no value is present for TrackingEvents, not even an explicit nil
### GetTrackingNumber

`func (o *Shipment) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *Shipment) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *Shipment) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *Shipment) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### SetTrackingNumberNil

`func (o *Shipment) SetTrackingNumberNil(b bool)`

 SetTrackingNumberNil sets the value for TrackingNumber to be an explicit nil

### UnsetTrackingNumber
`func (o *Shipment) UnsetTrackingNumber()`

UnsetTrackingNumber ensures that no value is present for TrackingNumber, not even an explicit nil
### GetTrackingUrl

`func (o *Shipment) GetTrackingUrl() string`

GetTrackingUrl returns the TrackingUrl field if non-nil, zero value otherwise.

### GetTrackingUrlOk

`func (o *Shipment) GetTrackingUrlOk() (*string, bool)`

GetTrackingUrlOk returns a tuple with the TrackingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingUrl

`func (o *Shipment) SetTrackingUrl(v string)`

SetTrackingUrl sets TrackingUrl field to given value.

### HasTrackingUrl

`func (o *Shipment) HasTrackingUrl() bool`

HasTrackingUrl returns a boolean if a field has been set.

### SetTrackingUrlNil

`func (o *Shipment) SetTrackingUrlNil(b bool)`

 SetTrackingUrlNil sets the value for TrackingUrl to be an explicit nil

### UnsetTrackingUrl
`func (o *Shipment) UnsetTrackingUrl()`

UnsetTrackingUrl ensures that no value is present for TrackingUrl, not even an explicit nil
### GetWeightKg

`func (o *Shipment) GetWeightKg() float64`

GetWeightKg returns the WeightKg field if non-nil, zero value otherwise.

### GetWeightKgOk

`func (o *Shipment) GetWeightKgOk() (*float64, bool)`

GetWeightKgOk returns a tuple with the WeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightKg

`func (o *Shipment) SetWeightKg(v float64)`

SetWeightKg sets WeightKg field to given value.

### HasWeightKg

`func (o *Shipment) HasWeightKg() bool`

HasWeightKg returns a boolean if a field has been set.

### SetWeightKgNil

`func (o *Shipment) SetWeightKgNil(b bool)`

 SetWeightKgNil sets the value for WeightKg to be an explicit nil

### UnsetWeightKg
`func (o *Shipment) UnsetWeightKg()`

UnsetWeightKg ensures that no value is present for WeightKg, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


