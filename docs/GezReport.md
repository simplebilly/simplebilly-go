# GezReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BeitragsfreieKfz** | **int64** |  | 
**BeitragspflichtigeKfz** | **int64** |  | 
**Betriebsstaetten** | [**[]BetriebsstaettenDetail**](BetriebsstaettenDetail.md) |  | 
**Hinweis** | **string** |  | 
**HotelzimmerBeitrag** | **string** |  | 
**JaehrlicherBeitrag** | **string** |  | 
**Jahr** | **int32** |  | 
**KfzBeitrag** | **string** |  | 
**MonatlicherBeitrag** | **string** |  | 
**VierteljaehrlicherBeitrag** | **string** |  | 

## Methods

### NewGezReport

`func NewGezReport(beitragsfreieKfz int64, beitragspflichtigeKfz int64, betriebsstaetten []BetriebsstaettenDetail, hinweis string, hotelzimmerBeitrag string, jaehrlicherBeitrag string, jahr int32, kfzBeitrag string, monatlicherBeitrag string, vierteljaehrlicherBeitrag string, ) *GezReport`

NewGezReport instantiates a new GezReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGezReportWithDefaults

`func NewGezReportWithDefaults() *GezReport`

NewGezReportWithDefaults instantiates a new GezReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBeitragsfreieKfz

`func (o *GezReport) GetBeitragsfreieKfz() int64`

GetBeitragsfreieKfz returns the BeitragsfreieKfz field if non-nil, zero value otherwise.

### GetBeitragsfreieKfzOk

`func (o *GezReport) GetBeitragsfreieKfzOk() (*int64, bool)`

GetBeitragsfreieKfzOk returns a tuple with the BeitragsfreieKfz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBeitragsfreieKfz

`func (o *GezReport) SetBeitragsfreieKfz(v int64)`

SetBeitragsfreieKfz sets BeitragsfreieKfz field to given value.


### GetBeitragspflichtigeKfz

`func (o *GezReport) GetBeitragspflichtigeKfz() int64`

GetBeitragspflichtigeKfz returns the BeitragspflichtigeKfz field if non-nil, zero value otherwise.

### GetBeitragspflichtigeKfzOk

`func (o *GezReport) GetBeitragspflichtigeKfzOk() (*int64, bool)`

GetBeitragspflichtigeKfzOk returns a tuple with the BeitragspflichtigeKfz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBeitragspflichtigeKfz

`func (o *GezReport) SetBeitragspflichtigeKfz(v int64)`

SetBeitragspflichtigeKfz sets BeitragspflichtigeKfz field to given value.


### GetBetriebsstaetten

`func (o *GezReport) GetBetriebsstaetten() []BetriebsstaettenDetail`

GetBetriebsstaetten returns the Betriebsstaetten field if non-nil, zero value otherwise.

### GetBetriebsstaettenOk

`func (o *GezReport) GetBetriebsstaettenOk() (*[]BetriebsstaettenDetail, bool)`

GetBetriebsstaettenOk returns a tuple with the Betriebsstaetten field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBetriebsstaetten

`func (o *GezReport) SetBetriebsstaetten(v []BetriebsstaettenDetail)`

SetBetriebsstaetten sets Betriebsstaetten field to given value.


### GetHinweis

`func (o *GezReport) GetHinweis() string`

GetHinweis returns the Hinweis field if non-nil, zero value otherwise.

### GetHinweisOk

`func (o *GezReport) GetHinweisOk() (*string, bool)`

GetHinweisOk returns a tuple with the Hinweis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHinweis

`func (o *GezReport) SetHinweis(v string)`

SetHinweis sets Hinweis field to given value.


### GetHotelzimmerBeitrag

`func (o *GezReport) GetHotelzimmerBeitrag() string`

GetHotelzimmerBeitrag returns the HotelzimmerBeitrag field if non-nil, zero value otherwise.

### GetHotelzimmerBeitragOk

`func (o *GezReport) GetHotelzimmerBeitragOk() (*string, bool)`

GetHotelzimmerBeitragOk returns a tuple with the HotelzimmerBeitrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHotelzimmerBeitrag

`func (o *GezReport) SetHotelzimmerBeitrag(v string)`

SetHotelzimmerBeitrag sets HotelzimmerBeitrag field to given value.


### GetJaehrlicherBeitrag

`func (o *GezReport) GetJaehrlicherBeitrag() string`

GetJaehrlicherBeitrag returns the JaehrlicherBeitrag field if non-nil, zero value otherwise.

### GetJaehrlicherBeitragOk

`func (o *GezReport) GetJaehrlicherBeitragOk() (*string, bool)`

GetJaehrlicherBeitragOk returns a tuple with the JaehrlicherBeitrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJaehrlicherBeitrag

`func (o *GezReport) SetJaehrlicherBeitrag(v string)`

SetJaehrlicherBeitrag sets JaehrlicherBeitrag field to given value.


### GetJahr

`func (o *GezReport) GetJahr() int32`

GetJahr returns the Jahr field if non-nil, zero value otherwise.

### GetJahrOk

`func (o *GezReport) GetJahrOk() (*int32, bool)`

GetJahrOk returns a tuple with the Jahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahr

`func (o *GezReport) SetJahr(v int32)`

SetJahr sets Jahr field to given value.


### GetKfzBeitrag

`func (o *GezReport) GetKfzBeitrag() string`

GetKfzBeitrag returns the KfzBeitrag field if non-nil, zero value otherwise.

### GetKfzBeitragOk

`func (o *GezReport) GetKfzBeitragOk() (*string, bool)`

GetKfzBeitragOk returns a tuple with the KfzBeitrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKfzBeitrag

`func (o *GezReport) SetKfzBeitrag(v string)`

SetKfzBeitrag sets KfzBeitrag field to given value.


### GetMonatlicherBeitrag

`func (o *GezReport) GetMonatlicherBeitrag() string`

GetMonatlicherBeitrag returns the MonatlicherBeitrag field if non-nil, zero value otherwise.

### GetMonatlicherBeitragOk

`func (o *GezReport) GetMonatlicherBeitragOk() (*string, bool)`

GetMonatlicherBeitragOk returns a tuple with the MonatlicherBeitrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonatlicherBeitrag

`func (o *GezReport) SetMonatlicherBeitrag(v string)`

SetMonatlicherBeitrag sets MonatlicherBeitrag field to given value.


### GetVierteljaehrlicherBeitrag

`func (o *GezReport) GetVierteljaehrlicherBeitrag() string`

GetVierteljaehrlicherBeitrag returns the VierteljaehrlicherBeitrag field if non-nil, zero value otherwise.

### GetVierteljaehrlicherBeitragOk

`func (o *GezReport) GetVierteljaehrlicherBeitragOk() (*string, bool)`

GetVierteljaehrlicherBeitragOk returns a tuple with the VierteljaehrlicherBeitrag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVierteljaehrlicherBeitrag

`func (o *GezReport) SetVierteljaehrlicherBeitrag(v string)`

SetVierteljaehrlicherBeitrag sets VierteljaehrlicherBeitrag field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


