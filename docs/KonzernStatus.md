# KonzernStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Groessenbefreit** | **bool** |  | 
**Kapitalmarktorientiert** | **bool** |  | 
**Konzernabschlusspflicht** | **bool** |  | 
**MissingGroupFigures** | **bool** | Keine group_figures-Zeile für das Jahr vorhanden → keine Größenbefreiung. | 
**Mutterunternehmen** | **bool** | Mutterunternehmen: mindestens eine beherrschte Beteiligung (§ 290 Abs. 1 HGB). | 
**ParentName** | Pointer to **NullableString** | Mutterunternehmen für die Zwischenholding-Befreiung (§ 291 HGB). | [optional] 
**ParentSitus** | Pointer to **NullableString** |  | [optional] 
**Participations** | [**[]KonzernBeteiligung**](KonzernBeteiligung.md) |  | 
**Thresholds** | [**KonzernThresholds**](KonzernThresholds.md) |  | 
**Year** | **int32** |  | 
**ZwischenholdingBefreit** | **bool** |  | 
**ZwischenholdingHinweis** | Pointer to **NullableString** | Hinweis zu den § 291-Voraussetzungen (EU/EWR-Sitz, geprüfter Konzernabschluss). | [optional] 

## Methods

### NewKonzernStatus

`func NewKonzernStatus(groessenbefreit bool, kapitalmarktorientiert bool, konzernabschlusspflicht bool, missingGroupFigures bool, mutterunternehmen bool, participations []KonzernBeteiligung, thresholds KonzernThresholds, year int32, zwischenholdingBefreit bool, ) *KonzernStatus`

NewKonzernStatus instantiates a new KonzernStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKonzernStatusWithDefaults

`func NewKonzernStatusWithDefaults() *KonzernStatus`

NewKonzernStatusWithDefaults instantiates a new KonzernStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroessenbefreit

`func (o *KonzernStatus) GetGroessenbefreit() bool`

GetGroessenbefreit returns the Groessenbefreit field if non-nil, zero value otherwise.

### GetGroessenbefreitOk

`func (o *KonzernStatus) GetGroessenbefreitOk() (*bool, bool)`

GetGroessenbefreitOk returns a tuple with the Groessenbefreit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroessenbefreit

`func (o *KonzernStatus) SetGroessenbefreit(v bool)`

SetGroessenbefreit sets Groessenbefreit field to given value.


### GetKapitalmarktorientiert

`func (o *KonzernStatus) GetKapitalmarktorientiert() bool`

GetKapitalmarktorientiert returns the Kapitalmarktorientiert field if non-nil, zero value otherwise.

### GetKapitalmarktorientiertOk

`func (o *KonzernStatus) GetKapitalmarktorientiertOk() (*bool, bool)`

GetKapitalmarktorientiertOk returns a tuple with the Kapitalmarktorientiert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKapitalmarktorientiert

`func (o *KonzernStatus) SetKapitalmarktorientiert(v bool)`

SetKapitalmarktorientiert sets Kapitalmarktorientiert field to given value.


### GetKonzernabschlusspflicht

`func (o *KonzernStatus) GetKonzernabschlusspflicht() bool`

GetKonzernabschlusspflicht returns the Konzernabschlusspflicht field if non-nil, zero value otherwise.

### GetKonzernabschlusspflichtOk

`func (o *KonzernStatus) GetKonzernabschlusspflichtOk() (*bool, bool)`

GetKonzernabschlusspflichtOk returns a tuple with the Konzernabschlusspflicht field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKonzernabschlusspflicht

`func (o *KonzernStatus) SetKonzernabschlusspflicht(v bool)`

SetKonzernabschlusspflicht sets Konzernabschlusspflicht field to given value.


### GetMissingGroupFigures

`func (o *KonzernStatus) GetMissingGroupFigures() bool`

GetMissingGroupFigures returns the MissingGroupFigures field if non-nil, zero value otherwise.

### GetMissingGroupFiguresOk

`func (o *KonzernStatus) GetMissingGroupFiguresOk() (*bool, bool)`

GetMissingGroupFiguresOk returns a tuple with the MissingGroupFigures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissingGroupFigures

`func (o *KonzernStatus) SetMissingGroupFigures(v bool)`

SetMissingGroupFigures sets MissingGroupFigures field to given value.


### GetMutterunternehmen

`func (o *KonzernStatus) GetMutterunternehmen() bool`

GetMutterunternehmen returns the Mutterunternehmen field if non-nil, zero value otherwise.

### GetMutterunternehmenOk

`func (o *KonzernStatus) GetMutterunternehmenOk() (*bool, bool)`

GetMutterunternehmenOk returns a tuple with the Mutterunternehmen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMutterunternehmen

`func (o *KonzernStatus) SetMutterunternehmen(v bool)`

SetMutterunternehmen sets Mutterunternehmen field to given value.


### GetParentName

`func (o *KonzernStatus) GetParentName() string`

GetParentName returns the ParentName field if non-nil, zero value otherwise.

### GetParentNameOk

`func (o *KonzernStatus) GetParentNameOk() (*string, bool)`

GetParentNameOk returns a tuple with the ParentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentName

`func (o *KonzernStatus) SetParentName(v string)`

SetParentName sets ParentName field to given value.

### HasParentName

`func (o *KonzernStatus) HasParentName() bool`

HasParentName returns a boolean if a field has been set.

### SetParentNameNil

`func (o *KonzernStatus) SetParentNameNil(b bool)`

 SetParentNameNil sets the value for ParentName to be an explicit nil

### UnsetParentName
`func (o *KonzernStatus) UnsetParentName()`

UnsetParentName ensures that no value is present for ParentName, not even an explicit nil
### GetParentSitus

`func (o *KonzernStatus) GetParentSitus() string`

GetParentSitus returns the ParentSitus field if non-nil, zero value otherwise.

### GetParentSitusOk

`func (o *KonzernStatus) GetParentSitusOk() (*string, bool)`

GetParentSitusOk returns a tuple with the ParentSitus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSitus

`func (o *KonzernStatus) SetParentSitus(v string)`

SetParentSitus sets ParentSitus field to given value.

### HasParentSitus

`func (o *KonzernStatus) HasParentSitus() bool`

HasParentSitus returns a boolean if a field has been set.

### SetParentSitusNil

`func (o *KonzernStatus) SetParentSitusNil(b bool)`

 SetParentSitusNil sets the value for ParentSitus to be an explicit nil

### UnsetParentSitus
`func (o *KonzernStatus) UnsetParentSitus()`

UnsetParentSitus ensures that no value is present for ParentSitus, not even an explicit nil
### GetParticipations

`func (o *KonzernStatus) GetParticipations() []KonzernBeteiligung`

GetParticipations returns the Participations field if non-nil, zero value otherwise.

### GetParticipationsOk

`func (o *KonzernStatus) GetParticipationsOk() (*[]KonzernBeteiligung, bool)`

GetParticipationsOk returns a tuple with the Participations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParticipations

`func (o *KonzernStatus) SetParticipations(v []KonzernBeteiligung)`

SetParticipations sets Participations field to given value.


### GetThresholds

`func (o *KonzernStatus) GetThresholds() KonzernThresholds`

GetThresholds returns the Thresholds field if non-nil, zero value otherwise.

### GetThresholdsOk

`func (o *KonzernStatus) GetThresholdsOk() (*KonzernThresholds, bool)`

GetThresholdsOk returns a tuple with the Thresholds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThresholds

`func (o *KonzernStatus) SetThresholds(v KonzernThresholds)`

SetThresholds sets Thresholds field to given value.


### GetYear

`func (o *KonzernStatus) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *KonzernStatus) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *KonzernStatus) SetYear(v int32)`

SetYear sets Year field to given value.


### GetZwischenholdingBefreit

`func (o *KonzernStatus) GetZwischenholdingBefreit() bool`

GetZwischenholdingBefreit returns the ZwischenholdingBefreit field if non-nil, zero value otherwise.

### GetZwischenholdingBefreitOk

`func (o *KonzernStatus) GetZwischenholdingBefreitOk() (*bool, bool)`

GetZwischenholdingBefreitOk returns a tuple with the ZwischenholdingBefreit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZwischenholdingBefreit

`func (o *KonzernStatus) SetZwischenholdingBefreit(v bool)`

SetZwischenholdingBefreit sets ZwischenholdingBefreit field to given value.


### GetZwischenholdingHinweis

`func (o *KonzernStatus) GetZwischenholdingHinweis() string`

GetZwischenholdingHinweis returns the ZwischenholdingHinweis field if non-nil, zero value otherwise.

### GetZwischenholdingHinweisOk

`func (o *KonzernStatus) GetZwischenholdingHinweisOk() (*string, bool)`

GetZwischenholdingHinweisOk returns a tuple with the ZwischenholdingHinweis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZwischenholdingHinweis

`func (o *KonzernStatus) SetZwischenholdingHinweis(v string)`

SetZwischenholdingHinweis sets ZwischenholdingHinweis field to given value.

### HasZwischenholdingHinweis

`func (o *KonzernStatus) HasZwischenholdingHinweis() bool`

HasZwischenholdingHinweis returns a boolean if a field has been set.

### SetZwischenholdingHinweisNil

`func (o *KonzernStatus) SetZwischenholdingHinweisNil(b bool)`

 SetZwischenholdingHinweisNil sets the value for ZwischenholdingHinweis to be an explicit nil

### UnsetZwischenholdingHinweis
`func (o *KonzernStatus) UnsetZwischenholdingHinweis()`

UnsetZwischenholdingHinweis ensures that no value is present for ZwischenholdingHinweis, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


