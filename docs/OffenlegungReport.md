# OffenlegungReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deadline** | **string** | Fristende (Abschlussstichtag + Frist). | 
**DeadlineMonths** | **int32** | Offenlegungsfrist in Monaten (§ 325 Abs. 4 HGB). | 
**Items** | [**[]OffenlegungItem**](OffenlegungItem.md) |  | 
**Kapitalmarktorientiert** | **bool** | Annahme über die Kapitalmarktorientierung. | 
**Note** | **string** |  | 
**Year** | **int32** | Berichtsjahr (laufendes Kalenderjahr). | 

## Methods

### NewOffenlegungReport

`func NewOffenlegungReport(deadline string, deadlineMonths int32, items []OffenlegungItem, kapitalmarktorientiert bool, note string, year int32, ) *OffenlegungReport`

NewOffenlegungReport instantiates a new OffenlegungReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOffenlegungReportWithDefaults

`func NewOffenlegungReportWithDefaults() *OffenlegungReport`

NewOffenlegungReportWithDefaults instantiates a new OffenlegungReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeadline

`func (o *OffenlegungReport) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *OffenlegungReport) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *OffenlegungReport) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.


### GetDeadlineMonths

`func (o *OffenlegungReport) GetDeadlineMonths() int32`

GetDeadlineMonths returns the DeadlineMonths field if non-nil, zero value otherwise.

### GetDeadlineMonthsOk

`func (o *OffenlegungReport) GetDeadlineMonthsOk() (*int32, bool)`

GetDeadlineMonthsOk returns a tuple with the DeadlineMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadlineMonths

`func (o *OffenlegungReport) SetDeadlineMonths(v int32)`

SetDeadlineMonths sets DeadlineMonths field to given value.


### GetItems

`func (o *OffenlegungReport) GetItems() []OffenlegungItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *OffenlegungReport) GetItemsOk() (*[]OffenlegungItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *OffenlegungReport) SetItems(v []OffenlegungItem)`

SetItems sets Items field to given value.


### GetKapitalmarktorientiert

`func (o *OffenlegungReport) GetKapitalmarktorientiert() bool`

GetKapitalmarktorientiert returns the Kapitalmarktorientiert field if non-nil, zero value otherwise.

### GetKapitalmarktorientiertOk

`func (o *OffenlegungReport) GetKapitalmarktorientiertOk() (*bool, bool)`

GetKapitalmarktorientiertOk returns a tuple with the Kapitalmarktorientiert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKapitalmarktorientiert

`func (o *OffenlegungReport) SetKapitalmarktorientiert(v bool)`

SetKapitalmarktorientiert sets Kapitalmarktorientiert field to given value.


### GetNote

`func (o *OffenlegungReport) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *OffenlegungReport) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *OffenlegungReport) SetNote(v string)`

SetNote sets Note field to given value.


### GetYear

`func (o *OffenlegungReport) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *OffenlegungReport) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *OffenlegungReport) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


