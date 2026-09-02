# AllocatePaymentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **float64** |  | 
**InvoiceId** | **string** |  | 
**PaymentId** | **string** |  | 

## Methods

### NewAllocatePaymentRequest

`func NewAllocatePaymentRequest(amount float64, invoiceId string, paymentId string, ) *AllocatePaymentRequest`

NewAllocatePaymentRequest instantiates a new AllocatePaymentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAllocatePaymentRequestWithDefaults

`func NewAllocatePaymentRequestWithDefaults() *AllocatePaymentRequest`

NewAllocatePaymentRequestWithDefaults instantiates a new AllocatePaymentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *AllocatePaymentRequest) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AllocatePaymentRequest) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AllocatePaymentRequest) SetAmount(v float64)`

SetAmount sets Amount field to given value.


### GetInvoiceId

`func (o *AllocatePaymentRequest) GetInvoiceId() string`

GetInvoiceId returns the InvoiceId field if non-nil, zero value otherwise.

### GetInvoiceIdOk

`func (o *AllocatePaymentRequest) GetInvoiceIdOk() (*string, bool)`

GetInvoiceIdOk returns a tuple with the InvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceId

`func (o *AllocatePaymentRequest) SetInvoiceId(v string)`

SetInvoiceId sets InvoiceId field to given value.


### GetPaymentId

`func (o *AllocatePaymentRequest) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *AllocatePaymentRequest) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *AllocatePaymentRequest) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


