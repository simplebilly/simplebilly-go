# ShippingCredentials

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Dhl** | Pointer to [**NullableDhlCredentials**](DhlCredentials.md) |  | [optional] 
**Ups** | Pointer to [**NullableUpsCredentials**](UpsCredentials.md) |  | [optional] 

## Methods

### NewShippingCredentials

`func NewShippingCredentials() *ShippingCredentials`

NewShippingCredentials instantiates a new ShippingCredentials object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShippingCredentialsWithDefaults

`func NewShippingCredentialsWithDefaults() *ShippingCredentials`

NewShippingCredentialsWithDefaults instantiates a new ShippingCredentials object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDhl

`func (o *ShippingCredentials) GetDhl() DhlCredentials`

GetDhl returns the Dhl field if non-nil, zero value otherwise.

### GetDhlOk

`func (o *ShippingCredentials) GetDhlOk() (*DhlCredentials, bool)`

GetDhlOk returns a tuple with the Dhl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhl

`func (o *ShippingCredentials) SetDhl(v DhlCredentials)`

SetDhl sets Dhl field to given value.

### HasDhl

`func (o *ShippingCredentials) HasDhl() bool`

HasDhl returns a boolean if a field has been set.

### SetDhlNil

`func (o *ShippingCredentials) SetDhlNil(b bool)`

 SetDhlNil sets the value for Dhl to be an explicit nil

### UnsetDhl
`func (o *ShippingCredentials) UnsetDhl()`

UnsetDhl ensures that no value is present for Dhl, not even an explicit nil
### GetUps

`func (o *ShippingCredentials) GetUps() UpsCredentials`

GetUps returns the Ups field if non-nil, zero value otherwise.

### GetUpsOk

`func (o *ShippingCredentials) GetUpsOk() (*UpsCredentials, bool)`

GetUpsOk returns a tuple with the Ups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUps

`func (o *ShippingCredentials) SetUps(v UpsCredentials)`

SetUps sets Ups field to given value.

### HasUps

`func (o *ShippingCredentials) HasUps() bool`

HasUps returns a boolean if a field has been set.

### SetUpsNil

`func (o *ShippingCredentials) SetUpsNil(b bool)`

 SetUpsNil sets the value for Ups to be an explicit nil

### UnsetUps
`func (o *ShippingCredentials) UnsetUps()`

UnsetUps ensures that no value is present for Ups, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


