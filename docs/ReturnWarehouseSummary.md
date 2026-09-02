# ReturnWarehouseSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ItemsRestocked** | **int64** |  | 
**ItemsScrapped** | **int64** |  | 
**Returns** | **int64** |  | 
**WarehouseId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewReturnWarehouseSummary

`func NewReturnWarehouseSummary(itemsRestocked int64, itemsScrapped int64, returns int64, ) *ReturnWarehouseSummary`

NewReturnWarehouseSummary instantiates a new ReturnWarehouseSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReturnWarehouseSummaryWithDefaults

`func NewReturnWarehouseSummaryWithDefaults() *ReturnWarehouseSummary`

NewReturnWarehouseSummaryWithDefaults instantiates a new ReturnWarehouseSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItemsRestocked

`func (o *ReturnWarehouseSummary) GetItemsRestocked() int64`

GetItemsRestocked returns the ItemsRestocked field if non-nil, zero value otherwise.

### GetItemsRestockedOk

`func (o *ReturnWarehouseSummary) GetItemsRestockedOk() (*int64, bool)`

GetItemsRestockedOk returns a tuple with the ItemsRestocked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsRestocked

`func (o *ReturnWarehouseSummary) SetItemsRestocked(v int64)`

SetItemsRestocked sets ItemsRestocked field to given value.


### GetItemsScrapped

`func (o *ReturnWarehouseSummary) GetItemsScrapped() int64`

GetItemsScrapped returns the ItemsScrapped field if non-nil, zero value otherwise.

### GetItemsScrappedOk

`func (o *ReturnWarehouseSummary) GetItemsScrappedOk() (*int64, bool)`

GetItemsScrappedOk returns a tuple with the ItemsScrapped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsScrapped

`func (o *ReturnWarehouseSummary) SetItemsScrapped(v int64)`

SetItemsScrapped sets ItemsScrapped field to given value.


### GetReturns

`func (o *ReturnWarehouseSummary) GetReturns() int64`

GetReturns returns the Returns field if non-nil, zero value otherwise.

### GetReturnsOk

`func (o *ReturnWarehouseSummary) GetReturnsOk() (*int64, bool)`

GetReturnsOk returns a tuple with the Returns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturns

`func (o *ReturnWarehouseSummary) SetReturns(v int64)`

SetReturns sets Returns field to given value.


### GetWarehouseId

`func (o *ReturnWarehouseSummary) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *ReturnWarehouseSummary) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *ReturnWarehouseSummary) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.

### HasWarehouseId

`func (o *ReturnWarehouseSummary) HasWarehouseId() bool`

HasWarehouseId returns a boolean if a field has been set.

### SetWarehouseIdNil

`func (o *ReturnWarehouseSummary) SetWarehouseIdNil(b bool)`

 SetWarehouseIdNil sets the value for WarehouseId to be an explicit nil

### UnsetWarehouseId
`func (o *ReturnWarehouseSummary) UnsetWarehouseId()`

UnsetWarehouseId ensures that no value is present for WarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


