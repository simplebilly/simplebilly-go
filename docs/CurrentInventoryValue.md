# CurrentInventoryValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**History** | [**[]InventoryValuePoint**](InventoryValuePoint.md) |  | 
**ProductCount** | **int64** |  | 
**TotalPurchaseValue** | **string** |  | 
**TotalSalesValue** | **string** |  | 

## Methods

### NewCurrentInventoryValue

`func NewCurrentInventoryValue(history []InventoryValuePoint, productCount int64, totalPurchaseValue string, totalSalesValue string, ) *CurrentInventoryValue`

NewCurrentInventoryValue instantiates a new CurrentInventoryValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentInventoryValueWithDefaults

`func NewCurrentInventoryValueWithDefaults() *CurrentInventoryValue`

NewCurrentInventoryValueWithDefaults instantiates a new CurrentInventoryValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHistory

`func (o *CurrentInventoryValue) GetHistory() []InventoryValuePoint`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *CurrentInventoryValue) GetHistoryOk() (*[]InventoryValuePoint, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *CurrentInventoryValue) SetHistory(v []InventoryValuePoint)`

SetHistory sets History field to given value.


### GetProductCount

`func (o *CurrentInventoryValue) GetProductCount() int64`

GetProductCount returns the ProductCount field if non-nil, zero value otherwise.

### GetProductCountOk

`func (o *CurrentInventoryValue) GetProductCountOk() (*int64, bool)`

GetProductCountOk returns a tuple with the ProductCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCount

`func (o *CurrentInventoryValue) SetProductCount(v int64)`

SetProductCount sets ProductCount field to given value.


### GetTotalPurchaseValue

`func (o *CurrentInventoryValue) GetTotalPurchaseValue() string`

GetTotalPurchaseValue returns the TotalPurchaseValue field if non-nil, zero value otherwise.

### GetTotalPurchaseValueOk

`func (o *CurrentInventoryValue) GetTotalPurchaseValueOk() (*string, bool)`

GetTotalPurchaseValueOk returns a tuple with the TotalPurchaseValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPurchaseValue

`func (o *CurrentInventoryValue) SetTotalPurchaseValue(v string)`

SetTotalPurchaseValue sets TotalPurchaseValue field to given value.


### GetTotalSalesValue

`func (o *CurrentInventoryValue) GetTotalSalesValue() string`

GetTotalSalesValue returns the TotalSalesValue field if non-nil, zero value otherwise.

### GetTotalSalesValueOk

`func (o *CurrentInventoryValue) GetTotalSalesValueOk() (*string, bool)`

GetTotalSalesValueOk returns a tuple with the TotalSalesValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSalesValue

`func (o *CurrentInventoryValue) SetTotalSalesValue(v string)`

SetTotalSalesValue sets TotalSalesValue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


