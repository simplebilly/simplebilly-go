# SuitabilityResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Methods** | [**[]MethodSuitability**](MethodSuitability.md) |  | 
**RecommendedBox** | Pointer to [**NullableBoxFit**](BoxFit.md) |  | [optional] 
**RequiresInsurance** | **bool** |  | 
**TotalValue** | **string** |  | 
**TotalWeightKg** | **float64** |  | 

## Methods

### NewSuitabilityResult

`func NewSuitabilityResult(methods []MethodSuitability, requiresInsurance bool, totalValue string, totalWeightKg float64, ) *SuitabilityResult`

NewSuitabilityResult instantiates a new SuitabilityResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuitabilityResultWithDefaults

`func NewSuitabilityResultWithDefaults() *SuitabilityResult`

NewSuitabilityResultWithDefaults instantiates a new SuitabilityResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMethods

`func (o *SuitabilityResult) GetMethods() []MethodSuitability`

GetMethods returns the Methods field if non-nil, zero value otherwise.

### GetMethodsOk

`func (o *SuitabilityResult) GetMethodsOk() (*[]MethodSuitability, bool)`

GetMethodsOk returns a tuple with the Methods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethods

`func (o *SuitabilityResult) SetMethods(v []MethodSuitability)`

SetMethods sets Methods field to given value.


### GetRecommendedBox

`func (o *SuitabilityResult) GetRecommendedBox() BoxFit`

GetRecommendedBox returns the RecommendedBox field if non-nil, zero value otherwise.

### GetRecommendedBoxOk

`func (o *SuitabilityResult) GetRecommendedBoxOk() (*BoxFit, bool)`

GetRecommendedBoxOk returns a tuple with the RecommendedBox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedBox

`func (o *SuitabilityResult) SetRecommendedBox(v BoxFit)`

SetRecommendedBox sets RecommendedBox field to given value.

### HasRecommendedBox

`func (o *SuitabilityResult) HasRecommendedBox() bool`

HasRecommendedBox returns a boolean if a field has been set.

### SetRecommendedBoxNil

`func (o *SuitabilityResult) SetRecommendedBoxNil(b bool)`

 SetRecommendedBoxNil sets the value for RecommendedBox to be an explicit nil

### UnsetRecommendedBox
`func (o *SuitabilityResult) UnsetRecommendedBox()`

UnsetRecommendedBox ensures that no value is present for RecommendedBox, not even an explicit nil
### GetRequiresInsurance

`func (o *SuitabilityResult) GetRequiresInsurance() bool`

GetRequiresInsurance returns the RequiresInsurance field if non-nil, zero value otherwise.

### GetRequiresInsuranceOk

`func (o *SuitabilityResult) GetRequiresInsuranceOk() (*bool, bool)`

GetRequiresInsuranceOk returns a tuple with the RequiresInsurance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresInsurance

`func (o *SuitabilityResult) SetRequiresInsurance(v bool)`

SetRequiresInsurance sets RequiresInsurance field to given value.


### GetTotalValue

`func (o *SuitabilityResult) GetTotalValue() string`

GetTotalValue returns the TotalValue field if non-nil, zero value otherwise.

### GetTotalValueOk

`func (o *SuitabilityResult) GetTotalValueOk() (*string, bool)`

GetTotalValueOk returns a tuple with the TotalValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalValue

`func (o *SuitabilityResult) SetTotalValue(v string)`

SetTotalValue sets TotalValue field to given value.


### GetTotalWeightKg

`func (o *SuitabilityResult) GetTotalWeightKg() float64`

GetTotalWeightKg returns the TotalWeightKg field if non-nil, zero value otherwise.

### GetTotalWeightKgOk

`func (o *SuitabilityResult) GetTotalWeightKgOk() (*float64, bool)`

GetTotalWeightKgOk returns a tuple with the TotalWeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalWeightKg

`func (o *SuitabilityResult) SetTotalWeightKg(v float64)`

SetTotalWeightKg sets TotalWeightKg field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


