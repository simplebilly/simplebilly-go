# SilentPartnerCreate

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

### NewSilentPartnerCreate

`func NewSilentPartnerCreate(instrumentType InstrumentType, ) *SilentPartnerCreate`

NewSilentPartnerCreate instantiates a new SilentPartnerCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSilentPartnerCreateWithDefaults

`func NewSilentPartnerCreateWithDefaults() *SilentPartnerCreate`

NewSilentPartnerCreateWithDefaults instantiates a new SilentPartnerCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContractDate

`func (o *SilentPartnerCreate) GetContractDate() string`

GetContractDate returns the ContractDate field if non-nil, zero value otherwise.

### GetContractDateOk

`func (o *SilentPartnerCreate) GetContractDateOk() (*string, bool)`

GetContractDateOk returns a tuple with the ContractDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractDate

`func (o *SilentPartnerCreate) SetContractDate(v string)`

SetContractDate sets ContractDate field to given value.

### HasContractDate

`func (o *SilentPartnerCreate) HasContractDate() bool`

HasContractDate returns a boolean if a field has been set.

### SetContractDateNil

`func (o *SilentPartnerCreate) SetContractDateNil(b bool)`

 SetContractDateNil sets the value for ContractDate to be an explicit nil

### UnsetContractDate
`func (o *SilentPartnerCreate) UnsetContractDate()`

UnsetContractDate ensures that no value is present for ContractDate, not even an explicit nil
### GetEinlage

`func (o *SilentPartnerCreate) GetEinlage() string`

GetEinlage returns the Einlage field if non-nil, zero value otherwise.

### GetEinlageOk

`func (o *SilentPartnerCreate) GetEinlageOk() (*string, bool)`

GetEinlageOk returns a tuple with the Einlage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEinlage

`func (o *SilentPartnerCreate) SetEinlage(v string)`

SetEinlage sets Einlage field to given value.

### HasEinlage

`func (o *SilentPartnerCreate) HasEinlage() bool`

HasEinlage returns a boolean if a field has been set.

### GetGewinnquotePct

`func (o *SilentPartnerCreate) GetGewinnquotePct() string`

GetGewinnquotePct returns the GewinnquotePct field if non-nil, zero value otherwise.

### GetGewinnquotePctOk

`func (o *SilentPartnerCreate) GetGewinnquotePctOk() (*string, bool)`

GetGewinnquotePctOk returns a tuple with the GewinnquotePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnquotePct

`func (o *SilentPartnerCreate) SetGewinnquotePct(v string)`

SetGewinnquotePct sets GewinnquotePct field to given value.

### HasGewinnquotePct

`func (o *SilentPartnerCreate) HasGewinnquotePct() bool`

HasGewinnquotePct returns a boolean if a field has been set.

### GetGewinnvortrag

`func (o *SilentPartnerCreate) GetGewinnvortrag() string`

GetGewinnvortrag returns the Gewinnvortrag field if non-nil, zero value otherwise.

### GetGewinnvortragOk

`func (o *SilentPartnerCreate) GetGewinnvortragOk() (*string, bool)`

GetGewinnvortragOk returns a tuple with the Gewinnvortrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnvortrag

`func (o *SilentPartnerCreate) SetGewinnvortrag(v string)`

SetGewinnvortrag sets Gewinnvortrag field to given value.

### HasGewinnvortrag

`func (o *SilentPartnerCreate) HasGewinnvortrag() bool`

HasGewinnvortrag returns a boolean if a field has been set.

### GetInstrumentType

`func (o *SilentPartnerCreate) GetInstrumentType() InstrumentType`

GetInstrumentType returns the InstrumentType field if non-nil, zero value otherwise.

### GetInstrumentTypeOk

`func (o *SilentPartnerCreate) GetInstrumentTypeOk() (*InstrumentType, bool)`

GetInstrumentTypeOk returns a tuple with the InstrumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstrumentType

`func (o *SilentPartnerCreate) SetInstrumentType(v InstrumentType)`

SetInstrumentType sets InstrumentType field to given value.


### GetKestPflichtig

`func (o *SilentPartnerCreate) GetKestPflichtig() bool`

GetKestPflichtig returns the KestPflichtig field if non-nil, zero value otherwise.

### GetKestPflichtigOk

`func (o *SilentPartnerCreate) GetKestPflichtigOk() (*bool, bool)`

GetKestPflichtigOk returns a tuple with the KestPflichtig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKestPflichtig

`func (o *SilentPartnerCreate) SetKestPflichtig(v bool)`

SetKestPflichtig sets KestPflichtig field to given value.

### HasKestPflichtig

`func (o *SilentPartnerCreate) HasKestPflichtig() bool`

HasKestPflichtig returns a boolean if a field has been set.

### GetName

`func (o *SilentPartnerCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SilentPartnerCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SilentPartnerCreate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SilentPartnerCreate) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotes

`func (o *SilentPartnerCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SilentPartnerCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SilentPartnerCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SilentPartnerCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SilentPartnerCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SilentPartnerCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetVerlustVerrechnungskonto

`func (o *SilentPartnerCreate) GetVerlustVerrechnungskonto() string`

GetVerlustVerrechnungskonto returns the VerlustVerrechnungskonto field if non-nil, zero value otherwise.

### GetVerlustVerrechnungskontoOk

`func (o *SilentPartnerCreate) GetVerlustVerrechnungskontoOk() (*string, bool)`

GetVerlustVerrechnungskontoOk returns a tuple with the VerlustVerrechnungskonto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustVerrechnungskonto

`func (o *SilentPartnerCreate) SetVerlustVerrechnungskonto(v string)`

SetVerlustVerrechnungskonto sets VerlustVerrechnungskonto field to given value.

### HasVerlustVerrechnungskonto

`func (o *SilentPartnerCreate) HasVerlustVerrechnungskonto() bool`

HasVerlustVerrechnungskonto returns a boolean if a field has been set.

### GetVerlustbeteiligung

`func (o *SilentPartnerCreate) GetVerlustbeteiligung() bool`

GetVerlustbeteiligung returns the Verlustbeteiligung field if non-nil, zero value otherwise.

### GetVerlustbeteiligungOk

`func (o *SilentPartnerCreate) GetVerlustbeteiligungOk() (*bool, bool)`

GetVerlustbeteiligungOk returns a tuple with the Verlustbeteiligung field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerlustbeteiligung

`func (o *SilentPartnerCreate) SetVerlustbeteiligung(v bool)`

SetVerlustbeteiligung sets Verlustbeteiligung field to given value.

### HasVerlustbeteiligung

`func (o *SilentPartnerCreate) HasVerlustbeteiligung() bool`

HasVerlustbeteiligung returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


