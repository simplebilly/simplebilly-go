# KycRecordCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **string** | Referenz auf den Kunden/Kontakt. | [optional] 
**CustomerName** | Pointer to **string** | Name des Kunden (für die Suche). | [optional] 
**KycDate** | Pointer to **string** | Datum der KYC-Prüfung (GwG § 8). | [optional] 
**Notes** | Pointer to **NullableString** | Freitext-Notizen. | [optional] 
**RetentionUntil** | Pointer to **string** | Aufbewahrungsfrist (GwG § 8 Abs. 4: 5 Jahre). | [optional] 
**RiskAssessment** | Pointer to **NullableString** | Risikoeinschätzung (z. B. Risikoklasse). | [optional] 

## Methods

### NewKycRecordCreate

`func NewKycRecordCreate() *KycRecordCreate`

NewKycRecordCreate instantiates a new KycRecordCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKycRecordCreateWithDefaults

`func NewKycRecordCreateWithDefaults() *KycRecordCreate`

NewKycRecordCreateWithDefaults instantiates a new KycRecordCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *KycRecordCreate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *KycRecordCreate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *KycRecordCreate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *KycRecordCreate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerName

`func (o *KycRecordCreate) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *KycRecordCreate) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *KycRecordCreate) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *KycRecordCreate) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetKycDate

`func (o *KycRecordCreate) GetKycDate() string`

GetKycDate returns the KycDate field if non-nil, zero value otherwise.

### GetKycDateOk

`func (o *KycRecordCreate) GetKycDateOk() (*string, bool)`

GetKycDateOk returns a tuple with the KycDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycDate

`func (o *KycRecordCreate) SetKycDate(v string)`

SetKycDate sets KycDate field to given value.

### HasKycDate

`func (o *KycRecordCreate) HasKycDate() bool`

HasKycDate returns a boolean if a field has been set.

### GetNotes

`func (o *KycRecordCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *KycRecordCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *KycRecordCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *KycRecordCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *KycRecordCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *KycRecordCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetRetentionUntil

`func (o *KycRecordCreate) GetRetentionUntil() string`

GetRetentionUntil returns the RetentionUntil field if non-nil, zero value otherwise.

### GetRetentionUntilOk

`func (o *KycRecordCreate) GetRetentionUntilOk() (*string, bool)`

GetRetentionUntilOk returns a tuple with the RetentionUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetentionUntil

`func (o *KycRecordCreate) SetRetentionUntil(v string)`

SetRetentionUntil sets RetentionUntil field to given value.

### HasRetentionUntil

`func (o *KycRecordCreate) HasRetentionUntil() bool`

HasRetentionUntil returns a boolean if a field has been set.

### GetRiskAssessment

`func (o *KycRecordCreate) GetRiskAssessment() string`

GetRiskAssessment returns the RiskAssessment field if non-nil, zero value otherwise.

### GetRiskAssessmentOk

`func (o *KycRecordCreate) GetRiskAssessmentOk() (*string, bool)`

GetRiskAssessmentOk returns a tuple with the RiskAssessment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskAssessment

`func (o *KycRecordCreate) SetRiskAssessment(v string)`

SetRiskAssessment sets RiskAssessment field to given value.

### HasRiskAssessment

`func (o *KycRecordCreate) HasRiskAssessment() bool`

HasRiskAssessment returns a boolean if a field has been set.

### SetRiskAssessmentNil

`func (o *KycRecordCreate) SetRiskAssessmentNil(b bool)`

 SetRiskAssessmentNil sets the value for RiskAssessment to be an explicit nil

### UnsetRiskAssessment
`func (o *KycRecordCreate) UnsetRiskAssessment()`

UnsetRiskAssessment ensures that no value is present for RiskAssessment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


