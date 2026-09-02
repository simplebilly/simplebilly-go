# FristenErgebnis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Anzahl** | **int32** |  | 
**Fristen** | [**[]FristEintrag**](FristEintrag.md) |  | 

## Methods

### NewFristenErgebnis

`func NewFristenErgebnis(anzahl int32, fristen []FristEintrag, ) *FristenErgebnis`

NewFristenErgebnis instantiates a new FristenErgebnis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFristenErgebnisWithDefaults

`func NewFristenErgebnisWithDefaults() *FristenErgebnis`

NewFristenErgebnisWithDefaults instantiates a new FristenErgebnis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnzahl

`func (o *FristenErgebnis) GetAnzahl() int32`

GetAnzahl returns the Anzahl field if non-nil, zero value otherwise.

### GetAnzahlOk

`func (o *FristenErgebnis) GetAnzahlOk() (*int32, bool)`

GetAnzahlOk returns a tuple with the Anzahl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnzahl

`func (o *FristenErgebnis) SetAnzahl(v int32)`

SetAnzahl sets Anzahl field to given value.


### GetFristen

`func (o *FristenErgebnis) GetFristen() []FristEintrag`

GetFristen returns the Fristen field if non-nil, zero value otherwise.

### GetFristenOk

`func (o *FristenErgebnis) GetFristenOk() (*[]FristEintrag, bool)`

GetFristenOk returns a tuple with the Fristen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFristen

`func (o *FristenErgebnis) SetFristen(v []FristEintrag)`

SetFristen sets Fristen field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


