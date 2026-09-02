# TaxRateCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountryCode** | **string** | ISO 3166-1 alpha-2 country code. | 
**EffectiveFrom** | Pointer to **NullableString** | Date this rate took effect; &#x60;None&#x60; &#x3D; not date-bound. | [optional] 
**IsDefault** | **bool** | Default rate for the country (one per country); fallback for lookups when no dated rate applies. | 
**Name** | **string** | Human name, e.g. \&quot;VAT\&quot;. | 
**RatePercent** | **int64** | Rate in hundredths of a percent: 1900 &#x3D; 19.00%. | 

## Methods

### NewTaxRateCreate

`func NewTaxRateCreate(countryCode string, isDefault bool, name string, ratePercent int64, ) *TaxRateCreate`

NewTaxRateCreate instantiates a new TaxRateCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaxRateCreateWithDefaults

`func NewTaxRateCreateWithDefaults() *TaxRateCreate`

NewTaxRateCreateWithDefaults instantiates a new TaxRateCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountryCode

`func (o *TaxRateCreate) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *TaxRateCreate) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *TaxRateCreate) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetEffectiveFrom

`func (o *TaxRateCreate) GetEffectiveFrom() string`

GetEffectiveFrom returns the EffectiveFrom field if non-nil, zero value otherwise.

### GetEffectiveFromOk

`func (o *TaxRateCreate) GetEffectiveFromOk() (*string, bool)`

GetEffectiveFromOk returns a tuple with the EffectiveFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveFrom

`func (o *TaxRateCreate) SetEffectiveFrom(v string)`

SetEffectiveFrom sets EffectiveFrom field to given value.

### HasEffectiveFrom

`func (o *TaxRateCreate) HasEffectiveFrom() bool`

HasEffectiveFrom returns a boolean if a field has been set.

### SetEffectiveFromNil

`func (o *TaxRateCreate) SetEffectiveFromNil(b bool)`

 SetEffectiveFromNil sets the value for EffectiveFrom to be an explicit nil

### UnsetEffectiveFrom
`func (o *TaxRateCreate) UnsetEffectiveFrom()`

UnsetEffectiveFrom ensures that no value is present for EffectiveFrom, not even an explicit nil
### GetIsDefault

`func (o *TaxRateCreate) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *TaxRateCreate) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *TaxRateCreate) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.


### GetName

`func (o *TaxRateCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TaxRateCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TaxRateCreate) SetName(v string)`

SetName sets Name field to given value.


### GetRatePercent

`func (o *TaxRateCreate) GetRatePercent() int64`

GetRatePercent returns the RatePercent field if non-nil, zero value otherwise.

### GetRatePercentOk

`func (o *TaxRateCreate) GetRatePercentOk() (*int64, bool)`

GetRatePercentOk returns a tuple with the RatePercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatePercent

`func (o *TaxRateCreate) SetRatePercent(v int64)`

SetRatePercent sets RatePercent field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


