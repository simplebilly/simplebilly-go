# CustomerCommunicationUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | Pointer to **NullableString** | The message body, call summary or note text. | [optional] 
**Channel** | Pointer to [**NullableCommunicationChannel**](CommunicationChannel.md) |  | [optional] 
**ContactId** | Pointer to **NullableString** | The contact (customer/supplier) this communication belongs to. References the contact entity. | [optional] 
**Counterparty** | Pointer to **NullableString** | Email/phone of the counterparty, if applicable. | [optional] 
**Direction** | Pointer to [**NullableCommunicationDirection**](CommunicationDirection.md) |  | [optional] 
**OccurredAt** | Pointer to **NullableTime** | When the communication happened (defaults to now on create). | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **interface{}** | Free-form tags, e.g. &#x60;[\&quot;follow-up-required\&quot;]&#x60;. | [optional] 

## Methods

### NewCustomerCommunicationUpdate

`func NewCustomerCommunicationUpdate() *CustomerCommunicationUpdate`

NewCustomerCommunicationUpdate instantiates a new CustomerCommunicationUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerCommunicationUpdateWithDefaults

`func NewCustomerCommunicationUpdateWithDefaults() *CustomerCommunicationUpdate`

NewCustomerCommunicationUpdateWithDefaults instantiates a new CustomerCommunicationUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *CustomerCommunicationUpdate) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *CustomerCommunicationUpdate) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *CustomerCommunicationUpdate) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *CustomerCommunicationUpdate) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *CustomerCommunicationUpdate) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *CustomerCommunicationUpdate) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil
### GetChannel

`func (o *CustomerCommunicationUpdate) GetChannel() CommunicationChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *CustomerCommunicationUpdate) GetChannelOk() (*CommunicationChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *CustomerCommunicationUpdate) SetChannel(v CommunicationChannel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *CustomerCommunicationUpdate) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### SetChannelNil

`func (o *CustomerCommunicationUpdate) SetChannelNil(b bool)`

 SetChannelNil sets the value for Channel to be an explicit nil

### UnsetChannel
`func (o *CustomerCommunicationUpdate) UnsetChannel()`

UnsetChannel ensures that no value is present for Channel, not even an explicit nil
### GetContactId

`func (o *CustomerCommunicationUpdate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *CustomerCommunicationUpdate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *CustomerCommunicationUpdate) SetContactId(v string)`

SetContactId sets ContactId field to given value.

### HasContactId

`func (o *CustomerCommunicationUpdate) HasContactId() bool`

HasContactId returns a boolean if a field has been set.

### SetContactIdNil

`func (o *CustomerCommunicationUpdate) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *CustomerCommunicationUpdate) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetCounterparty

`func (o *CustomerCommunicationUpdate) GetCounterparty() string`

GetCounterparty returns the Counterparty field if non-nil, zero value otherwise.

### GetCounterpartyOk

`func (o *CustomerCommunicationUpdate) GetCounterpartyOk() (*string, bool)`

GetCounterpartyOk returns a tuple with the Counterparty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounterparty

`func (o *CustomerCommunicationUpdate) SetCounterparty(v string)`

SetCounterparty sets Counterparty field to given value.

### HasCounterparty

`func (o *CustomerCommunicationUpdate) HasCounterparty() bool`

HasCounterparty returns a boolean if a field has been set.

### SetCounterpartyNil

`func (o *CustomerCommunicationUpdate) SetCounterpartyNil(b bool)`

 SetCounterpartyNil sets the value for Counterparty to be an explicit nil

### UnsetCounterparty
`func (o *CustomerCommunicationUpdate) UnsetCounterparty()`

UnsetCounterparty ensures that no value is present for Counterparty, not even an explicit nil
### GetDirection

`func (o *CustomerCommunicationUpdate) GetDirection() CommunicationDirection`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *CustomerCommunicationUpdate) GetDirectionOk() (*CommunicationDirection, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *CustomerCommunicationUpdate) SetDirection(v CommunicationDirection)`

SetDirection sets Direction field to given value.

### HasDirection

`func (o *CustomerCommunicationUpdate) HasDirection() bool`

HasDirection returns a boolean if a field has been set.

### SetDirectionNil

`func (o *CustomerCommunicationUpdate) SetDirectionNil(b bool)`

 SetDirectionNil sets the value for Direction to be an explicit nil

### UnsetDirection
`func (o *CustomerCommunicationUpdate) UnsetDirection()`

UnsetDirection ensures that no value is present for Direction, not even an explicit nil
### GetOccurredAt

`func (o *CustomerCommunicationUpdate) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *CustomerCommunicationUpdate) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *CustomerCommunicationUpdate) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *CustomerCommunicationUpdate) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### SetOccurredAtNil

`func (o *CustomerCommunicationUpdate) SetOccurredAtNil(b bool)`

 SetOccurredAtNil sets the value for OccurredAt to be an explicit nil

### UnsetOccurredAt
`func (o *CustomerCommunicationUpdate) UnsetOccurredAt()`

UnsetOccurredAt ensures that no value is present for OccurredAt, not even an explicit nil
### GetSubject

`func (o *CustomerCommunicationUpdate) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *CustomerCommunicationUpdate) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *CustomerCommunicationUpdate) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *CustomerCommunicationUpdate) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *CustomerCommunicationUpdate) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *CustomerCommunicationUpdate) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetTags

`func (o *CustomerCommunicationUpdate) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CustomerCommunicationUpdate) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CustomerCommunicationUpdate) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *CustomerCommunicationUpdate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *CustomerCommunicationUpdate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *CustomerCommunicationUpdate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


