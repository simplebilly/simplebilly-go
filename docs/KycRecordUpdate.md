# KycRecordUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **NullableString** | Referenz auf den Kunden/Kontakt. | [optional] 
**CustomerName** | Pointer to **NullableString** | Name des Kunden (für die Suche). | [optional] 
**KycDate** | Pointer to **NullableString** | Datum der KYC-Prüfung (GwG § 8). | [optional] 
**Notes** | Pointer to **NullableString** | Freitext-Notizen. | [optional] 
**RetentionUntil** | Pointer to **NullableString** | Aufbewahrungsfrist (GwG § 8 Abs. 4: 5 Jahre). | [optional] 
**RiskAssessment** | Pointer to **NullableString** | Risikoeinschätzung (z. B. Risikoklasse). | [optional] 

## Methods

### NewKycRecordUpdate

`func NewKycRecordUpdate() *KycRecordUpdate`

NewKycRecordUpdate instantiates a new KycRecordUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKycRecordUpdateWithDefaults

`func NewKycRecordUpdateWithDefaults() *KycRecordUpdate`

NewKycRecordUpdateWithDefaults instantiates a new KycRecordUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *KycRecordUpdate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *KycRecordUpdate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *KycRecordUpdate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *KycRecordUpdate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *KycRecordUpdate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *KycRecordUpdate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerName

`func (o *KycRecordUpdate) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *KycRecordUpdate) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *KycRecordUpdate) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *KycRecordUpdate) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *KycRecordUpdate) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *KycRecordUpdate) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetKycDate

`func (o *KycRecordUpdate) GetKycDate() string`

GetKycDate returns the KycDate field if non-nil, zero value otherwise.

### GetKycDateOk

`func (o *KycRecordUpdate) GetKycDateOk() (*string, bool)`

GetKycDateOk returns a tuple with the KycDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycDate

`func (o *KycRecordUpdate) SetKycDate(v string)`

SetKycDate sets KycDate field to given value.

### HasKycDate

`func (o *KycRecordUpdate) HasKycDate() bool`

HasKycDate returns a boolean if a field has been set.

### SetKycDateNil

`func (o *KycRecordUpdate) SetKycDateNil(b bool)`

 SetKycDateNil sets the value for KycDate to be an explicit nil

### UnsetKycDate
`func (o *KycRecordUpdate) UnsetKycDate()`

UnsetKycDate ensures that no value is present for KycDate, not even an explicit nil
### GetNotes

`func (o *KycRecordUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *KycRecordUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *KycRecordUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *KycRecordUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *KycRecordUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *KycRecordUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetRetentionUntil

`func (o *KycRecordUpdate) GetRetentionUntil() string`

GetRetentionUntil returns the RetentionUntil field if non-nil, zero value otherwise.

### GetRetentionUntilOk

`func (o *KycRecordUpdate) GetRetentionUntilOk() (*string, bool)`

GetRetentionUntilOk returns a tuple with the RetentionUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetentionUntil

`func (o *KycRecordUpdate) SetRetentionUntil(v string)`

SetRetentionUntil sets RetentionUntil field to given value.

### HasRetentionUntil

`func (o *KycRecordUpdate) HasRetentionUntil() bool`

HasRetentionUntil returns a boolean if a field has been set.

### SetRetentionUntilNil

`func (o *KycRecordUpdate) SetRetentionUntilNil(b bool)`

 SetRetentionUntilNil sets the value for RetentionUntil to be an explicit nil

### UnsetRetentionUntil
`func (o *KycRecordUpdate) UnsetRetentionUntil()`

UnsetRetentionUntil ensures that no value is present for RetentionUntil, not even an explicit nil
### GetRiskAssessment

`func (o *KycRecordUpdate) GetRiskAssessment() string`

GetRiskAssessment returns the RiskAssessment field if non-nil, zero value otherwise.

### GetRiskAssessmentOk

`func (o *KycRecordUpdate) GetRiskAssessmentOk() (*string, bool)`

GetRiskAssessmentOk returns a tuple with the RiskAssessment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskAssessment

`func (o *KycRecordUpdate) SetRiskAssessment(v string)`

SetRiskAssessment sets RiskAssessment field to given value.

### HasRiskAssessment

`func (o *KycRecordUpdate) HasRiskAssessment() bool`

HasRiskAssessment returns a boolean if a field has been set.

### SetRiskAssessmentNil

`func (o *KycRecordUpdate) SetRiskAssessmentNil(b bool)`

 SetRiskAssessmentNil sets the value for RiskAssessment to be an explicit nil

### UnsetRiskAssessment
`func (o *KycRecordUpdate) UnsetRiskAssessment()`

UnsetRiskAssessment ensures that no value is present for RiskAssessment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


