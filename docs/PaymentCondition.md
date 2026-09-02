# PaymentCondition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DiscountDays** | **int32** |  | 
**DiscountPercentage** | **float64** |  | 
**Id** | **string** |  | 
**Name** | **string** |  | 
**PaymentTermDays** | **int32** |  | 

## Methods

### NewPaymentCondition

`func NewPaymentCondition(discountDays int32, discountPercentage float64, id string, name string, paymentTermDays int32, ) *PaymentCondition`

NewPaymentCondition instantiates a new PaymentCondition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentConditionWithDefaults

`func NewPaymentConditionWithDefaults() *PaymentCondition`

NewPaymentConditionWithDefaults instantiates a new PaymentCondition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDiscountDays

`func (o *PaymentCondition) GetDiscountDays() int32`

GetDiscountDays returns the DiscountDays field if non-nil, zero value otherwise.

### GetDiscountDaysOk

`func (o *PaymentCondition) GetDiscountDaysOk() (*int32, bool)`

GetDiscountDaysOk returns a tuple with the DiscountDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDays

`func (o *PaymentCondition) SetDiscountDays(v int32)`

SetDiscountDays sets DiscountDays field to given value.


### GetDiscountPercentage

`func (o *PaymentCondition) GetDiscountPercentage() float64`

GetDiscountPercentage returns the DiscountPercentage field if non-nil, zero value otherwise.

### GetDiscountPercentageOk

`func (o *PaymentCondition) GetDiscountPercentageOk() (*float64, bool)`

GetDiscountPercentageOk returns a tuple with the DiscountPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountPercentage

`func (o *PaymentCondition) SetDiscountPercentage(v float64)`

SetDiscountPercentage sets DiscountPercentage field to given value.


### GetId

`func (o *PaymentCondition) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PaymentCondition) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PaymentCondition) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *PaymentCondition) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PaymentCondition) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PaymentCondition) SetName(v string)`

SetName sets Name field to given value.


### GetPaymentTermDays

`func (o *PaymentCondition) GetPaymentTermDays() int32`

GetPaymentTermDays returns the PaymentTermDays field if non-nil, zero value otherwise.

### GetPaymentTermDaysOk

`func (o *PaymentCondition) GetPaymentTermDaysOk() (*int32, bool)`

GetPaymentTermDaysOk returns a tuple with the PaymentTermDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTermDays

`func (o *PaymentCondition) SetPaymentTermDays(v int32)`

SetPaymentTermDays sets PaymentTermDays field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


