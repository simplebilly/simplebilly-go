# ReturnLogisticsSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByStatus** | **interface{}** | Number of return orders per status. | 
**ByWarehouse** | [**[]ReturnWarehouseSummary**](ReturnWarehouseSummary.md) | Per-warehouse aggregation. | 
**ItemsRestocked** | **int64** | Sum of &#x60;restock: true&#x60; line-item quantities. | 
**ItemsScrapped** | **int64** | Sum of &#x60;restock: false&#x60; line-item quantities (scrapped/disposed). | 
**TotalItems** | **int64** | Sum of all line-item quantities across returns. | 
**TotalReturns** | **int64** | Total number of return orders (excluding soft-deleted). | 

## Methods

### NewReturnLogisticsSummary

`func NewReturnLogisticsSummary(byStatus interface{}, byWarehouse []ReturnWarehouseSummary, itemsRestocked int64, itemsScrapped int64, totalItems int64, totalReturns int64, ) *ReturnLogisticsSummary`

NewReturnLogisticsSummary instantiates a new ReturnLogisticsSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReturnLogisticsSummaryWithDefaults

`func NewReturnLogisticsSummaryWithDefaults() *ReturnLogisticsSummary`

NewReturnLogisticsSummaryWithDefaults instantiates a new ReturnLogisticsSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetByStatus

`func (o *ReturnLogisticsSummary) GetByStatus() interface{}`

GetByStatus returns the ByStatus field if non-nil, zero value otherwise.

### GetByStatusOk

`func (o *ReturnLogisticsSummary) GetByStatusOk() (*interface{}, bool)`

GetByStatusOk returns a tuple with the ByStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByStatus

`func (o *ReturnLogisticsSummary) SetByStatus(v interface{})`

SetByStatus sets ByStatus field to given value.


### SetByStatusNil

`func (o *ReturnLogisticsSummary) SetByStatusNil(b bool)`

 SetByStatusNil sets the value for ByStatus to be an explicit nil

### UnsetByStatus
`func (o *ReturnLogisticsSummary) UnsetByStatus()`

UnsetByStatus ensures that no value is present for ByStatus, not even an explicit nil
### GetByWarehouse

`func (o *ReturnLogisticsSummary) GetByWarehouse() []ReturnWarehouseSummary`

GetByWarehouse returns the ByWarehouse field if non-nil, zero value otherwise.

### GetByWarehouseOk

`func (o *ReturnLogisticsSummary) GetByWarehouseOk() (*[]ReturnWarehouseSummary, bool)`

GetByWarehouseOk returns a tuple with the ByWarehouse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByWarehouse

`func (o *ReturnLogisticsSummary) SetByWarehouse(v []ReturnWarehouseSummary)`

SetByWarehouse sets ByWarehouse field to given value.


### GetItemsRestocked

`func (o *ReturnLogisticsSummary) GetItemsRestocked() int64`

GetItemsRestocked returns the ItemsRestocked field if non-nil, zero value otherwise.

### GetItemsRestockedOk

`func (o *ReturnLogisticsSummary) GetItemsRestockedOk() (*int64, bool)`

GetItemsRestockedOk returns a tuple with the ItemsRestocked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsRestocked

`func (o *ReturnLogisticsSummary) SetItemsRestocked(v int64)`

SetItemsRestocked sets ItemsRestocked field to given value.


### GetItemsScrapped

`func (o *ReturnLogisticsSummary) GetItemsScrapped() int64`

GetItemsScrapped returns the ItemsScrapped field if non-nil, zero value otherwise.

### GetItemsScrappedOk

`func (o *ReturnLogisticsSummary) GetItemsScrappedOk() (*int64, bool)`

GetItemsScrappedOk returns a tuple with the ItemsScrapped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsScrapped

`func (o *ReturnLogisticsSummary) SetItemsScrapped(v int64)`

SetItemsScrapped sets ItemsScrapped field to given value.


### GetTotalItems

`func (o *ReturnLogisticsSummary) GetTotalItems() int64`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *ReturnLogisticsSummary) GetTotalItemsOk() (*int64, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *ReturnLogisticsSummary) SetTotalItems(v int64)`

SetTotalItems sets TotalItems field to given value.


### GetTotalReturns

`func (o *ReturnLogisticsSummary) GetTotalReturns() int64`

GetTotalReturns returns the TotalReturns field if non-nil, zero value otherwise.

### GetTotalReturnsOk

`func (o *ReturnLogisticsSummary) GetTotalReturnsOk() (*int64, bool)`

GetTotalReturnsOk returns a tuple with the TotalReturns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalReturns

`func (o *ReturnLogisticsSummary) SetTotalReturns(v int64)`

SetTotalReturns sets TotalReturns field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


