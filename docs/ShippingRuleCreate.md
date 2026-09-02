# ShippingRuleCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | Pointer to **NullableString** | Provider that auto-filled this rule (e.g. \&quot;ups\&quot;), if any. | [optional] 
**Country** | Pointer to [**NullableCountryCode**](CountryCode.md) | None &#x3D; applies to all countries. | [optional] 
**DeliveryTime** | Pointer to **NullableString** | Delivery time text, e.g. \&quot;1-3\&quot;. | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**MaxWeightKg** | Pointer to **NullableFloat64** |  | [optional] 
**MinWeightKg** | Pointer to **NullableFloat64** |  | [optional] 
**Name** | **string** | Delivery-method label, e.g. \&quot;Standardversand\&quot;. | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Price** | **string** | Shipping cost in the shop&#39;s currency. | 
**Priority** | Pointer to **int32** | Lower wins when multiple rules match. | [optional] 

## Methods

### NewShippingRuleCreate

`func NewShippingRuleCreate(name string, price string, ) *ShippingRuleCreate`

NewShippingRuleCreate instantiates a new ShippingRuleCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingRuleCreateWithDefaults

`func NewShippingRuleCreateWithDefaults() *ShippingRuleCreate`

NewShippingRuleCreateWithDefaults instantiates a new ShippingRuleCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *ShippingRuleCreate) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ShippingRuleCreate) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ShippingRuleCreate) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *ShippingRuleCreate) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### SetCarrierNil

`func (o *ShippingRuleCreate) SetCarrierNil(b bool)`

 SetCarrierNil sets the value for Carrier to be an explicit nil

### UnsetCarrier
`func (o *ShippingRuleCreate) UnsetCarrier()`

UnsetCarrier ensures that no value is present for Carrier, not even an explicit nil
### GetCountry

`func (o *ShippingRuleCreate) GetCountry() CountryCode`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *ShippingRuleCreate) GetCountryOk() (*CountryCode, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *ShippingRuleCreate) SetCountry(v CountryCode)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *ShippingRuleCreate) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *ShippingRuleCreate) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *ShippingRuleCreate) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetDeliveryTime

`func (o *ShippingRuleCreate) GetDeliveryTime() string`

GetDeliveryTime returns the DeliveryTime field if non-nil, zero value otherwise.

### GetDeliveryTimeOk

`func (o *ShippingRuleCreate) GetDeliveryTimeOk() (*string, bool)`

GetDeliveryTimeOk returns a tuple with the DeliveryTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTime

`func (o *ShippingRuleCreate) SetDeliveryTime(v string)`

SetDeliveryTime sets DeliveryTime field to given value.

### HasDeliveryTime

`func (o *ShippingRuleCreate) HasDeliveryTime() bool`

HasDeliveryTime returns a boolean if a field has been set.

### SetDeliveryTimeNil

`func (o *ShippingRuleCreate) SetDeliveryTimeNil(b bool)`

 SetDeliveryTimeNil sets the value for DeliveryTime to be an explicit nil

### UnsetDeliveryTime
`func (o *ShippingRuleCreate) UnsetDeliveryTime()`

UnsetDeliveryTime ensures that no value is present for DeliveryTime, not even an explicit nil
### GetIsActive

`func (o *ShippingRuleCreate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ShippingRuleCreate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ShippingRuleCreate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ShippingRuleCreate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetMaxWeightKg

`func (o *ShippingRuleCreate) GetMaxWeightKg() float64`

GetMaxWeightKg returns the MaxWeightKg field if non-nil, zero value otherwise.

### GetMaxWeightKgOk

`func (o *ShippingRuleCreate) GetMaxWeightKgOk() (*float64, bool)`

GetMaxWeightKgOk returns a tuple with the MaxWeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxWeightKg

`func (o *ShippingRuleCreate) SetMaxWeightKg(v float64)`

SetMaxWeightKg sets MaxWeightKg field to given value.

### HasMaxWeightKg

`func (o *ShippingRuleCreate) HasMaxWeightKg() bool`

HasMaxWeightKg returns a boolean if a field has been set.

### SetMaxWeightKgNil

`func (o *ShippingRuleCreate) SetMaxWeightKgNil(b bool)`

 SetMaxWeightKgNil sets the value for MaxWeightKg to be an explicit nil

### UnsetMaxWeightKg
`func (o *ShippingRuleCreate) UnsetMaxWeightKg()`

UnsetMaxWeightKg ensures that no value is present for MaxWeightKg, not even an explicit nil
### GetMinWeightKg

`func (o *ShippingRuleCreate) GetMinWeightKg() float64`

GetMinWeightKg returns the MinWeightKg field if non-nil, zero value otherwise.

### GetMinWeightKgOk

`func (o *ShippingRuleCreate) GetMinWeightKgOk() (*float64, bool)`

GetMinWeightKgOk returns a tuple with the MinWeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWeightKg

`func (o *ShippingRuleCreate) SetMinWeightKg(v float64)`

SetMinWeightKg sets MinWeightKg field to given value.

### HasMinWeightKg

`func (o *ShippingRuleCreate) HasMinWeightKg() bool`

HasMinWeightKg returns a boolean if a field has been set.

### SetMinWeightKgNil

`func (o *ShippingRuleCreate) SetMinWeightKgNil(b bool)`

 SetMinWeightKgNil sets the value for MinWeightKg to be an explicit nil

### UnsetMinWeightKg
`func (o *ShippingRuleCreate) UnsetMinWeightKg()`

UnsetMinWeightKg ensures that no value is present for MinWeightKg, not even an explicit nil
### GetName

`func (o *ShippingRuleCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShippingRuleCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShippingRuleCreate) SetName(v string)`

SetName sets Name field to given value.


### GetNotes

`func (o *ShippingRuleCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ShippingRuleCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ShippingRuleCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ShippingRuleCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ShippingRuleCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ShippingRuleCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPrice

`func (o *ShippingRuleCreate) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ShippingRuleCreate) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ShippingRuleCreate) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetPriority

`func (o *ShippingRuleCreate) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ShippingRuleCreate) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ShippingRuleCreate) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ShippingRuleCreate) HasPriority() bool`

HasPriority returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


