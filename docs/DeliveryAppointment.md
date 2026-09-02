# DeliveryAppointment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**RequestedDate** | **string** |  | 
**Status** | [**DeliveryAppointmentStatus**](DeliveryAppointmentStatus.md) | One of: requested | confirmed | arrived | cancelled | completed | 
**SupplierName** | **string** |  | 
**TimeSlot** | Pointer to **NullableString** | e.g. \&quot;08:00-10:00\&quot; | [optional] 
**WarehouseId** | **string** | References the warehouse entity. | 

## Methods

### NewDeliveryAppointment

`func NewDeliveryAppointment(email string, requestedDate string, status DeliveryAppointmentStatus, supplierName string, warehouseId string, ) *DeliveryAppointment`

NewDeliveryAppointment instantiates a new DeliveryAppointment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliveryAppointmentWithDefaults

`func NewDeliveryAppointmentWithDefaults() *DeliveryAppointment`

NewDeliveryAppointmentWithDefaults instantiates a new DeliveryAppointment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *DeliveryAppointment) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *DeliveryAppointment) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *DeliveryAppointment) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetNotes

`func (o *DeliveryAppointment) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *DeliveryAppointment) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *DeliveryAppointment) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *DeliveryAppointment) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *DeliveryAppointment) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *DeliveryAppointment) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPhone

`func (o *DeliveryAppointment) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *DeliveryAppointment) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *DeliveryAppointment) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *DeliveryAppointment) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *DeliveryAppointment) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *DeliveryAppointment) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetRequestedDate

`func (o *DeliveryAppointment) GetRequestedDate() string`

GetRequestedDate returns the RequestedDate field if non-nil, zero value otherwise.

### GetRequestedDateOk

`func (o *DeliveryAppointment) GetRequestedDateOk() (*string, bool)`

GetRequestedDateOk returns a tuple with the RequestedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDate

`func (o *DeliveryAppointment) SetRequestedDate(v string)`

SetRequestedDate sets RequestedDate field to given value.


### GetStatus

`func (o *DeliveryAppointment) GetStatus() DeliveryAppointmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeliveryAppointment) GetStatusOk() (*DeliveryAppointmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeliveryAppointment) SetStatus(v DeliveryAppointmentStatus)`

SetStatus sets Status field to given value.


### GetSupplierName

`func (o *DeliveryAppointment) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *DeliveryAppointment) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *DeliveryAppointment) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.


### GetTimeSlot

`func (o *DeliveryAppointment) GetTimeSlot() string`

GetTimeSlot returns the TimeSlot field if non-nil, zero value otherwise.

### GetTimeSlotOk

`func (o *DeliveryAppointment) GetTimeSlotOk() (*string, bool)`

GetTimeSlotOk returns a tuple with the TimeSlot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSlot

`func (o *DeliveryAppointment) SetTimeSlot(v string)`

SetTimeSlot sets TimeSlot field to given value.

### HasTimeSlot

`func (o *DeliveryAppointment) HasTimeSlot() bool`

HasTimeSlot returns a boolean if a field has been set.

### SetTimeSlotNil

`func (o *DeliveryAppointment) SetTimeSlotNil(b bool)`

 SetTimeSlotNil sets the value for TimeSlot to be an explicit nil

### UnsetTimeSlot
`func (o *DeliveryAppointment) UnsetTimeSlot()`

UnsetTimeSlot ensures that no value is present for TimeSlot, not even an explicit nil
### GetWarehouseId

`func (o *DeliveryAppointment) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *DeliveryAppointment) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *DeliveryAppointment) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


