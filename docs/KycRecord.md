# KycRecord

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

### NewKycRecord

`func NewKycRecord() *KycRecord`

NewKycRecord instantiates a new KycRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKycRecordWithDefaults

`func NewKycRecordWithDefaults() *KycRecord`

NewKycRecordWithDefaults instantiates a new KycRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *KycRecord) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *KycRecord) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *KycRecord) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *KycRecord) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerName

`func (o *KycRecord) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *KycRecord) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *KycRecord) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *KycRecord) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetKycDate

`func (o *KycRecord) GetKycDate() string`

GetKycDate returns the KycDate field if non-nil, zero value otherwise.

### GetKycDateOk

`func (o *KycRecord) GetKycDateOk() (*string, bool)`

GetKycDateOk returns a tuple with the KycDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKycDate

`func (o *KycRecord) SetKycDate(v string)`

SetKycDate sets KycDate field to given value.

### HasKycDate

`func (o *KycRecord) HasKycDate() bool`

HasKycDate returns a boolean if a field has been set.

### GetNotes

`func (o *KycRecord) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *KycRecord) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *KycRecord) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *KycRecord) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *KycRecord) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *KycRecord) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetRetentionUntil

`func (o *KycRecord) GetRetentionUntil() string`

GetRetentionUntil returns the RetentionUntil field if non-nil, zero value otherwise.

### GetRetentionUntilOk

`func (o *KycRecord) GetRetentionUntilOk() (*string, bool)`

GetRetentionUntilOk returns a tuple with the RetentionUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetentionUntil

`func (o *KycRecord) SetRetentionUntil(v string)`

SetRetentionUntil sets RetentionUntil field to given value.

### HasRetentionUntil

`func (o *KycRecord) HasRetentionUntil() bool`

HasRetentionUntil returns a boolean if a field has been set.

### GetRiskAssessment

`func (o *KycRecord) GetRiskAssessment() string`

GetRiskAssessment returns the RiskAssessment field if non-nil, zero value otherwise.

### GetRiskAssessmentOk

`func (o *KycRecord) GetRiskAssessmentOk() (*string, bool)`

GetRiskAssessmentOk returns a tuple with the RiskAssessment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskAssessment

`func (o *KycRecord) SetRiskAssessment(v string)`

SetRiskAssessment sets RiskAssessment field to given value.

### HasRiskAssessment

`func (o *KycRecord) HasRiskAssessment() bool`

HasRiskAssessment returns a boolean if a field has been set.

### SetRiskAssessmentNil

`func (o *KycRecord) SetRiskAssessmentNil(b bool)`

 SetRiskAssessmentNil sets the value for RiskAssessment to be an explicit nil

### UnsetRiskAssessment
`func (o *KycRecord) UnsetRiskAssessment()`

UnsetRiskAssessment ensures that no value is present for RiskAssessment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


