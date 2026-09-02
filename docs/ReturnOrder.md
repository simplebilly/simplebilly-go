# ReturnOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerContactId** | Pointer to **NullableString** | References the contact entity. | [optional] 
**CustomerName** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** | JSON array of &#x60;{product_id, name, quantity, condition, restock, batch_number?}&#x60;. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderId** | Pointer to **NullableString** | References the order entity. | [optional] 
**OrderNumber** | Pointer to **NullableString** |  | [optional] 
**ReturnNumber** | **string** |  | 
**ReturnReason** | Pointer to **NullableString** |  | [optional] 
**Status** | [**ReturnOrderStatus**](ReturnOrderStatus.md) | One of: requested | received | inspected | restocked | closed | 
**WarehouseId** | Pointer to **NullableString** | Warehouse into which restockable items are returned. References the warehouse entity. | [optional] 

## Methods

### NewReturnOrder

`func NewReturnOrder(returnNumber string, status ReturnOrderStatus, ) *ReturnOrder`

NewReturnOrder instantiates a new ReturnOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReturnOrderWithDefaults

`func NewReturnOrderWithDefaults() *ReturnOrder`

NewReturnOrderWithDefaults instantiates a new ReturnOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerContactId

`func (o *ReturnOrder) GetCustomerContactId() string`

GetCustomerContactId returns the CustomerContactId field if non-nil, zero value otherwise.

### GetCustomerContactIdOk

`func (o *ReturnOrder) GetCustomerContactIdOk() (*string, bool)`

GetCustomerContactIdOk returns a tuple with the CustomerContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerContactId

`func (o *ReturnOrder) SetCustomerContactId(v string)`

SetCustomerContactId sets CustomerContactId field to given value.

### HasCustomerContactId

`func (o *ReturnOrder) HasCustomerContactId() bool`

HasCustomerContactId returns a boolean if a field has been set.

### SetCustomerContactIdNil

`func (o *ReturnOrder) SetCustomerContactIdNil(b bool)`

 SetCustomerContactIdNil sets the value for CustomerContactId to be an explicit nil

### UnsetCustomerContactId
`func (o *ReturnOrder) UnsetCustomerContactId()`

UnsetCustomerContactId ensures that no value is present for CustomerContactId, not even an explicit nil
### GetCustomerName

`func (o *ReturnOrder) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *ReturnOrder) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *ReturnOrder) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *ReturnOrder) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *ReturnOrder) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *ReturnOrder) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetLineItems

`func (o *ReturnOrder) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *ReturnOrder) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *ReturnOrder) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *ReturnOrder) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *ReturnOrder) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *ReturnOrder) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *ReturnOrder) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ReturnOrder) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ReturnOrder) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ReturnOrder) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ReturnOrder) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ReturnOrder) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderId

`func (o *ReturnOrder) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *ReturnOrder) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *ReturnOrder) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *ReturnOrder) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### SetOrderIdNil

`func (o *ReturnOrder) SetOrderIdNil(b bool)`

 SetOrderIdNil sets the value for OrderId to be an explicit nil

### UnsetOrderId
`func (o *ReturnOrder) UnsetOrderId()`

UnsetOrderId ensures that no value is present for OrderId, not even an explicit nil
### GetOrderNumber

`func (o *ReturnOrder) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ReturnOrder) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ReturnOrder) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *ReturnOrder) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *ReturnOrder) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *ReturnOrder) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetReturnNumber

`func (o *ReturnOrder) GetReturnNumber() string`

GetReturnNumber returns the ReturnNumber field if non-nil, zero value otherwise.

### GetReturnNumberOk

`func (o *ReturnOrder) GetReturnNumberOk() (*string, bool)`

GetReturnNumberOk returns a tuple with the ReturnNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnNumber

`func (o *ReturnOrder) SetReturnNumber(v string)`

SetReturnNumber sets ReturnNumber field to given value.


### GetReturnReason

`func (o *ReturnOrder) GetReturnReason() string`

GetReturnReason returns the ReturnReason field if non-nil, zero value otherwise.

### GetReturnReasonOk

`func (o *ReturnOrder) GetReturnReasonOk() (*string, bool)`

GetReturnReasonOk returns a tuple with the ReturnReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnReason

`func (o *ReturnOrder) SetReturnReason(v string)`

SetReturnReason sets ReturnReason field to given value.

### HasReturnReason

`func (o *ReturnOrder) HasReturnReason() bool`

HasReturnReason returns a boolean if a field has been set.

### SetReturnReasonNil

`func (o *ReturnOrder) SetReturnReasonNil(b bool)`

 SetReturnReasonNil sets the value for ReturnReason to be an explicit nil

### UnsetReturnReason
`func (o *ReturnOrder) UnsetReturnReason()`

UnsetReturnReason ensures that no value is present for ReturnReason, not even an explicit nil
### GetStatus

`func (o *ReturnOrder) GetStatus() ReturnOrderStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReturnOrder) GetStatusOk() (*ReturnOrderStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReturnOrder) SetStatus(v ReturnOrderStatus)`

SetStatus sets Status field to given value.


### GetWarehouseId

`func (o *ReturnOrder) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *ReturnOrder) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *ReturnOrder) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.

### HasWarehouseId

`func (o *ReturnOrder) HasWarehouseId() bool`

HasWarehouseId returns a boolean if a field has been set.

### SetWarehouseIdNil

`func (o *ReturnOrder) SetWarehouseIdNil(b bool)`

 SetWarehouseIdNil sets the value for WarehouseId to be an explicit nil

### UnsetWarehouseId
`func (o *ReturnOrder) UnsetWarehouseId()`

UnsetWarehouseId ensures that no value is present for WarehouseId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


