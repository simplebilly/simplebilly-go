# SilentPartnerUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContractDate** | Pointer to **NullableString** | Datum des Vertragsabschlusses. | [optional] 
**Einlage** | Pointer to **NullableString** | Einlage (§ 230 HGB). | [optional] 
**GewinnquotePct** | Pointer to **NullableString** | Gewinnbeteiligungsquote in Prozent (§ 231 HGB). | [optional] 
**Gewinnvortrag** | Pointer to **NullableString** | Nicht erhobene Gewinne (§ 232 Abs. 3 HGB). | [optional] 
**InstrumentType** | Pointer to [**NullableInstrumentType**](InstrumentType.md) | Instrument: \&quot;typisch\&quot; | \&quot;atypisch\&quot; | \&quot;partiarisches_darlehen\&quot; | \&quot;genussrecht\&quot;. | [optional] 
**KestPflichtig** | Pointer to **NullableBool** | 25 % Kapitalertragsteuer einbehalten (§ 43 Abs. 1 Nr. 3 EStG; typisch + partiarisches Darlehen). | [optional] 
**Name** | Pointer to **NullableString** | Name des stillen Gesellschafters. | [optional] 
**Notes** | Pointer to **NullableString** | Freitext-Notizen. | [optional] 
**VerlustVerrechnungskonto** | Pointer to **NullableString** | Kumulierte Verluste gegen die Einlage (§ 232 Abs. 2 HGB, ≤ Einlage). | [optional] 
**Verlustbeteiligung** | Pointer to **NullableBool** | Verlustbeteiligung (§ 231 Abs. 2 HGB; kann ausgeschlossen werden). | [optional] 

## Methods

### NewSilentPartnerUpdate

`func NewSilentPartnerUpdate() *SilentPartnerUpdate`

NewSilentPartnerUpdate instantiates a new SilentPartnerUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSilentPartnerUpdateWithDefaults

`func NewSilentPartnerUpdateWithDefaults() *SilentPartnerUpdate`

NewSilentPartnerUpdateWithDefaults instantiates a new SilentPartnerUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContractDate

`func (o *SilentPartnerUpdate) GetContractDate() string`

GetContractDate returns the ContractDate field if non-nil, zero value otherwise.

### GetContractDateOk

`func (o *SilentPartnerUpdate) GetContractDateOk() (*string, bool)`

GetContractDateOk returns a tuple with the ContractDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractDate

`func (o *SilentPartnerUpdate) SetContractDate(v string)`

SetContractDate sets ContractDate field to given value.

### HasContractDate

`func (o *SilentPartnerUpdate) HasContractDate() bool`

HasContractDate returns a boolean if a field has been set.

### SetContractDateNil

`func (o *SilentPartnerUpdate) SetContractDateNil(b bool)`

 SetContractDateNil sets the value for ContractDate to be an explicit nil

### UnsetContractDate
`func (o *SilentPartnerUpdate) UnsetContractDate()`

UnsetContractDate ensures that no value is present for ContractDate, not even an explicit nil
### GetEinlage

`func (o *SilentPartnerUpdate) GetEinlage() string`

GetEinlage returns the Einlage field if non-nil, zero value otherwise.

### GetEinlageOk

`func (o *SilentPartnerUpdate) GetEinlageOk() (*string, bool)`

GetEinlageOk returns a tuple with the Einlage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEinlage

`func (o *SilentPartnerUpdate) SetEinlage(v string)`

SetEinlage sets Einlage field to given value.

### HasEinlage

`func (o *SilentPartnerUpdate) HasEinlage() bool`

HasEinlage returns a boolean if a field has been set.

### SetEinlageNil

`func (o *SilentPartnerUpdate) SetEinlageNil(b bool)`

 SetEinlageNil sets the value for Einlage to be an explicit nil

### UnsetEinlage
`func (o *SilentPartnerUpdate) UnsetEinlage()`

UnsetEinlage ensures that no value is present for Einlage, not even an explicit nil
### GetGewinnquotePct

`func (o *SilentPartnerUpdate) GetGewinnquotePct() string`

GetGewinnquotePct returns the GewinnquotePct field if non-nil, zero value otherwise.

### GetGewinnquotePctOk

`func (o *SilentPartnerUpdate) GetGewinnquotePctOk() (*string, bool)`

GetGewinnquotePctOk returns a tuple with the GewinnquotePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnquotePct

`func (o *SilentPartnerUpdate) SetGewinnquotePct(v string)`

SetGewinnquotePct sets GewinnquotePct field to given value.

### HasGewinnquotePct

`func (o *SilentPartnerUpdate) HasGewinnquotePct() bool`

HasGewinnquotePct returns a boolean if a field has been set.

### SetGewinnquotePctNil

`func (o *SilentPartnerUpdate) SetGewinnquotePctNil(b bool)`

 SetGewinnquotePctNil sets the value for GewinnquotePct to be an explicit nil

### UnsetGewinnquotePct
`func (o *SilentPartnerUpdate) UnsetGewinnquotePct()`

UnsetGewinnquotePct ensures that no value is present for GewinnquotePct, not even an explicit nil
### GetGewinnvortrag

`func (o *SilentPartnerUpdate) GetGewinnvortrag() string`

GetGewinnvortrag returns the Gewinnvortrag field if non-nil, zero value otherwise.

### GetGewinnvortragOk

`func (o *SilentPartnerUpdate) GetGewinnvortragOk() (*string, bool)`

GetGewinnvortragOk returns a tuple with the Gewinnvortrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnvortrag

`func (o *SilentPartnerUpdate) SetGewinnvortrag(v string)`

SetGewinnvortrag sets Gewinnvortrag field to given value.

### HasGewinnvortrag

`func (o *SilentPartnerUpdate) HasGewinnvortrag() bool`

HasGewinnvortrag returns a boolean if a field has been set.

### SetGewinnvortragNil

`func (o *SilentPartnerUpdate) SetGewinnvortragNil(b bool)`

 SetGewinnvortragNil sets the value for Gewinnvortrag to be an explicit nil

### UnsetGewinnvortrag
`func (o *SilentPartnerUpdate) UnsetGewinnvortrag()`

UnsetGewinnvortrag ensures that no value is present for Gewinnvortrag, not even an explicit nil
### GetInstrumentType

`func (o *SilentPartnerUpdate) GetInstrumentType() InstrumentType`

GetInstrumentType returns the InstrumentType field if non-nil, zero value otherwise.

### GetInstrumentTypeOk

`func (o *SilentPartnerUpdate) GetInstrumentTypeOk() (*InstrumentType, bool)`

GetInstrumentTypeOk returns a tuple with the InstrumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstrumentType

`func (o *SilentPartnerUpdate) SetInstrumentType(v InstrumentType)`

SetInstrumentType sets InstrumentType field to given value.

### HasInstrumentType

`func (o *SilentPartnerUpdate) HasInstrumentType() bool`

HasInstrumentType returns a boolean if a field has been set.

### SetInstrumentTypeNil

`func (o *SilentPartnerUpdate) SetInstrumentTypeNil(b bool)`

 SetInstrumentTypeNil sets the value for InstrumentType to be an explicit nil

### UnsetInstrumentType
`func (o *SilentPartnerUpdate) UnsetInstrumentType()`

UnsetInstrumentType ensures that no value is present for InstrumentType, not even an explicit nil
### GetKestPflichtig

`func (o *SilentPartnerUpdate) GetKestPflichtig() bool`

GetKestPflichtig returns the KestPflichtig field if non-nil, zero value otherwise.

### GetKestPflichtigOk

`func (o *SilentPartnerUpdate) GetKestPflichtigOk() (*bool, bool)`

GetKestPflichtigOk returns a tuple with the KestPflichtig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKestPflichtig

`func (o *SilentPartnerUpdate) SetKestPflichtig(v bool)`

SetKestPflichtig sets KestPflichtig field to given value.

### HasKestPflichtig

`func (o *SilentPartnerUpdate) HasKestPflichtig() bool`

HasKestPflichtig returns a boolean if a field has been set.

### SetKestPflichtigNil

`func (o *SilentPartnerUpdate) SetKestPflichtigNil(b bool)`

 SetKestPflichtigNil sets the value for KestPflichtig to be an explicit nil

### UnsetKestPflichtig
`func (o *SilentPartnerUpdate) UnsetKestPflichtig()`

UnsetKestPflichtig ensures that no value is present for KestPflichtig, not even an explicit nil
### GetName

`func (o *SilentPartnerUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SilentPartnerUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SilentPartnerUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SilentPartnerUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *SilentPartnerUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *SilentPartnerUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetNotes

`func (o *SilentPartnerUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SilentPartnerUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SilentPartnerUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SilentPartnerUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SilentPartnerUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SilentPartnerUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetVerlustVerrechnungskonto

`func (o *SilentPartnerUpdate) GetVerlustVerrechnungskonto() string`

GetVerlustVerrechnungskonto returns the VerlustVerrechnungskonto field if non-nil, zero value otherwise.

### GetVerlustVerrechnungskontoOk

`func (o *SilentPartnerUpdate) GetVerlustVerrechnungskontoOk() (*string, bool)`

GetVerlustVerrechnungskontoOk returns a tuple with the VerlustVerrechnungskonto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustVerrechnungskonto

`func (o *SilentPartnerUpdate) SetVerlustVerrechnungskonto(v string)`

SetVerlustVerrechnungskonto sets VerlustVerrechnungskonto field to given value.

### HasVerlustVerrechnungskonto

`func (o *SilentPartnerUpdate) HasVerlustVerrechnungskonto() bool`

HasVerlustVerrechnungskonto returns a boolean if a field has been set.

### SetVerlustVerrechnungskontoNil

`func (o *SilentPartnerUpdate) SetVerlustVerrechnungskontoNil(b bool)`

 SetVerlustVerrechnungskontoNil sets the value for VerlustVerrechnungskonto to be an explicit nil

### UnsetVerlustVerrechnungskonto
`func (o *SilentPartnerUpdate) UnsetVerlustVerrechnungskonto()`

UnsetVerlustVerrechnungskonto ensures that no value is present for VerlustVerrechnungskonto, not even an explicit nil
### GetVerlustbeteiligung

`func (o *SilentPartnerUpdate) GetVerlustbeteiligung() bool`

GetVerlustbeteiligung returns the Verlustbeteiligung field if non-nil, zero value otherwise.

### GetVerlustbeteiligungOk

`func (o *SilentPartnerUpdate) GetVerlustbeteiligungOk() (*bool, bool)`

GetVerlustbeteiligungOk returns a tuple with the Verlustbeteiligung field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustbeteiligung

`func (o *SilentPartnerUpdate) SetVerlustbeteiligung(v bool)`

SetVerlustbeteiligung sets Verlustbeteiligung field to given value.

### HasVerlustbeteiligung

`func (o *SilentPartnerUpdate) HasVerlustbeteiligung() bool`

HasVerlustbeteiligung returns a boolean if a field has been set.

### SetVerlustbeteiligungNil

`func (o *SilentPartnerUpdate) SetVerlustbeteiligungNil(b bool)`

 SetVerlustbeteiligungNil sets the value for Verlustbeteiligung to be an explicit nil

### UnsetVerlustbeteiligung
`func (o *SilentPartnerUpdate) UnsetVerlustbeteiligung()`

UnsetVerlustbeteiligung ensures that no value is present for Verlustbeteiligung, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


