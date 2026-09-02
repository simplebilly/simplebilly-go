# ApiResponseVecPlanDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Features** | [**PlanFeatures**](PlanFeatures.md) |  | 
**Id** | **string** |  | 
**Limits** | [**PlanLimits**](PlanLimits.md) |  | 
**Name** | **string** |  | 
**PriceEur** | **float64** |  | 

## Methods

### NewApiResponseVecPlanDataInner

`func NewApiResponseVecPlanDataInner(features PlanFeatures, id string, limits PlanLimits, name string, priceEur float64, ) *ApiResponseVecPlanDataInner`

NewApiResponseVecPlanDataInner instantiates a new ApiResponseVecPlanDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseVecPlanDataInnerWithDefaults

`func NewApiResponseVecPlanDataInnerWithDefaults() *ApiResponseVecPlanDataInner`

NewApiResponseVecPlanDataInnerWithDefaults instantiates a new ApiResponseVecPlanDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatures

`func (o *ApiResponseVecPlanDataInner) GetFeatures() PlanFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *ApiResponseVecPlanDataInner) GetFeaturesOk() (*PlanFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *ApiResponseVecPlanDataInner) SetFeatures(v PlanFeatures)`

SetFeatures sets Features field to given value.


### GetId

`func (o *ApiResponseVecPlanDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApiResponseVecPlanDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApiResponseVecPlanDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetLimits

`func (o *ApiResponseVecPlanDataInner) GetLimits() PlanLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *ApiResponseVecPlanDataInner) GetLimitsOk() (*PlanLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *ApiResponseVecPlanDataInner) SetLimits(v PlanLimits)`

SetLimits sets Limits field to given value.


### GetName

`func (o *ApiResponseVecPlanDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiResponseVecPlanDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiResponseVecPlanDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetPriceEur

`func (o *ApiResponseVecPlanDataInner) GetPriceEur() float64`

GetPriceEur returns the PriceEur field if non-nil, zero value otherwise.

### GetPriceEurOk

`func (o *ApiResponseVecPlanDataInner) GetPriceEurOk() (*float64, bool)`

GetPriceEurOk returns a tuple with the PriceEur field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceEur

`func (o *ApiResponseVecPlanDataInner) SetPriceEur(v float64)`

SetPriceEur sets PriceEur field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


