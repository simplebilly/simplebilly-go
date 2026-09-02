# SalesVolumeReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GrandTotal** | **string** |  | 
**Items** | [**[]SalesVolumeItem**](SalesVolumeItem.md) |  | 
**TotalCount** | **int64** |  | 

## Methods

### NewSalesVolumeReport

`func NewSalesVolumeReport(grandTotal string, items []SalesVolumeItem, totalCount int64, ) *SalesVolumeReport`

NewSalesVolumeReport instantiates a new SalesVolumeReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesVolumeReportWithDefaults

`func NewSalesVolumeReportWithDefaults() *SalesVolumeReport`

NewSalesVolumeReportWithDefaults instantiates a new SalesVolumeReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGrandTotal

`func (o *SalesVolumeReport) GetGrandTotal() string`

GetGrandTotal returns the GrandTotal field if non-nil, zero value otherwise.

### GetGrandTotalOk

`func (o *SalesVolumeReport) GetGrandTotalOk() (*string, bool)`

GetGrandTotalOk returns a tuple with the GrandTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrandTotal

`func (o *SalesVolumeReport) SetGrandTotal(v string)`

SetGrandTotal sets GrandTotal field to given value.


### GetItems

`func (o *SalesVolumeReport) GetItems() []SalesVolumeItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SalesVolumeReport) GetItemsOk() (*[]SalesVolumeItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SalesVolumeReport) SetItems(v []SalesVolumeItem)`

SetItems sets Items field to given value.


### GetTotalCount

`func (o *SalesVolumeReport) GetTotalCount() int64`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *SalesVolumeReport) GetTotalCountOk() (*int64, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *SalesVolumeReport) SetTotalCount(v int64)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


