# ContactTimelineResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactId** | **string** |  | 
**Events** | [**[]TimelineEvent**](TimelineEvent.md) |  | 

## Methods

### NewContactTimelineResponse

`func NewContactTimelineResponse(contactId string, events []TimelineEvent, ) *ContactTimelineResponse`

NewContactTimelineResponse instantiates a new ContactTimelineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactTimelineResponseWithDefaults

`func NewContactTimelineResponseWithDefaults() *ContactTimelineResponse`

NewContactTimelineResponseWithDefaults instantiates a new ContactTimelineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactId

`func (o *ContactTimelineResponse) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *ContactTimelineResponse) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *ContactTimelineResponse) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### GetEvents

`func (o *ContactTimelineResponse) GetEvents() []TimelineEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *ContactTimelineResponse) GetEventsOk() (*[]TimelineEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *ContactTimelineResponse) SetEvents(v []TimelineEvent)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


