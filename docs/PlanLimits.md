# PlanLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MaxConnectors** | **int32** |  | 
**MaxInvoicesPerMonth** | **int64** |  | 
**MaxUsers** | **int32** |  | 
**Metered** | Pointer to **map[string]int64** |  | [optional] 
**PaidConnectors** | **[]string** | Connectors that are *not* included in this plan (require a higher tier). Empty &#x3D; all connectors included on this plan. | 

## Methods

### NewPlanLimits

`func NewPlanLimits(maxConnectors int32, maxInvoicesPerMonth int64, maxUsers int32, paidConnectors []string, ) *PlanLimits`

NewPlanLimits instantiates a new PlanLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlanLimitsWithDefaults

`func NewPlanLimitsWithDefaults() *PlanLimits`

NewPlanLimitsWithDefaults instantiates a new PlanLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaxConnectors

`func (o *PlanLimits) GetMaxConnectors() int32`

GetMaxConnectors returns the MaxConnectors field if non-nil, zero value otherwise.

### GetMaxConnectorsOk

`func (o *PlanLimits) GetMaxConnectorsOk() (*int32, bool)`

GetMaxConnectorsOk returns a tuple with the MaxConnectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxConnectors

`func (o *PlanLimits) SetMaxConnectors(v int32)`

SetMaxConnectors sets MaxConnectors field to given value.


### GetMaxInvoicesPerMonth

`func (o *PlanLimits) GetMaxInvoicesPerMonth() int64`

GetMaxInvoicesPerMonth returns the MaxInvoicesPerMonth field if non-nil, zero value otherwise.

### GetMaxInvoicesPerMonthOk

`func (o *PlanLimits) GetMaxInvoicesPerMonthOk() (*int64, bool)`

GetMaxInvoicesPerMonthOk returns a tuple with the MaxInvoicesPerMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxInvoicesPerMonth

`func (o *PlanLimits) SetMaxInvoicesPerMonth(v int64)`

SetMaxInvoicesPerMonth sets MaxInvoicesPerMonth field to given value.


### GetMaxUsers

`func (o *PlanLimits) GetMaxUsers() int32`

GetMaxUsers returns the MaxUsers field if non-nil, zero value otherwise.

### GetMaxUsersOk

`func (o *PlanLimits) GetMaxUsersOk() (*int32, bool)`

GetMaxUsersOk returns a tuple with the MaxUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxUsers

`func (o *PlanLimits) SetMaxUsers(v int32)`

SetMaxUsers sets MaxUsers field to given value.


### GetMetered

`func (o *PlanLimits) GetMetered() map[string]int64`

GetMetered returns the Metered field if non-nil, zero value otherwise.

### GetMeteredOk

`func (o *PlanLimits) GetMeteredOk() (*map[string]int64, bool)`

GetMeteredOk returns a tuple with the Metered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetered

`func (o *PlanLimits) SetMetered(v map[string]int64)`

SetMetered sets Metered field to given value.

### HasMetered

`func (o *PlanLimits) HasMetered() bool`

HasMetered returns a boolean if a field has been set.

### GetPaidConnectors

`func (o *PlanLimits) GetPaidConnectors() []string`

GetPaidConnectors returns the PaidConnectors field if non-nil, zero value otherwise.

### GetPaidConnectorsOk

`func (o *PlanLimits) GetPaidConnectorsOk() (*[]string, bool)`

GetPaidConnectorsOk returns a tuple with the PaidConnectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidConnectors

`func (o *PlanLimits) SetPaidConnectors(v []string)`

SetPaidConnectors sets PaidConnectors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


