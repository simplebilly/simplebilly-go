# SilentPartner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContractDate** | Pointer to **NullableString** | Datum des Vertragsabschlusses. | [optional] 
**Einlage** | Pointer to **string** | Einlage (§ 230 HGB). | [optional] 
**GewinnquotePct** | Pointer to **string** | Gewinnbeteiligungsquote in Prozent (§ 231 HGB). | [optional] 
**Gewinnvortrag** | Pointer to **string** | Nicht erhobene Gewinne (§ 232 Abs. 3 HGB). | [optional] 
**InstrumentType** | [**InstrumentType**](InstrumentType.md) | Instrument: \&quot;typisch\&quot; | \&quot;atypisch\&quot; | \&quot;partiarisches_darlehen\&quot; | \&quot;genussrecht\&quot;. | 
**KestPflichtig** | Pointer to **bool** | 25 % Kapitalertragsteuer einbehalten (§ 43 Abs. 1 Nr. 3 EStG; typisch + partiarisches Darlehen). | [optional] 
**Name** | Pointer to **string** | Name des stillen Gesellschafters. | [optional] 
**Notes** | Pointer to **NullableString** | Freitext-Notizen. | [optional] 
**VerlustVerrechnungskonto** | Pointer to **string** | Kumulierte Verluste gegen die Einlage (§ 232 Abs. 2 HGB, ≤ Einlage). | [optional] 
**Verlustbeteiligung** | Pointer to **bool** | Verlustbeteiligung (§ 231 Abs. 2 HGB; kann ausgeschlossen werden). | [optional] 

## Methods

### NewSilentPartner

`func NewSilentPartner(instrumentType InstrumentType, ) *SilentPartner`

NewSilentPartner instantiates a new SilentPartner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSilentPartnerWithDefaults

`func NewSilentPartnerWithDefaults() *SilentPartner`

NewSilentPartnerWithDefaults instantiates a new SilentPartner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContractDate

`func (o *SilentPartner) GetContractDate() string`

GetContractDate returns the ContractDate field if non-nil, zero value otherwise.

### GetContractDateOk

`func (o *SilentPartner) GetContractDateOk() (*string, bool)`

GetContractDateOk returns a tuple with the ContractDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractDate

`func (o *SilentPartner) SetContractDate(v string)`

SetContractDate sets ContractDate field to given value.

### HasContractDate

`func (o *SilentPartner) HasContractDate() bool`

HasContractDate returns a boolean if a field has been set.

### SetContractDateNil

`func (o *SilentPartner) SetContractDateNil(b bool)`

 SetContractDateNil sets the value for ContractDate to be an explicit nil

### UnsetContractDate
`func (o *SilentPartner) UnsetContractDate()`

UnsetContractDate ensures that no value is present for ContractDate, not even an explicit nil
### GetEinlage

`func (o *SilentPartner) GetEinlage() string`

GetEinlage returns the Einlage field if non-nil, zero value otherwise.

### GetEinlageOk

`func (o *SilentPartner) GetEinlageOk() (*string, bool)`

GetEinlageOk returns a tuple with the Einlage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEinlage

`func (o *SilentPartner) SetEinlage(v string)`

SetEinlage sets Einlage field to given value.

### HasEinlage

`func (o *SilentPartner) HasEinlage() bool`

HasEinlage returns a boolean if a field has been set.

### GetGewinnquotePct

`func (o *SilentPartner) GetGewinnquotePct() string`

GetGewinnquotePct returns the GewinnquotePct field if non-nil, zero value otherwise.

### GetGewinnquotePctOk

`func (o *SilentPartner) GetGewinnquotePctOk() (*string, bool)`

GetGewinnquotePctOk returns a tuple with the GewinnquotePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnquotePct

`func (o *SilentPartner) SetGewinnquotePct(v string)`

SetGewinnquotePct sets GewinnquotePct field to given value.

### HasGewinnquotePct

`func (o *SilentPartner) HasGewinnquotePct() bool`

HasGewinnquotePct returns a boolean if a field has been set.

### GetGewinnvortrag

`func (o *SilentPartner) GetGewinnvortrag() string`

GetGewinnvortrag returns the Gewinnvortrag field if non-nil, zero value otherwise.

### GetGewinnvortragOk

`func (o *SilentPartner) GetGewinnvortragOk() (*string, bool)`

GetGewinnvortragOk returns a tuple with the Gewinnvortrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnvortrag

`func (o *SilentPartner) SetGewinnvortrag(v string)`

SetGewinnvortrag sets Gewinnvortrag field to given value.

### HasGewinnvortrag

`func (o *SilentPartner) HasGewinnvortrag() bool`

HasGewinnvortrag returns a boolean if a field has been set.

### GetInstrumentType

`func (o *SilentPartner) GetInstrumentType() InstrumentType`

GetInstrumentType returns the InstrumentType field if non-nil, zero value otherwise.

### GetInstrumentTypeOk

`func (o *SilentPartner) GetInstrumentTypeOk() (*InstrumentType, bool)`

GetInstrumentTypeOk returns a tuple with the InstrumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstrumentType

`func (o *SilentPartner) SetInstrumentType(v InstrumentType)`

SetInstrumentType sets InstrumentType field to given value.


### GetKestPflichtig

`func (o *SilentPartner) GetKestPflichtig() bool`

GetKestPflichtig returns the KestPflichtig field if non-nil, zero value otherwise.

### GetKestPflichtigOk

`func (o *SilentPartner) GetKestPflichtigOk() (*bool, bool)`

GetKestPflichtigOk returns a tuple with the KestPflichtig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKestPflichtig

`func (o *SilentPartner) SetKestPflichtig(v bool)`

SetKestPflichtig sets KestPflichtig field to given value.

### HasKestPflichtig

`func (o *SilentPartner) HasKestPflichtig() bool`

HasKestPflichtig returns a boolean if a field has been set.

### GetName

`func (o *SilentPartner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SilentPartner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SilentPartner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SilentPartner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotes

`func (o *SilentPartner) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SilentPartner) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SilentPartner) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SilentPartner) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SilentPartner) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SilentPartner) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetVerlustVerrechnungskonto

`func (o *SilentPartner) GetVerlustVerrechnungskonto() string`

GetVerlustVerrechnungskonto returns the VerlustVerrechnungskonto field if non-nil, zero value otherwise.

### GetVerlustVerrechnungskontoOk

`func (o *SilentPartner) GetVerlustVerrechnungskontoOk() (*string, bool)`

GetVerlustVerrechnungskontoOk returns a tuple with the VerlustVerrechnungskonto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustVerrechnungskonto

`func (o *SilentPartner) SetVerlustVerrechnungskonto(v string)`

SetVerlustVerrechnungskonto sets VerlustVerrechnungskonto field to given value.

### HasVerlustVerrechnungskonto

`func (o *SilentPartner) HasVerlustVerrechnungskonto() bool`

HasVerlustVerrechnungskonto returns a boolean if a field has been set.

### GetVerlustbeteiligung

`func (o *SilentPartner) GetVerlustbeteiligung() bool`

GetVerlustbeteiligung returns the Verlustbeteiligung field if non-nil, zero value otherwise.

### GetVerlustbeteiligungOk

`func (o *SilentPartner) GetVerlustbeteiligungOk() (*bool, bool)`

GetVerlustbeteiligungOk returns a tuple with the Verlustbeteiligung field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustbeteiligung

`func (o *SilentPartner) SetVerlustbeteiligung(v bool)`

SetVerlustbeteiligung sets Verlustbeteiligung field to given value.

### HasVerlustbeteiligung

`func (o *SilentPartner) HasVerlustbeteiligung() bool`

HasVerlustbeteiligung returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


