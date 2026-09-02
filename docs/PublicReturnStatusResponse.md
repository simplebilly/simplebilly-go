# PublicReturnStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** |  | 
**Items** | **interface{}** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | Pointer to **NullableString** |  | [optional] 
**ReturnNumber** | **string** |  | 
**ReturnOrderId** | **string** |  | 
**Status** | **string** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewPublicReturnStatusResponse

`func NewPublicReturnStatusResponse(createdAt time.Time, items interface{}, returnNumber string, returnOrderId string, status string, ) *PublicReturnStatusResponse`

NewPublicReturnStatusResponse instantiates a new PublicReturnStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicReturnStatusResponseWithDefaults

`func NewPublicReturnStatusResponseWithDefaults() *PublicReturnStatusResponse`

NewPublicReturnStatusResponseWithDefaults instantiates a new PublicReturnStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *PublicReturnStatusResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PublicReturnStatusResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PublicReturnStatusResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetItems

`func (o *PublicReturnStatusResponse) GetItems() interface{}`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PublicReturnStatusResponse) GetItemsOk() (*interface{}, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PublicReturnStatusResponse) SetItems(v interface{})`

SetItems sets Items field to given value.


### SetItemsNil

`func (o *PublicReturnStatusResponse) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *PublicReturnStatusResponse) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil
### GetNotes

`func (o *PublicReturnStatusResponse) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *PublicReturnStatusResponse) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *PublicReturnStatusResponse) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *PublicReturnStatusResponse) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *PublicReturnStatusResponse) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *PublicReturnStatusResponse) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderNumber

`func (o *PublicReturnStatusResponse) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *PublicReturnStatusResponse) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *PublicReturnStatusResponse) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *PublicReturnStatusResponse) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *PublicReturnStatusResponse) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *PublicReturnStatusResponse) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetReturnNumber

`func (o *PublicReturnStatusResponse) GetReturnNumber() string`

GetReturnNumber returns the ReturnNumber field if non-nil, zero value otherwise.

### GetReturnNumberOk

`func (o *PublicReturnStatusResponse) GetReturnNumberOk() (*string, bool)`

GetReturnNumberOk returns a tuple with the ReturnNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnNumber

`func (o *PublicReturnStatusResponse) SetReturnNumber(v string)`

SetReturnNumber sets ReturnNumber field to given value.


### GetReturnOrderId

`func (o *PublicReturnStatusResponse) GetReturnOrderId() string`

GetReturnOrderId returns the ReturnOrderId field if non-nil, zero value otherwise.

### GetReturnOrderIdOk

`func (o *PublicReturnStatusResponse) GetReturnOrderIdOk() (*string, bool)`

GetReturnOrderIdOk returns a tuple with the ReturnOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnOrderId

`func (o *PublicReturnStatusResponse) SetReturnOrderId(v string)`

SetReturnOrderId sets ReturnOrderId field to given value.


### GetStatus

`func (o *PublicReturnStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PublicReturnStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PublicReturnStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *PublicReturnStatusResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PublicReturnStatusResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PublicReturnStatusResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PublicReturnStatusResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *PublicReturnStatusResponse) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *PublicReturnStatusResponse) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


