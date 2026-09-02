# ServiceJob

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **string** | Street + zip + city of the job location. | [optional] 
**CustomerEmail** | Pointer to **NullableString** | Customer email for email notifications. | [optional] 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**CustomerName** | Pointer to **NullableString** | Denormalized customer name for quick display. | [optional] 
**CustomerPhone** | Pointer to **NullableString** | Customer phone for SMS notifications later. | [optional] 
**Description** | Pointer to **string** | What work needs to be done. | [optional] 
**EstimatedDurationMinutes** | Pointer to **int32** | Estimated time for the job in minutes. | [optional] 
**Lat** | Pointer to **NullableFloat64** | Latitude for map display (OpenStreetMap). | [optional] 
**Lng** | Pointer to **NullableFloat64** | Longitude for map display (OpenStreetMap). | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**ServiceJobStatus**](ServiceJobStatus.md) | Dispatch status: \&quot;pending\&quot;, \&quot;assigned\&quot;, \&quot;en_route\&quot;, \&quot;in_progress\&quot;, \&quot;completed\&quot;, \&quot;cancelled\&quot;. | [optional] 

## Methods

### NewServiceJob

`func NewServiceJob() *ServiceJob`

NewServiceJob instantiates a new ServiceJob object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceJobWithDefaults

`func NewServiceJobWithDefaults() *ServiceJob`

NewServiceJobWithDefaults instantiates a new ServiceJob object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *ServiceJob) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ServiceJob) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ServiceJob) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ServiceJob) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *ServiceJob) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *ServiceJob) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *ServiceJob) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *ServiceJob) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *ServiceJob) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *ServiceJob) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetCustomerId

`func (o *ServiceJob) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ServiceJob) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ServiceJob) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ServiceJob) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *ServiceJob) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *ServiceJob) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerName

`func (o *ServiceJob) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *ServiceJob) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *ServiceJob) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *ServiceJob) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *ServiceJob) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *ServiceJob) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerPhone

`func (o *ServiceJob) GetCustomerPhone() string`

GetCustomerPhone returns the CustomerPhone field if non-nil, zero value otherwise.

### GetCustomerPhoneOk

`func (o *ServiceJob) GetCustomerPhoneOk() (*string, bool)`

GetCustomerPhoneOk returns a tuple with the CustomerPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPhone

`func (o *ServiceJob) SetCustomerPhone(v string)`

SetCustomerPhone sets CustomerPhone field to given value.

### HasCustomerPhone

`func (o *ServiceJob) HasCustomerPhone() bool`

HasCustomerPhone returns a boolean if a field has been set.

### SetCustomerPhoneNil

`func (o *ServiceJob) SetCustomerPhoneNil(b bool)`

 SetCustomerPhoneNil sets the value for CustomerPhone to be an explicit nil

### UnsetCustomerPhone
`func (o *ServiceJob) UnsetCustomerPhone()`

UnsetCustomerPhone ensures that no value is present for CustomerPhone, not even an explicit nil
### GetDescription

`func (o *ServiceJob) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ServiceJob) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ServiceJob) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ServiceJob) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEstimatedDurationMinutes

`func (o *ServiceJob) GetEstimatedDurationMinutes() int32`

GetEstimatedDurationMinutes returns the EstimatedDurationMinutes field if non-nil, zero value otherwise.

### GetEstimatedDurationMinutesOk

`func (o *ServiceJob) GetEstimatedDurationMinutesOk() (*int32, bool)`

GetEstimatedDurationMinutesOk returns a tuple with the EstimatedDurationMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedDurationMinutes

`func (o *ServiceJob) SetEstimatedDurationMinutes(v int32)`

SetEstimatedDurationMinutes sets EstimatedDurationMinutes field to given value.

### HasEstimatedDurationMinutes

`func (o *ServiceJob) HasEstimatedDurationMinutes() bool`

HasEstimatedDurationMinutes returns a boolean if a field has been set.

### GetLat

`func (o *ServiceJob) GetLat() float64`

GetLat returns the Lat field if non-nil, zero value otherwise.

### GetLatOk

`func (o *ServiceJob) GetLatOk() (*float64, bool)`

GetLatOk returns a tuple with the Lat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLat

`func (o *ServiceJob) SetLat(v float64)`

SetLat sets Lat field to given value.

### HasLat

`func (o *ServiceJob) HasLat() bool`

HasLat returns a boolean if a field has been set.

### SetLatNil

`func (o *ServiceJob) SetLatNil(b bool)`

 SetLatNil sets the value for Lat to be an explicit nil

### UnsetLat
`func (o *ServiceJob) UnsetLat()`

UnsetLat ensures that no value is present for Lat, not even an explicit nil
### GetLng

`func (o *ServiceJob) GetLng() float64`

GetLng returns the Lng field if non-nil, zero value otherwise.

### GetLngOk

`func (o *ServiceJob) GetLngOk() (*float64, bool)`

GetLngOk returns a tuple with the Lng field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLng

`func (o *ServiceJob) SetLng(v float64)`

SetLng sets Lng field to given value.

### HasLng

`func (o *ServiceJob) HasLng() bool`

HasLng returns a boolean if a field has been set.

### SetLngNil

`func (o *ServiceJob) SetLngNil(b bool)`

 SetLngNil sets the value for Lng to be an explicit nil

### UnsetLng
`func (o *ServiceJob) UnsetLng()`

UnsetLng ensures that no value is present for Lng, not even an explicit nil
### GetNotes

`func (o *ServiceJob) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ServiceJob) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ServiceJob) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ServiceJob) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ServiceJob) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ServiceJob) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *ServiceJob) GetStatus() ServiceJobStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ServiceJob) GetStatusOk() (*ServiceJobStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ServiceJob) SetStatus(v ServiceJobStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ServiceJob) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


