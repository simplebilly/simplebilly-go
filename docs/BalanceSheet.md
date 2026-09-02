# BalanceSheet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assets** | [**[]BalanceItem**](BalanceItem.md) |  | 
**Balanced** | **bool** |  | 
**EquityLiabilities** | [**[]BalanceItem**](BalanceItem.md) |  | 
**TotalAssets** | **string** |  | 
**TotalEquityLiabilities** | **string** |  | 

## Methods

### NewBalanceSheet

`func NewBalanceSheet(assets []BalanceItem, balanced bool, equityLiabilities []BalanceItem, totalAssets string, totalEquityLiabilities string, ) *BalanceSheet`

NewBalanceSheet instantiates a new BalanceSheet object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBalanceSheetWithDefaults

`func NewBalanceSheetWithDefaults() *BalanceSheet`

NewBalanceSheetWithDefaults instantiates a new BalanceSheet object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssets

`func (o *BalanceSheet) GetAssets() []BalanceItem`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *BalanceSheet) GetAssetsOk() (*[]BalanceItem, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *BalanceSheet) SetAssets(v []BalanceItem)`

SetAssets sets Assets field to given value.


### GetBalanced

`func (o *BalanceSheet) GetBalanced() bool`

GetBalanced returns the Balanced field if non-nil, zero value otherwise.

### GetBalancedOk

`func (o *BalanceSheet) GetBalancedOk() (*bool, bool)`

GetBalancedOk returns a tuple with the Balanced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanced

`func (o *BalanceSheet) SetBalanced(v bool)`

SetBalanced sets Balanced field to given value.


### GetEquityLiabilities

`func (o *BalanceSheet) GetEquityLiabilities() []BalanceItem`

GetEquityLiabilities returns the EquityLiabilities field if non-nil, zero value otherwise.

### GetEquityLiabilitiesOk

`func (o *BalanceSheet) GetEquityLiabilitiesOk() (*[]BalanceItem, bool)`

GetEquityLiabilitiesOk returns a tuple with the EquityLiabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEquityLiabilities

`func (o *BalanceSheet) SetEquityLiabilities(v []BalanceItem)`

SetEquityLiabilities sets EquityLiabilities field to given value.


### GetTotalAssets

`func (o *BalanceSheet) GetTotalAssets() string`

GetTotalAssets returns the TotalAssets field if non-nil, zero value otherwise.

### GetTotalAssetsOk

`func (o *BalanceSheet) GetTotalAssetsOk() (*string, bool)`

GetTotalAssetsOk returns a tuple with the TotalAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAssets

`func (o *BalanceSheet) SetTotalAssets(v string)`

SetTotalAssets sets TotalAssets field to given value.


### GetTotalEquityLiabilities

`func (o *BalanceSheet) GetTotalEquityLiabilities() string`

GetTotalEquityLiabilities returns the TotalEquityLiabilities field if non-nil, zero value otherwise.

### GetTotalEquityLiabilitiesOk

`func (o *BalanceSheet) GetTotalEquityLiabilitiesOk() (*string, bool)`

GetTotalEquityLiabilitiesOk returns a tuple with the TotalEquityLiabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEquityLiabilities

`func (o *BalanceSheet) SetTotalEquityLiabilities(v string)`

SetTotalEquityLiabilities sets TotalEquityLiabilities field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


