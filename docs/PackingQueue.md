# PackingQueue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]PackingQueueItem**](PackingQueueItem.md) |  | 
**Page** | **int32** |  | 
**PageSize** | **int32** |  | 
**TotalCount** | **int64** |  | 

## Methods

### NewPackingQueue

`func NewPackingQueue(items []PackingQueueItem, page int32, pageSize int32, totalCount int64, ) *PackingQueue`

NewPackingQueue instantiates a new PackingQueue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPackingQueueWithDefaults

`func NewPackingQueueWithDefaults() *PackingQueue`

NewPackingQueueWithDefaults instantiates a new PackingQueue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *PackingQueue) GetItems() []PackingQueueItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PackingQueue) GetItemsOk() (*[]PackingQueueItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PackingQueue) SetItems(v []PackingQueueItem)`

SetItems sets Items field to given value.


### GetPage

`func (o *PackingQueue) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PackingQueue) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PackingQueue) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPageSize

`func (o *PackingQueue) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *PackingQueue) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *PackingQueue) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.


### GetTotalCount

`func (o *PackingQueue) GetTotalCount() int64`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *PackingQueue) GetTotalCountOk() (*int64, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *PackingQueue) SetTotalCount(v int64)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


