# KontoReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  | 
**Konten** | [**[]KontoItem**](KontoItem.md) |  | 
**Period** | **string** |  | 

## Methods

### NewKontoReport

`func NewKontoReport(generatedAt string, konten []KontoItem, period string, ) *KontoReport`

NewKontoReport instantiates a new KontoReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKontoReportWithDefaults

`func NewKontoReportWithDefaults() *KontoReport`

NewKontoReportWithDefaults instantiates a new KontoReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGeneratedAt

`func (o *KontoReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *KontoReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *KontoReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetKonten

`func (o *KontoReport) GetKonten() []KontoItem`

GetKonten returns the Konten field if non-nil, zero value otherwise.

### GetKontenOk

`func (o *KontoReport) GetKontenOk() (*[]KontoItem, bool)`

GetKontenOk returns a tuple with the Konten field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKonten

`func (o *KontoReport) SetKonten(v []KontoItem)`

SetKonten sets Konten field to given value.


### GetPeriod

`func (o *KontoReport) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *KontoReport) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *KontoReport) SetPeriod(v string)`

SetPeriod sets Period field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


