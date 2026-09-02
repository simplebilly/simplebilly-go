# RateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rates** | [**[]ShippingRate**](ShippingRate.md) |  | 

## Methods

### NewRateResponse

`func NewRateResponse(rates []ShippingRate, ) *RateResponse`

NewRateResponse instantiates a new RateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRateResponseWithDefaults

`func NewRateResponseWithDefaults() *RateResponse`

NewRateResponseWithDefaults instantiates a new RateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRates

`func (o *RateResponse) GetRates() []ShippingRate`

GetRates returns the Rates field if non-nil, zero value otherwise.

### GetRatesOk

`func (o *RateResponse) GetRatesOk() (*[]ShippingRate, bool)`

GetRatesOk returns a tuple with the Rates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRates

`func (o *RateResponse) SetRates(v []ShippingRate)`

SetRates sets Rates field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


