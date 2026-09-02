# PublicDeliveryAppointmentStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppointmentId** | **string** |  | 
**RequestedDate** | **string** |  | 
**Status** | **string** |  | 
**TimeSlot** | Pointer to **NullableString** |  | [optional] 
**WarehouseName** | **string** |  | 

## Methods

### NewPublicDeliveryAppointmentStatusResponse

`func NewPublicDeliveryAppointmentStatusResponse(appointmentId string, requestedDate string, status string, warehouseName string, ) *PublicDeliveryAppointmentStatusResponse`

NewPublicDeliveryAppointmentStatusResponse instantiates a new PublicDeliveryAppointmentStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicDeliveryAppointmentStatusResponseWithDefaults

`func NewPublicDeliveryAppointmentStatusResponseWithDefaults() *PublicDeliveryAppointmentStatusResponse`

NewPublicDeliveryAppointmentStatusResponseWithDefaults instantiates a new PublicDeliveryAppointmentStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppointmentId

`func (o *PublicDeliveryAppointmentStatusResponse) GetAppointmentId() string`

GetAppointmentId returns the AppointmentId field if non-nil, zero value otherwise.

### GetAppointmentIdOk

`func (o *PublicDeliveryAppointmentStatusResponse) GetAppointmentIdOk() (*string, bool)`

GetAppointmentIdOk returns a tuple with the AppointmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppointmentId

`func (o *PublicDeliveryAppointmentStatusResponse) SetAppointmentId(v string)`

SetAppointmentId sets AppointmentId field to given value.


### GetRequestedDate

`func (o *PublicDeliveryAppointmentStatusResponse) GetRequestedDate() string`

GetRequestedDate returns the RequestedDate field if non-nil, zero value otherwise.

### GetRequestedDateOk

`func (o *PublicDeliveryAppointmentStatusResponse) GetRequestedDateOk() (*string, bool)`

GetRequestedDateOk returns a tuple with the RequestedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDate

`func (o *PublicDeliveryAppointmentStatusResponse) SetRequestedDate(v string)`

SetRequestedDate sets RequestedDate field to given value.


### GetStatus

`func (o *PublicDeliveryAppointmentStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PublicDeliveryAppointmentStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PublicDeliveryAppointmentStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTimeSlot

`func (o *PublicDeliveryAppointmentStatusResponse) GetTimeSlot() string`

GetTimeSlot returns the TimeSlot field if non-nil, zero value otherwise.

### GetTimeSlotOk

`func (o *PublicDeliveryAppointmentStatusResponse) GetTimeSlotOk() (*string, bool)`

GetTimeSlotOk returns a tuple with the TimeSlot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSlot

`func (o *PublicDeliveryAppointmentStatusResponse) SetTimeSlot(v string)`

SetTimeSlot sets TimeSlot field to given value.

### HasTimeSlot

`func (o *PublicDeliveryAppointmentStatusResponse) HasTimeSlot() bool`

HasTimeSlot returns a boolean if a field has been set.

### SetTimeSlotNil

`func (o *PublicDeliveryAppointmentStatusResponse) SetTimeSlotNil(b bool)`

 SetTimeSlotNil sets the value for TimeSlot to be an explicit nil

### UnsetTimeSlot
`func (o *PublicDeliveryAppointmentStatusResponse) UnsetTimeSlot()`

UnsetTimeSlot ensures that no value is present for TimeSlot, not even an explicit nil
### GetWarehouseName

`func (o *PublicDeliveryAppointmentStatusResponse) GetWarehouseName() string`

GetWarehouseName returns the WarehouseName field if non-nil, zero value otherwise.

### GetWarehouseNameOk

`func (o *PublicDeliveryAppointmentStatusResponse) GetWarehouseNameOk() (*string, bool)`

GetWarehouseNameOk returns a tuple with the WarehouseName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseName

`func (o *PublicDeliveryAppointmentStatusResponse) SetWarehouseName(v string)`

SetWarehouseName sets WarehouseName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


