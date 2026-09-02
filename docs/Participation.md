# Participation

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

### NewParticipation

`func NewParticipation() *Participation`

NewParticipation instantiates a new Participation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewParticipationWithDefaults

`func NewParticipationWithDefaults() *Participation`

NewParticipationWithDefaults instantiates a new Participation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcquiredAt

`func (o *Participation) GetAcquiredAt() string`

GetAcquiredAt returns the AcquiredAt field if non-nil, zero value otherwise.

### GetAcquiredAtOk

`func (o *Participation) GetAcquiredAtOk() (*string, bool)`

GetAcquiredAtOk returns a tuple with the AcquiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcquiredAt

`func (o *Participation) SetAcquiredAt(v string)`

SetAcquiredAt sets AcquiredAt field to given value.

### HasAcquiredAt

`func (o *Participation) HasAcquiredAt() bool`

HasAcquiredAt returns a boolean if a field has been set.

### SetAcquiredAtNil

`func (o *Participation) SetAcquiredAtNil(b bool)`

 SetAcquiredAtNil sets the value for AcquiredAt to be an explicit nil

### UnsetAcquiredAt
`func (o *Participation) UnsetAcquiredAt()`

UnsetAcquiredAt ensures that no value is present for AcquiredAt, not even an explicit nil
### GetBoardAppointment

`func (o *Participation) GetBoardAppointment() bool`

GetBoardAppointment returns the BoardAppointment field if non-nil, zero value otherwise.

### GetBoardAppointmentOk

`func (o *Participation) GetBoardAppointmentOk() (*bool, bool)`

GetBoardAppointmentOk returns a tuple with the BoardAppointment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardAppointment

`func (o *Participation) SetBoardAppointment(v bool)`

SetBoardAppointment sets BoardAppointment field to given value.

### HasBoardAppointment

`func (o *Participation) HasBoardAppointment() bool`

HasBoardAppointment returns a boolean if a field has been set.

### GetCompanyName

`func (o *Participation) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *Participation) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *Participation) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *Participation) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetControlAgreement

`func (o *Participation) GetControlAgreement() bool`

GetControlAgreement returns the ControlAgreement field if non-nil, zero value otherwise.

### GetControlAgreementOk

`func (o *Participation) GetControlAgreementOk() (*bool, bool)`

GetControlAgreementOk returns a tuple with the ControlAgreement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlAgreement

`func (o *Participation) SetControlAgreement(v bool)`

SetControlAgreement sets ControlAgreement field to given value.

### HasControlAgreement

`func (o *Participation) HasControlAgreement() bool`

HasControlAgreement returns a boolean if a field has been set.

### GetLegalForm

`func (o *Participation) GetLegalForm() string`

GetLegalForm returns the LegalForm field if non-nil, zero value otherwise.

### GetLegalFormOk

`func (o *Participation) GetLegalFormOk() (*string, bool)`

GetLegalFormOk returns a tuple with the LegalForm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalForm

`func (o *Participation) SetLegalForm(v string)`

SetLegalForm sets LegalForm field to given value.

### HasLegalForm

`func (o *Participation) HasLegalForm() bool`

HasLegalForm returns a boolean if a field has been set.

### SetLegalFormNil

`func (o *Participation) SetLegalFormNil(b bool)`

 SetLegalFormNil sets the value for LegalForm to be an explicit nil

### UnsetLegalForm
`func (o *Participation) UnsetLegalForm()`

UnsetLegalForm ensures that no value is present for LegalForm, not even an explicit nil
### GetOwnershipPct

`func (o *Participation) GetOwnershipPct() string`

GetOwnershipPct returns the OwnershipPct field if non-nil, zero value otherwise.

### GetOwnershipPctOk

`func (o *Participation) GetOwnershipPctOk() (*string, bool)`

GetOwnershipPctOk returns a tuple with the OwnershipPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnershipPct

`func (o *Participation) SetOwnershipPct(v string)`

SetOwnershipPct sets OwnershipPct field to given value.

### HasOwnershipPct

`func (o *Participation) HasOwnershipPct() bool`

HasOwnershipPct returns a boolean if a field has been set.

### GetPurposeVehicle

`func (o *Participation) GetPurposeVehicle() bool`

GetPurposeVehicle returns the PurposeVehicle field if non-nil, zero value otherwise.

### GetPurposeVehicleOk

`func (o *Participation) GetPurposeVehicleOk() (*bool, bool)`

GetPurposeVehicleOk returns a tuple with the PurposeVehicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurposeVehicle

`func (o *Participation) SetPurposeVehicle(v bool)`

SetPurposeVehicle sets PurposeVehicle field to given value.

### HasPurposeVehicle

`func (o *Participation) HasPurposeVehicle() bool`

HasPurposeVehicle returns a boolean if a field has been set.

### GetVotingMajority

`func (o *Participation) GetVotingMajority() bool`

GetVotingMajority returns the VotingMajority field if non-nil, zero value otherwise.

### GetVotingMajorityOk

`func (o *Participation) GetVotingMajorityOk() (*bool, bool)`

GetVotingMajorityOk returns a tuple with the VotingMajority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotingMajority

`func (o *Participation) SetVotingMajority(v bool)`

SetVotingMajority sets VotingMajority field to given value.

### HasVotingMajority

`func (o *Participation) HasVotingMajority() bool`

HasVotingMajority returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


