# AnlageGErgebnis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GewinnVerlust** | **string** |  | 
**GewstGezahlt** | **string** |  | 
**GewstMessbetragApprox** | **string** |  | 
**GewstPflichtig** | **bool** |  | 
**Jahr** | **int32** |  | 
**KfzHinweise** | [**[]AnlageGKfzHinweis**](AnlageGKfzHinweis.md) |  | 

## Methods

### NewAnlageGErgebnis

`func NewAnlageGErgebnis(gewinnVerlust string, gewstGezahlt string, gewstMessbetragApprox string, gewstPflichtig bool, jahr int32, kfzHinweise []AnlageGKfzHinweis, ) *AnlageGErgebnis`

NewAnlageGErgebnis instantiates a new AnlageGErgebnis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnlageGErgebnisWithDefaults

`func NewAnlageGErgebnisWithDefaults() *AnlageGErgebnis`

NewAnlageGErgebnisWithDefaults instantiates a new AnlageGErgebnis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGewinnVerlust

`func (o *AnlageGErgebnis) GetGewinnVerlust() string`

GetGewinnVerlust returns the GewinnVerlust field if non-nil, zero value otherwise.

### GetGewinnVerlustOk

`func (o *AnlageGErgebnis) GetGewinnVerlustOk() (*string, bool)`

GetGewinnVerlustOk returns a tuple with the GewinnVerlust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewinnVerlust

`func (o *AnlageGErgebnis) SetGewinnVerlust(v string)`

SetGewinnVerlust sets GewinnVerlust field to given value.


### GetGewstGezahlt

`func (o *AnlageGErgebnis) GetGewstGezahlt() string`

GetGewstGezahlt returns the GewstGezahlt field if non-nil, zero value otherwise.

### GetGewstGezahltOk

`func (o *AnlageGErgebnis) GetGewstGezahltOk() (*string, bool)`

GetGewstGezahltOk returns a tuple with the GewstGezahlt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewstGezahlt

`func (o *AnlageGErgebnis) SetGewstGezahlt(v string)`

SetGewstGezahlt sets GewstGezahlt field to given value.


### GetGewstMessbetragApprox

`func (o *AnlageGErgebnis) GetGewstMessbetragApprox() string`

GetGewstMessbetragApprox returns the GewstMessbetragApprox field if non-nil, zero value otherwise.

### GetGewstMessbetragApproxOk

`func (o *AnlageGErgebnis) GetGewstMessbetragApproxOk() (*string, bool)`

GetGewstMessbetragApproxOk returns a tuple with the GewstMessbetragApprox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewstMessbetragApprox

`func (o *AnlageGErgebnis) SetGewstMessbetragApprox(v string)`

SetGewstMessbetragApprox sets GewstMessbetragApprox field to given value.


### GetGewstPflichtig

`func (o *AnlageGErgebnis) GetGewstPflichtig() bool`

GetGewstPflichtig returns the GewstPflichtig field if non-nil, zero value otherwise.

### GetGewstPflichtigOk

`func (o *AnlageGErgebnis) GetGewstPflichtigOk() (*bool, bool)`

GetGewstPflichtigOk returns a tuple with the GewstPflichtig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGewstPflichtig

`func (o *AnlageGErgebnis) SetGewstPflichtig(v bool)`

SetGewstPflichtig sets GewstPflichtig field to given value.


### GetJahr

`func (o *AnlageGErgebnis) GetJahr() int32`

GetJahr returns the Jahr field if non-nil, zero value otherwise.

### GetJahrOk

`func (o *AnlageGErgebnis) GetJahrOk() (*int32, bool)`

GetJahrOk returns a tuple with the Jahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahr

`func (o *AnlageGErgebnis) SetJahr(v int32)`

SetJahr sets Jahr field to given value.


### GetKfzHinweise

`func (o *AnlageGErgebnis) GetKfzHinweise() []AnlageGKfzHinweis`

GetKfzHinweise returns the KfzHinweise field if non-nil, zero value otherwise.

### GetKfzHinweiseOk

`func (o *AnlageGErgebnis) GetKfzHinweiseOk() (*[]AnlageGKfzHinweis, bool)`

GetKfzHinweiseOk returns a tuple with the KfzHinweise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKfzHinweise

`func (o *AnlageGErgebnis) SetKfzHinweise(v []AnlageGKfzHinweis)`

SetKfzHinweise sets KfzHinweise field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


