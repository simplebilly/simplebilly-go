# EuerDetailErgebnis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Jahr** | **int32** |  | 
**Zeilen** | [**[]EuerZeileDetail**](EuerZeileDetail.md) |  | 

## Methods

### NewEuerDetailErgebnis

`func NewEuerDetailErgebnis(jahr int32, zeilen []EuerZeileDetail, ) *EuerDetailErgebnis`

NewEuerDetailErgebnis instantiates a new EuerDetailErgebnis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEuerDetailErgebnisWithDefaults

`func NewEuerDetailErgebnisWithDefaults() *EuerDetailErgebnis`

NewEuerDetailErgebnisWithDefaults instantiates a new EuerDetailErgebnis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJahr

`func (o *EuerDetailErgebnis) GetJahr() int32`

GetJahr returns the Jahr field if non-nil, zero value otherwise.

### GetJahrOk

`func (o *EuerDetailErgebnis) GetJahrOk() (*int32, bool)`

GetJahrOk returns a tuple with the Jahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahr

`func (o *EuerDetailErgebnis) SetJahr(v int32)`

SetJahr sets Jahr field to given value.


### GetZeilen

`func (o *EuerDetailErgebnis) GetZeilen() []EuerZeileDetail`

GetZeilen returns the Zeilen field if non-nil, zero value otherwise.

### GetZeilenOk

`func (o *EuerDetailErgebnis) GetZeilenOk() (*[]EuerZeileDetail, bool)`

GetZeilenOk returns a tuple with the Zeilen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZeilen

`func (o *EuerDetailErgebnis) SetZeilen(v []EuerZeileDetail)`

SetZeilen sets Zeilen field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


