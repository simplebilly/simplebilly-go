# VatSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InputTaxItems** | [**[]VatItem**](VatItem.md) |  | 
**OutputTaxItems** | [**[]VatItem**](VatItem.md) |  | 
**TotalInputTax** | **string** |  | 
**TotalOutputTax** | **string** |  | 
**VatDue** | **string** |  | 

## Methods

### NewVatSummary

`func NewVatSummary(inputTaxItems []VatItem, outputTaxItems []VatItem, totalInputTax string, totalOutputTax string, vatDue string, ) *VatSummary`

NewVatSummary instantiates a new VatSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVatSummaryWithDefaults

`func NewVatSummaryWithDefaults() *VatSummary`

NewVatSummaryWithDefaults instantiates a new VatSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInputTaxItems

`func (o *VatSummary) GetInputTaxItems() []VatItem`

GetInputTaxItems returns the InputTaxItems field if non-nil, zero value otherwise.

### GetInputTaxItemsOk

`func (o *VatSummary) GetInputTaxItemsOk() (*[]VatItem, bool)`

GetInputTaxItemsOk returns a tuple with the InputTaxItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputTaxItems

`func (o *VatSummary) SetInputTaxItems(v []VatItem)`

SetInputTaxItems sets InputTaxItems field to given value.


### GetOutputTaxItems

`func (o *VatSummary) GetOutputTaxItems() []VatItem`

GetOutputTaxItems returns the OutputTaxItems field if non-nil, zero value otherwise.

### GetOutputTaxItemsOk

`func (o *VatSummary) GetOutputTaxItemsOk() (*[]VatItem, bool)`

GetOutputTaxItemsOk returns a tuple with the OutputTaxItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputTaxItems

`func (o *VatSummary) SetOutputTaxItems(v []VatItem)`

SetOutputTaxItems sets OutputTaxItems field to given value.


### GetTotalInputTax

`func (o *VatSummary) GetTotalInputTax() string`

GetTotalInputTax returns the TotalInputTax field if non-nil, zero value otherwise.

### GetTotalInputTaxOk

`func (o *VatSummary) GetTotalInputTaxOk() (*string, bool)`

GetTotalInputTaxOk returns a tuple with the TotalInputTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalInputTax

`func (o *VatSummary) SetTotalInputTax(v string)`

SetTotalInputTax sets TotalInputTax field to given value.


### GetTotalOutputTax

`func (o *VatSummary) GetTotalOutputTax() string`

GetTotalOutputTax returns the TotalOutputTax field if non-nil, zero value otherwise.

### GetTotalOutputTaxOk

`func (o *VatSummary) GetTotalOutputTaxOk() (*string, bool)`

GetTotalOutputTaxOk returns a tuple with the TotalOutputTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalOutputTax

`func (o *VatSummary) SetTotalOutputTax(v string)`

SetTotalOutputTax sets TotalOutputTax field to given value.


### GetVatDue

`func (o *VatSummary) GetVatDue() string`

GetVatDue returns the VatDue field if non-nil, zero value otherwise.

### GetVatDueOk

`func (o *VatSummary) GetVatDueOk() (*string, bool)`

GetVatDueOk returns a tuple with the VatDue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatDue

`func (o *VatSummary) SetVatDue(v string)`

SetVatDue sets VatDue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


