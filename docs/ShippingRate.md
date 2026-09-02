# ShippingRate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Breakdown** | Pointer to **NullableString** |  | [optional] 
**Carrier** | **string** |  | 
**CrossBorderSurcharge** | Pointer to **NullableString** |  | [optional] 
**DestinationCountry** | **string** | ISO-2 code of destination country. | 
**EstimatedDays** | Pointer to **NullableInt32** |  | [optional] 
**FromApi** | **bool** | True when the rate was obtained via an API call rather than calculation. | 
**InsuredValue** | Pointer to **NullableString** |  | [optional] 
**IslandSurcharge** | Pointer to **NullableString** |  | [optional] 
**OriginCountry** | **string** | ISO-2 code of origin country. | 
**Rate** | **string** |  | 
**Service** | **string** |  | 
**VolumeDiscount** | Pointer to **NullableString** |  | [optional] 
**WeightKg** | **float64** |  | 

## Methods

### NewShippingRate

`func NewShippingRate(carrier string, destinationCountry string, fromApi bool, originCountry string, rate string, service string, weightKg float64, ) *ShippingRate`

NewShippingRate instantiates a new ShippingRate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingRateWithDefaults

`func NewShippingRateWithDefaults() *ShippingRate`

NewShippingRateWithDefaults instantiates a new ShippingRate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBreakdown

`func (o *ShippingRate) GetBreakdown() string`

GetBreakdown returns the Breakdown field if non-nil, zero value otherwise.

### GetBreakdownOk

`func (o *ShippingRate) GetBreakdownOk() (*string, bool)`

GetBreakdownOk returns a tuple with the Breakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakdown

`func (o *ShippingRate) SetBreakdown(v string)`

SetBreakdown sets Breakdown field to given value.

### HasBreakdown

`func (o *ShippingRate) HasBreakdown() bool`

HasBreakdown returns a boolean if a field has been set.

### SetBreakdownNil

`func (o *ShippingRate) SetBreakdownNil(b bool)`

 SetBreakdownNil sets the value for Breakdown to be an explicit nil

### UnsetBreakdown
`func (o *ShippingRate) UnsetBreakdown()`

UnsetBreakdown ensures that no value is present for Breakdown, not even an explicit nil
### GetCarrier

`func (o *ShippingRate) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ShippingRate) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ShippingRate) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.


### GetCrossBorderSurcharge

`func (o *ShippingRate) GetCrossBorderSurcharge() string`

GetCrossBorderSurcharge returns the CrossBorderSurcharge field if non-nil, zero value otherwise.

### GetCrossBorderSurchargeOk

`func (o *ShippingRate) GetCrossBorderSurchargeOk() (*string, bool)`

GetCrossBorderSurchargeOk returns a tuple with the CrossBorderSurcharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrossBorderSurcharge

`func (o *ShippingRate) SetCrossBorderSurcharge(v string)`

SetCrossBorderSurcharge sets CrossBorderSurcharge field to given value.

### HasCrossBorderSurcharge

`func (o *ShippingRate) HasCrossBorderSurcharge() bool`

HasCrossBorderSurcharge returns a boolean if a field has been set.

### SetCrossBorderSurchargeNil

`func (o *ShippingRate) SetCrossBorderSurchargeNil(b bool)`

 SetCrossBorderSurchargeNil sets the value for CrossBorderSurcharge to be an explicit nil

### UnsetCrossBorderSurcharge
`func (o *ShippingRate) UnsetCrossBorderSurcharge()`

UnsetCrossBorderSurcharge ensures that no value is present for CrossBorderSurcharge, not even an explicit nil
### GetDestinationCountry

`func (o *ShippingRate) GetDestinationCountry() string`

GetDestinationCountry returns the DestinationCountry field if non-nil, zero value otherwise.

### GetDestinationCountryOk

`func (o *ShippingRate) GetDestinationCountryOk() (*string, bool)`

GetDestinationCountryOk returns a tuple with the DestinationCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationCountry

`func (o *ShippingRate) SetDestinationCountry(v string)`

SetDestinationCountry sets DestinationCountry field to given value.


### GetEstimatedDays

`func (o *ShippingRate) GetEstimatedDays() int32`

GetEstimatedDays returns the EstimatedDays field if non-nil, zero value otherwise.

### GetEstimatedDaysOk

`func (o *ShippingRate) GetEstimatedDaysOk() (*int32, bool)`

GetEstimatedDaysOk returns a tuple with the EstimatedDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedDays

`func (o *ShippingRate) SetEstimatedDays(v int32)`

SetEstimatedDays sets EstimatedDays field to given value.

### HasEstimatedDays

`func (o *ShippingRate) HasEstimatedDays() bool`

HasEstimatedDays returns a boolean if a field has been set.

### SetEstimatedDaysNil

`func (o *ShippingRate) SetEstimatedDaysNil(b bool)`

 SetEstimatedDaysNil sets the value for EstimatedDays to be an explicit nil

### UnsetEstimatedDays
`func (o *ShippingRate) UnsetEstimatedDays()`

UnsetEstimatedDays ensures that no value is present for EstimatedDays, not even an explicit nil
### GetFromApi

`func (o *ShippingRate) GetFromApi() bool`

GetFromApi returns the FromApi field if non-nil, zero value otherwise.

### GetFromApiOk

`func (o *ShippingRate) GetFromApiOk() (*bool, bool)`

GetFromApiOk returns a tuple with the FromApi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromApi

`func (o *ShippingRate) SetFromApi(v bool)`

SetFromApi sets FromApi field to given value.


### GetInsuredValue

`func (o *ShippingRate) GetInsuredValue() string`

GetInsuredValue returns the InsuredValue field if non-nil, zero value otherwise.

### GetInsuredValueOk

`func (o *ShippingRate) GetInsuredValueOk() (*string, bool)`

GetInsuredValueOk returns a tuple with the InsuredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsuredValue

`func (o *ShippingRate) SetInsuredValue(v string)`

SetInsuredValue sets InsuredValue field to given value.

### HasInsuredValue

`func (o *ShippingRate) HasInsuredValue() bool`

HasInsuredValue returns a boolean if a field has been set.

### SetInsuredValueNil

`func (o *ShippingRate) SetInsuredValueNil(b bool)`

 SetInsuredValueNil sets the value for InsuredValue to be an explicit nil

### UnsetInsuredValue
`func (o *ShippingRate) UnsetInsuredValue()`

UnsetInsuredValue ensures that no value is present for InsuredValue, not even an explicit nil
### GetIslandSurcharge

`func (o *ShippingRate) GetIslandSurcharge() string`

GetIslandSurcharge returns the IslandSurcharge field if non-nil, zero value otherwise.

### GetIslandSurchargeOk

`func (o *ShippingRate) GetIslandSurchargeOk() (*string, bool)`

GetIslandSurchargeOk returns a tuple with the IslandSurcharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIslandSurcharge

`func (o *ShippingRate) SetIslandSurcharge(v string)`

SetIslandSurcharge sets IslandSurcharge field to given value.

### HasIslandSurcharge

`func (o *ShippingRate) HasIslandSurcharge() bool`

HasIslandSurcharge returns a boolean if a field has been set.

### SetIslandSurchargeNil

`func (o *ShippingRate) SetIslandSurchargeNil(b bool)`

 SetIslandSurchargeNil sets the value for IslandSurcharge to be an explicit nil

### UnsetIslandSurcharge
`func (o *ShippingRate) UnsetIslandSurcharge()`

UnsetIslandSurcharge ensures that no value is present for IslandSurcharge, not even an explicit nil
### GetOriginCountry

`func (o *ShippingRate) GetOriginCountry() string`

GetOriginCountry returns the OriginCountry field if non-nil, zero value otherwise.

### GetOriginCountryOk

`func (o *ShippingRate) GetOriginCountryOk() (*string, bool)`

GetOriginCountryOk returns a tuple with the OriginCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginCountry

`func (o *ShippingRate) SetOriginCountry(v string)`

SetOriginCountry sets OriginCountry field to given value.


### GetRate

`func (o *ShippingRate) GetRate() string`

GetRate returns the Rate field if non-nil, zero value otherwise.

### GetRateOk

`func (o *ShippingRate) GetRateOk() (*string, bool)`

GetRateOk returns a tuple with the Rate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRate

`func (o *ShippingRate) SetRate(v string)`

SetRate sets Rate field to given value.


### GetService

`func (o *ShippingRate) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *ShippingRate) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *ShippingRate) SetService(v string)`

SetService sets Service field to given value.


### GetVolumeDiscount

`func (o *ShippingRate) GetVolumeDiscount() string`

GetVolumeDiscount returns the VolumeDiscount field if non-nil, zero value otherwise.

### GetVolumeDiscountOk

`func (o *ShippingRate) GetVolumeDiscountOk() (*string, bool)`

GetVolumeDiscountOk returns a tuple with the VolumeDiscount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumeDiscount

`func (o *ShippingRate) SetVolumeDiscount(v string)`

SetVolumeDiscount sets VolumeDiscount field to given value.

### HasVolumeDiscount

`func (o *ShippingRate) HasVolumeDiscount() bool`

HasVolumeDiscount returns a boolean if a field has been set.

### SetVolumeDiscountNil

`func (o *ShippingRate) SetVolumeDiscountNil(b bool)`

 SetVolumeDiscountNil sets the value for VolumeDiscount to be an explicit nil

### UnsetVolumeDiscount
`func (o *ShippingRate) UnsetVolumeDiscount()`

UnsetVolumeDiscount ensures that no value is present for VolumeDiscount, not even an explicit nil
### GetWeightKg

`func (o *ShippingRate) GetWeightKg() float64`

GetWeightKg returns the WeightKg field if non-nil, zero value otherwise.

### GetWeightKgOk

`func (o *ShippingRate) GetWeightKgOk() (*float64, bool)`

GetWeightKgOk returns a tuple with the WeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightKg

`func (o *ShippingRate) SetWeightKg(v float64)`

SetWeightKg sets WeightKg field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


