# ProposedAssignment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AmountPaid** | **string** |  | 
**Confidence** | **float64** |  | 
**CustomerId** | Pointer to **NullableString** |  | [optional] 
**InvoiceId** | **string** |  | 
**InvoiceNumber** | **string** |  | 
**OpenAmount** | **string** |  | 
**PaymentDate** | **string** |  | 
**PaymentId** | **string** |  | 
**Reason** | **string** |  | 
**Reference** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProposedAssignment

`func NewProposedAssignment(amountPaid string, confidence float64, invoiceId string, invoiceNumber string, openAmount string, paymentDate string, paymentId string, reason string, ) *ProposedAssignment`

NewProposedAssignment instantiates a new ProposedAssignment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProposedAssignmentWithDefaults

`func NewProposedAssignmentWithDefaults() *ProposedAssignment`

NewProposedAssignmentWithDefaults instantiates a new ProposedAssignment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmountPaid

`func (o *ProposedAssignment) GetAmountPaid() string`

GetAmountPaid returns the AmountPaid field if non-nil, zero value otherwise.

### GetAmountPaidOk

`func (o *ProposedAssignment) GetAmountPaidOk() (*string, bool)`

GetAmountPaidOk returns a tuple with the AmountPaid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountPaid

`func (o *ProposedAssignment) SetAmountPaid(v string)`

SetAmountPaid sets AmountPaid field to given value.


### GetConfidence

`func (o *ProposedAssignment) GetConfidence() float64`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *ProposedAssignment) GetConfidenceOk() (*float64, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *ProposedAssignment) SetConfidence(v float64)`

SetConfidence sets Confidence field to given value.


### GetCustomerId

`func (o *ProposedAssignment) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ProposedAssignment) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ProposedAssignment) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ProposedAssignment) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *ProposedAssignment) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *ProposedAssignment) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetInvoiceId

`func (o *ProposedAssignment) GetInvoiceId() string`

GetInvoiceId returns the InvoiceId field if non-nil, zero value otherwise.

### GetInvoiceIdOk

`func (o *ProposedAssignment) GetInvoiceIdOk() (*string, bool)`

GetInvoiceIdOk returns a tuple with the InvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceId

`func (o *ProposedAssignment) SetInvoiceId(v string)`

SetInvoiceId sets InvoiceId field to given value.


### GetInvoiceNumber

`func (o *ProposedAssignment) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *ProposedAssignment) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *ProposedAssignment) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### GetOpenAmount

`func (o *ProposedAssignment) GetOpenAmount() string`

GetOpenAmount returns the OpenAmount field if non-nil, zero value otherwise.

### GetOpenAmountOk

`func (o *ProposedAssignment) GetOpenAmountOk() (*string, bool)`

GetOpenAmountOk returns a tuple with the OpenAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenAmount

`func (o *ProposedAssignment) SetOpenAmount(v string)`

SetOpenAmount sets OpenAmount field to given value.


### GetPaymentDate

`func (o *ProposedAssignment) GetPaymentDate() string`

GetPaymentDate returns the PaymentDate field if non-nil, zero value otherwise.

### GetPaymentDateOk

`func (o *ProposedAssignment) GetPaymentDateOk() (*string, bool)`

GetPaymentDateOk returns a tuple with the PaymentDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDate

`func (o *ProposedAssignment) SetPaymentDate(v string)`

SetPaymentDate sets PaymentDate field to given value.


### GetPaymentId

`func (o *ProposedAssignment) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *ProposedAssignment) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *ProposedAssignment) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.


### GetReason

`func (o *ProposedAssignment) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ProposedAssignment) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ProposedAssignment) SetReason(v string)`

SetReason sets Reason field to given value.


### GetReference

`func (o *ProposedAssignment) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ProposedAssignment) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ProposedAssignment) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *ProposedAssignment) HasReference() bool`

HasReference returns a boolean if a field has been set.

### SetReferenceNil

`func (o *ProposedAssignment) SetReferenceNil(b bool)`

 SetReferenceNil sets the value for Reference to be an explicit nil

### UnsetReference
`func (o *ProposedAssignment) UnsetReference()`

UnsetReference ensures that no value is present for Reference, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


