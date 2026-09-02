# EuerErgebnis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnlageZugaenge** | **string** |  | 
**GewinnVerlust** | **string** |  | 
**Jahr** | **int32** |  | 
**SummeAusgaben** | **string** |  | 
**SummeEinnahmen** | **string** |  | 
**Zeilen** | [**[]EuerZeile**](EuerZeile.md) |  | 

## Methods

### NewEuerErgebnis

`func NewEuerErgebnis(anlageZugaenge string, gewinnVerlust string, jahr int32, summeAusgaben string, summeEinnahmen string, zeilen []EuerZeile, ) *EuerErgebnis`

NewEuerErgebnis instantiates a new EuerErgebnis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEuerErgebnisWithDefaults

`func NewEuerErgebnisWithDefaults() *EuerErgebnis`

NewEuerErgebnisWithDefaults instantiates a new EuerErgebnis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnlageZugaenge

`func (o *EuerErgebnis) GetAnlageZugaenge() string`

GetAnlageZugaenge returns the AnlageZugaenge field if non-nil, zero value otherwise.

### GetAnlageZugaengeOk

`func (o *EuerErgebnis) GetAnlageZugaengeOk() (*string, bool)`

GetAnlageZugaengeOk returns a tuple with the AnlageZugaenge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnlageZugaenge

`func (o *EuerErgebnis) SetAnlageZugaenge(v string)`

SetAnlageZugaenge sets AnlageZugaenge field to given value.


### GetGewinnVerlust

`func (o *EuerErgebnis) GetGewinnVerlust() string`

GetGewinnVerlust returns the GewinnVerlust field if non-nil, zero value otherwise.

### GetGewinnVerlustOk

`func (o *EuerErgebnis) GetGewinnVerlustOk() (*string, bool)`

GetGewinnVerlustOk returns a tuple with the GewinnVerlust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnVerlust

`func (o *EuerErgebnis) SetGewinnVerlust(v string)`

SetGewinnVerlust sets GewinnVerlust field to given value.


### GetJahr

`func (o *EuerErgebnis) GetJahr() int32`

GetJahr returns the Jahr field if non-nil, zero value otherwise.

### GetJahrOk

`func (o *EuerErgebnis) GetJahrOk() (*int32, bool)`

GetJahrOk returns a tuple with the Jahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahr

`func (o *EuerErgebnis) SetJahr(v int32)`

SetJahr sets Jahr field to given value.


### GetSummeAusgaben

`func (o *EuerErgebnis) GetSummeAusgaben() string`

GetSummeAusgaben returns the SummeAusgaben field if non-nil, zero value otherwise.

### GetSummeAusgabenOk

`func (o *EuerErgebnis) GetSummeAusgabenOk() (*string, bool)`

GetSummeAusgabenOk returns a tuple with the SummeAusgaben field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummeAusgaben

`func (o *EuerErgebnis) SetSummeAusgaben(v string)`

SetSummeAusgaben sets SummeAusgaben field to given value.


### GetSummeEinnahmen

`func (o *EuerErgebnis) GetSummeEinnahmen() string`

GetSummeEinnahmen returns the SummeEinnahmen field if non-nil, zero value otherwise.

### GetSummeEinnahmenOk

`func (o *EuerErgebnis) GetSummeEinnahmenOk() (*string, bool)`

GetSummeEinnahmenOk returns a tuple with the SummeEinnahmen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummeEinnahmen

`func (o *EuerErgebnis) SetSummeEinnahmen(v string)`

SetSummeEinnahmen sets SummeEinnahmen field to given value.


### GetZeilen

`func (o *EuerErgebnis) GetZeilen() []EuerZeile`

GetZeilen returns the Zeilen field if non-nil, zero value otherwise.

### GetZeilenOk

`func (o *EuerErgebnis) GetZeilenOk() (*[]EuerZeile, bool)`

GetZeilenOk returns a tuple with the Zeilen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZeilen

`func (o *EuerErgebnis) SetZeilen(v []EuerZeile)`

SetZeilen sets Zeilen field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


