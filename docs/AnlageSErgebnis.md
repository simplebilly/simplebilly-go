# AnlageSErgebnis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GewinnVerlust** | **string** |  | 
**Jahr** | **int32** |  | 
**KfzHinweise** | [**[]AnlageSKfzHinweis**](AnlageSKfzHinweis.md) |  | 

## Methods

### NewAnlageSErgebnis

`func NewAnlageSErgebnis(gewinnVerlust string, jahr int32, kfzHinweise []AnlageSKfzHinweis, ) *AnlageSErgebnis`

NewAnlageSErgebnis instantiates a new AnlageSErgebnis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnlageSErgebnisWithDefaults

`func NewAnlageSErgebnisWithDefaults() *AnlageSErgebnis`

NewAnlageSErgebnisWithDefaults instantiates a new AnlageSErgebnis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGewinnVerlust

`func (o *AnlageSErgebnis) GetGewinnVerlust() string`

GetGewinnVerlust returns the GewinnVerlust field if non-nil, zero value otherwise.

### GetGewinnVerlustOk

`func (o *AnlageSErgebnis) GetGewinnVerlustOk() (*string, bool)`

GetGewinnVerlustOk returns a tuple with the GewinnVerlust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnVerlust

`func (o *AnlageSErgebnis) SetGewinnVerlust(v string)`

SetGewinnVerlust sets GewinnVerlust field to given value.


### GetJahr

`func (o *AnlageSErgebnis) GetJahr() int32`

GetJahr returns the Jahr field if non-nil, zero value otherwise.

### GetJahrOk

`func (o *AnlageSErgebnis) GetJahrOk() (*int32, bool)`

GetJahrOk returns a tuple with the Jahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahr

`func (o *AnlageSErgebnis) SetJahr(v int32)`

SetJahr sets Jahr field to given value.


### GetKfzHinweise

`func (o *AnlageSErgebnis) GetKfzHinweise() []AnlageSKfzHinweis`

GetKfzHinweise returns the KfzHinweise field if non-nil, zero value otherwise.

### GetKfzHinweiseOk

`func (o *AnlageSErgebnis) GetKfzHinweiseOk() (*[]AnlageSKfzHinweis, bool)`

GetKfzHinweiseOk returns a tuple with the KfzHinweise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKfzHinweise

`func (o *AnlageSErgebnis) SetKfzHinweise(v []AnlageSKfzHinweis)`

SetKfzHinweise sets KfzHinweise field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


