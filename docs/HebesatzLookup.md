# HebesatzLookup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bundesland** | **string** |  | 
**CountryCode** | **string** |  | 
**GemeindeName** | **string** |  | 
**Gemeindeschluessel** | **string** |  | 
**HebesatzGewerbesteuer** | **float64** |  | 
**HebesatzGrundsteuerB** | Pointer to **NullableFloat64** |  | [optional] 
**Jahr** | **int32** |  | 
**Landkreis** | Pointer to **NullableString** |  | [optional] 
**ValidFrom** | **string** |  | 
**ValidTo** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewHebesatzLookup

`func NewHebesatzLookup(bundesland string, countryCode string, gemeindeName string, gemeindeschluessel string, hebesatzGewerbesteuer float64, jahr int32, validFrom string, ) *HebesatzLookup`

NewHebesatzLookup instantiates a new HebesatzLookup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHebesatzLookupWithDefaults

`func NewHebesatzLookupWithDefaults() *HebesatzLookup`

NewHebesatzLookupWithDefaults instantiates a new HebesatzLookup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBundesland

`func (o *HebesatzLookup) GetBundesland() string`

GetBundesland returns the Bundesland field if non-nil, zero value otherwise.

### GetBundeslandOk

`func (o *HebesatzLookup) GetBundeslandOk() (*string, bool)`

GetBundeslandOk returns a tuple with the Bundesland field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundesland

`func (o *HebesatzLookup) SetBundesland(v string)`

SetBundesland sets Bundesland field to given value.


### GetCountryCode

`func (o *HebesatzLookup) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *HebesatzLookup) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *HebesatzLookup) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetGemeindeName

`func (o *HebesatzLookup) GetGemeindeName() string`

GetGemeindeName returns the GemeindeName field if non-nil, zero value otherwise.

### GetGemeindeNameOk

`func (o *HebesatzLookup) GetGemeindeNameOk() (*string, bool)`

GetGemeindeNameOk returns a tuple with the GemeindeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGemeindeName

`func (o *HebesatzLookup) SetGemeindeName(v string)`

SetGemeindeName sets GemeindeName field to given value.


### GetGemeindeschluessel

`func (o *HebesatzLookup) GetGemeindeschluessel() string`

GetGemeindeschluessel returns the Gemeindeschluessel field if non-nil, zero value otherwise.

### GetGemeindeschluesselOk

`func (o *HebesatzLookup) GetGemeindeschluesselOk() (*string, bool)`

GetGemeindeschluesselOk returns a tuple with the Gemeindeschluessel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGemeindeschluessel

`func (o *HebesatzLookup) SetGemeindeschluessel(v string)`

SetGemeindeschluessel sets Gemeindeschluessel field to given value.


### GetHebesatzGewerbesteuer

`func (o *HebesatzLookup) GetHebesatzGewerbesteuer() float64`

GetHebesatzGewerbesteuer returns the HebesatzGewerbesteuer field if non-nil, zero value otherwise.

### GetHebesatzGewerbesteuerOk

`func (o *HebesatzLookup) GetHebesatzGewerbesteuerOk() (*float64, bool)`

GetHebesatzGewerbesteuerOk returns a tuple with the HebesatzGewerbesteuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHebesatzGewerbesteuer

`func (o *HebesatzLookup) SetHebesatzGewerbesteuer(v float64)`

SetHebesatzGewerbesteuer sets HebesatzGewerbesteuer field to given value.


### GetHebesatzGrundsteuerB

`func (o *HebesatzLookup) GetHebesatzGrundsteuerB() float64`

GetHebesatzGrundsteuerB returns the HebesatzGrundsteuerB field if non-nil, zero value otherwise.

### GetHebesatzGrundsteuerBOk

`func (o *HebesatzLookup) GetHebesatzGrundsteuerBOk() (*float64, bool)`

GetHebesatzGrundsteuerBOk returns a tuple with the HebesatzGrundsteuerB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHebesatzGrundsteuerB

`func (o *HebesatzLookup) SetHebesatzGrundsteuerB(v float64)`

SetHebesatzGrundsteuerB sets HebesatzGrundsteuerB field to given value.

### HasHebesatzGrundsteuerB

`func (o *HebesatzLookup) HasHebesatzGrundsteuerB() bool`

HasHebesatzGrundsteuerB returns a boolean if a field has been set.

### SetHebesatzGrundsteuerBNil

`func (o *HebesatzLookup) SetHebesatzGrundsteuerBNil(b bool)`

 SetHebesatzGrundsteuerBNil sets the value for HebesatzGrundsteuerB to be an explicit nil

### UnsetHebesatzGrundsteuerB
`func (o *HebesatzLookup) UnsetHebesatzGrundsteuerB()`

UnsetHebesatzGrundsteuerB ensures that no value is present for HebesatzGrundsteuerB, not even an explicit nil
### GetJahr

`func (o *HebesatzLookup) GetJahr() int32`

GetJahr returns the Jahr field if non-nil, zero value otherwise.

### GetJahrOk

`func (o *HebesatzLookup) GetJahrOk() (*int32, bool)`

GetJahrOk returns a tuple with the Jahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahr

`func (o *HebesatzLookup) SetJahr(v int32)`

SetJahr sets Jahr field to given value.


### GetLandkreis

`func (o *HebesatzLookup) GetLandkreis() string`

GetLandkreis returns the Landkreis field if non-nil, zero value otherwise.

### GetLandkreisOk

`func (o *HebesatzLookup) GetLandkreisOk() (*string, bool)`

GetLandkreisOk returns a tuple with the Landkreis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLandkreis

`func (o *HebesatzLookup) SetLandkreis(v string)`

SetLandkreis sets Landkreis field to given value.

### HasLandkreis

`func (o *HebesatzLookup) HasLandkreis() bool`

HasLandkreis returns a boolean if a field has been set.

### SetLandkreisNil

`func (o *HebesatzLookup) SetLandkreisNil(b bool)`

 SetLandkreisNil sets the value for Landkreis to be an explicit nil

### UnsetLandkreis
`func (o *HebesatzLookup) UnsetLandkreis()`

UnsetLandkreis ensures that no value is present for Landkreis, not even an explicit nil
### GetValidFrom

`func (o *HebesatzLookup) GetValidFrom() string`

GetValidFrom returns the ValidFrom field if non-nil, zero value otherwise.

### GetValidFromOk

`func (o *HebesatzLookup) GetValidFromOk() (*string, bool)`

GetValidFromOk returns a tuple with the ValidFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidFrom

`func (o *HebesatzLookup) SetValidFrom(v string)`

SetValidFrom sets ValidFrom field to given value.


### GetValidTo

`func (o *HebesatzLookup) GetValidTo() string`

GetValidTo returns the ValidTo field if non-nil, zero value otherwise.

### GetValidToOk

`func (o *HebesatzLookup) GetValidToOk() (*string, bool)`

GetValidToOk returns a tuple with the ValidTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidTo

`func (o *HebesatzLookup) SetValidTo(v string)`

SetValidTo sets ValidTo field to given value.

### HasValidTo

`func (o *HebesatzLookup) HasValidTo() bool`

HasValidTo returns a boolean if a field has been set.

### SetValidToNil

`func (o *HebesatzLookup) SetValidToNil(b bool)`

 SetValidToNil sets the value for ValidTo to be an explicit nil

### UnsetValidTo
`func (o *HebesatzLookup) UnsetValidTo()`

UnsetValidTo ensures that no value is present for ValidTo, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


