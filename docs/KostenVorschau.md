# KostenVorschau

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Eintraege** | [**[]KostenEintrag**](KostenEintrag.md) |  | 
**Gesamt** | **string** |  | 

## Methods

### NewKostenVorschau

`func NewKostenVorschau(eintraege []KostenEintrag, gesamt string, ) *KostenVorschau`

NewKostenVorschau instantiates a new KostenVorschau object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKostenVorschauWithDefaults

`func NewKostenVorschauWithDefaults() *KostenVorschau`

NewKostenVorschauWithDefaults instantiates a new KostenVorschau object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEintraege

`func (o *KostenVorschau) GetEintraege() []KostenEintrag`

GetEintraege returns the Eintraege field if non-nil, zero value otherwise.

### GetEintraegeOk

`func (o *KostenVorschau) GetEintraegeOk() (*[]KostenEintrag, bool)`

GetEintraegeOk returns a tuple with the Eintraege field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEintraege

`func (o *KostenVorschau) SetEintraege(v []KostenEintrag)`

SetEintraege sets Eintraege field to given value.


### GetGesamt

`func (o *KostenVorschau) GetGesamt() string`

GetGesamt returns the Gesamt field if non-nil, zero value otherwise.

### GetGesamtOk

`func (o *KostenVorschau) GetGesamtOk() (*string, bool)`

GetGesamtOk returns a tuple with the Gesamt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGesamt

`func (o *KostenVorschau) SetGesamt(v string)`

SetGesamt sets Gesamt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


