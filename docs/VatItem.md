# VatItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NetAmount** | **string** |  | 
**TaxAmount** | **string** |  | 
**TaxRate** | **string** |  | 

## Methods

### NewVatItem

`func NewVatItem(netAmount string, taxAmount string, taxRate string, ) *VatItem`

NewVatItem instantiates a new VatItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVatItemWithDefaults

`func NewVatItemWithDefaults() *VatItem`

NewVatItemWithDefaults instantiates a new VatItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetAmount

`func (o *VatItem) GetNetAmount() string`

GetNetAmount returns the NetAmount field if non-nil, zero value otherwise.

### GetNetAmountOk

`func (o *VatItem) GetNetAmountOk() (*string, bool)`

GetNetAmountOk returns a tuple with the NetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetAmount

`func (o *VatItem) SetNetAmount(v string)`

SetNetAmount sets NetAmount field to given value.


### GetTaxAmount

`func (o *VatItem) GetTaxAmount() string`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *VatItem) GetTaxAmountOk() (*string, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *VatItem) SetTaxAmount(v string)`

SetTaxAmount sets TaxAmount field to given value.


### GetTaxRate

`func (o *VatItem) GetTaxRate() string`

GetTaxRate returns the TaxRate field if non-nil, zero value otherwise.

### GetTaxRateOk

`func (o *VatItem) GetTaxRateOk() (*string, bool)`

GetTaxRateOk returns a tuple with the TaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRate

`func (o *VatItem) SetTaxRate(v string)`

SetTaxRate sets TaxRate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


