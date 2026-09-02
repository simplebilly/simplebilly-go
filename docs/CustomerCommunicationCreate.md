# CustomerCommunicationCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | Pointer to **NullableString** | The message body, call summary or note text. | [optional] 
**Channel** | [**CommunicationChannel**](CommunicationChannel.md) |  | 
**ContactId** | **string** | The contact (customer/supplier) this communication belongs to. References the contact entity. | 
**Counterparty** | Pointer to **NullableString** | Email/phone of the counterparty, if applicable. | [optional] 
**Direction** | [**CommunicationDirection**](CommunicationDirection.md) |  | 
**OccurredAt** | Pointer to **time.Time** | When the communication happened (defaults to now on create). | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **interface{}** | Free-form tags, e.g. &#x60;[\&quot;follow-up-required\&quot;]&#x60;. | [optional] 

## Methods

### NewCustomerCommunicationCreate

`func NewCustomerCommunicationCreate(channel CommunicationChannel, contactId string, direction CommunicationDirection, ) *CustomerCommunicationCreate`

NewCustomerCommunicationCreate instantiates a new CustomerCommunicationCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerCommunicationCreateWithDefaults

`func NewCustomerCommunicationCreateWithDefaults() *CustomerCommunicationCreate`

NewCustomerCommunicationCreateWithDefaults instantiates a new CustomerCommunicationCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *CustomerCommunicationCreate) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *CustomerCommunicationCreate) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *CustomerCommunicationCreate) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *CustomerCommunicationCreate) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *CustomerCommunicationCreate) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *CustomerCommunicationCreate) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil
### GetChannel

`func (o *CustomerCommunicationCreate) GetChannel() CommunicationChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *CustomerCommunicationCreate) GetChannelOk() (*CommunicationChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *CustomerCommunicationCreate) SetChannel(v CommunicationChannel)`

SetChannel sets Channel field to given value.


### GetContactId

`func (o *CustomerCommunicationCreate) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *CustomerCommunicationCreate) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *CustomerCommunicationCreate) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### GetCounterparty

`func (o *CustomerCommunicationCreate) GetCounterparty() string`

GetCounterparty returns the Counterparty field if non-nil, zero value otherwise.

### GetCounterpartyOk

`func (o *CustomerCommunicationCreate) GetCounterpartyOk() (*string, bool)`

GetCounterpartyOk returns a tuple with the Counterparty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounterparty

`func (o *CustomerCommunicationCreate) SetCounterparty(v string)`

SetCounterparty sets Counterparty field to given value.

### HasCounterparty

`func (o *CustomerCommunicationCreate) HasCounterparty() bool`

HasCounterparty returns a boolean if a field has been set.

### SetCounterpartyNil

`func (o *CustomerCommunicationCreate) SetCounterpartyNil(b bool)`

 SetCounterpartyNil sets the value for Counterparty to be an explicit nil

### UnsetCounterparty
`func (o *CustomerCommunicationCreate) UnsetCounterparty()`

UnsetCounterparty ensures that no value is present for Counterparty, not even an explicit nil
### GetDirection

`func (o *CustomerCommunicationCreate) GetDirection() CommunicationDirection`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *CustomerCommunicationCreate) GetDirectionOk() (*CommunicationDirection, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *CustomerCommunicationCreate) SetDirection(v CommunicationDirection)`

SetDirection sets Direction field to given value.


### GetOccurredAt

`func (o *CustomerCommunicationCreate) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *CustomerCommunicationCreate) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *CustomerCommunicationCreate) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *CustomerCommunicationCreate) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### GetSubject

`func (o *CustomerCommunicationCreate) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *CustomerCommunicationCreate) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *CustomerCommunicationCreate) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *CustomerCommunicationCreate) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *CustomerCommunicationCreate) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *CustomerCommunicationCreate) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetTags

`func (o *CustomerCommunicationCreate) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CustomerCommunicationCreate) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CustomerCommunicationCreate) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *CustomerCommunicationCreate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *CustomerCommunicationCreate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *CustomerCommunicationCreate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


