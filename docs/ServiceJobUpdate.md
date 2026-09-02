# ServiceJobUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **NullableString** | Street + zip + city of the job location. | [optional] 
**CustomerEmail** | Pointer to **NullableString** | Customer email for email notifications. | [optional] 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**CustomerName** | Pointer to **NullableString** | Denormalized customer name for quick display. | [optional] 
**CustomerPhone** | Pointer to **NullableString** | Customer phone for SMS notifications later. | [optional] 
**Description** | Pointer to **NullableString** | What work needs to be done. | [optional] 
**EstimatedDurationMinutes** | Pointer to **NullableInt32** | Estimated time for the job in minutes. | [optional] 
**Lat** | Pointer to **NullableFloat64** | Latitude for map display (OpenStreetMap). | [optional] 
**Lng** | Pointer to **NullableFloat64** | Longitude for map display (OpenStreetMap). | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableServiceJobStatus**](ServiceJobStatus.md) | Dispatch status: \&quot;pending\&quot;, \&quot;assigned\&quot;, \&quot;en_route\&quot;, \&quot;in_progress\&quot;, \&quot;completed\&quot;, \&quot;cancelled\&quot;. | [optional] 

## Methods

### NewServiceJobUpdate

`func NewServiceJobUpdate() *ServiceJobUpdate`

NewServiceJobUpdate instantiates a new ServiceJobUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceJobUpdateWithDefaults

`func NewServiceJobUpdateWithDefaults() *ServiceJobUpdate`

NewServiceJobUpdateWithDefaults instantiates a new ServiceJobUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *ServiceJobUpdate) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ServiceJobUpdate) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ServiceJobUpdate) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ServiceJobUpdate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *ServiceJobUpdate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *ServiceJobUpdate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetCustomerEmail

`func (o *ServiceJobUpdate) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *ServiceJobUpdate) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *ServiceJobUpdate) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *ServiceJobUpdate) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *ServiceJobUpdate) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *ServiceJobUpdate) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetCustomerId

`func (o *ServiceJobUpdate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ServiceJobUpdate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ServiceJobUpdate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ServiceJobUpdate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *ServiceJobUpdate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *ServiceJobUpdate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerName

`func (o *ServiceJobUpdate) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *ServiceJobUpdate) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *ServiceJobUpdate) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *ServiceJobUpdate) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *ServiceJobUpdate) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *ServiceJobUpdate) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerPhone

`func (o *ServiceJobUpdate) GetCustomerPhone() string`

GetCustomerPhone returns the CustomerPhone field if non-nil, zero value otherwise.

### GetCustomerPhoneOk

`func (o *ServiceJobUpdate) GetCustomerPhoneOk() (*string, bool)`

GetCustomerPhoneOk returns a tuple with the CustomerPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerPhone

`func (o *ServiceJobUpdate) SetCustomerPhone(v string)`

SetCustomerPhone sets CustomerPhone field to given value.

### HasCustomerPhone

`func (o *ServiceJobUpdate) HasCustomerPhone() bool`

HasCustomerPhone returns a boolean if a field has been set.

### SetCustomerPhoneNil

`func (o *ServiceJobUpdate) SetCustomerPhoneNil(b bool)`

 SetCustomerPhoneNil sets the value for CustomerPhone to be an explicit nil

### UnsetCustomerPhone
`func (o *ServiceJobUpdate) UnsetCustomerPhone()`

UnsetCustomerPhone ensures that no value is present for CustomerPhone, not even an explicit nil
### GetDescription

`func (o *ServiceJobUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ServiceJobUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ServiceJobUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ServiceJobUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ServiceJobUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ServiceJobUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEstimatedDurationMinutes

`func (o *ServiceJobUpdate) GetEstimatedDurationMinutes() int32`

GetEstimatedDurationMinutes returns the EstimatedDurationMinutes field if non-nil, zero value otherwise.

### GetEstimatedDurationMinutesOk

`func (o *ServiceJobUpdate) GetEstimatedDurationMinutesOk() (*int32, bool)`

GetEstimatedDurationMinutesOk returns a tuple with the EstimatedDurationMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedDurationMinutes

`func (o *ServiceJobUpdate) SetEstimatedDurationMinutes(v int32)`

SetEstimatedDurationMinutes sets EstimatedDurationMinutes field to given value.

### HasEstimatedDurationMinutes

`func (o *ServiceJobUpdate) HasEstimatedDurationMinutes() bool`

HasEstimatedDurationMinutes returns a boolean if a field has been set.

### SetEstimatedDurationMinutesNil

`func (o *ServiceJobUpdate) SetEstimatedDurationMinutesNil(b bool)`

 SetEstimatedDurationMinutesNil sets the value for EstimatedDurationMinutes to be an explicit nil

### UnsetEstimatedDurationMinutes
`func (o *ServiceJobUpdate) UnsetEstimatedDurationMinutes()`

UnsetEstimatedDurationMinutes ensures that no value is present for EstimatedDurationMinutes, not even an explicit nil
### GetLat

`func (o *ServiceJobUpdate) GetLat() float64`

GetLat returns the Lat field if non-nil, zero value otherwise.

### GetLatOk

`func (o *ServiceJobUpdate) GetLatOk() (*float64, bool)`

GetLatOk returns a tuple with the Lat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLat

`func (o *ServiceJobUpdate) SetLat(v float64)`

SetLat sets Lat field to given value.

### HasLat

`func (o *ServiceJobUpdate) HasLat() bool`

HasLat returns a boolean if a field has been set.

### SetLatNil

`func (o *ServiceJobUpdate) SetLatNil(b bool)`

 SetLatNil sets the value for Lat to be an explicit nil

### UnsetLat
`func (o *ServiceJobUpdate) UnsetLat()`

UnsetLat ensures that no value is present for Lat, not even an explicit nil
### GetLng

`func (o *ServiceJobUpdate) GetLng() float64`

GetLng returns the Lng field if non-nil, zero value otherwise.

### GetLngOk

`func (o *ServiceJobUpdate) GetLngOk() (*float64, bool)`

GetLngOk returns a tuple with the Lng field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLng

`func (o *ServiceJobUpdate) SetLng(v float64)`

SetLng sets Lng field to given value.

### HasLng

`func (o *ServiceJobUpdate) HasLng() bool`

HasLng returns a boolean if a field has been set.

### SetLngNil

`func (o *ServiceJobUpdate) SetLngNil(b bool)`

 SetLngNil sets the value for Lng to be an explicit nil

### UnsetLng
`func (o *ServiceJobUpdate) UnsetLng()`

UnsetLng ensures that no value is present for Lng, not even an explicit nil
### GetNotes

`func (o *ServiceJobUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ServiceJobUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ServiceJobUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ServiceJobUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ServiceJobUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ServiceJobUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *ServiceJobUpdate) GetStatus() ServiceJobStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ServiceJobUpdate) GetStatusOk() (*ServiceJobStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ServiceJobUpdate) SetStatus(v ServiceJobStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ServiceJobUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *ServiceJobUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ServiceJobUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


