# ParticipationCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcquiredAt** | Pointer to **NullableString** | Datum des Erwerbs der Beteiligung. | [optional] 
**BoardAppointment** | Pointer to **bool** | Bestellungsrecht für Geschäftsführung/Aufsichtsrat (§ 290 Abs. 2 Nr. 2 HGB). | [optional] 
**CompanyName** | Pointer to **string** | Name des Beteiligungsunternehmens (§ 271 HGB). | [optional] 
**ControlAgreement** | Pointer to **bool** | Beherrschungsvertrag (§ 290 Abs. 2 Nr. 3 HGB). | [optional] 
**LegalForm** | Pointer to **NullableString** | Rechtsform, z. B. \&quot;GmbH\&quot;. | [optional] 
**OwnershipPct** | Pointer to **string** | Anteilsquote in Prozent (§ 271 HGB; &gt; 20 % widerlegbare Vermutung). | [optional] 
**PurposeVehicle** | Pointer to **bool** | Zweckgesellschaft (§ 290 Abs. 2 Nr. 4 HGB). | [optional] 
**VotingMajority** | Pointer to **bool** | Stimmrechtsmehrheit (§ 290 Abs. 2 Nr. 1 HGB). | [optional] 

## Methods

### NewParticipationCreate

`func NewParticipationCreate() *ParticipationCreate`

NewParticipationCreate instantiates a new ParticipationCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewParticipationCreateWithDefaults

`func NewParticipationCreateWithDefaults() *ParticipationCreate`

NewParticipationCreateWithDefaults instantiates a new ParticipationCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcquiredAt

`func (o *ParticipationCreate) GetAcquiredAt() string`

GetAcquiredAt returns the AcquiredAt field if non-nil, zero value otherwise.

### GetAcquiredAtOk

`func (o *ParticipationCreate) GetAcquiredAtOk() (*string, bool)`

GetAcquiredAtOk returns a tuple with the AcquiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcquiredAt

`func (o *ParticipationCreate) SetAcquiredAt(v string)`

SetAcquiredAt sets AcquiredAt field to given value.

### HasAcquiredAt

`func (o *ParticipationCreate) HasAcquiredAt() bool`

HasAcquiredAt returns a boolean if a field has been set.

### SetAcquiredAtNil

`func (o *ParticipationCreate) SetAcquiredAtNil(b bool)`

 SetAcquiredAtNil sets the value for AcquiredAt to be an explicit nil

### UnsetAcquiredAt
`func (o *ParticipationCreate) UnsetAcquiredAt()`

UnsetAcquiredAt ensures that no value is present for AcquiredAt, not even an explicit nil
### GetBoardAppointment

`func (o *ParticipationCreate) GetBoardAppointment() bool`

GetBoardAppointment returns the BoardAppointment field if non-nil, zero value otherwise.

### GetBoardAppointmentOk

`func (o *ParticipationCreate) GetBoardAppointmentOk() (*bool, bool)`

GetBoardAppointmentOk returns a tuple with the BoardAppointment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardAppointment

`func (o *ParticipationCreate) SetBoardAppointment(v bool)`

SetBoardAppointment sets BoardAppointment field to given value.

### HasBoardAppointment

`func (o *ParticipationCreate) HasBoardAppointment() bool`

HasBoardAppointment returns a boolean if a field has been set.

### GetCompanyName

`func (o *ParticipationCreate) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ParticipationCreate) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ParticipationCreate) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ParticipationCreate) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetControlAgreement

`func (o *ParticipationCreate) GetControlAgreement() bool`

GetControlAgreement returns the ControlAgreement field if non-nil, zero value otherwise.

### GetControlAgreementOk

`func (o *ParticipationCreate) GetControlAgreementOk() (*bool, bool)`

GetControlAgreementOk returns a tuple with the ControlAgreement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlAgreement

`func (o *ParticipationCreate) SetControlAgreement(v bool)`

SetControlAgreement sets ControlAgreement field to given value.

### HasControlAgreement

`func (o *ParticipationCreate) HasControlAgreement() bool`

HasControlAgreement returns a boolean if a field has been set.

### GetLegalForm

`func (o *ParticipationCreate) GetLegalForm() string`

GetLegalForm returns the LegalForm field if non-nil, zero value otherwise.

### GetLegalFormOk

`func (o *ParticipationCreate) GetLegalFormOk() (*string, bool)`

GetLegalFormOk returns a tuple with the LegalForm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalForm

`func (o *ParticipationCreate) SetLegalForm(v string)`

SetLegalForm sets LegalForm field to given value.

### HasLegalForm

`func (o *ParticipationCreate) HasLegalForm() bool`

HasLegalForm returns a boolean if a field has been set.

### SetLegalFormNil

`func (o *ParticipationCreate) SetLegalFormNil(b bool)`

 SetLegalFormNil sets the value for LegalForm to be an explicit nil

### UnsetLegalForm
`func (o *ParticipationCreate) UnsetLegalForm()`

UnsetLegalForm ensures that no value is present for LegalForm, not even an explicit nil
### GetOwnershipPct

`func (o *ParticipationCreate) GetOwnershipPct() string`

GetOwnershipPct returns the OwnershipPct field if non-nil, zero value otherwise.

### GetOwnershipPctOk

`func (o *ParticipationCreate) GetOwnershipPctOk() (*string, bool)`

GetOwnershipPctOk returns a tuple with the OwnershipPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnershipPct

`func (o *ParticipationCreate) SetOwnershipPct(v string)`

SetOwnershipPct sets OwnershipPct field to given value.

### HasOwnershipPct

`func (o *ParticipationCreate) HasOwnershipPct() bool`

HasOwnershipPct returns a boolean if a field has been set.

### GetPurposeVehicle

`func (o *ParticipationCreate) GetPurposeVehicle() bool`

GetPurposeVehicle returns the PurposeVehicle field if non-nil, zero value otherwise.

### GetPurposeVehicleOk

`func (o *ParticipationCreate) GetPurposeVehicleOk() (*bool, bool)`

GetPurposeVehicleOk returns a tuple with the PurposeVehicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurposeVehicle

`func (o *ParticipationCreate) SetPurposeVehicle(v bool)`

SetPurposeVehicle sets PurposeVehicle field to given value.

### HasPurposeVehicle

`func (o *ParticipationCreate) HasPurposeVehicle() bool`

HasPurposeVehicle returns a boolean if a field has been set.

### GetVotingMajority

`func (o *ParticipationCreate) GetVotingMajority() bool`

GetVotingMajority returns the VotingMajority field if non-nil, zero value otherwise.

### GetVotingMajorityOk

`func (o *ParticipationCreate) GetVotingMajorityOk() (*bool, bool)`

GetVotingMajorityOk returns a tuple with the VotingMajority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotingMajority

`func (o *ParticipationCreate) SetVotingMajority(v bool)`

SetVotingMajority sets VotingMajority field to given value.

### HasVotingMajority

`func (o *ParticipationCreate) HasVotingMajority() bool`

HasVotingMajority returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


