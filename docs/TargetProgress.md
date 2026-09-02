# TargetProgress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseValue** | **float64** |  | 
**BaseYear** | **int32** |  | 
**Description** | **string** |  | 
**Id** | **string** |  | 
**ProgressPct** | Pointer to **NullableFloat64** | Current year&#39;s emissions for the scope as % of the target. None when no data. | [optional] 
**Scope** | **string** |  | 
**TargetValue** | **float64** |  | 
**TargetYear** | **int32** |  | 

## Methods

### NewTargetProgress

`func NewTargetProgress(baseValue float64, baseYear int32, description string, id string, scope string, targetValue float64, targetYear int32, ) *TargetProgress`

NewTargetProgress instantiates a new TargetProgress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTargetProgressWithDefaults

`func NewTargetProgressWithDefaults() *TargetProgress`

NewTargetProgressWithDefaults instantiates a new TargetProgress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseValue

`func (o *TargetProgress) GetBaseValue() float64`

GetBaseValue returns the BaseValue field if non-nil, zero value otherwise.

### GetBaseValueOk

`func (o *TargetProgress) GetBaseValueOk() (*float64, bool)`

GetBaseValueOk returns a tuple with the BaseValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseValue

`func (o *TargetProgress) SetBaseValue(v float64)`

SetBaseValue sets BaseValue field to given value.


### GetBaseYear

`func (o *TargetProgress) GetBaseYear() int32`

GetBaseYear returns the BaseYear field if non-nil, zero value otherwise.

### GetBaseYearOk

`func (o *TargetProgress) GetBaseYearOk() (*int32, bool)`

GetBaseYearOk returns a tuple with the BaseYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseYear

`func (o *TargetProgress) SetBaseYear(v int32)`

SetBaseYear sets BaseYear field to given value.


### GetDescription

`func (o *TargetProgress) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TargetProgress) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TargetProgress) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *TargetProgress) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TargetProgress) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TargetProgress) SetId(v string)`

SetId sets Id field to given value.


### GetProgressPct

`func (o *TargetProgress) GetProgressPct() float64`

GetProgressPct returns the ProgressPct field if non-nil, zero value otherwise.

### GetProgressPctOk

`func (o *TargetProgress) GetProgressPctOk() (*float64, bool)`

GetProgressPctOk returns a tuple with the ProgressPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressPct

`func (o *TargetProgress) SetProgressPct(v float64)`

SetProgressPct sets ProgressPct field to given value.

### HasProgressPct

`func (o *TargetProgress) HasProgressPct() bool`

HasProgressPct returns a boolean if a field has been set.

### SetProgressPctNil

`func (o *TargetProgress) SetProgressPctNil(b bool)`

 SetProgressPctNil sets the value for ProgressPct to be an explicit nil

### UnsetProgressPct
`func (o *TargetProgress) UnsetProgressPct()`

UnsetProgressPct ensures that no value is present for ProgressPct, not even an explicit nil
### GetScope

`func (o *TargetProgress) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *TargetProgress) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *TargetProgress) SetScope(v string)`

SetScope sets Scope field to given value.


### GetTargetValue

`func (o *TargetProgress) GetTargetValue() float64`

GetTargetValue returns the TargetValue field if non-nil, zero value otherwise.

### GetTargetValueOk

`func (o *TargetProgress) GetTargetValueOk() (*float64, bool)`

GetTargetValueOk returns a tuple with the TargetValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetValue

`func (o *TargetProgress) SetTargetValue(v float64)`

SetTargetValue sets TargetValue field to given value.


### GetTargetYear

`func (o *TargetProgress) GetTargetYear() int32`

GetTargetYear returns the TargetYear field if non-nil, zero value otherwise.

### GetTargetYearOk

`func (o *TargetProgress) GetTargetYearOk() (*int32, bool)`

GetTargetYearOk returns a tuple with the TargetYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetYear

`func (o *TargetProgress) SetTargetYear(v int32)`

SetTargetYear sets TargetYear field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


