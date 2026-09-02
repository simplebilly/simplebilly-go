# EuerZeileDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Abschnitt** | **string** |  | 
**BetragGesamt** | **string** |  | 
**Bezeichnung** | **string** |  | 
**Kategorien** | [**[]EuerKatSumme**](EuerKatSumme.md) |  | 
**Zeile** | **int32** |  | 

## Methods

### NewEuerZeileDetail

`func NewEuerZeileDetail(abschnitt string, betragGesamt string, bezeichnung string, kategorien []EuerKatSumme, zeile int32, ) *EuerZeileDetail`

NewEuerZeileDetail instantiates a new EuerZeileDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEuerZeileDetailWithDefaults

`func NewEuerZeileDetailWithDefaults() *EuerZeileDetail`

NewEuerZeileDetailWithDefaults instantiates a new EuerZeileDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAbschnitt

`func (o *EuerZeileDetail) GetAbschnitt() string`

GetAbschnitt returns the Abschnitt field if non-nil, zero value otherwise.

### GetAbschnittOk

`func (o *EuerZeileDetail) GetAbschnittOk() (*string, bool)`

GetAbschnittOk returns a tuple with the Abschnitt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbschnitt

`func (o *EuerZeileDetail) SetAbschnitt(v string)`

SetAbschnitt sets Abschnitt field to given value.


### GetBetragGesamt

`func (o *EuerZeileDetail) GetBetragGesamt() string`

GetBetragGesamt returns the BetragGesamt field if non-nil, zero value otherwise.

### GetBetragGesamtOk

`func (o *EuerZeileDetail) GetBetragGesamtOk() (*string, bool)`

GetBetragGesamtOk returns a tuple with the BetragGesamt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBetragGesamt

`func (o *EuerZeileDetail) SetBetragGesamt(v string)`

SetBetragGesamt sets BetragGesamt field to given value.


### GetBezeichnung

`func (o *EuerZeileDetail) GetBezeichnung() string`

GetBezeichnung returns the Bezeichnung field if non-nil, zero value otherwise.

### GetBezeichnungOk

`func (o *EuerZeileDetail) GetBezeichnungOk() (*string, bool)`

GetBezeichnungOk returns a tuple with the Bezeichnung field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBezeichnung

`func (o *EuerZeileDetail) SetBezeichnung(v string)`

SetBezeichnung sets Bezeichnung field to given value.


### GetKategorien

`func (o *EuerZeileDetail) GetKategorien() []EuerKatSumme`

GetKategorien returns the Kategorien field if non-nil, zero value otherwise.

### GetKategorienOk

`func (o *EuerZeileDetail) GetKategorienOk() (*[]EuerKatSumme, bool)`

GetKategorienOk returns a tuple with the Kategorien field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKategorien

`func (o *EuerZeileDetail) SetKategorien(v []EuerKatSumme)`

SetKategorien sets Kategorien field to given value.


### GetZeile

`func (o *EuerZeileDetail) GetZeile() int32`

GetZeile returns the Zeile field if non-nil, zero value otherwise.

### GetZeileOk

`func (o *EuerZeileDetail) GetZeileOk() (*int32, bool)`

GetZeileOk returns a tuple with the Zeile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZeile

`func (o *EuerZeileDetail) SetZeile(v int32)`

SetZeile sets Zeile field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


