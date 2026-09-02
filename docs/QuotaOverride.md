# QuotaOverride

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Features** | Pointer to [**NullableQuotaOverrideFeatures**](QuotaOverrideFeatures.md) |  | [optional] 
**MaxConnectors** | Pointer to **NullableInt32** |  | [optional] 
**MaxInvoicesPerMonth** | Pointer to **NullableInt64** |  | [optional] 
**MaxUsers** | Pointer to **NullableInt32** |  | [optional] 
**Metered** | Pointer to **map[string]int64** |  | [optional] 
**Plan** | Pointer to **NullableString** | Custom plan id; unknown ids resolve to enterprise limits. | [optional] 

## Methods

### NewQuotaOverride

`func NewQuotaOverride() *QuotaOverride`

NewQuotaOverride instantiates a new QuotaOverride object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuotaOverrideWithDefaults

`func NewQuotaOverrideWithDefaults() *QuotaOverride`

NewQuotaOverrideWithDefaults instantiates a new QuotaOverride object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatures

`func (o *QuotaOverride) GetFeatures() QuotaOverrideFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *QuotaOverride) GetFeaturesOk() (*QuotaOverrideFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *QuotaOverride) SetFeatures(v QuotaOverrideFeatures)`

SetFeatures sets Features field to given value.

### HasFeatures

`func (o *QuotaOverride) HasFeatures() bool`

HasFeatures returns a boolean if a field has been set.

### SetFeaturesNil

`func (o *QuotaOverride) SetFeaturesNil(b bool)`

 SetFeaturesNil sets the value for Features to be an explicit nil

### UnsetFeatures
`func (o *QuotaOverride) UnsetFeatures()`

UnsetFeatures ensures that no value is present for Features, not even an explicit nil
### GetMaxConnectors

`func (o *QuotaOverride) GetMaxConnectors() int32`

GetMaxConnectors returns the MaxConnectors field if non-nil, zero value otherwise.

### GetMaxConnectorsOk

`func (o *QuotaOverride) GetMaxConnectorsOk() (*int32, bool)`

GetMaxConnectorsOk returns a tuple with the MaxConnectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxConnectors

`func (o *QuotaOverride) SetMaxConnectors(v int32)`

SetMaxConnectors sets MaxConnectors field to given value.

### HasMaxConnectors

`func (o *QuotaOverride) HasMaxConnectors() bool`

HasMaxConnectors returns a boolean if a field has been set.

### SetMaxConnectorsNil

`func (o *QuotaOverride) SetMaxConnectorsNil(b bool)`

 SetMaxConnectorsNil sets the value for MaxConnectors to be an explicit nil

### UnsetMaxConnectors
`func (o *QuotaOverride) UnsetMaxConnectors()`

UnsetMaxConnectors ensures that no value is present for MaxConnectors, not even an explicit nil
### GetMaxInvoicesPerMonth

`func (o *QuotaOverride) GetMaxInvoicesPerMonth() int64`

GetMaxInvoicesPerMonth returns the MaxInvoicesPerMonth field if non-nil, zero value otherwise.

### GetMaxInvoicesPerMonthOk

`func (o *QuotaOverride) GetMaxInvoicesPerMonthOk() (*int64, bool)`

GetMaxInvoicesPerMonthOk returns a tuple with the MaxInvoicesPerMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxInvoicesPerMonth

`func (o *QuotaOverride) SetMaxInvoicesPerMonth(v int64)`

SetMaxInvoicesPerMonth sets MaxInvoicesPerMonth field to given value.

### HasMaxInvoicesPerMonth

`func (o *QuotaOverride) HasMaxInvoicesPerMonth() bool`

HasMaxInvoicesPerMonth returns a boolean if a field has been set.

### SetMaxInvoicesPerMonthNil

`func (o *QuotaOverride) SetMaxInvoicesPerMonthNil(b bool)`

 SetMaxInvoicesPerMonthNil sets the value for MaxInvoicesPerMonth to be an explicit nil

### UnsetMaxInvoicesPerMonth
`func (o *QuotaOverride) UnsetMaxInvoicesPerMonth()`

UnsetMaxInvoicesPerMonth ensures that no value is present for MaxInvoicesPerMonth, not even an explicit nil
### GetMaxUsers

`func (o *QuotaOverride) GetMaxUsers() int32`

GetMaxUsers returns the MaxUsers field if non-nil, zero value otherwise.

### GetMaxUsersOk

`func (o *QuotaOverride) GetMaxUsersOk() (*int32, bool)`

GetMaxUsersOk returns a tuple with the MaxUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUsers

`func (o *QuotaOverride) SetMaxUsers(v int32)`

SetMaxUsers sets MaxUsers field to given value.

### HasMaxUsers

`func (o *QuotaOverride) HasMaxUsers() bool`

HasMaxUsers returns a boolean if a field has been set.

### SetMaxUsersNil

`func (o *QuotaOverride) SetMaxUsersNil(b bool)`

 SetMaxUsersNil sets the value for MaxUsers to be an explicit nil

### UnsetMaxUsers
`func (o *QuotaOverride) UnsetMaxUsers()`

UnsetMaxUsers ensures that no value is present for MaxUsers, not even an explicit nil
### GetMetered

`func (o *QuotaOverride) GetMetered() map[string]int64`

GetMetered returns the Metered field if non-nil, zero value otherwise.

### GetMeteredOk

`func (o *QuotaOverride) GetMeteredOk() (*map[string]int64, bool)`

GetMeteredOk returns a tuple with the Metered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetered

`func (o *QuotaOverride) SetMetered(v map[string]int64)`

SetMetered sets Metered field to given value.

### HasMetered

`func (o *QuotaOverride) HasMetered() bool`

HasMetered returns a boolean if a field has been set.

### SetMeteredNil

`func (o *QuotaOverride) SetMeteredNil(b bool)`

 SetMeteredNil sets the value for Metered to be an explicit nil

### UnsetMetered
`func (o *QuotaOverride) UnsetMetered()`

UnsetMetered ensures that no value is present for Metered, not even an explicit nil
### GetPlan

`func (o *QuotaOverride) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *QuotaOverride) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *QuotaOverride) SetPlan(v string)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *QuotaOverride) HasPlan() bool`

HasPlan returns a boolean if a field has been set.

### SetPlanNil

`func (o *QuotaOverride) SetPlanNil(b bool)`

 SetPlanNil sets the value for Plan to be an explicit nil

### UnsetPlan
`func (o *QuotaOverride) UnsetPlan()`

UnsetPlan ensures that no value is present for Plan, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


