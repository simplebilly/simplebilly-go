# EmissionTarget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseValue** | **string** |  | 
**BaseYear** | **int32** | tCO2e in the base year (actuals). | 
**Description** | **string** | Transition-plan narrative (ESRS E1-1 light), may be empty. | 
**Scope** | [**EmissionTargetScope**](EmissionTargetScope.md) | \&quot;total\&quot; | \&quot;1\&quot; | \&quot;2\&quot; | \&quot;3\&quot;. | 
**TargetValue** | **string** |  | 
**TargetYear** | **int32** | tCO2e target for the target year. | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewEmissionTarget

`func NewEmissionTarget(baseValue string, baseYear int32, description string, scope EmissionTargetScope, targetValue string, targetYear int32, ) *EmissionTarget`

NewEmissionTarget instantiates a new EmissionTarget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmissionTargetWithDefaults

`func NewEmissionTargetWithDefaults() *EmissionTarget`

NewEmissionTargetWithDefaults instantiates a new EmissionTarget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseValue

`func (o *EmissionTarget) GetBaseValue() string`

GetBaseValue returns the BaseValue field if non-nil, zero value otherwise.

### GetBaseValueOk

`func (o *EmissionTarget) GetBaseValueOk() (*string, bool)`

GetBaseValueOk returns a tuple with the BaseValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseValue

`func (o *EmissionTarget) SetBaseValue(v string)`

SetBaseValue sets BaseValue field to given value.


### GetBaseYear

`func (o *EmissionTarget) GetBaseYear() int32`

GetBaseYear returns the BaseYear field if non-nil, zero value otherwise.

### GetBaseYearOk

`func (o *EmissionTarget) GetBaseYearOk() (*int32, bool)`

GetBaseYearOk returns a tuple with the BaseYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseYear

`func (o *EmissionTarget) SetBaseYear(v int32)`

SetBaseYear sets BaseYear field to given value.


### GetDescription

`func (o *EmissionTarget) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EmissionTarget) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EmissionTarget) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetScope

`func (o *EmissionTarget) GetScope() EmissionTargetScope`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *EmissionTarget) GetScopeOk() (*EmissionTargetScope, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *EmissionTarget) SetScope(v EmissionTargetScope)`

SetScope sets Scope field to given value.


### GetTargetValue

`func (o *EmissionTarget) GetTargetValue() string`

GetTargetValue returns the TargetValue field if non-nil, zero value otherwise.

### GetTargetValueOk

`func (o *EmissionTarget) GetTargetValueOk() (*string, bool)`

GetTargetValueOk returns a tuple with the TargetValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetValue

`func (o *EmissionTarget) SetTargetValue(v string)`

SetTargetValue sets TargetValue field to given value.


### GetTargetYear

`func (o *EmissionTarget) GetTargetYear() int32`

GetTargetYear returns the TargetYear field if non-nil, zero value otherwise.

### GetTargetYearOk

`func (o *EmissionTarget) GetTargetYearOk() (*int32, bool)`

GetTargetYearOk returns a tuple with the TargetYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetYear

`func (o *EmissionTarget) SetTargetYear(v int32)`

SetTargetYear sets TargetYear field to given value.


### GetUpdatedAt

`func (o *EmissionTarget) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *EmissionTarget) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *EmissionTarget) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *EmissionTarget) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *EmissionTarget) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *EmissionTarget) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


