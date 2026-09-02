# ShippingRule

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

### NewShippingRule

`func NewShippingRule(name string, price string, ) *ShippingRule`

NewShippingRule instantiates a new ShippingRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingRuleWithDefaults

`func NewShippingRuleWithDefaults() *ShippingRule`

NewShippingRuleWithDefaults instantiates a new ShippingRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *ShippingRule) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ShippingRule) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ShippingRule) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *ShippingRule) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### SetCarrierNil

`func (o *ShippingRule) SetCarrierNil(b bool)`

 SetCarrierNil sets the value for Carrier to be an explicit nil

### UnsetCarrier
`func (o *ShippingRule) UnsetCarrier()`

UnsetCarrier ensures that no value is present for Carrier, not even an explicit nil
### GetCountry

`func (o *ShippingRule) GetCountry() CountryCode`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *ShippingRule) GetCountryOk() (*CountryCode, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *ShippingRule) SetCountry(v CountryCode)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *ShippingRule) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *ShippingRule) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *ShippingRule) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetDeliveryTime

`func (o *ShippingRule) GetDeliveryTime() string`

GetDeliveryTime returns the DeliveryTime field if non-nil, zero value otherwise.

### GetDeliveryTimeOk

`func (o *ShippingRule) GetDeliveryTimeOk() (*string, bool)`

GetDeliveryTimeOk returns a tuple with the DeliveryTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTime

`func (o *ShippingRule) SetDeliveryTime(v string)`

SetDeliveryTime sets DeliveryTime field to given value.

### HasDeliveryTime

`func (o *ShippingRule) HasDeliveryTime() bool`

HasDeliveryTime returns a boolean if a field has been set.

### SetDeliveryTimeNil

`func (o *ShippingRule) SetDeliveryTimeNil(b bool)`

 SetDeliveryTimeNil sets the value for DeliveryTime to be an explicit nil

### UnsetDeliveryTime
`func (o *ShippingRule) UnsetDeliveryTime()`

UnsetDeliveryTime ensures that no value is present for DeliveryTime, not even an explicit nil
### GetIsActive

`func (o *ShippingRule) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ShippingRule) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ShippingRule) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ShippingRule) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetMaxWeightKg

`func (o *ShippingRule) GetMaxWeightKg() float64`

GetMaxWeightKg returns the MaxWeightKg field if non-nil, zero value otherwise.

### GetMaxWeightKgOk

`func (o *ShippingRule) GetMaxWeightKgOk() (*float64, bool)`

GetMaxWeightKgOk returns a tuple with the MaxWeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxWeightKg

`func (o *ShippingRule) SetMaxWeightKg(v float64)`

SetMaxWeightKg sets MaxWeightKg field to given value.

### HasMaxWeightKg

`func (o *ShippingRule) HasMaxWeightKg() bool`

HasMaxWeightKg returns a boolean if a field has been set.

### SetMaxWeightKgNil

`func (o *ShippingRule) SetMaxWeightKgNil(b bool)`

 SetMaxWeightKgNil sets the value for MaxWeightKg to be an explicit nil

### UnsetMaxWeightKg
`func (o *ShippingRule) UnsetMaxWeightKg()`

UnsetMaxWeightKg ensures that no value is present for MaxWeightKg, not even an explicit nil
### GetMinWeightKg

`func (o *ShippingRule) GetMinWeightKg() float64`

GetMinWeightKg returns the MinWeightKg field if non-nil, zero value otherwise.

### GetMinWeightKgOk

`func (o *ShippingRule) GetMinWeightKgOk() (*float64, bool)`

GetMinWeightKgOk returns a tuple with the MinWeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWeightKg

`func (o *ShippingRule) SetMinWeightKg(v float64)`

SetMinWeightKg sets MinWeightKg field to given value.

### HasMinWeightKg

`func (o *ShippingRule) HasMinWeightKg() bool`

HasMinWeightKg returns a boolean if a field has been set.

### SetMinWeightKgNil

`func (o *ShippingRule) SetMinWeightKgNil(b bool)`

 SetMinWeightKgNil sets the value for MinWeightKg to be an explicit nil

### UnsetMinWeightKg
`func (o *ShippingRule) UnsetMinWeightKg()`

UnsetMinWeightKg ensures that no value is present for MinWeightKg, not even an explicit nil
### GetName

`func (o *ShippingRule) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShippingRule) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShippingRule) SetName(v string)`

SetName sets Name field to given value.


### GetNotes

`func (o *ShippingRule) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ShippingRule) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ShippingRule) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ShippingRule) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ShippingRule) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ShippingRule) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPrice

`func (o *ShippingRule) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ShippingRule) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ShippingRule) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetPriority

`func (o *ShippingRule) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ShippingRule) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ShippingRule) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ShippingRule) HasPriority() bool`

HasPriority returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


