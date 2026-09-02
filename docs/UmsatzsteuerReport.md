# UmsatzsteuerReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  | 
**InputTax** | [**[]VatDetail**](VatDetail.md) |  | 
**OutputTax** | [**[]VatDetail**](VatDetail.md) |  | 
**Period** | **string** |  | 
**TotalInputTax** | **string** |  | 
**TotalOutputTax** | **string** |  | 
**VatPayable** | **string** |  | 
**VatRefund** | **string** |  | 

## Methods

### NewUmsatzsteuerReport

`func NewUmsatzsteuerReport(generatedAt string, inputTax []VatDetail, outputTax []VatDetail, period string, totalInputTax string, totalOutputTax string, vatPayable string, vatRefund string, ) *UmsatzsteuerReport`

NewUmsatzsteuerReport instantiates a new UmsatzsteuerReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUmsatzsteuerReportWithDefaults

`func NewUmsatzsteuerReportWithDefaults() *UmsatzsteuerReport`

NewUmsatzsteuerReportWithDefaults instantiates a new UmsatzsteuerReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGeneratedAt

`func (o *UmsatzsteuerReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *UmsatzsteuerReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *UmsatzsteuerReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetInputTax

`func (o *UmsatzsteuerReport) GetInputTax() []VatDetail`

GetInputTax returns the InputTax field if non-nil, zero value otherwise.

### GetInputTaxOk

`func (o *UmsatzsteuerReport) GetInputTaxOk() (*[]VatDetail, bool)`

GetInputTaxOk returns a tuple with the InputTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputTax

`func (o *UmsatzsteuerReport) SetInputTax(v []VatDetail)`

SetInputTax sets InputTax field to given value.


### GetOutputTax

`func (o *UmsatzsteuerReport) GetOutputTax() []VatDetail`

GetOutputTax returns the OutputTax field if non-nil, zero value otherwise.

### GetOutputTaxOk

`func (o *UmsatzsteuerReport) GetOutputTaxOk() (*[]VatDetail, bool)`

GetOutputTaxOk returns a tuple with the OutputTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputTax

`func (o *UmsatzsteuerReport) SetOutputTax(v []VatDetail)`

SetOutputTax sets OutputTax field to given value.


### GetPeriod

`func (o *UmsatzsteuerReport) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *UmsatzsteuerReport) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *UmsatzsteuerReport) SetPeriod(v string)`

SetPeriod sets Period field to given value.


### GetTotalInputTax

`func (o *UmsatzsteuerReport) GetTotalInputTax() string`

GetTotalInputTax returns the TotalInputTax field if non-nil, zero value otherwise.

### GetTotalInputTaxOk

`func (o *UmsatzsteuerReport) GetTotalInputTaxOk() (*string, bool)`

GetTotalInputTaxOk returns a tuple with the TotalInputTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalInputTax

`func (o *UmsatzsteuerReport) SetTotalInputTax(v string)`

SetTotalInputTax sets TotalInputTax field to given value.


### GetTotalOutputTax

`func (o *UmsatzsteuerReport) GetTotalOutputTax() string`

GetTotalOutputTax returns the TotalOutputTax field if non-nil, zero value otherwise.

### GetTotalOutputTaxOk

`func (o *UmsatzsteuerReport) GetTotalOutputTaxOk() (*string, bool)`

GetTotalOutputTaxOk returns a tuple with the TotalOutputTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalOutputTax

`func (o *UmsatzsteuerReport) SetTotalOutputTax(v string)`

SetTotalOutputTax sets TotalOutputTax field to given value.


### GetVatPayable

`func (o *UmsatzsteuerReport) GetVatPayable() string`

GetVatPayable returns the VatPayable field if non-nil, zero value otherwise.

### GetVatPayableOk

`func (o *UmsatzsteuerReport) GetVatPayableOk() (*string, bool)`

GetVatPayableOk returns a tuple with the VatPayable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatPayable

`func (o *UmsatzsteuerReport) SetVatPayable(v string)`

SetVatPayable sets VatPayable field to given value.


### GetVatRefund

`func (o *UmsatzsteuerReport) GetVatRefund() string`

GetVatRefund returns the VatRefund field if non-nil, zero value otherwise.

### GetVatRefundOk

`func (o *UmsatzsteuerReport) GetVatRefundOk() (*string, bool)`

GetVatRefundOk returns a tuple with the VatRefund field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatRefund

`func (o *UmsatzsteuerReport) SetVatRefund(v string)`

SetVatRefund sets VatRefund field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


