# CreateShipmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | **string** | Carrier name as configured in shipping settings: &#x60;ups&#x60; or &#x60;dhl&#x60;. | 
**Service** | Pointer to **NullableString** |  | [optional] 
**WeightKg** | Pointer to **NullableFloat64** |  | [optional] 

## Methods

### NewCreateShipmentRequest

`func NewCreateShipmentRequest(carrier string, ) *CreateShipmentRequest`

NewCreateShipmentRequest instantiates a new CreateShipmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestWithDefaults

`func NewCreateShipmentRequestWithDefaults() *CreateShipmentRequest`

NewCreateShipmentRequestWithDefaults instantiates a new CreateShipmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *CreateShipmentRequest) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *CreateShipmentRequest) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *CreateShipmentRequest) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.


### GetService

`func (o *CreateShipmentRequest) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *CreateShipmentRequest) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *CreateShipmentRequest) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *CreateShipmentRequest) HasService() bool`

HasService returns a boolean if a field has been set.

### SetServiceNil

`func (o *CreateShipmentRequest) SetServiceNil(b bool)`

 SetServiceNil sets the value for Service to be an explicit nil

### UnsetService
`func (o *CreateShipmentRequest) UnsetService()`

UnsetService ensures that no value is present for Service, not even an explicit nil
### GetWeightKg

`func (o *CreateShipmentRequest) GetWeightKg() float64`

GetWeightKg returns the WeightKg field if non-nil, zero value otherwise.

### GetWeightKgOk

`func (o *CreateShipmentRequest) GetWeightKgOk() (*float64, bool)`

GetWeightKgOk returns a tuple with the WeightKg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightKg

`func (o *CreateShipmentRequest) SetWeightKg(v float64)`

SetWeightKg sets WeightKg field to given value.

### HasWeightKg

`func (o *CreateShipmentRequest) HasWeightKg() bool`

HasWeightKg returns a boolean if a field has been set.

### SetWeightKgNil

`func (o *CreateShipmentRequest) SetWeightKgNil(b bool)`

 SetWeightKgNil sets the value for WeightKg to be an explicit nil

### UnsetWeightKg
`func (o *CreateShipmentRequest) UnsetWeightKg()`

UnsetWeightKg ensures that no value is present for WeightKg, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


