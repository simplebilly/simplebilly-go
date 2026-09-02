# CustomerCommunication

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

### NewCustomerCommunication

`func NewCustomerCommunication(channel CommunicationChannel, contactId string, direction CommunicationDirection, ) *CustomerCommunication`

NewCustomerCommunication instantiates a new CustomerCommunication object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerCommunicationWithDefaults

`func NewCustomerCommunicationWithDefaults() *CustomerCommunication`

NewCustomerCommunicationWithDefaults instantiates a new CustomerCommunication object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *CustomerCommunication) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *CustomerCommunication) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *CustomerCommunication) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *CustomerCommunication) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *CustomerCommunication) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *CustomerCommunication) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil
### GetChannel

`func (o *CustomerCommunication) GetChannel() CommunicationChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *CustomerCommunication) GetChannelOk() (*CommunicationChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *CustomerCommunication) SetChannel(v CommunicationChannel)`

SetChannel sets Channel field to given value.


### GetContactId

`func (o *CustomerCommunication) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *CustomerCommunication) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *CustomerCommunication) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### GetCounterparty

`func (o *CustomerCommunication) GetCounterparty() string`

GetCounterparty returns the Counterparty field if non-nil, zero value otherwise.

### GetCounterpartyOk

`func (o *CustomerCommunication) GetCounterpartyOk() (*string, bool)`

GetCounterpartyOk returns a tuple with the Counterparty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounterparty

`func (o *CustomerCommunication) SetCounterparty(v string)`

SetCounterparty sets Counterparty field to given value.

### HasCounterparty

`func (o *CustomerCommunication) HasCounterparty() bool`

HasCounterparty returns a boolean if a field has been set.

### SetCounterpartyNil

`func (o *CustomerCommunication) SetCounterpartyNil(b bool)`

 SetCounterpartyNil sets the value for Counterparty to be an explicit nil

### UnsetCounterparty
`func (o *CustomerCommunication) UnsetCounterparty()`

UnsetCounterparty ensures that no value is present for Counterparty, not even an explicit nil
### GetDirection

`func (o *CustomerCommunication) GetDirection() CommunicationDirection`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *CustomerCommunication) GetDirectionOk() (*CommunicationDirection, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *CustomerCommunication) SetDirection(v CommunicationDirection)`

SetDirection sets Direction field to given value.


### GetOccurredAt

`func (o *CustomerCommunication) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *CustomerCommunication) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *CustomerCommunication) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *CustomerCommunication) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### GetSubject

`func (o *CustomerCommunication) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *CustomerCommunication) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *CustomerCommunication) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *CustomerCommunication) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *CustomerCommunication) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *CustomerCommunication) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetTags

`func (o *CustomerCommunication) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CustomerCommunication) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CustomerCommunication) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *CustomerCommunication) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *CustomerCommunication) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *CustomerCommunication) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


