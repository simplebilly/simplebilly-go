# PackingQueueItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **string** |  | 
**CustomerId** | **string** |  | 
**DeliveryNotePrinted** | **bool** |  | 
**Items** | **interface{}** |  | 
**ItemsCount** | **int32** |  | 
**LabelPrinted** | **bool** |  | 
**OrderNumber** | **string** |  | 
**OrderStatus** | **string** |  | 
**ShipmentId** | Pointer to **NullableString** |  | [optional] 
**ShippingAddress** | Pointer to **interface{}** |  | [optional] 
**ShippingMethod** | **string** |  | 
**TrackingNumber** | Pointer to **NullableString** |  | [optional] 
**VideoRecording** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPackingQueueItem

`func NewPackingQueueItem(createdAt string, customerId string, deliveryNotePrinted bool, items interface{}, itemsCount int32, labelPrinted bool, orderNumber string, orderStatus string, shippingMethod string, ) *PackingQueueItem`

NewPackingQueueItem instantiates a new PackingQueueItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPackingQueueItemWithDefaults

`func NewPackingQueueItemWithDefaults() *PackingQueueItem`

NewPackingQueueItemWithDefaults instantiates a new PackingQueueItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *PackingQueueItem) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PackingQueueItem) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PackingQueueItem) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomerId

`func (o *PackingQueueItem) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *PackingQueueItem) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *PackingQueueItem) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetDeliveryNotePrinted

`func (o *PackingQueueItem) GetDeliveryNotePrinted() bool`

GetDeliveryNotePrinted returns the DeliveryNotePrinted field if non-nil, zero value otherwise.

### GetDeliveryNotePrintedOk

`func (o *PackingQueueItem) GetDeliveryNotePrintedOk() (*bool, bool)`

GetDeliveryNotePrintedOk returns a tuple with the DeliveryNotePrinted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryNotePrinted

`func (o *PackingQueueItem) SetDeliveryNotePrinted(v bool)`

SetDeliveryNotePrinted sets DeliveryNotePrinted field to given value.


### GetItems

`func (o *PackingQueueItem) GetItems() interface{}`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PackingQueueItem) GetItemsOk() (*interface{}, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PackingQueueItem) SetItems(v interface{})`

SetItems sets Items field to given value.


### SetItemsNil

`func (o *PackingQueueItem) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *PackingQueueItem) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil
### GetItemsCount

`func (o *PackingQueueItem) GetItemsCount() int32`

GetItemsCount returns the ItemsCount field if non-nil, zero value otherwise.

### GetItemsCountOk

`func (o *PackingQueueItem) GetItemsCountOk() (*int32, bool)`

GetItemsCountOk returns a tuple with the ItemsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsCount

`func (o *PackingQueueItem) SetItemsCount(v int32)`

SetItemsCount sets ItemsCount field to given value.


### GetLabelPrinted

`func (o *PackingQueueItem) GetLabelPrinted() bool`

GetLabelPrinted returns the LabelPrinted field if non-nil, zero value otherwise.

### GetLabelPrintedOk

`func (o *PackingQueueItem) GetLabelPrintedOk() (*bool, bool)`

GetLabelPrintedOk returns a tuple with the LabelPrinted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinted

`func (o *PackingQueueItem) SetLabelPrinted(v bool)`

SetLabelPrinted sets LabelPrinted field to given value.


### GetOrderNumber

`func (o *PackingQueueItem) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *PackingQueueItem) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *PackingQueueItem) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetOrderStatus

`func (o *PackingQueueItem) GetOrderStatus() string`

GetOrderStatus returns the OrderStatus field if non-nil, zero value otherwise.

### GetOrderStatusOk

`func (o *PackingQueueItem) GetOrderStatusOk() (*string, bool)`

GetOrderStatusOk returns a tuple with the OrderStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderStatus

`func (o *PackingQueueItem) SetOrderStatus(v string)`

SetOrderStatus sets OrderStatus field to given value.


### GetShipmentId

`func (o *PackingQueueItem) GetShipmentId() string`

GetShipmentId returns the ShipmentId field if non-nil, zero value otherwise.

### GetShipmentIdOk

`func (o *PackingQueueItem) GetShipmentIdOk() (*string, bool)`

GetShipmentIdOk returns a tuple with the ShipmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentId

`func (o *PackingQueueItem) SetShipmentId(v string)`

SetShipmentId sets ShipmentId field to given value.

### HasShipmentId

`func (o *PackingQueueItem) HasShipmentId() bool`

HasShipmentId returns a boolean if a field has been set.

### SetShipmentIdNil

`func (o *PackingQueueItem) SetShipmentIdNil(b bool)`

 SetShipmentIdNil sets the value for ShipmentId to be an explicit nil

### UnsetShipmentId
`func (o *PackingQueueItem) UnsetShipmentId()`

UnsetShipmentId ensures that no value is present for ShipmentId, not even an explicit nil
### GetShippingAddress

`func (o *PackingQueueItem) GetShippingAddress() interface{}`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *PackingQueueItem) GetShippingAddressOk() (*interface{}, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *PackingQueueItem) SetShippingAddress(v interface{})`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *PackingQueueItem) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *PackingQueueItem) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *PackingQueueItem) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetShippingMethod

`func (o *PackingQueueItem) GetShippingMethod() string`

GetShippingMethod returns the ShippingMethod field if non-nil, zero value otherwise.

### GetShippingMethodOk

`func (o *PackingQueueItem) GetShippingMethodOk() (*string, bool)`

GetShippingMethodOk returns a tuple with the ShippingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethod

`func (o *PackingQueueItem) SetShippingMethod(v string)`

SetShippingMethod sets ShippingMethod field to given value.


### GetTrackingNumber

`func (o *PackingQueueItem) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *PackingQueueItem) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *PackingQueueItem) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *PackingQueueItem) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### SetTrackingNumberNil

`func (o *PackingQueueItem) SetTrackingNumberNil(b bool)`

 SetTrackingNumberNil sets the value for TrackingNumber to be an explicit nil

### UnsetTrackingNumber
`func (o *PackingQueueItem) UnsetTrackingNumber()`

UnsetTrackingNumber ensures that no value is present for TrackingNumber, not even an explicit nil
### GetVideoRecording

`func (o *PackingQueueItem) GetVideoRecording() string`

GetVideoRecording returns the VideoRecording field if non-nil, zero value otherwise.

### GetVideoRecordingOk

`func (o *PackingQueueItem) GetVideoRecordingOk() (*string, bool)`

GetVideoRecordingOk returns a tuple with the VideoRecording field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoRecording

`func (o *PackingQueueItem) SetVideoRecording(v string)`

SetVideoRecording sets VideoRecording field to given value.

### HasVideoRecording

`func (o *PackingQueueItem) HasVideoRecording() bool`

HasVideoRecording returns a boolean if a field has been set.

### SetVideoRecordingNil

`func (o *PackingQueueItem) SetVideoRecordingNil(b bool)`

 SetVideoRecordingNil sets the value for VideoRecording to be an explicit nil

### UnsetVideoRecording
`func (o *PackingQueueItem) UnsetVideoRecording()`

UnsetVideoRecording ensures that no value is present for VideoRecording, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


