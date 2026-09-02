# SubscriptionOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPeriodEnd** | Pointer to **NullableTime** |  | [optional] 
**Features** | [**PlanFeatures**](PlanFeatures.md) |  | 
**IsTrialing** | **bool** |  | 
**Limits** | [**PlanLimits**](PlanLimits.md) |  | 
**ManageUrl** | Pointer to **NullableString** |  | [optional] 
**Plan** | **string** | Resolved plan id (free/starter/business/enterprise, or a custom override id). | 
**PlanName** | **string** |  | 
**PriceEur** | **float64** | Monthly price in EUR; &#x60;-1.0&#x60; &#x3D; custom pricing (enterprise). | 
**Quantity** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to **NullableString** |  | [optional] 
**SubscriptionId** | Pointer to **NullableString** |  | [optional] 
**TrialEndsAt** | Pointer to **NullableTime** |  | [optional] 
**Usage** | [**UsageSnapshot**](UsageSnapshot.md) |  | 

## Methods

### NewSubscriptionOverview

`func NewSubscriptionOverview(features PlanFeatures, isTrialing bool, limits PlanLimits, plan string, planName string, priceEur float64, usage UsageSnapshot, ) *SubscriptionOverview`

NewSubscriptionOverview instantiates a new SubscriptionOverview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionOverviewWithDefaults

`func NewSubscriptionOverviewWithDefaults() *SubscriptionOverview`

NewSubscriptionOverviewWithDefaults instantiates a new SubscriptionOverview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPeriodEnd

`func (o *SubscriptionOverview) GetCurrentPeriodEnd() time.Time`

GetCurrentPeriodEnd returns the CurrentPeriodEnd field if non-nil, zero value otherwise.

### GetCurrentPeriodEndOk

`func (o *SubscriptionOverview) GetCurrentPeriodEndOk() (*time.Time, bool)`

GetCurrentPeriodEndOk returns a tuple with the CurrentPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriodEnd

`func (o *SubscriptionOverview) SetCurrentPeriodEnd(v time.Time)`

SetCurrentPeriodEnd sets CurrentPeriodEnd field to given value.

### HasCurrentPeriodEnd

`func (o *SubscriptionOverview) HasCurrentPeriodEnd() bool`

HasCurrentPeriodEnd returns a boolean if a field has been set.

### SetCurrentPeriodEndNil

`func (o *SubscriptionOverview) SetCurrentPeriodEndNil(b bool)`

 SetCurrentPeriodEndNil sets the value for CurrentPeriodEnd to be an explicit nil

### UnsetCurrentPeriodEnd
`func (o *SubscriptionOverview) UnsetCurrentPeriodEnd()`

UnsetCurrentPeriodEnd ensures that no value is present for CurrentPeriodEnd, not even an explicit nil
### GetFeatures

`func (o *SubscriptionOverview) GetFeatures() PlanFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *SubscriptionOverview) GetFeaturesOk() (*PlanFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *SubscriptionOverview) SetFeatures(v PlanFeatures)`

SetFeatures sets Features field to given value.


### GetIsTrialing

`func (o *SubscriptionOverview) GetIsTrialing() bool`

GetIsTrialing returns the IsTrialing field if non-nil, zero value otherwise.

### GetIsTrialingOk

`func (o *SubscriptionOverview) GetIsTrialingOk() (*bool, bool)`

GetIsTrialingOk returns a tuple with the IsTrialing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrialing

`func (o *SubscriptionOverview) SetIsTrialing(v bool)`

SetIsTrialing sets IsTrialing field to given value.


### GetLimits

`func (o *SubscriptionOverview) GetLimits() PlanLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *SubscriptionOverview) GetLimitsOk() (*PlanLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *SubscriptionOverview) SetLimits(v PlanLimits)`

SetLimits sets Limits field to given value.


### GetManageUrl

`func (o *SubscriptionOverview) GetManageUrl() string`

GetManageUrl returns the ManageUrl field if non-nil, zero value otherwise.

### GetManageUrlOk

`func (o *SubscriptionOverview) GetManageUrlOk() (*string, bool)`

GetManageUrlOk returns a tuple with the ManageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManageUrl

`func (o *SubscriptionOverview) SetManageUrl(v string)`

SetManageUrl sets ManageUrl field to given value.

### HasManageUrl

`func (o *SubscriptionOverview) HasManageUrl() bool`

HasManageUrl returns a boolean if a field has been set.

### SetManageUrlNil

`func (o *SubscriptionOverview) SetManageUrlNil(b bool)`

 SetManageUrlNil sets the value for ManageUrl to be an explicit nil

### UnsetManageUrl
`func (o *SubscriptionOverview) UnsetManageUrl()`

UnsetManageUrl ensures that no value is present for ManageUrl, not even an explicit nil
### GetPlan

`func (o *SubscriptionOverview) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *SubscriptionOverview) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *SubscriptionOverview) SetPlan(v string)`

SetPlan sets Plan field to given value.


### GetPlanName

`func (o *SubscriptionOverview) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *SubscriptionOverview) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *SubscriptionOverview) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.


### GetPriceEur

`func (o *SubscriptionOverview) GetPriceEur() float64`

GetPriceEur returns the PriceEur field if non-nil, zero value otherwise.

### GetPriceEurOk

`func (o *SubscriptionOverview) GetPriceEurOk() (*float64, bool)`

GetPriceEurOk returns a tuple with the PriceEur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceEur

`func (o *SubscriptionOverview) SetPriceEur(v float64)`

SetPriceEur sets PriceEur field to given value.


### GetQuantity

`func (o *SubscriptionOverview) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SubscriptionOverview) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SubscriptionOverview) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *SubscriptionOverview) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### SetQuantityNil

`func (o *SubscriptionOverview) SetQuantityNil(b bool)`

 SetQuantityNil sets the value for Quantity to be an explicit nil

### UnsetQuantity
`func (o *SubscriptionOverview) UnsetQuantity()`

UnsetQuantity ensures that no value is present for Quantity, not even an explicit nil
### GetStatus

`func (o *SubscriptionOverview) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SubscriptionOverview) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SubscriptionOverview) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SubscriptionOverview) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *SubscriptionOverview) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *SubscriptionOverview) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSubscriptionId

`func (o *SubscriptionOverview) GetSubscriptionId() string`

GetSubscriptionId returns the SubscriptionId field if non-nil, zero value otherwise.

### GetSubscriptionIdOk

`func (o *SubscriptionOverview) GetSubscriptionIdOk() (*string, bool)`

GetSubscriptionIdOk returns a tuple with the SubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionId

`func (o *SubscriptionOverview) SetSubscriptionId(v string)`

SetSubscriptionId sets SubscriptionId field to given value.

### HasSubscriptionId

`func (o *SubscriptionOverview) HasSubscriptionId() bool`

HasSubscriptionId returns a boolean if a field has been set.

### SetSubscriptionIdNil

`func (o *SubscriptionOverview) SetSubscriptionIdNil(b bool)`

 SetSubscriptionIdNil sets the value for SubscriptionId to be an explicit nil

### UnsetSubscriptionId
`func (o *SubscriptionOverview) UnsetSubscriptionId()`

UnsetSubscriptionId ensures that no value is present for SubscriptionId, not even an explicit nil
### GetTrialEndsAt

`func (o *SubscriptionOverview) GetTrialEndsAt() time.Time`

GetTrialEndsAt returns the TrialEndsAt field if non-nil, zero value otherwise.

### GetTrialEndsAtOk

`func (o *SubscriptionOverview) GetTrialEndsAtOk() (*time.Time, bool)`

GetTrialEndsAtOk returns a tuple with the TrialEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialEndsAt

`func (o *SubscriptionOverview) SetTrialEndsAt(v time.Time)`

SetTrialEndsAt sets TrialEndsAt field to given value.

### HasTrialEndsAt

`func (o *SubscriptionOverview) HasTrialEndsAt() bool`

HasTrialEndsAt returns a boolean if a field has been set.

### SetTrialEndsAtNil

`func (o *SubscriptionOverview) SetTrialEndsAtNil(b bool)`

 SetTrialEndsAtNil sets the value for TrialEndsAt to be an explicit nil

### UnsetTrialEndsAt
`func (o *SubscriptionOverview) UnsetTrialEndsAt()`

UnsetTrialEndsAt ensures that no value is present for TrialEndsAt, not even an explicit nil
### GetUsage

`func (o *SubscriptionOverview) GetUsage() UsageSnapshot`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *SubscriptionOverview) GetUsageOk() (*UsageSnapshot, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *SubscriptionOverview) SetUsage(v UsageSnapshot)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


