# CouponCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**DiscountType** | [**DiscountType**](DiscountType.md) |  | 
**DiscountValue** | **string** |  | 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**IsCombineable** | Pointer to **bool** |  | [optional] 
**MaxDiscountAmount** | Pointer to **NullableString** |  | [optional] 
**MaxUses** | Pointer to **NullableInt32** |  | [optional] 
**MaxUsesPerCustomer** | Pointer to **NullableInt32** |  | [optional] 
**MinOrderAmount** | Pointer to **NullableString** |  | [optional] 
**ProductIds** | Pointer to **interface{}** |  | [optional] 
**StartsAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewCouponCreate

`func NewCouponCreate(code string, discountType DiscountType, discountValue string, ) *CouponCreate`

NewCouponCreate instantiates a new CouponCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCouponCreateWithDefaults

`func NewCouponCreateWithDefaults() *CouponCreate`

NewCouponCreateWithDefaults instantiates a new CouponCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *CouponCreate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CouponCreate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CouponCreate) SetCode(v string)`

SetCode sets Code field to given value.


### GetDescription

`func (o *CouponCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CouponCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CouponCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CouponCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CouponCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CouponCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDiscountType

`func (o *CouponCreate) GetDiscountType() DiscountType`

GetDiscountType returns the DiscountType field if non-nil, zero value otherwise.

### GetDiscountTypeOk

`func (o *CouponCreate) GetDiscountTypeOk() (*DiscountType, bool)`

GetDiscountTypeOk returns a tuple with the DiscountType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountType

`func (o *CouponCreate) SetDiscountType(v DiscountType)`

SetDiscountType sets DiscountType field to given value.


### GetDiscountValue

`func (o *CouponCreate) GetDiscountValue() string`

GetDiscountValue returns the DiscountValue field if non-nil, zero value otherwise.

### GetDiscountValueOk

`func (o *CouponCreate) GetDiscountValueOk() (*string, bool)`

GetDiscountValueOk returns a tuple with the DiscountValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountValue

`func (o *CouponCreate) SetDiscountValue(v string)`

SetDiscountValue sets DiscountValue field to given value.


### GetExpiresAt

`func (o *CouponCreate) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CouponCreate) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CouponCreate) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CouponCreate) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *CouponCreate) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CouponCreate) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetIsActive

`func (o *CouponCreate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *CouponCreate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *CouponCreate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *CouponCreate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetIsCombineable

`func (o *CouponCreate) GetIsCombineable() bool`

GetIsCombineable returns the IsCombineable field if non-nil, zero value otherwise.

### GetIsCombineableOk

`func (o *CouponCreate) GetIsCombineableOk() (*bool, bool)`

GetIsCombineableOk returns a tuple with the IsCombineable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCombineable

`func (o *CouponCreate) SetIsCombineable(v bool)`

SetIsCombineable sets IsCombineable field to given value.

### HasIsCombineable

`func (o *CouponCreate) HasIsCombineable() bool`

HasIsCombineable returns a boolean if a field has been set.

### GetMaxDiscountAmount

`func (o *CouponCreate) GetMaxDiscountAmount() string`

GetMaxDiscountAmount returns the MaxDiscountAmount field if non-nil, zero value otherwise.

### GetMaxDiscountAmountOk

`func (o *CouponCreate) GetMaxDiscountAmountOk() (*string, bool)`

GetMaxDiscountAmountOk returns a tuple with the MaxDiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDiscountAmount

`func (o *CouponCreate) SetMaxDiscountAmount(v string)`

SetMaxDiscountAmount sets MaxDiscountAmount field to given value.

### HasMaxDiscountAmount

`func (o *CouponCreate) HasMaxDiscountAmount() bool`

HasMaxDiscountAmount returns a boolean if a field has been set.

### SetMaxDiscountAmountNil

`func (o *CouponCreate) SetMaxDiscountAmountNil(b bool)`

 SetMaxDiscountAmountNil sets the value for MaxDiscountAmount to be an explicit nil

### UnsetMaxDiscountAmount
`func (o *CouponCreate) UnsetMaxDiscountAmount()`

UnsetMaxDiscountAmount ensures that no value is present for MaxDiscountAmount, not even an explicit nil
### GetMaxUses

`func (o *CouponCreate) GetMaxUses() int32`

GetMaxUses returns the MaxUses field if non-nil, zero value otherwise.

### GetMaxUsesOk

`func (o *CouponCreate) GetMaxUsesOk() (*int32, bool)`

GetMaxUsesOk returns a tuple with the MaxUses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUses

`func (o *CouponCreate) SetMaxUses(v int32)`

SetMaxUses sets MaxUses field to given value.

### HasMaxUses

`func (o *CouponCreate) HasMaxUses() bool`

HasMaxUses returns a boolean if a field has been set.

### SetMaxUsesNil

`func (o *CouponCreate) SetMaxUsesNil(b bool)`

 SetMaxUsesNil sets the value for MaxUses to be an explicit nil

### UnsetMaxUses
`func (o *CouponCreate) UnsetMaxUses()`

UnsetMaxUses ensures that no value is present for MaxUses, not even an explicit nil
### GetMaxUsesPerCustomer

`func (o *CouponCreate) GetMaxUsesPerCustomer() int32`

GetMaxUsesPerCustomer returns the MaxUsesPerCustomer field if non-nil, zero value otherwise.

### GetMaxUsesPerCustomerOk

`func (o *CouponCreate) GetMaxUsesPerCustomerOk() (*int32, bool)`

GetMaxUsesPerCustomerOk returns a tuple with the MaxUsesPerCustomer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUsesPerCustomer

`func (o *CouponCreate) SetMaxUsesPerCustomer(v int32)`

SetMaxUsesPerCustomer sets MaxUsesPerCustomer field to given value.

### HasMaxUsesPerCustomer

`func (o *CouponCreate) HasMaxUsesPerCustomer() bool`

HasMaxUsesPerCustomer returns a boolean if a field has been set.

### SetMaxUsesPerCustomerNil

`func (o *CouponCreate) SetMaxUsesPerCustomerNil(b bool)`

 SetMaxUsesPerCustomerNil sets the value for MaxUsesPerCustomer to be an explicit nil

### UnsetMaxUsesPerCustomer
`func (o *CouponCreate) UnsetMaxUsesPerCustomer()`

UnsetMaxUsesPerCustomer ensures that no value is present for MaxUsesPerCustomer, not even an explicit nil
### GetMinOrderAmount

`func (o *CouponCreate) GetMinOrderAmount() string`

GetMinOrderAmount returns the MinOrderAmount field if non-nil, zero value otherwise.

### GetMinOrderAmountOk

`func (o *CouponCreate) GetMinOrderAmountOk() (*string, bool)`

GetMinOrderAmountOk returns a tuple with the MinOrderAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinOrderAmount

`func (o *CouponCreate) SetMinOrderAmount(v string)`

SetMinOrderAmount sets MinOrderAmount field to given value.

### HasMinOrderAmount

`func (o *CouponCreate) HasMinOrderAmount() bool`

HasMinOrderAmount returns a boolean if a field has been set.

### SetMinOrderAmountNil

`func (o *CouponCreate) SetMinOrderAmountNil(b bool)`

 SetMinOrderAmountNil sets the value for MinOrderAmount to be an explicit nil

### UnsetMinOrderAmount
`func (o *CouponCreate) UnsetMinOrderAmount()`

UnsetMinOrderAmount ensures that no value is present for MinOrderAmount, not even an explicit nil
### GetProductIds

`func (o *CouponCreate) GetProductIds() interface{}`

GetProductIds returns the ProductIds field if non-nil, zero value otherwise.

### GetProductIdsOk

`func (o *CouponCreate) GetProductIdsOk() (*interface{}, bool)`

GetProductIdsOk returns a tuple with the ProductIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductIds

`func (o *CouponCreate) SetProductIds(v interface{})`

SetProductIds sets ProductIds field to given value.

### HasProductIds

`func (o *CouponCreate) HasProductIds() bool`

HasProductIds returns a boolean if a field has been set.

### SetProductIdsNil

`func (o *CouponCreate) SetProductIdsNil(b bool)`

 SetProductIdsNil sets the value for ProductIds to be an explicit nil

### UnsetProductIds
`func (o *CouponCreate) UnsetProductIds()`

UnsetProductIds ensures that no value is present for ProductIds, not even an explicit nil
### GetStartsAt

`func (o *CouponCreate) GetStartsAt() time.Time`

GetStartsAt returns the StartsAt field if non-nil, zero value otherwise.

### GetStartsAtOk

`func (o *CouponCreate) GetStartsAtOk() (*time.Time, bool)`

GetStartsAtOk returns a tuple with the StartsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsAt

`func (o *CouponCreate) SetStartsAt(v time.Time)`

SetStartsAt sets StartsAt field to given value.

### HasStartsAt

`func (o *CouponCreate) HasStartsAt() bool`

HasStartsAt returns a boolean if a field has been set.

### SetStartsAtNil

`func (o *CouponCreate) SetStartsAtNil(b bool)`

 SetStartsAtNil sets the value for StartsAt to be an explicit nil

### UnsetStartsAt
`func (o *CouponCreate) UnsetStartsAt()`

UnsetStartsAt ensures that no value is present for StartsAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


