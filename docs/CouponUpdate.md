# CouponUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**DiscountType** | Pointer to [**NullableDiscountType**](DiscountType.md) |  | [optional] 
**DiscountValue** | Pointer to **NullableString** |  | [optional] 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**IsCombineable** | Pointer to **NullableBool** |  | [optional] 
**MaxDiscountAmount** | Pointer to **NullableString** |  | [optional] 
**MaxUses** | Pointer to **NullableInt32** |  | [optional] 
**MaxUsesPerCustomer** | Pointer to **NullableInt32** |  | [optional] 
**MinOrderAmount** | Pointer to **NullableString** |  | [optional] 
**ProductIds** | Pointer to **interface{}** |  | [optional] 
**StartsAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewCouponUpdate

`func NewCouponUpdate() *CouponUpdate`

NewCouponUpdate instantiates a new CouponUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCouponUpdateWithDefaults

`func NewCouponUpdateWithDefaults() *CouponUpdate`

NewCouponUpdateWithDefaults instantiates a new CouponUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *CouponUpdate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CouponUpdate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CouponUpdate) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CouponUpdate) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *CouponUpdate) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *CouponUpdate) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetDescription

`func (o *CouponUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CouponUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CouponUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CouponUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CouponUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CouponUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDiscountType

`func (o *CouponUpdate) GetDiscountType() DiscountType`

GetDiscountType returns the DiscountType field if non-nil, zero value otherwise.

### GetDiscountTypeOk

`func (o *CouponUpdate) GetDiscountTypeOk() (*DiscountType, bool)`

GetDiscountTypeOk returns a tuple with the DiscountType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountType

`func (o *CouponUpdate) SetDiscountType(v DiscountType)`

SetDiscountType sets DiscountType field to given value.

### HasDiscountType

`func (o *CouponUpdate) HasDiscountType() bool`

HasDiscountType returns a boolean if a field has been set.

### SetDiscountTypeNil

`func (o *CouponUpdate) SetDiscountTypeNil(b bool)`

 SetDiscountTypeNil sets the value for DiscountType to be an explicit nil

### UnsetDiscountType
`func (o *CouponUpdate) UnsetDiscountType()`

UnsetDiscountType ensures that no value is present for DiscountType, not even an explicit nil
### GetDiscountValue

`func (o *CouponUpdate) GetDiscountValue() string`

GetDiscountValue returns the DiscountValue field if non-nil, zero value otherwise.

### GetDiscountValueOk

`func (o *CouponUpdate) GetDiscountValueOk() (*string, bool)`

GetDiscountValueOk returns a tuple with the DiscountValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountValue

`func (o *CouponUpdate) SetDiscountValue(v string)`

SetDiscountValue sets DiscountValue field to given value.

### HasDiscountValue

`func (o *CouponUpdate) HasDiscountValue() bool`

HasDiscountValue returns a boolean if a field has been set.

### SetDiscountValueNil

`func (o *CouponUpdate) SetDiscountValueNil(b bool)`

 SetDiscountValueNil sets the value for DiscountValue to be an explicit nil

### UnsetDiscountValue
`func (o *CouponUpdate) UnsetDiscountValue()`

UnsetDiscountValue ensures that no value is present for DiscountValue, not even an explicit nil
### GetExpiresAt

`func (o *CouponUpdate) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CouponUpdate) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CouponUpdate) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CouponUpdate) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *CouponUpdate) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CouponUpdate) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetIsActive

`func (o *CouponUpdate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *CouponUpdate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *CouponUpdate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *CouponUpdate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *CouponUpdate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *CouponUpdate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetIsCombineable

`func (o *CouponUpdate) GetIsCombineable() bool`

GetIsCombineable returns the IsCombineable field if non-nil, zero value otherwise.

### GetIsCombineableOk

`func (o *CouponUpdate) GetIsCombineableOk() (*bool, bool)`

GetIsCombineableOk returns a tuple with the IsCombineable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCombineable

`func (o *CouponUpdate) SetIsCombineable(v bool)`

SetIsCombineable sets IsCombineable field to given value.

### HasIsCombineable

`func (o *CouponUpdate) HasIsCombineable() bool`

HasIsCombineable returns a boolean if a field has been set.

### SetIsCombineableNil

`func (o *CouponUpdate) SetIsCombineableNil(b bool)`

 SetIsCombineableNil sets the value for IsCombineable to be an explicit nil

### UnsetIsCombineable
`func (o *CouponUpdate) UnsetIsCombineable()`

UnsetIsCombineable ensures that no value is present for IsCombineable, not even an explicit nil
### GetMaxDiscountAmount

`func (o *CouponUpdate) GetMaxDiscountAmount() string`

GetMaxDiscountAmount returns the MaxDiscountAmount field if non-nil, zero value otherwise.

### GetMaxDiscountAmountOk

`func (o *CouponUpdate) GetMaxDiscountAmountOk() (*string, bool)`

GetMaxDiscountAmountOk returns a tuple with the MaxDiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDiscountAmount

`func (o *CouponUpdate) SetMaxDiscountAmount(v string)`

SetMaxDiscountAmount sets MaxDiscountAmount field to given value.

### HasMaxDiscountAmount

`func (o *CouponUpdate) HasMaxDiscountAmount() bool`

HasMaxDiscountAmount returns a boolean if a field has been set.

### SetMaxDiscountAmountNil

`func (o *CouponUpdate) SetMaxDiscountAmountNil(b bool)`

 SetMaxDiscountAmountNil sets the value for MaxDiscountAmount to be an explicit nil

### UnsetMaxDiscountAmount
`func (o *CouponUpdate) UnsetMaxDiscountAmount()`

UnsetMaxDiscountAmount ensures that no value is present for MaxDiscountAmount, not even an explicit nil
### GetMaxUses

`func (o *CouponUpdate) GetMaxUses() int32`

GetMaxUses returns the MaxUses field if non-nil, zero value otherwise.

### GetMaxUsesOk

`func (o *CouponUpdate) GetMaxUsesOk() (*int32, bool)`

GetMaxUsesOk returns a tuple with the MaxUses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUses

`func (o *CouponUpdate) SetMaxUses(v int32)`

SetMaxUses sets MaxUses field to given value.

### HasMaxUses

`func (o *CouponUpdate) HasMaxUses() bool`

HasMaxUses returns a boolean if a field has been set.

### SetMaxUsesNil

`func (o *CouponUpdate) SetMaxUsesNil(b bool)`

 SetMaxUsesNil sets the value for MaxUses to be an explicit nil

### UnsetMaxUses
`func (o *CouponUpdate) UnsetMaxUses()`

UnsetMaxUses ensures that no value is present for MaxUses, not even an explicit nil
### GetMaxUsesPerCustomer

`func (o *CouponUpdate) GetMaxUsesPerCustomer() int32`

GetMaxUsesPerCustomer returns the MaxUsesPerCustomer field if non-nil, zero value otherwise.

### GetMaxUsesPerCustomerOk

`func (o *CouponUpdate) GetMaxUsesPerCustomerOk() (*int32, bool)`

GetMaxUsesPerCustomerOk returns a tuple with the MaxUsesPerCustomer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUsesPerCustomer

`func (o *CouponUpdate) SetMaxUsesPerCustomer(v int32)`

SetMaxUsesPerCustomer sets MaxUsesPerCustomer field to given value.

### HasMaxUsesPerCustomer

`func (o *CouponUpdate) HasMaxUsesPerCustomer() bool`

HasMaxUsesPerCustomer returns a boolean if a field has been set.

### SetMaxUsesPerCustomerNil

`func (o *CouponUpdate) SetMaxUsesPerCustomerNil(b bool)`

 SetMaxUsesPerCustomerNil sets the value for MaxUsesPerCustomer to be an explicit nil

### UnsetMaxUsesPerCustomer
`func (o *CouponUpdate) UnsetMaxUsesPerCustomer()`

UnsetMaxUsesPerCustomer ensures that no value is present for MaxUsesPerCustomer, not even an explicit nil
### GetMinOrderAmount

`func (o *CouponUpdate) GetMinOrderAmount() string`

GetMinOrderAmount returns the MinOrderAmount field if non-nil, zero value otherwise.

### GetMinOrderAmountOk

`func (o *CouponUpdate) GetMinOrderAmountOk() (*string, bool)`

GetMinOrderAmountOk returns a tuple with the MinOrderAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinOrderAmount

`func (o *CouponUpdate) SetMinOrderAmount(v string)`

SetMinOrderAmount sets MinOrderAmount field to given value.

### HasMinOrderAmount

`func (o *CouponUpdate) HasMinOrderAmount() bool`

HasMinOrderAmount returns a boolean if a field has been set.

### SetMinOrderAmountNil

`func (o *CouponUpdate) SetMinOrderAmountNil(b bool)`

 SetMinOrderAmountNil sets the value for MinOrderAmount to be an explicit nil

### UnsetMinOrderAmount
`func (o *CouponUpdate) UnsetMinOrderAmount()`

UnsetMinOrderAmount ensures that no value is present for MinOrderAmount, not even an explicit nil
### GetProductIds

`func (o *CouponUpdate) GetProductIds() interface{}`

GetProductIds returns the ProductIds field if non-nil, zero value otherwise.

### GetProductIdsOk

`func (o *CouponUpdate) GetProductIdsOk() (*interface{}, bool)`

GetProductIdsOk returns a tuple with the ProductIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductIds

`func (o *CouponUpdate) SetProductIds(v interface{})`

SetProductIds sets ProductIds field to given value.

### HasProductIds

`func (o *CouponUpdate) HasProductIds() bool`

HasProductIds returns a boolean if a field has been set.

### SetProductIdsNil

`func (o *CouponUpdate) SetProductIdsNil(b bool)`

 SetProductIdsNil sets the value for ProductIds to be an explicit nil

### UnsetProductIds
`func (o *CouponUpdate) UnsetProductIds()`

UnsetProductIds ensures that no value is present for ProductIds, not even an explicit nil
### GetStartsAt

`func (o *CouponUpdate) GetStartsAt() time.Time`

GetStartsAt returns the StartsAt field if non-nil, zero value otherwise.

### GetStartsAtOk

`func (o *CouponUpdate) GetStartsAtOk() (*time.Time, bool)`

GetStartsAtOk returns a tuple with the StartsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsAt

`func (o *CouponUpdate) SetStartsAt(v time.Time)`

SetStartsAt sets StartsAt field to given value.

### HasStartsAt

`func (o *CouponUpdate) HasStartsAt() bool`

HasStartsAt returns a boolean if a field has been set.

### SetStartsAtNil

`func (o *CouponUpdate) SetStartsAtNil(b bool)`

 SetStartsAtNil sets the value for StartsAt to be an explicit nil

### UnsetStartsAt
`func (o *CouponUpdate) UnsetStartsAt()`

UnsetStartsAt ensures that no value is present for StartsAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


