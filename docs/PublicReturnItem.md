# PublicReturnItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**ProductId** | **string** |  | 
**Quantity** | **int64** |  | 
**Reason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPublicReturnItem

`func NewPublicReturnItem(productId string, quantity int64, ) *PublicReturnItem`

NewPublicReturnItem instantiates a new PublicReturnItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicReturnItemWithDefaults

`func NewPublicReturnItemWithDefaults() *PublicReturnItem`

NewPublicReturnItemWithDefaults instantiates a new PublicReturnItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PublicReturnItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PublicReturnItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PublicReturnItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PublicReturnItem) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *PublicReturnItem) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *PublicReturnItem) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetProductId

`func (o *PublicReturnItem) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *PublicReturnItem) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *PublicReturnItem) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetQuantity

`func (o *PublicReturnItem) GetQuantity() int64`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *PublicReturnItem) GetQuantityOk() (*int64, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *PublicReturnItem) SetQuantity(v int64)`

SetQuantity sets Quantity field to given value.


### GetReason

`func (o *PublicReturnItem) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *PublicReturnItem) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *PublicReturnItem) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *PublicReturnItem) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *PublicReturnItem) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *PublicReturnItem) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


