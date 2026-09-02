# MethodSuitability

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | **string** |  | 
**Rate** | Pointer to [**NullableShippingRate**](ShippingRate.md) |  | [optional] 
**Reasons** | **[]string** |  | 
**Service** | **string** |  | 
**Suitable** | **bool** |  | 

## Methods

### NewMethodSuitability

`func NewMethodSuitability(carrier string, reasons []string, service string, suitable bool, ) *MethodSuitability`

NewMethodSuitability instantiates a new MethodSuitability object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMethodSuitabilityWithDefaults

`func NewMethodSuitabilityWithDefaults() *MethodSuitability`

NewMethodSuitabilityWithDefaults instantiates a new MethodSuitability object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *MethodSuitability) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *MethodSuitability) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *MethodSuitability) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.


### GetRate

`func (o *MethodSuitability) GetRate() ShippingRate`

GetRate returns the Rate field if non-nil, zero value otherwise.

### GetRateOk

`func (o *MethodSuitability) GetRateOk() (*ShippingRate, bool)`

GetRateOk returns a tuple with the Rate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRate

`func (o *MethodSuitability) SetRate(v ShippingRate)`

SetRate sets Rate field to given value.

### HasRate

`func (o *MethodSuitability) HasRate() bool`

HasRate returns a boolean if a field has been set.

### SetRateNil

`func (o *MethodSuitability) SetRateNil(b bool)`

 SetRateNil sets the value for Rate to be an explicit nil

### UnsetRate
`func (o *MethodSuitability) UnsetRate()`

UnsetRate ensures that no value is present for Rate, not even an explicit nil
### GetReasons

`func (o *MethodSuitability) GetReasons() []string`

GetReasons returns the Reasons field if non-nil, zero value otherwise.

### GetReasonsOk

`func (o *MethodSuitability) GetReasonsOk() (*[]string, bool)`

GetReasonsOk returns a tuple with the Reasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasons

`func (o *MethodSuitability) SetReasons(v []string)`

SetReasons sets Reasons field to given value.


### GetService

`func (o *MethodSuitability) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *MethodSuitability) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *MethodSuitability) SetService(v string)`

SetService sets Service field to given value.


### GetSuitable

`func (o *MethodSuitability) GetSuitable() bool`

GetSuitable returns the Suitable field if non-nil, zero value otherwise.

### GetSuitableOk

`func (o *MethodSuitability) GetSuitableOk() (*bool, bool)`

GetSuitableOk returns a tuple with the Suitable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuitable

`func (o *MethodSuitability) SetSuitable(v bool)`

SetSuitable sets Suitable field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


