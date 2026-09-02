# ExtraPayment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **string** |  | 
**EmployeeId** | **string** |  | 
**Reason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewExtraPayment

`func NewExtraPayment(amount string, employeeId string, ) *ExtraPayment`

NewExtraPayment instantiates a new ExtraPayment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtraPaymentWithDefaults

`func NewExtraPaymentWithDefaults() *ExtraPayment`

NewExtraPaymentWithDefaults instantiates a new ExtraPayment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *ExtraPayment) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *ExtraPayment) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *ExtraPayment) SetAmount(v string)`

SetAmount sets Amount field to given value.


### GetEmployeeId

`func (o *ExtraPayment) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *ExtraPayment) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *ExtraPayment) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.


### GetReason

`func (o *ExtraPayment) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ExtraPayment) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ExtraPayment) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *ExtraPayment) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *ExtraPayment) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *ExtraPayment) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


