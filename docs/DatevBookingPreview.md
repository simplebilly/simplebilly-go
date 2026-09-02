# DatevBookingPreview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountNumber** | **string** |  | 
**DebitCredit** | **string** |  | 
**DocumentDate** | **string** |  | 
**DocumentText** | **string** |  | 
**NetAmount** | **string** |  | 
**OppositeAccount** | **string** |  | 
**TaxAmount** | Pointer to **NullableString** |  | [optional] 
**TaxRate** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDatevBookingPreview

`func NewDatevBookingPreview(accountNumber string, debitCredit string, documentDate string, documentText string, netAmount string, oppositeAccount string, ) *DatevBookingPreview`

NewDatevBookingPreview instantiates a new DatevBookingPreview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatevBookingPreviewWithDefaults

`func NewDatevBookingPreviewWithDefaults() *DatevBookingPreview`

NewDatevBookingPreviewWithDefaults instantiates a new DatevBookingPreview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountNumber

`func (o *DatevBookingPreview) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *DatevBookingPreview) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *DatevBookingPreview) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.


### GetDebitCredit

`func (o *DatevBookingPreview) GetDebitCredit() string`

GetDebitCredit returns the DebitCredit field if non-nil, zero value otherwise.

### GetDebitCreditOk

`func (o *DatevBookingPreview) GetDebitCreditOk() (*string, bool)`

GetDebitCreditOk returns a tuple with the DebitCredit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitCredit

`func (o *DatevBookingPreview) SetDebitCredit(v string)`

SetDebitCredit sets DebitCredit field to given value.


### GetDocumentDate

`func (o *DatevBookingPreview) GetDocumentDate() string`

GetDocumentDate returns the DocumentDate field if non-nil, zero value otherwise.

### GetDocumentDateOk

`func (o *DatevBookingPreview) GetDocumentDateOk() (*string, bool)`

GetDocumentDateOk returns a tuple with the DocumentDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentDate

`func (o *DatevBookingPreview) SetDocumentDate(v string)`

SetDocumentDate sets DocumentDate field to given value.


### GetDocumentText

`func (o *DatevBookingPreview) GetDocumentText() string`

GetDocumentText returns the DocumentText field if non-nil, zero value otherwise.

### GetDocumentTextOk

`func (o *DatevBookingPreview) GetDocumentTextOk() (*string, bool)`

GetDocumentTextOk returns a tuple with the DocumentText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentText

`func (o *DatevBookingPreview) SetDocumentText(v string)`

SetDocumentText sets DocumentText field to given value.


### GetNetAmount

`func (o *DatevBookingPreview) GetNetAmount() string`

GetNetAmount returns the NetAmount field if non-nil, zero value otherwise.

### GetNetAmountOk

`func (o *DatevBookingPreview) GetNetAmountOk() (*string, bool)`

GetNetAmountOk returns a tuple with the NetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetAmount

`func (o *DatevBookingPreview) SetNetAmount(v string)`

SetNetAmount sets NetAmount field to given value.


### GetOppositeAccount

`func (o *DatevBookingPreview) GetOppositeAccount() string`

GetOppositeAccount returns the OppositeAccount field if non-nil, zero value otherwise.

### GetOppositeAccountOk

`func (o *DatevBookingPreview) GetOppositeAccountOk() (*string, bool)`

GetOppositeAccountOk returns a tuple with the OppositeAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOppositeAccount

`func (o *DatevBookingPreview) SetOppositeAccount(v string)`

SetOppositeAccount sets OppositeAccount field to given value.


### GetTaxAmount

`func (o *DatevBookingPreview) GetTaxAmount() string`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *DatevBookingPreview) GetTaxAmountOk() (*string, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *DatevBookingPreview) SetTaxAmount(v string)`

SetTaxAmount sets TaxAmount field to given value.

### HasTaxAmount

`func (o *DatevBookingPreview) HasTaxAmount() bool`

HasTaxAmount returns a boolean if a field has been set.

### SetTaxAmountNil

`func (o *DatevBookingPreview) SetTaxAmountNil(b bool)`

 SetTaxAmountNil sets the value for TaxAmount to be an explicit nil

### UnsetTaxAmount
`func (o *DatevBookingPreview) UnsetTaxAmount()`

UnsetTaxAmount ensures that no value is present for TaxAmount, not even an explicit nil
### GetTaxRate

`func (o *DatevBookingPreview) GetTaxRate() string`

GetTaxRate returns the TaxRate field if non-nil, zero value otherwise.

### GetTaxRateOk

`func (o *DatevBookingPreview) GetTaxRateOk() (*string, bool)`

GetTaxRateOk returns a tuple with the TaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRate

`func (o *DatevBookingPreview) SetTaxRate(v string)`

SetTaxRate sets TaxRate field to given value.

### HasTaxRate

`func (o *DatevBookingPreview) HasTaxRate() bool`

HasTaxRate returns a boolean if a field has been set.

### SetTaxRateNil

`func (o *DatevBookingPreview) SetTaxRateNil(b bool)`

 SetTaxRateNil sets the value for TaxRate to be an explicit nil

### UnsetTaxRate
`func (o *DatevBookingPreview) UnsetTaxRate()`

UnsetTaxRate ensures that no value is present for TaxRate, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


