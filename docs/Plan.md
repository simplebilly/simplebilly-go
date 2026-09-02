# Plan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Features** | [**PlanFeatures**](PlanFeatures.md) |  | 
**Id** | **string** |  | 
**Limits** | [**PlanLimits**](PlanLimits.md) |  | 
**Name** | **string** |  | 
**PriceEur** | **float64** |  | 

## Methods

### NewPlan

`func NewPlan(features PlanFeatures, id string, limits PlanLimits, name string, priceEur float64, ) *Plan`

NewPlan instantiates a new Plan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlanWithDefaults

`func NewPlanWithDefaults() *Plan`

NewPlanWithDefaults instantiates a new Plan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatures

`func (o *Plan) GetFeatures() PlanFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *Plan) GetFeaturesOk() (*PlanFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *Plan) SetFeatures(v PlanFeatures)`

SetFeatures sets Features field to given value.


### GetId

`func (o *Plan) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Plan) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Plan) SetId(v string)`

SetId sets Id field to given value.


### GetLimits

`func (o *Plan) GetLimits() PlanLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *Plan) GetLimitsOk() (*PlanLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *Plan) SetLimits(v PlanLimits)`

SetLimits sets Limits field to given value.


### GetName

`func (o *Plan) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Plan) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Plan) SetName(v string)`

SetName sets Name field to given value.


### GetPriceEur

`func (o *Plan) GetPriceEur() float64`

GetPriceEur returns the PriceEur field if non-nil, zero value otherwise.

### GetPriceEurOk

`func (o *Plan) GetPriceEurOk() (*float64, bool)`

GetPriceEurOk returns a tuple with the PriceEur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceEur

`func (o *Plan) SetPriceEur(v float64)`

SetPriceEur sets PriceEur field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


