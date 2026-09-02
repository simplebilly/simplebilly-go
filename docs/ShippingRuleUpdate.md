# ShippingRuleUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | Pointer to **NullableString** | Provider that auto-filled this rule (e.g. \&quot;ups\&quot;), if any. | [optional] 
**Country** | Pointer to [**NullableCountryCode**](CountryCode.md) | None &#x3D; applies to all countries. | [optional] 
**DeliveryTime** | Pointer to **NullableString** | Delivery time text, e.g. \&quot;1-3\&quot;. | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**MaxWeightKg** | Pointer to **NullableFloat64** |  | [optional] 
**MinWeightKg** | Pointer to **NullableFloat64** |  | [optional] 
**Name** | Pointer to **NullableString** | Delivery-method label, e.g. \&quot;Standardversand\&quot;. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Price** | Pointer to **NullableString** | Shipping cost in the shop&#39;s currency. | [optional] 
**Priority** | Pointer to **NullableInt32** | Lower wins when multiple rules match. | [optional] 

## Methods

### NewShippingRuleUpdate

`func NewShippingRuleUpdate() *ShippingRuleUpdate`

NewShippingRuleUpdate instantiates a new ShippingRuleUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingRuleUpdateWithDefaults

`func NewShippingRuleUpdateWithDefaults() *ShippingRuleUpdate`

NewShippingRuleUpdateWithDefaults instantiates a new ShippingRuleUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *ShippingRuleUpdate) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ShippingRuleUpdate) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ShippingRuleUpdate) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *ShippingRuleUpdate) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### SetCarrierNil

`func (o *ShippingRuleUpdate) SetCarrierNil(b bool)`

 SetCarrierNil sets the value for Carrier to be an explicit nil

### UnsetCarrier
`func (o *ShippingRuleUpdate) UnsetCarrier()`

UnsetCarrier ensures that no value is present for Carrier, not even an explicit nil
### GetCountry

`func (o *ShippingRuleUpdate) GetCountry() CountryCode`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *ShippingRuleUpdate) GetCountryOk() (*CountryCode, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *ShippingRuleUpdate) SetCountry(v CountryCode)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *ShippingRuleUpdate) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *ShippingRuleUpdate) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *ShippingRuleUpdate) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetDeliveryTime

`func (o *ShippingRuleUpdate) GetDeliveryTime() string`

GetDeliveryTime returns the DeliveryTime field if non-nil, zero value otherwise.

### GetDeliveryTimeOk

`func (o *ShippingRuleUpdate) GetDeliveryTimeOk() (*string, bool)`

GetDeliveryTimeOk returns a tuple with the DeliveryTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTime

`func (o *ShippingRuleUpdate) SetDeliveryTime(v string)`

SetDeliveryTime sets DeliveryTime field to given value.

### HasDeliveryTime

`func (o *ShippingRuleUpdate) HasDeliveryTime() bool`

HasDeliveryTime returns a boolean if a field has been set.

### SetDeliveryTimeNil

`func (o *ShippingRuleUpdate) SetDeliveryTimeNil(b bool)`

 SetDeliveryTimeNil sets the value for DeliveryTime to be an explicit nil

### UnsetDeliveryTime
`func (o *ShippingRuleUpdate) UnsetDeliveryTime()`

UnsetDeliveryTime ensures that no value is present for DeliveryTime, not even an explicit nil
### GetIsActive

`func (o *ShippingRuleUpdate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ShippingRuleUpdate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ShippingRuleUpdate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ShippingRuleUpdate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *ShippingRuleUpdate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *ShippingRuleUpdate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetMaxWeightKg

`func (o *ShippingRuleUpdate) GetMaxWeightKg() float64`

GetMaxWeightKg returns the MaxWeightKg field if non-nil, zero value otherwise.

### GetMaxWeightKgOk

`func (o *ShippingRuleUpdate) GetMaxWeightKgOk() (*float64, bool)`

GetMaxWeightKgOk returns a tuple with the MaxWeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxWeightKg

`func (o *ShippingRuleUpdate) SetMaxWeightKg(v float64)`

SetMaxWeightKg sets MaxWeightKg field to given value.

### HasMaxWeightKg

`func (o *ShippingRuleUpdate) HasMaxWeightKg() bool`

HasMaxWeightKg returns a boolean if a field has been set.

### SetMaxWeightKgNil

`func (o *ShippingRuleUpdate) SetMaxWeightKgNil(b bool)`

 SetMaxWeightKgNil sets the value for MaxWeightKg to be an explicit nil

### UnsetMaxWeightKg
`func (o *ShippingRuleUpdate) UnsetMaxWeightKg()`

UnsetMaxWeightKg ensures that no value is present for MaxWeightKg, not even an explicit nil
### GetMinWeightKg

`func (o *ShippingRuleUpdate) GetMinWeightKg() float64`

GetMinWeightKg returns the MinWeightKg field if non-nil, zero value otherwise.

### GetMinWeightKgOk

`func (o *ShippingRuleUpdate) GetMinWeightKgOk() (*float64, bool)`

GetMinWeightKgOk returns a tuple with the MinWeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWeightKg

`func (o *ShippingRuleUpdate) SetMinWeightKg(v float64)`

SetMinWeightKg sets MinWeightKg field to given value.

### HasMinWeightKg

`func (o *ShippingRuleUpdate) HasMinWeightKg() bool`

HasMinWeightKg returns a boolean if a field has been set.

### SetMinWeightKgNil

`func (o *ShippingRuleUpdate) SetMinWeightKgNil(b bool)`

 SetMinWeightKgNil sets the value for MinWeightKg to be an explicit nil

### UnsetMinWeightKg
`func (o *ShippingRuleUpdate) UnsetMinWeightKg()`

UnsetMinWeightKg ensures that no value is present for MinWeightKg, not even an explicit nil
### GetName

`func (o *ShippingRuleUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShippingRuleUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShippingRuleUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ShippingRuleUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ShippingRuleUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ShippingRuleUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetNotes

`func (o *ShippingRuleUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ShippingRuleUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ShippingRuleUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ShippingRuleUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ShippingRuleUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ShippingRuleUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPrice

`func (o *ShippingRuleUpdate) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ShippingRuleUpdate) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ShippingRuleUpdate) SetPrice(v string)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ShippingRuleUpdate) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### SetPriceNil

`func (o *ShippingRuleUpdate) SetPriceNil(b bool)`

 SetPriceNil sets the value for Price to be an explicit nil

### UnsetPrice
`func (o *ShippingRuleUpdate) UnsetPrice()`

UnsetPrice ensures that no value is present for Price, not even an explicit nil
### GetPriority

`func (o *ShippingRuleUpdate) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ShippingRuleUpdate) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ShippingRuleUpdate) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ShippingRuleUpdate) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### SetPriorityNil

`func (o *ShippingRuleUpdate) SetPriorityNil(b bool)`

 SetPriorityNil sets the value for Priority to be an explicit nil

### UnsetPriority
`func (o *ShippingRuleUpdate) UnsetPriority()`

UnsetPriority ensures that no value is present for Priority, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


