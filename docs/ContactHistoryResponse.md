# ContactHistoryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactId** | **string** |  | 
**InboundCount** | **int64** |  | 
**Items** | [**[]CustomerCommunication**](CustomerCommunication.md) |  | 
**OutboundCount** | **int64** |  | 

## Methods

### NewContactHistoryResponse

`func NewContactHistoryResponse(contactId string, inboundCount int64, items []CustomerCommunication, outboundCount int64, ) *ContactHistoryResponse`

NewContactHistoryResponse instantiates a new ContactHistoryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactHistoryResponseWithDefaults

`func NewContactHistoryResponseWithDefaults() *ContactHistoryResponse`

NewContactHistoryResponseWithDefaults instantiates a new ContactHistoryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactId

`func (o *ContactHistoryResponse) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *ContactHistoryResponse) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *ContactHistoryResponse) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### GetInboundCount

`func (o *ContactHistoryResponse) GetInboundCount() int64`

GetInboundCount returns the InboundCount field if non-nil, zero value otherwise.

### GetInboundCountOk

`func (o *ContactHistoryResponse) GetInboundCountOk() (*int64, bool)`

GetInboundCountOk returns a tuple with the InboundCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundCount

`func (o *ContactHistoryResponse) SetInboundCount(v int64)`

SetInboundCount sets InboundCount field to given value.


### GetItems

`func (o *ContactHistoryResponse) GetItems() []CustomerCommunication`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ContactHistoryResponse) GetItemsOk() (*[]CustomerCommunication, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ContactHistoryResponse) SetItems(v []CustomerCommunication)`

SetItems sets Items field to given value.


### GetOutboundCount

`func (o *ContactHistoryResponse) GetOutboundCount() int64`

GetOutboundCount returns the OutboundCount field if non-nil, zero value otherwise.

### GetOutboundCountOk

`func (o *ContactHistoryResponse) GetOutboundCountOk() (*int64, bool)`

GetOutboundCountOk returns a tuple with the OutboundCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundCount

`func (o *ContactHistoryResponse) SetOutboundCount(v int64)`

SetOutboundCount sets OutboundCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


