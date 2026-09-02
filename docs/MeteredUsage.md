# MeteredUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | **int64** |  | 
**Meter** | **string** |  | 
**Used** | **int64** |  | 

## Methods

### NewMeteredUsage

`func NewMeteredUsage(limit int64, meter string, used int64, ) *MeteredUsage`

NewMeteredUsage instantiates a new MeteredUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeteredUsageWithDefaults

`func NewMeteredUsageWithDefaults() *MeteredUsage`

NewMeteredUsageWithDefaults instantiates a new MeteredUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *MeteredUsage) GetLimit() int64`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *MeteredUsage) GetLimitOk() (*int64, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *MeteredUsage) SetLimit(v int64)`

SetLimit sets Limit field to given value.


### GetMeter

`func (o *MeteredUsage) GetMeter() string`

GetMeter returns the Meter field if non-nil, zero value otherwise.

### GetMeterOk

`func (o *MeteredUsage) GetMeterOk() (*string, bool)`

GetMeterOk returns a tuple with the Meter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeter

`func (o *MeteredUsage) SetMeter(v string)`

SetMeter sets Meter field to given value.


### GetUsed

`func (o *MeteredUsage) GetUsed() int64`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *MeteredUsage) GetUsedOk() (*int64, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *MeteredUsage) SetUsed(v int64)`

SetUsed sets Used field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


