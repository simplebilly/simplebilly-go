# PublicReturnRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**Items** | [**[]PublicReturnItem**](PublicReturnItem.md) |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | **string** |  | 

## Methods

### NewPublicReturnRequest

`func NewPublicReturnRequest(email string, items []PublicReturnItem, orderNumber string, ) *PublicReturnRequest`

NewPublicReturnRequest instantiates a new PublicReturnRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicReturnRequestWithDefaults

`func NewPublicReturnRequestWithDefaults() *PublicReturnRequest`

NewPublicReturnRequestWithDefaults instantiates a new PublicReturnRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *PublicReturnRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PublicReturnRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PublicReturnRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetItems

`func (o *PublicReturnRequest) GetItems() []PublicReturnItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PublicReturnRequest) GetItemsOk() (*[]PublicReturnItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PublicReturnRequest) SetItems(v []PublicReturnItem)`

SetItems sets Items field to given value.


### GetNotes

`func (o *PublicReturnRequest) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *PublicReturnRequest) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *PublicReturnRequest) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *PublicReturnRequest) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *PublicReturnRequest) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *PublicReturnRequest) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderNumber

`func (o *PublicReturnRequest) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *PublicReturnRequest) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *PublicReturnRequest) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


