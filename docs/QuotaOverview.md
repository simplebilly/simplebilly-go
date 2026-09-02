# QuotaOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Features** | [**PlanFeatures**](PlanFeatures.md) |  | 
**IsTrialing** | **bool** |  | 
**Limits** | [**PlanLimits**](PlanLimits.md) |  | 
**Metered** | [**[]MeteredUsage**](MeteredUsage.md) |  | 
**Plan** | **string** |  | 
**PlanName** | **string** |  | 
**TrialEndsAt** | Pointer to **NullableTime** |  | [optional] 
**Usage** | [**UsageSnapshot**](UsageSnapshot.md) |  | 

## Methods

### NewQuotaOverview

`func NewQuotaOverview(features PlanFeatures, isTrialing bool, limits PlanLimits, metered []MeteredUsage, plan string, planName string, usage UsageSnapshot, ) *QuotaOverview`

NewQuotaOverview instantiates a new QuotaOverview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuotaOverviewWithDefaults

`func NewQuotaOverviewWithDefaults() *QuotaOverview`

NewQuotaOverviewWithDefaults instantiates a new QuotaOverview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatures

`func (o *QuotaOverview) GetFeatures() PlanFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *QuotaOverview) GetFeaturesOk() (*PlanFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *QuotaOverview) SetFeatures(v PlanFeatures)`

SetFeatures sets Features field to given value.


### GetIsTrialing

`func (o *QuotaOverview) GetIsTrialing() bool`

GetIsTrialing returns the IsTrialing field if non-nil, zero value otherwise.

### GetIsTrialingOk

`func (o *QuotaOverview) GetIsTrialingOk() (*bool, bool)`

GetIsTrialingOk returns a tuple with the IsTrialing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrialing

`func (o *QuotaOverview) SetIsTrialing(v bool)`

SetIsTrialing sets IsTrialing field to given value.


### GetLimits

`func (o *QuotaOverview) GetLimits() PlanLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *QuotaOverview) GetLimitsOk() (*PlanLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *QuotaOverview) SetLimits(v PlanLimits)`

SetLimits sets Limits field to given value.


### GetMetered

`func (o *QuotaOverview) GetMetered() []MeteredUsage`

GetMetered returns the Metered field if non-nil, zero value otherwise.

### GetMeteredOk

`func (o *QuotaOverview) GetMeteredOk() (*[]MeteredUsage, bool)`

GetMeteredOk returns a tuple with the Metered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetered

`func (o *QuotaOverview) SetMetered(v []MeteredUsage)`

SetMetered sets Metered field to given value.


### GetPlan

`func (o *QuotaOverview) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *QuotaOverview) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *QuotaOverview) SetPlan(v string)`

SetPlan sets Plan field to given value.


### GetPlanName

`func (o *QuotaOverview) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *QuotaOverview) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *QuotaOverview) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.


### GetTrialEndsAt

`func (o *QuotaOverview) GetTrialEndsAt() time.Time`

GetTrialEndsAt returns the TrialEndsAt field if non-nil, zero value otherwise.

### GetTrialEndsAtOk

`func (o *QuotaOverview) GetTrialEndsAtOk() (*time.Time, bool)`

GetTrialEndsAtOk returns a tuple with the TrialEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialEndsAt

`func (o *QuotaOverview) SetTrialEndsAt(v time.Time)`

SetTrialEndsAt sets TrialEndsAt field to given value.

### HasTrialEndsAt

`func (o *QuotaOverview) HasTrialEndsAt() bool`

HasTrialEndsAt returns a boolean if a field has been set.

### SetTrialEndsAtNil

`func (o *QuotaOverview) SetTrialEndsAtNil(b bool)`

 SetTrialEndsAtNil sets the value for TrialEndsAt to be an explicit nil

### UnsetTrialEndsAt
`func (o *QuotaOverview) UnsetTrialEndsAt()`

UnsetTrialEndsAt ensures that no value is present for TrialEndsAt, not even an explicit nil
### GetUsage

`func (o *QuotaOverview) GetUsage() UsageSnapshot`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *QuotaOverview) GetUsageOk() (*UsageSnapshot, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *QuotaOverview) SetUsage(v UsageSnapshot)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


