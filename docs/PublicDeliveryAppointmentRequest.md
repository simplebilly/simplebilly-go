# PublicDeliveryAppointmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**RequestedDate** | **string** |  | 
**SupplierName** | **string** |  | 
**TimeSlot** | Pointer to **NullableString** |  | [optional] 
**WarehouseCode** | **string** | Warehouse &#x60;code&#x60; — the supplier does not know the warehouse uuid. | 

## Methods

### NewPublicDeliveryAppointmentRequest

`func NewPublicDeliveryAppointmentRequest(email string, requestedDate string, supplierName string, warehouseCode string, ) *PublicDeliveryAppointmentRequest`

NewPublicDeliveryAppointmentRequest instantiates a new PublicDeliveryAppointmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicDeliveryAppointmentRequestWithDefaults

`func NewPublicDeliveryAppointmentRequestWithDefaults() *PublicDeliveryAppointmentRequest`

NewPublicDeliveryAppointmentRequestWithDefaults instantiates a new PublicDeliveryAppointmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *PublicDeliveryAppointmentRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PublicDeliveryAppointmentRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PublicDeliveryAppointmentRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetNotes

`func (o *PublicDeliveryAppointmentRequest) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *PublicDeliveryAppointmentRequest) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *PublicDeliveryAppointmentRequest) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *PublicDeliveryAppointmentRequest) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *PublicDeliveryAppointmentRequest) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *PublicDeliveryAppointmentRequest) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetRequestedDate

`func (o *PublicDeliveryAppointmentRequest) GetRequestedDate() string`

GetRequestedDate returns the RequestedDate field if non-nil, zero value otherwise.

### GetRequestedDateOk

`func (o *PublicDeliveryAppointmentRequest) GetRequestedDateOk() (*string, bool)`

GetRequestedDateOk returns a tuple with the RequestedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDate

`func (o *PublicDeliveryAppointmentRequest) SetRequestedDate(v string)`

SetRequestedDate sets RequestedDate field to given value.


### GetSupplierName

`func (o *PublicDeliveryAppointmentRequest) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *PublicDeliveryAppointmentRequest) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *PublicDeliveryAppointmentRequest) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.


### GetTimeSlot

`func (o *PublicDeliveryAppointmentRequest) GetTimeSlot() string`

GetTimeSlot returns the TimeSlot field if non-nil, zero value otherwise.

### GetTimeSlotOk

`func (o *PublicDeliveryAppointmentRequest) GetTimeSlotOk() (*string, bool)`

GetTimeSlotOk returns a tuple with the TimeSlot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSlot

`func (o *PublicDeliveryAppointmentRequest) SetTimeSlot(v string)`

SetTimeSlot sets TimeSlot field to given value.

### HasTimeSlot

`func (o *PublicDeliveryAppointmentRequest) HasTimeSlot() bool`

HasTimeSlot returns a boolean if a field has been set.

### SetTimeSlotNil

`func (o *PublicDeliveryAppointmentRequest) SetTimeSlotNil(b bool)`

 SetTimeSlotNil sets the value for TimeSlot to be an explicit nil

### UnsetTimeSlot
`func (o *PublicDeliveryAppointmentRequest) UnsetTimeSlot()`

UnsetTimeSlot ensures that no value is present for TimeSlot, not even an explicit nil
### GetWarehouseCode

`func (o *PublicDeliveryAppointmentRequest) GetWarehouseCode() string`

GetWarehouseCode returns the WarehouseCode field if non-nil, zero value otherwise.

### GetWarehouseCodeOk

`func (o *PublicDeliveryAppointmentRequest) GetWarehouseCodeOk() (*string, bool)`

GetWarehouseCodeOk returns a tuple with the WarehouseCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseCode

`func (o *PublicDeliveryAppointmentRequest) SetWarehouseCode(v string)`

SetWarehouseCode sets WarehouseCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


