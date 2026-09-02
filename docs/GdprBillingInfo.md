# GdprBillingInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPeriodEnd** | Pointer to **NullableTime** |  | [optional] 
**CurrentPeriodStart** | Pointer to **NullableTime** |  | [optional] 
**Plan** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to **NullableString** |  | [optional] 
**TenantId** | **string** |  | 

## Methods

### NewGdprBillingInfo

`func NewGdprBillingInfo(tenantId string, ) *GdprBillingInfo`

NewGdprBillingInfo instantiates a new GdprBillingInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGdprBillingInfoWithDefaults

`func NewGdprBillingInfoWithDefaults() *GdprBillingInfo`

NewGdprBillingInfoWithDefaults instantiates a new GdprBillingInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPeriodEnd

`func (o *GdprBillingInfo) GetCurrentPeriodEnd() time.Time`

GetCurrentPeriodEnd returns the CurrentPeriodEnd field if non-nil, zero value otherwise.

### GetCurrentPeriodEndOk

`func (o *GdprBillingInfo) GetCurrentPeriodEndOk() (*time.Time, bool)`

GetCurrentPeriodEndOk returns a tuple with the CurrentPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriodEnd

`func (o *GdprBillingInfo) SetCurrentPeriodEnd(v time.Time)`

SetCurrentPeriodEnd sets CurrentPeriodEnd field to given value.

### HasCurrentPeriodEnd

`func (o *GdprBillingInfo) HasCurrentPeriodEnd() bool`

HasCurrentPeriodEnd returns a boolean if a field has been set.

### SetCurrentPeriodEndNil

`func (o *GdprBillingInfo) SetCurrentPeriodEndNil(b bool)`

 SetCurrentPeriodEndNil sets the value for CurrentPeriodEnd to be an explicit nil

### UnsetCurrentPeriodEnd
`func (o *GdprBillingInfo) UnsetCurrentPeriodEnd()`

UnsetCurrentPeriodEnd ensures that no value is present for CurrentPeriodEnd, not even an explicit nil
### GetCurrentPeriodStart

`func (o *GdprBillingInfo) GetCurrentPeriodStart() time.Time`

GetCurrentPeriodStart returns the CurrentPeriodStart field if non-nil, zero value otherwise.

### GetCurrentPeriodStartOk

`func (o *GdprBillingInfo) GetCurrentPeriodStartOk() (*time.Time, bool)`

GetCurrentPeriodStartOk returns a tuple with the CurrentPeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriodStart

`func (o *GdprBillingInfo) SetCurrentPeriodStart(v time.Time)`

SetCurrentPeriodStart sets CurrentPeriodStart field to given value.

### HasCurrentPeriodStart

`func (o *GdprBillingInfo) HasCurrentPeriodStart() bool`

HasCurrentPeriodStart returns a boolean if a field has been set.

### SetCurrentPeriodStartNil

`func (o *GdprBillingInfo) SetCurrentPeriodStartNil(b bool)`

 SetCurrentPeriodStartNil sets the value for CurrentPeriodStart to be an explicit nil

### UnsetCurrentPeriodStart
`func (o *GdprBillingInfo) UnsetCurrentPeriodStart()`

UnsetCurrentPeriodStart ensures that no value is present for CurrentPeriodStart, not even an explicit nil
### GetPlan

`func (o *GdprBillingInfo) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *GdprBillingInfo) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *GdprBillingInfo) SetPlan(v string)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *GdprBillingInfo) HasPlan() bool`

HasPlan returns a boolean if a field has been set.

### SetPlanNil

`func (o *GdprBillingInfo) SetPlanNil(b bool)`

 SetPlanNil sets the value for Plan to be an explicit nil

### UnsetPlan
`func (o *GdprBillingInfo) UnsetPlan()`

UnsetPlan ensures that no value is present for Plan, not even an explicit nil
### GetStatus

`func (o *GdprBillingInfo) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GdprBillingInfo) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GdprBillingInfo) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GdprBillingInfo) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *GdprBillingInfo) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *GdprBillingInfo) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetTenantId

`func (o *GdprBillingInfo) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *GdprBillingInfo) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *GdprBillingInfo) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


