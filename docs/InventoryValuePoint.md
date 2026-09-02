# InventoryValuePoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductCount** | **int64** |  | 
**RecordedAt** | **time.Time** |  | 
**TotalPurchaseValue** | **string** |  | 
**TotalSalesValue** | **string** |  | 

## Methods

### NewInventoryValuePoint

`func NewInventoryValuePoint(productCount int64, recordedAt time.Time, totalPurchaseValue string, totalSalesValue string, ) *InventoryValuePoint`

NewInventoryValuePoint instantiates a new InventoryValuePoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryValuePointWithDefaults

`func NewInventoryValuePointWithDefaults() *InventoryValuePoint`

NewInventoryValuePointWithDefaults instantiates a new InventoryValuePoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductCount

`func (o *InventoryValuePoint) GetProductCount() int64`

GetProductCount returns the ProductCount field if non-nil, zero value otherwise.

### GetProductCountOk

`func (o *InventoryValuePoint) GetProductCountOk() (*int64, bool)`

GetProductCountOk returns a tuple with the ProductCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCount

`func (o *InventoryValuePoint) SetProductCount(v int64)`

SetProductCount sets ProductCount field to given value.


### GetRecordedAt

`func (o *InventoryValuePoint) GetRecordedAt() time.Time`

GetRecordedAt returns the RecordedAt field if non-nil, zero value otherwise.

### GetRecordedAtOk

`func (o *InventoryValuePoint) GetRecordedAtOk() (*time.Time, bool)`

GetRecordedAtOk returns a tuple with the RecordedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordedAt

`func (o *InventoryValuePoint) SetRecordedAt(v time.Time)`

SetRecordedAt sets RecordedAt field to given value.


### GetTotalPurchaseValue

`func (o *InventoryValuePoint) GetTotalPurchaseValue() string`

GetTotalPurchaseValue returns the TotalPurchaseValue field if non-nil, zero value otherwise.

### GetTotalPurchaseValueOk

`func (o *InventoryValuePoint) GetTotalPurchaseValueOk() (*string, bool)`

GetTotalPurchaseValueOk returns a tuple with the TotalPurchaseValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPurchaseValue

`func (o *InventoryValuePoint) SetTotalPurchaseValue(v string)`

SetTotalPurchaseValue sets TotalPurchaseValue field to given value.


### GetTotalSalesValue

`func (o *InventoryValuePoint) GetTotalSalesValue() string`

GetTotalSalesValue returns the TotalSalesValue field if non-nil, zero value otherwise.

### GetTotalSalesValueOk

`func (o *InventoryValuePoint) GetTotalSalesValueOk() (*string, bool)`

GetTotalSalesValueOk returns a tuple with the TotalSalesValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSalesValue

`func (o *InventoryValuePoint) SetTotalSalesValue(v string)`

SetTotalSalesValue sets TotalSalesValue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


