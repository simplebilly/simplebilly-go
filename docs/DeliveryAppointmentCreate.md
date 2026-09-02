# DeliveryAppointmentCreate

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

### NewDeliveryAppointmentCreate

`func NewDeliveryAppointmentCreate(email string, requestedDate string, status DeliveryAppointmentStatus, supplierName string, warehouseId string, ) *DeliveryAppointmentCreate`

NewDeliveryAppointmentCreate instantiates a new DeliveryAppointmentCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliveryAppointmentCreateWithDefaults

`func NewDeliveryAppointmentCreateWithDefaults() *DeliveryAppointmentCreate`

NewDeliveryAppointmentCreateWithDefaults instantiates a new DeliveryAppointmentCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *DeliveryAppointmentCreate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *DeliveryAppointmentCreate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *DeliveryAppointmentCreate) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetNotes

`func (o *DeliveryAppointmentCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *DeliveryAppointmentCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *DeliveryAppointmentCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *DeliveryAppointmentCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *DeliveryAppointmentCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *DeliveryAppointmentCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPhone

`func (o *DeliveryAppointmentCreate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *DeliveryAppointmentCreate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *DeliveryAppointmentCreate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *DeliveryAppointmentCreate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *DeliveryAppointmentCreate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *DeliveryAppointmentCreate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetRequestedDate

`func (o *DeliveryAppointmentCreate) GetRequestedDate() string`

GetRequestedDate returns the RequestedDate field if non-nil, zero value otherwise.

### GetRequestedDateOk

`func (o *DeliveryAppointmentCreate) GetRequestedDateOk() (*string, bool)`

GetRequestedDateOk returns a tuple with the RequestedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDate

`func (o *DeliveryAppointmentCreate) SetRequestedDate(v string)`

SetRequestedDate sets RequestedDate field to given value.


### GetStatus

`func (o *DeliveryAppointmentCreate) GetStatus() DeliveryAppointmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeliveryAppointmentCreate) GetStatusOk() (*DeliveryAppointmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeliveryAppointmentCreate) SetStatus(v DeliveryAppointmentStatus)`

SetStatus sets Status field to given value.


### GetSupplierName

`func (o *DeliveryAppointmentCreate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *DeliveryAppointmentCreate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *DeliveryAppointmentCreate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.


### GetTimeSlot

`func (o *DeliveryAppointmentCreate) GetTimeSlot() string`

GetTimeSlot returns the TimeSlot field if non-nil, zero value otherwise.

### GetTimeSlotOk

`func (o *DeliveryAppointmentCreate) GetTimeSlotOk() (*string, bool)`

GetTimeSlotOk returns a tuple with the TimeSlot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSlot

`func (o *DeliveryAppointmentCreate) SetTimeSlot(v string)`

SetTimeSlot sets TimeSlot field to given value.

### HasTimeSlot

`func (o *DeliveryAppointmentCreate) HasTimeSlot() bool`

HasTimeSlot returns a boolean if a field has been set.

### SetTimeSlotNil

`func (o *DeliveryAppointmentCreate) SetTimeSlotNil(b bool)`

 SetTimeSlotNil sets the value for TimeSlot to be an explicit nil

### UnsetTimeSlot
`func (o *DeliveryAppointmentCreate) UnsetTimeSlot()`

UnsetTimeSlot ensures that no value is present for TimeSlot, not even an explicit nil
### GetWarehouseId

`func (o *DeliveryAppointmentCreate) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *DeliveryAppointmentCreate) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *DeliveryAppointmentCreate) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


