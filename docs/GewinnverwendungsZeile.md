# GewinnverwendungsZeile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Betrag** | **string** | Betrag in EUR (2 Nachkommastellen, als String formatiert). | 
**Label** | **string** | Deutsche Bezeichnung der Zeile. | 

## Methods

### NewGewinnverwendungsZeile

`func NewGewinnverwendungsZeile(betrag string, label string, ) *GewinnverwendungsZeile`

NewGewinnverwendungsZeile instantiates a new GewinnverwendungsZeile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGewinnverwendungsZeileWithDefaults

`func NewGewinnverwendungsZeileWithDefaults() *GewinnverwendungsZeile`

NewGewinnverwendungsZeileWithDefaults instantiates a new GewinnverwendungsZeile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBetrag

`func (o *GewinnverwendungsZeile) GetBetrag() string`

GetBetrag returns the Betrag field if non-nil, zero value otherwise.

### GetBetragOk

`func (o *GewinnverwendungsZeile) GetBetragOk() (*string, bool)`

GetBetragOk returns a tuple with the Betrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBetrag

`func (o *GewinnverwendungsZeile) SetBetrag(v string)`

SetBetrag sets Betrag field to given value.


### GetLabel

`func (o *GewinnverwendungsZeile) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *GewinnverwendungsZeile) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *GewinnverwendungsZeile) SetLabel(v string)`

SetLabel sets Label field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


