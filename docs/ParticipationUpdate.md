# ParticipationUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcquiredAt** | Pointer to **NullableString** | Datum des Erwerbs der Beteiligung. | [optional] 
**BoardAppointment** | Pointer to **NullableBool** | Bestellungsrecht für Geschäftsführung/Aufsichtsrat (§ 290 Abs. 2 Nr. 2 HGB). | [optional] 
**CompanyName** | Pointer to **NullableString** | Name des Beteiligungsunternehmens (§ 271 HGB). | [optional] 
**ControlAgreement** | Pointer to **NullableBool** | Beherrschungsvertrag (§ 290 Abs. 2 Nr. 3 HGB). | [optional] 
**LegalForm** | Pointer to **NullableString** | Rechtsform, z. B. \&quot;GmbH\&quot;. | [optional] 
**OwnershipPct** | Pointer to **NullableString** | Anteilsquote in Prozent (§ 271 HGB; &gt; 20 % widerlegbare Vermutung). | [optional] 
**PurposeVehicle** | Pointer to **NullableBool** | Zweckgesellschaft (§ 290 Abs. 2 Nr. 4 HGB). | [optional] 
**VotingMajority** | Pointer to **NullableBool** | Stimmrechtsmehrheit (§ 290 Abs. 2 Nr. 1 HGB). | [optional] 

## Methods

### NewParticipationUpdate

`func NewParticipationUpdate() *ParticipationUpdate`

NewParticipationUpdate instantiates a new ParticipationUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewParticipationUpdateWithDefaults

`func NewParticipationUpdateWithDefaults() *ParticipationUpdate`

NewParticipationUpdateWithDefaults instantiates a new ParticipationUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcquiredAt

`func (o *ParticipationUpdate) GetAcquiredAt() string`

GetAcquiredAt returns the AcquiredAt field if non-nil, zero value otherwise.

### GetAcquiredAtOk

`func (o *ParticipationUpdate) GetAcquiredAtOk() (*string, bool)`

GetAcquiredAtOk returns a tuple with the AcquiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcquiredAt

`func (o *ParticipationUpdate) SetAcquiredAt(v string)`

SetAcquiredAt sets AcquiredAt field to given value.

### HasAcquiredAt

`func (o *ParticipationUpdate) HasAcquiredAt() bool`

HasAcquiredAt returns a boolean if a field has been set.

### SetAcquiredAtNil

`func (o *ParticipationUpdate) SetAcquiredAtNil(b bool)`

 SetAcquiredAtNil sets the value for AcquiredAt to be an explicit nil

### UnsetAcquiredAt
`func (o *ParticipationUpdate) UnsetAcquiredAt()`

UnsetAcquiredAt ensures that no value is present for AcquiredAt, not even an explicit nil
### GetBoardAppointment

`func (o *ParticipationUpdate) GetBoardAppointment() bool`

GetBoardAppointment returns the BoardAppointment field if non-nil, zero value otherwise.

### GetBoardAppointmentOk

`func (o *ParticipationUpdate) GetBoardAppointmentOk() (*bool, bool)`

GetBoardAppointmentOk returns a tuple with the BoardAppointment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardAppointment

`func (o *ParticipationUpdate) SetBoardAppointment(v bool)`

SetBoardAppointment sets BoardAppointment field to given value.

### HasBoardAppointment

`func (o *ParticipationUpdate) HasBoardAppointment() bool`

HasBoardAppointment returns a boolean if a field has been set.

### SetBoardAppointmentNil

`func (o *ParticipationUpdate) SetBoardAppointmentNil(b bool)`

 SetBoardAppointmentNil sets the value for BoardAppointment to be an explicit nil

### UnsetBoardAppointment
`func (o *ParticipationUpdate) UnsetBoardAppointment()`

UnsetBoardAppointment ensures that no value is present for BoardAppointment, not even an explicit nil
### GetCompanyName

`func (o *ParticipationUpdate) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ParticipationUpdate) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ParticipationUpdate) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ParticipationUpdate) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### SetCompanyNameNil

`func (o *ParticipationUpdate) SetCompanyNameNil(b bool)`

 SetCompanyNameNil sets the value for CompanyName to be an explicit nil

### UnsetCompanyName
`func (o *ParticipationUpdate) UnsetCompanyName()`

UnsetCompanyName ensures that no value is present for CompanyName, not even an explicit nil
### GetControlAgreement

`func (o *ParticipationUpdate) GetControlAgreement() bool`

GetControlAgreement returns the ControlAgreement field if non-nil, zero value otherwise.

### GetControlAgreementOk

`func (o *ParticipationUpdate) GetControlAgreementOk() (*bool, bool)`

GetControlAgreementOk returns a tuple with the ControlAgreement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlAgreement

`func (o *ParticipationUpdate) SetControlAgreement(v bool)`

SetControlAgreement sets ControlAgreement field to given value.

### HasControlAgreement

`func (o *ParticipationUpdate) HasControlAgreement() bool`

HasControlAgreement returns a boolean if a field has been set.

### SetControlAgreementNil

`func (o *ParticipationUpdate) SetControlAgreementNil(b bool)`

 SetControlAgreementNil sets the value for ControlAgreement to be an explicit nil

### UnsetControlAgreement
`func (o *ParticipationUpdate) UnsetControlAgreement()`

UnsetControlAgreement ensures that no value is present for ControlAgreement, not even an explicit nil
### GetLegalForm

`func (o *ParticipationUpdate) GetLegalForm() string`

GetLegalForm returns the LegalForm field if non-nil, zero value otherwise.

### GetLegalFormOk

`func (o *ParticipationUpdate) GetLegalFormOk() (*string, bool)`

GetLegalFormOk returns a tuple with the LegalForm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalForm

`func (o *ParticipationUpdate) SetLegalForm(v string)`

SetLegalForm sets LegalForm field to given value.

### HasLegalForm

`func (o *ParticipationUpdate) HasLegalForm() bool`

HasLegalForm returns a boolean if a field has been set.

### SetLegalFormNil

`func (o *ParticipationUpdate) SetLegalFormNil(b bool)`

 SetLegalFormNil sets the value for LegalForm to be an explicit nil

### UnsetLegalForm
`func (o *ParticipationUpdate) UnsetLegalForm()`

UnsetLegalForm ensures that no value is present for LegalForm, not even an explicit nil
### GetOwnershipPct

`func (o *ParticipationUpdate) GetOwnershipPct() string`

GetOwnershipPct returns the OwnershipPct field if non-nil, zero value otherwise.

### GetOwnershipPctOk

`func (o *ParticipationUpdate) GetOwnershipPctOk() (*string, bool)`

GetOwnershipPctOk returns a tuple with the OwnershipPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnershipPct

`func (o *ParticipationUpdate) SetOwnershipPct(v string)`

SetOwnershipPct sets OwnershipPct field to given value.

### HasOwnershipPct

`func (o *ParticipationUpdate) HasOwnershipPct() bool`

HasOwnershipPct returns a boolean if a field has been set.

### SetOwnershipPctNil

`func (o *ParticipationUpdate) SetOwnershipPctNil(b bool)`

 SetOwnershipPctNil sets the value for OwnershipPct to be an explicit nil

### UnsetOwnershipPct
`func (o *ParticipationUpdate) UnsetOwnershipPct()`

UnsetOwnershipPct ensures that no value is present for OwnershipPct, not even an explicit nil
### GetPurposeVehicle

`func (o *ParticipationUpdate) GetPurposeVehicle() bool`

GetPurposeVehicle returns the PurposeVehicle field if non-nil, zero value otherwise.

### GetPurposeVehicleOk

`func (o *ParticipationUpdate) GetPurposeVehicleOk() (*bool, bool)`

GetPurposeVehicleOk returns a tuple with the PurposeVehicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurposeVehicle

`func (o *ParticipationUpdate) SetPurposeVehicle(v bool)`

SetPurposeVehicle sets PurposeVehicle field to given value.

### HasPurposeVehicle

`func (o *ParticipationUpdate) HasPurposeVehicle() bool`

HasPurposeVehicle returns a boolean if a field has been set.

### SetPurposeVehicleNil

`func (o *ParticipationUpdate) SetPurposeVehicleNil(b bool)`

 SetPurposeVehicleNil sets the value for PurposeVehicle to be an explicit nil

### UnsetPurposeVehicle
`func (o *ParticipationUpdate) UnsetPurposeVehicle()`

UnsetPurposeVehicle ensures that no value is present for PurposeVehicle, not even an explicit nil
### GetVotingMajority

`func (o *ParticipationUpdate) GetVotingMajority() bool`

GetVotingMajority returns the VotingMajority field if non-nil, zero value otherwise.

### GetVotingMajorityOk

`func (o *ParticipationUpdate) GetVotingMajorityOk() (*bool, bool)`

GetVotingMajorityOk returns a tuple with the VotingMajority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotingMajority

`func (o *ParticipationUpdate) SetVotingMajority(v bool)`

SetVotingMajority sets VotingMajority field to given value.

### HasVotingMajority

`func (o *ParticipationUpdate) HasVotingMajority() bool`

HasVotingMajority returns a boolean if a field has been set.

### SetVotingMajorityNil

`func (o *ParticipationUpdate) SetVotingMajorityNil(b bool)`

 SetVotingMajorityNil sets the value for VotingMajority to be an explicit nil

### UnsetVotingMajority
`func (o *ParticipationUpdate) UnsetVotingMajority()`

UnsetVotingMajority ensures that no value is present for VotingMajority, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


