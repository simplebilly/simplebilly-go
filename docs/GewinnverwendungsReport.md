# GewinnverwendungsReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bilanzgewinn** | **string** | Bilanzgewinn nach Einstellung (§ 174 AktG, Beschluss der HV). | 
**GesetzlicheRuecklageBestand** | **string** |  | 
**GesetzlicheRuecklageCap** | **string** | Deckel: 10 % des Grundkapitals (§ 150 Abs. 2 AktG). | 
**GesetzlicheRuecklageNach** | **string** | Rücklage nach Einstellung. | 
**GesetzlicheRuecklageSoll** | **string** | Vorgeschlagene Einstellung in die gesetzliche Rücklage (§ 150 Abs. 2 AktG). | 
**GezeichnetesKapital** | **string** |  | 
**Jahresueberschuss** | **string** |  | 
**Year** | **int32** |  | 
**Zeilen** | [**[]GewinnverwendungsZeile**](GewinnverwendungsZeile.md) |  | 

## Methods

### NewGewinnverwendungsReport

`func NewGewinnverwendungsReport(bilanzgewinn string, gesetzlicheRuecklageBestand string, gesetzlicheRuecklageCap string, gesetzlicheRuecklageNach string, gesetzlicheRuecklageSoll string, gezeichnetesKapital string, jahresueberschuss string, year int32, zeilen []GewinnverwendungsZeile, ) *GewinnverwendungsReport`

NewGewinnverwendungsReport instantiates a new GewinnverwendungsReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGewinnverwendungsReportWithDefaults

`func NewGewinnverwendungsReportWithDefaults() *GewinnverwendungsReport`

NewGewinnverwendungsReportWithDefaults instantiates a new GewinnverwendungsReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilanzgewinn

`func (o *GewinnverwendungsReport) GetBilanzgewinn() string`

GetBilanzgewinn returns the Bilanzgewinn field if non-nil, zero value otherwise.

### GetBilanzgewinnOk

`func (o *GewinnverwendungsReport) GetBilanzgewinnOk() (*string, bool)`

GetBilanzgewinnOk returns a tuple with the Bilanzgewinn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilanzgewinn

`func (o *GewinnverwendungsReport) SetBilanzgewinn(v string)`

SetBilanzgewinn sets Bilanzgewinn field to given value.


### GetGesetzlicheRuecklageBestand

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageBestand() string`

GetGesetzlicheRuecklageBestand returns the GesetzlicheRuecklageBestand field if non-nil, zero value otherwise.

### GetGesetzlicheRuecklageBestandOk

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageBestandOk() (*string, bool)`

GetGesetzlicheRuecklageBestandOk returns a tuple with the GesetzlicheRuecklageBestand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGesetzlicheRuecklageBestand

`func (o *GewinnverwendungsReport) SetGesetzlicheRuecklageBestand(v string)`

SetGesetzlicheRuecklageBestand sets GesetzlicheRuecklageBestand field to given value.


### GetGesetzlicheRuecklageCap

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageCap() string`

GetGesetzlicheRuecklageCap returns the GesetzlicheRuecklageCap field if non-nil, zero value otherwise.

### GetGesetzlicheRuecklageCapOk

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageCapOk() (*string, bool)`

GetGesetzlicheRuecklageCapOk returns a tuple with the GesetzlicheRuecklageCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGesetzlicheRuecklageCap

`func (o *GewinnverwendungsReport) SetGesetzlicheRuecklageCap(v string)`

SetGesetzlicheRuecklageCap sets GesetzlicheRuecklageCap field to given value.


### GetGesetzlicheRuecklageNach

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageNach() string`

GetGesetzlicheRuecklageNach returns the GesetzlicheRuecklageNach field if non-nil, zero value otherwise.

### GetGesetzlicheRuecklageNachOk

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageNachOk() (*string, bool)`

GetGesetzlicheRuecklageNachOk returns a tuple with the GesetzlicheRuecklageNach field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGesetzlicheRuecklageNach

`func (o *GewinnverwendungsReport) SetGesetzlicheRuecklageNach(v string)`

SetGesetzlicheRuecklageNach sets GesetzlicheRuecklageNach field to given value.


### GetGesetzlicheRuecklageSoll

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageSoll() string`

GetGesetzlicheRuecklageSoll returns the GesetzlicheRuecklageSoll field if non-nil, zero value otherwise.

### GetGesetzlicheRuecklageSollOk

`func (o *GewinnverwendungsReport) GetGesetzlicheRuecklageSollOk() (*string, bool)`

GetGesetzlicheRuecklageSollOk returns a tuple with the GesetzlicheRuecklageSoll field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGesetzlicheRuecklageSoll

`func (o *GewinnverwendungsReport) SetGesetzlicheRuecklageSoll(v string)`

SetGesetzlicheRuecklageSoll sets GesetzlicheRuecklageSoll field to given value.


### GetGezeichnetesKapital

`func (o *GewinnverwendungsReport) GetGezeichnetesKapital() string`

GetGezeichnetesKapital returns the GezeichnetesKapital field if non-nil, zero value otherwise.

### GetGezeichnetesKapitalOk

`func (o *GewinnverwendungsReport) GetGezeichnetesKapitalOk() (*string, bool)`

GetGezeichnetesKapitalOk returns a tuple with the GezeichnetesKapital field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGezeichnetesKapital

`func (o *GewinnverwendungsReport) SetGezeichnetesKapital(v string)`

SetGezeichnetesKapital sets GezeichnetesKapital field to given value.


### GetJahresueberschuss

`func (o *GewinnverwendungsReport) GetJahresueberschuss() string`

GetJahresueberschuss returns the Jahresueberschuss field if non-nil, zero value otherwise.

### GetJahresueberschussOk

`func (o *GewinnverwendungsReport) GetJahresueberschussOk() (*string, bool)`

GetJahresueberschussOk returns a tuple with the Jahresueberschuss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahresueberschuss

`func (o *GewinnverwendungsReport) SetJahresueberschuss(v string)`

SetJahresueberschuss sets Jahresueberschuss field to given value.


### GetYear

`func (o *GewinnverwendungsReport) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *GewinnverwendungsReport) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *GewinnverwendungsReport) SetYear(v int32)`

SetYear sets Year field to given value.


### GetZeilen

`func (o *GewinnverwendungsReport) GetZeilen() []GewinnverwendungsZeile`

GetZeilen returns the Zeilen field if non-nil, zero value otherwise.

### GetZeilenOk

`func (o *GewinnverwendungsReport) GetZeilenOk() (*[]GewinnverwendungsZeile, bool)`

GetZeilenOk returns a tuple with the Zeilen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZeilen

`func (o *GewinnverwendungsReport) SetZeilen(v []GewinnverwendungsZeile)`

SetZeilen sets Zeilen field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


