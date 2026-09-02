# ReturnLogisticsQueueItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgeDays** | **int64** | Days since creation, oldest first. | 
**CreatedAt** | **time.Time** |  | 
**CustomerName** | Pointer to **NullableString** |  | [optional] 
**LineItems** | **interface{}** |  | 
**OrderNumber** | Pointer to **NullableString** |  | [optional] 
**ReturnNumber** | **string** |  | 
**ReturnOrderId** | **string** |  | 
**Status** | **string** |  | 
**WarehouseId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewReturnLogisticsQueueItem

`func NewReturnLogisticsQueueItem(ageDays int64, createdAt time.Time, lineItems interface{}, returnNumber string, returnOrderId string, status string, ) *ReturnLogisticsQueueItem`

NewReturnLogisticsQueueItem instantiates a new ReturnLogisticsQueueItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReturnLogisticsQueueItemWithDefaults

`func NewReturnLogisticsQueueItemWithDefaults() *ReturnLogisticsQueueItem`

NewReturnLogisticsQueueItemWithDefaults instantiates a new ReturnLogisticsQueueItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgeDays

`func (o *ReturnLogisticsQueueItem) GetAgeDays() int64`

GetAgeDays returns the AgeDays field if non-nil, zero value otherwise.

### GetAgeDaysOk

`func (o *ReturnLogisticsQueueItem) GetAgeDaysOk() (*int64, bool)`

GetAgeDaysOk returns a tuple with the AgeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgeDays

`func (o *ReturnLogisticsQueueItem) SetAgeDays(v int64)`

SetAgeDays sets AgeDays field to given value.


### GetCreatedAt

`func (o *ReturnLogisticsQueueItem) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReturnLogisticsQueueItem) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReturnLogisticsQueueItem) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomerName

`func (o *ReturnLogisticsQueueItem) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *ReturnLogisticsQueueItem) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *ReturnLogisticsQueueItem) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *ReturnLogisticsQueueItem) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *ReturnLogisticsQueueItem) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *ReturnLogisticsQueueItem) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetLineItems

`func (o *ReturnLogisticsQueueItem) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *ReturnLogisticsQueueItem) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *ReturnLogisticsQueueItem) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *ReturnLogisticsQueueItem) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *ReturnLogisticsQueueItem) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetOrderNumber

`func (o *ReturnLogisticsQueueItem) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ReturnLogisticsQueueItem) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ReturnLogisticsQueueItem) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *ReturnLogisticsQueueItem) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *ReturnLogisticsQueueItem) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *ReturnLogisticsQueueItem) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetReturnNumber

`func (o *ReturnLogisticsQueueItem) GetReturnNumber() string`

GetReturnNumber returns the ReturnNumber field if non-nil, zero value otherwise.

### GetReturnNumberOk

`func (o *ReturnLogisticsQueueItem) GetReturnNumberOk() (*string, bool)`

GetReturnNumberOk returns a tuple with the ReturnNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnNumber

`func (o *ReturnLogisticsQueueItem) SetReturnNumber(v string)`

SetReturnNumber sets ReturnNumber field to given value.


### GetReturnOrderId

`func (o *ReturnLogisticsQueueItem) GetReturnOrderId() string`

GetReturnOrderId returns the ReturnOrderId field if non-nil, zero value otherwise.

### GetReturnOrderIdOk

`func (o *ReturnLogisticsQueueItem) GetReturnOrderIdOk() (*string, bool)`

GetReturnOrderIdOk returns a tuple with the ReturnOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnOrderId

`func (o *ReturnLogisticsQueueItem) SetReturnOrderId(v string)`

SetReturnOrderId sets ReturnOrderId field to given value.


### GetStatus

`func (o *ReturnLogisticsQueueItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReturnLogisticsQueueItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReturnLogisticsQueueItem) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetWarehouseId

`func (o *ReturnLogisticsQueueItem) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *ReturnLogisticsQueueItem) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *ReturnLogisticsQueueItem) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.

### HasWarehouseId

`func (o *ReturnLogisticsQueueItem) HasWarehouseId() bool`

HasWarehouseId returns a boolean if a field has been set.

### SetWarehouseIdNil

`func (o *ReturnLogisticsQueueItem) SetWarehouseIdNil(b bool)`

 SetWarehouseIdNil sets the value for WarehouseId to be an explicit nil

### UnsetWarehouseId
`func (o *ReturnLogisticsQueueItem) UnsetWarehouseId()`

UnsetWarehouseId ensures that no value is present for WarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


