# StilleReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Jahresueberschuss** | **string** |  | 
**Partners** | [**[]StillePartnerZeile**](StillePartnerZeile.md) |  | 
**Year** | **int32** |  | 

## Methods

### NewStilleReport

`func NewStilleReport(jahresueberschuss string, partners []StillePartnerZeile, year int32, ) *StilleReport`

NewStilleReport instantiates a new StilleReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStilleReportWithDefaults

`func NewStilleReportWithDefaults() *StilleReport`

NewStilleReportWithDefaults instantiates a new StilleReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJahresueberschuss

`func (o *StilleReport) GetJahresueberschuss() string`

GetJahresueberschuss returns the Jahresueberschuss field if non-nil, zero value otherwise.

### GetJahresueberschussOk

`func (o *StilleReport) GetJahresueberschussOk() (*string, bool)`

GetJahresueberschussOk returns a tuple with the Jahresueberschuss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahresueberschuss

`func (o *StilleReport) SetJahresueberschuss(v string)`

SetJahresueberschuss sets Jahresueberschuss field to given value.


### GetPartners

`func (o *StilleReport) GetPartners() []StillePartnerZeile`

GetPartners returns the Partners field if non-nil, zero value otherwise.

### GetPartnersOk

`func (o *StilleReport) GetPartnersOk() (*[]StillePartnerZeile, bool)`

GetPartnersOk returns a tuple with the Partners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartners

`func (o *StilleReport) SetPartners(v []StillePartnerZeile)`

SetPartners sets Partners field to given value.


### GetYear

`func (o *StilleReport) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *StilleReport) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *StilleReport) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


