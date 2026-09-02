# StillePartnerZeile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Auseinandersetzungsguthaben** | **string** |  | 
**Gewinnanteil** | **string** |  | 
**Gewinnvortrag** | **string** |  | 
**Hinweis** | Pointer to **NullableString** |  | [optional] 
**InstrumentType** | **string** |  | 
**Kest** | **string** |  | 
**Name** | **string** |  | 
**VerlustVerrechnungskonto** | **string** |  | 
**Verlustanteil** | **string** |  | 

## Methods

### NewStillePartnerZeile

`func NewStillePartnerZeile(auseinandersetzungsguthaben string, gewinnanteil string, gewinnvortrag string, instrumentType string, kest string, name string, verlustVerrechnungskonto string, verlustanteil string, ) *StillePartnerZeile`

NewStillePartnerZeile instantiates a new StillePartnerZeile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStillePartnerZeileWithDefaults

`func NewStillePartnerZeileWithDefaults() *StillePartnerZeile`

NewStillePartnerZeileWithDefaults instantiates a new StillePartnerZeile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuseinandersetzungsguthaben

`func (o *StillePartnerZeile) GetAuseinandersetzungsguthaben() string`

GetAuseinandersetzungsguthaben returns the Auseinandersetzungsguthaben field if non-nil, zero value otherwise.

### GetAuseinandersetzungsguthabenOk

`func (o *StillePartnerZeile) GetAuseinandersetzungsguthabenOk() (*string, bool)`

GetAuseinandersetzungsguthabenOk returns a tuple with the Auseinandersetzungsguthaben field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuseinandersetzungsguthaben

`func (o *StillePartnerZeile) SetAuseinandersetzungsguthaben(v string)`

SetAuseinandersetzungsguthaben sets Auseinandersetzungsguthaben field to given value.


### GetGewinnanteil

`func (o *StillePartnerZeile) GetGewinnanteil() string`

GetGewinnanteil returns the Gewinnanteil field if non-nil, zero value otherwise.

### GetGewinnanteilOk

`func (o *StillePartnerZeile) GetGewinnanteilOk() (*string, bool)`

GetGewinnanteilOk returns a tuple with the Gewinnanteil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnanteil

`func (o *StillePartnerZeile) SetGewinnanteil(v string)`

SetGewinnanteil sets Gewinnanteil field to given value.


### GetGewinnvortrag

`func (o *StillePartnerZeile) GetGewinnvortrag() string`

GetGewinnvortrag returns the Gewinnvortrag field if non-nil, zero value otherwise.

### GetGewinnvortragOk

`func (o *StillePartnerZeile) GetGewinnvortragOk() (*string, bool)`

GetGewinnvortragOk returns a tuple with the Gewinnvortrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnvortrag

`func (o *StillePartnerZeile) SetGewinnvortrag(v string)`

SetGewinnvortrag sets Gewinnvortrag field to given value.


### GetHinweis

`func (o *StillePartnerZeile) GetHinweis() string`

GetHinweis returns the Hinweis field if non-nil, zero value otherwise.

### GetHinweisOk

`func (o *StillePartnerZeile) GetHinweisOk() (*string, bool)`

GetHinweisOk returns a tuple with the Hinweis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHinweis

`func (o *StillePartnerZeile) SetHinweis(v string)`

SetHinweis sets Hinweis field to given value.

### HasHinweis

`func (o *StillePartnerZeile) HasHinweis() bool`

HasHinweis returns a boolean if a field has been set.

### SetHinweisNil

`func (o *StillePartnerZeile) SetHinweisNil(b bool)`

 SetHinweisNil sets the value for Hinweis to be an explicit nil

### UnsetHinweis
`func (o *StillePartnerZeile) UnsetHinweis()`

UnsetHinweis ensures that no value is present for Hinweis, not even an explicit nil
### GetInstrumentType

`func (o *StillePartnerZeile) GetInstrumentType() string`

GetInstrumentType returns the InstrumentType field if non-nil, zero value otherwise.

### GetInstrumentTypeOk

`func (o *StillePartnerZeile) GetInstrumentTypeOk() (*string, bool)`

GetInstrumentTypeOk returns a tuple with the InstrumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstrumentType

`func (o *StillePartnerZeile) SetInstrumentType(v string)`

SetInstrumentType sets InstrumentType field to given value.


### GetKest

`func (o *StillePartnerZeile) GetKest() string`

GetKest returns the Kest field if non-nil, zero value otherwise.

### GetKestOk

`func (o *StillePartnerZeile) GetKestOk() (*string, bool)`

GetKestOk returns a tuple with the Kest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKest

`func (o *StillePartnerZeile) SetKest(v string)`

SetKest sets Kest field to given value.


### GetName

`func (o *StillePartnerZeile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StillePartnerZeile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StillePartnerZeile) SetName(v string)`

SetName sets Name field to given value.


### GetVerlustVerrechnungskonto

`func (o *StillePartnerZeile) GetVerlustVerrechnungskonto() string`

GetVerlustVerrechnungskonto returns the VerlustVerrechnungskonto field if non-nil, zero value otherwise.

### GetVerlustVerrechnungskontoOk

`func (o *StillePartnerZeile) GetVerlustVerrechnungskontoOk() (*string, bool)`

GetVerlustVerrechnungskontoOk returns a tuple with the VerlustVerrechnungskonto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustVerrechnungskonto

`func (o *StillePartnerZeile) SetVerlustVerrechnungskonto(v string)`

SetVerlustVerrechnungskonto sets VerlustVerrechnungskonto field to given value.


### GetVerlustanteil

`func (o *StillePartnerZeile) GetVerlustanteil() string`

GetVerlustanteil returns the Verlustanteil field if non-nil, zero value otherwise.

### GetVerlustanteilOk

`func (o *StillePartnerZeile) GetVerlustanteilOk() (*string, bool)`

GetVerlustanteilOk returns a tuple with the Verlustanteil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustanteil

`func (o *StillePartnerZeile) SetVerlustanteil(v string)`

SetVerlustanteil sets Verlustanteil field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


