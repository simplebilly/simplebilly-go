# CouponValidation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**DiscountType** | **string** |  | 
**DiscountValue** | **string** |  | 
**DiscountedAmount** | **string** |  | 
**MaxDiscountAmount** | Pointer to **NullableString** |  | [optional] 
**Reason** | Pointer to **NullableString** |  | [optional] 
**Valid** | **bool** |  | 

## Methods

### NewCouponValidation

`func NewCouponValidation(code string, discountType string, discountValue string, discountedAmount string, valid bool, ) *CouponValidation`

NewCouponValidation instantiates a new CouponValidation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCouponValidationWithDefaults

`func NewCouponValidationWithDefaults() *CouponValidation`

NewCouponValidationWithDefaults instantiates a new CouponValidation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *CouponValidation) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CouponValidation) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CouponValidation) SetCode(v string)`

SetCode sets Code field to given value.


### GetDiscountType

`func (o *CouponValidation) GetDiscountType() string`

GetDiscountType returns the DiscountType field if non-nil, zero value otherwise.

### GetDiscountTypeOk

`func (o *CouponValidation) GetDiscountTypeOk() (*string, bool)`

GetDiscountTypeOk returns a tuple with the DiscountType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountType

`func (o *CouponValidation) SetDiscountType(v string)`

SetDiscountType sets DiscountType field to given value.


### GetDiscountValue

`func (o *CouponValidation) GetDiscountValue() string`

GetDiscountValue returns the DiscountValue field if non-nil, zero value otherwise.

### GetDiscountValueOk

`func (o *CouponValidation) GetDiscountValueOk() (*string, bool)`

GetDiscountValueOk returns a tuple with the DiscountValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountValue

`func (o *CouponValidation) SetDiscountValue(v string)`

SetDiscountValue sets DiscountValue field to given value.


### GetDiscountedAmount

`func (o *CouponValidation) GetDiscountedAmount() string`

GetDiscountedAmount returns the DiscountedAmount field if non-nil, zero value otherwise.

### GetDiscountedAmountOk

`func (o *CouponValidation) GetDiscountedAmountOk() (*string, bool)`

GetDiscountedAmountOk returns a tuple with the DiscountedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountedAmount

`func (o *CouponValidation) SetDiscountedAmount(v string)`

SetDiscountedAmount sets DiscountedAmount field to given value.


### GetMaxDiscountAmount

`func (o *CouponValidation) GetMaxDiscountAmount() string`

GetMaxDiscountAmount returns the MaxDiscountAmount field if non-nil, zero value otherwise.

### GetMaxDiscountAmountOk

`func (o *CouponValidation) GetMaxDiscountAmountOk() (*string, bool)`

GetMaxDiscountAmountOk returns a tuple with the MaxDiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDiscountAmount

`func (o *CouponValidation) SetMaxDiscountAmount(v string)`

SetMaxDiscountAmount sets MaxDiscountAmount field to given value.

### HasMaxDiscountAmount

`func (o *CouponValidation) HasMaxDiscountAmount() bool`

HasMaxDiscountAmount returns a boolean if a field has been set.

### SetMaxDiscountAmountNil

`func (o *CouponValidation) SetMaxDiscountAmountNil(b bool)`

 SetMaxDiscountAmountNil sets the value for MaxDiscountAmount to be an explicit nil

### UnsetMaxDiscountAmount
`func (o *CouponValidation) UnsetMaxDiscountAmount()`

UnsetMaxDiscountAmount ensures that no value is present for MaxDiscountAmount, not even an explicit nil
### GetReason

`func (o *CouponValidation) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CouponValidation) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CouponValidation) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *CouponValidation) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *CouponValidation) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *CouponValidation) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetValid

`func (o *CouponValidation) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *CouponValidation) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *CouponValidation) SetValid(v bool)`

SetValid sets Valid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


