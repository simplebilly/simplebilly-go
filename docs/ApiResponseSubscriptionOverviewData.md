# ApiResponseSubscriptionOverviewData

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

### NewApiResponseSubscriptionOverviewData

`func NewApiResponseSubscriptionOverviewData(features PlanFeatures, isTrialing bool, limits PlanLimits, plan string, planName string, priceEur float64, usage UsageSnapshot, ) *ApiResponseSubscriptionOverviewData`

NewApiResponseSubscriptionOverviewData instantiates a new ApiResponseSubscriptionOverviewData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseSubscriptionOverviewDataWithDefaults

`func NewApiResponseSubscriptionOverviewDataWithDefaults() *ApiResponseSubscriptionOverviewData`

NewApiResponseSubscriptionOverviewDataWithDefaults instantiates a new ApiResponseSubscriptionOverviewData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPeriodEnd

`func (o *ApiResponseSubscriptionOverviewData) GetCurrentPeriodEnd() time.Time`

GetCurrentPeriodEnd returns the CurrentPeriodEnd field if non-nil, zero value otherwise.

### GetCurrentPeriodEndOk

`func (o *ApiResponseSubscriptionOverviewData) GetCurrentPeriodEndOk() (*time.Time, bool)`

GetCurrentPeriodEndOk returns a tuple with the CurrentPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriodEnd

`func (o *ApiResponseSubscriptionOverviewData) SetCurrentPeriodEnd(v time.Time)`

SetCurrentPeriodEnd sets CurrentPeriodEnd field to given value.

### HasCurrentPeriodEnd

`func (o *ApiResponseSubscriptionOverviewData) HasCurrentPeriodEnd() bool`

HasCurrentPeriodEnd returns a boolean if a field has been set.

### SetCurrentPeriodEndNil

`func (o *ApiResponseSubscriptionOverviewData) SetCurrentPeriodEndNil(b bool)`

 SetCurrentPeriodEndNil sets the value for CurrentPeriodEnd to be an explicit nil

### UnsetCurrentPeriodEnd
`func (o *ApiResponseSubscriptionOverviewData) UnsetCurrentPeriodEnd()`

UnsetCurrentPeriodEnd ensures that no value is present for CurrentPeriodEnd, not even an explicit nil
### GetFeatures

`func (o *ApiResponseSubscriptionOverviewData) GetFeatures() PlanFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *ApiResponseSubscriptionOverviewData) GetFeaturesOk() (*PlanFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *ApiResponseSubscriptionOverviewData) SetFeatures(v PlanFeatures)`

SetFeatures sets Features field to given value.


### GetIsTrialing

`func (o *ApiResponseSubscriptionOverviewData) GetIsTrialing() bool`

GetIsTrialing returns the IsTrialing field if non-nil, zero value otherwise.

### GetIsTrialingOk

`func (o *ApiResponseSubscriptionOverviewData) GetIsTrialingOk() (*bool, bool)`

GetIsTrialingOk returns a tuple with the IsTrialing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrialing

`func (o *ApiResponseSubscriptionOverviewData) SetIsTrialing(v bool)`

SetIsTrialing sets IsTrialing field to given value.


### GetLimits

`func (o *ApiResponseSubscriptionOverviewData) GetLimits() PlanLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *ApiResponseSubscriptionOverviewData) GetLimitsOk() (*PlanLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *ApiResponseSubscriptionOverviewData) SetLimits(v PlanLimits)`

SetLimits sets Limits field to given value.


### GetManageUrl

`func (o *ApiResponseSubscriptionOverviewData) GetManageUrl() string`

GetManageUrl returns the ManageUrl field if non-nil, zero value otherwise.

### GetManageUrlOk

`func (o *ApiResponseSubscriptionOverviewData) GetManageUrlOk() (*string, bool)`

GetManageUrlOk returns a tuple with the ManageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManageUrl

`func (o *ApiResponseSubscriptionOverviewData) SetManageUrl(v string)`

SetManageUrl sets ManageUrl field to given value.

### HasManageUrl

`func (o *ApiResponseSubscriptionOverviewData) HasManageUrl() bool`

HasManageUrl returns a boolean if a field has been set.

### SetManageUrlNil

`func (o *ApiResponseSubscriptionOverviewData) SetManageUrlNil(b bool)`

 SetManageUrlNil sets the value for ManageUrl to be an explicit nil

### UnsetManageUrl
`func (o *ApiResponseSubscriptionOverviewData) UnsetManageUrl()`

UnsetManageUrl ensures that no value is present for ManageUrl, not even an explicit nil
### GetPlan

`func (o *ApiResponseSubscriptionOverviewData) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *ApiResponseSubscriptionOverviewData) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *ApiResponseSubscriptionOverviewData) SetPlan(v string)`

SetPlan sets Plan field to given value.


### GetPlanName

`func (o *ApiResponseSubscriptionOverviewData) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *ApiResponseSubscriptionOverviewData) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *ApiResponseSubscriptionOverviewData) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.


### GetPriceEur

`func (o *ApiResponseSubscriptionOverviewData) GetPriceEur() float64`

GetPriceEur returns the PriceEur field if non-nil, zero value otherwise.

### GetPriceEurOk

`func (o *ApiResponseSubscriptionOverviewData) GetPriceEurOk() (*float64, bool)`

GetPriceEurOk returns a tuple with the PriceEur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceEur

`func (o *ApiResponseSubscriptionOverviewData) SetPriceEur(v float64)`

SetPriceEur sets PriceEur field to given value.


### GetQuantity

`func (o *ApiResponseSubscriptionOverviewData) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ApiResponseSubscriptionOverviewData) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ApiResponseSubscriptionOverviewData) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *ApiResponseSubscriptionOverviewData) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### SetQuantityNil

`func (o *ApiResponseSubscriptionOverviewData) SetQuantityNil(b bool)`

 SetQuantityNil sets the value for Quantity to be an explicit nil

### UnsetQuantity
`func (o *ApiResponseSubscriptionOverviewData) UnsetQuantity()`

UnsetQuantity ensures that no value is present for Quantity, not even an explicit nil
### GetStatus

`func (o *ApiResponseSubscriptionOverviewData) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ApiResponseSubscriptionOverviewData) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ApiResponseSubscriptionOverviewData) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ApiResponseSubscriptionOverviewData) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *ApiResponseSubscriptionOverviewData) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ApiResponseSubscriptionOverviewData) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSubscriptionId

`func (o *ApiResponseSubscriptionOverviewData) GetSubscriptionId() string`

GetSubscriptionId returns the SubscriptionId field if non-nil, zero value otherwise.

### GetSubscriptionIdOk

`func (o *ApiResponseSubscriptionOverviewData) GetSubscriptionIdOk() (*string, bool)`

GetSubscriptionIdOk returns a tuple with the SubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionId

`func (o *ApiResponseSubscriptionOverviewData) SetSubscriptionId(v string)`

SetSubscriptionId sets SubscriptionId field to given value.

### HasSubscriptionId

`func (o *ApiResponseSubscriptionOverviewData) HasSubscriptionId() bool`

HasSubscriptionId returns a boolean if a field has been set.

### SetSubscriptionIdNil

`func (o *ApiResponseSubscriptionOverviewData) SetSubscriptionIdNil(b bool)`

 SetSubscriptionIdNil sets the value for SubscriptionId to be an explicit nil

### UnsetSubscriptionId
`func (o *ApiResponseSubscriptionOverviewData) UnsetSubscriptionId()`

UnsetSubscriptionId ensures that no value is present for SubscriptionId, not even an explicit nil
### GetTrialEndsAt

`func (o *ApiResponseSubscriptionOverviewData) GetTrialEndsAt() time.Time`

GetTrialEndsAt returns the TrialEndsAt field if non-nil, zero value otherwise.

### GetTrialEndsAtOk

`func (o *ApiResponseSubscriptionOverviewData) GetTrialEndsAtOk() (*time.Time, bool)`

GetTrialEndsAtOk returns a tuple with the TrialEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialEndsAt

`func (o *ApiResponseSubscriptionOverviewData) SetTrialEndsAt(v time.Time)`

SetTrialEndsAt sets TrialEndsAt field to given value.

### HasTrialEndsAt

`func (o *ApiResponseSubscriptionOverviewData) HasTrialEndsAt() bool`

HasTrialEndsAt returns a boolean if a field has been set.

### SetTrialEndsAtNil

`func (o *ApiResponseSubscriptionOverviewData) SetTrialEndsAtNil(b bool)`

 SetTrialEndsAtNil sets the value for TrialEndsAt to be an explicit nil

### UnsetTrialEndsAt
`func (o *ApiResponseSubscriptionOverviewData) UnsetTrialEndsAt()`

UnsetTrialEndsAt ensures that no value is present for TrialEndsAt, not even an explicit nil
### GetUsage

`func (o *ApiResponseSubscriptionOverviewData) GetUsage() UsageSnapshot`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *ApiResponseSubscriptionOverviewData) GetUsageOk() (*UsageSnapshot, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *ApiResponseSubscriptionOverviewData) SetUsage(v UsageSnapshot)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


