# PublicDeliveryAppointmentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppointmentId** | **string** |  | 
**ConfirmationHint** | **string** | Carries the status-check token (email is out of scope for now). | 
**Message** | **string** |  | 
**Status** | **string** |  | 

## Methods

### NewPublicDeliveryAppointmentResponse

`func NewPublicDeliveryAppointmentResponse(appointmentId string, confirmationHint string, message string, status string, ) *PublicDeliveryAppointmentResponse`

NewPublicDeliveryAppointmentResponse instantiates a new PublicDeliveryAppointmentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicDeliveryAppointmentResponseWithDefaults

`func NewPublicDeliveryAppointmentResponseWithDefaults() *PublicDeliveryAppointmentResponse`

NewPublicDeliveryAppointmentResponseWithDefaults instantiates a new PublicDeliveryAppointmentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppointmentId

`func (o *PublicDeliveryAppointmentResponse) GetAppointmentId() string`

GetAppointmentId returns the AppointmentId field if non-nil, zero value otherwise.

### GetAppointmentIdOk

`func (o *PublicDeliveryAppointmentResponse) GetAppointmentIdOk() (*string, bool)`

GetAppointmentIdOk returns a tuple with the AppointmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppointmentId

`func (o *PublicDeliveryAppointmentResponse) SetAppointmentId(v string)`

SetAppointmentId sets AppointmentId field to given value.


### GetConfirmationHint

`func (o *PublicDeliveryAppointmentResponse) GetConfirmationHint() string`

GetConfirmationHint returns the ConfirmationHint field if non-nil, zero value otherwise.

### GetConfirmationHintOk

`func (o *PublicDeliveryAppointmentResponse) GetConfirmationHintOk() (*string, bool)`

GetConfirmationHintOk returns a tuple with the ConfirmationHint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmationHint

`func (o *PublicDeliveryAppointmentResponse) SetConfirmationHint(v string)`

SetConfirmationHint sets ConfirmationHint field to given value.


### GetMessage

`func (o *PublicDeliveryAppointmentResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PublicDeliveryAppointmentResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PublicDeliveryAppointmentResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetStatus

`func (o *PublicDeliveryAppointmentResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PublicDeliveryAppointmentResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PublicDeliveryAppointmentResponse) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


