# TicketMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthorEmail** | Pointer to **NullableString** |  | [optional] 
**AuthorName** | Pointer to **NullableString** |  | [optional] 
**Body** | **string** |  | 
**BodyHtml** | Pointer to **NullableString** |  | [optional] 
**ChannelId** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**Direction** | [**MessageDirection**](MessageDirection.md) |  | 
**ExternalId** | Pointer to **NullableString** |  | [optional] 
**IsInternal** | **bool** |  | 
**MessageType** | [**MessageType**](MessageType.md) |  | 
**Metadata** | **interface{}** |  | 
**TenantId** | **string** |  | 
**TicketId** | **string** | References the ticket entity. | 

## Methods

### NewTicketMessage

`func NewTicketMessage(body string, createdAt time.Time, direction MessageDirection, isInternal bool, messageType MessageType, metadata interface{}, tenantId string, ticketId string, ) *TicketMessage`

NewTicketMessage instantiates a new TicketMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketMessageWithDefaults

`func NewTicketMessageWithDefaults() *TicketMessage`

NewTicketMessageWithDefaults instantiates a new TicketMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthorEmail

`func (o *TicketMessage) GetAuthorEmail() string`

GetAuthorEmail returns the AuthorEmail field if non-nil, zero value otherwise.

### GetAuthorEmailOk

`func (o *TicketMessage) GetAuthorEmailOk() (*string, bool)`

GetAuthorEmailOk returns a tuple with the AuthorEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorEmail

`func (o *TicketMessage) SetAuthorEmail(v string)`

SetAuthorEmail sets AuthorEmail field to given value.

### HasAuthorEmail

`func (o *TicketMessage) HasAuthorEmail() bool`

HasAuthorEmail returns a boolean if a field has been set.

### SetAuthorEmailNil

`func (o *TicketMessage) SetAuthorEmailNil(b bool)`

 SetAuthorEmailNil sets the value for AuthorEmail to be an explicit nil

### UnsetAuthorEmail
`func (o *TicketMessage) UnsetAuthorEmail()`

UnsetAuthorEmail ensures that no value is present for AuthorEmail, not even an explicit nil
### GetAuthorName

`func (o *TicketMessage) GetAuthorName() string`

GetAuthorName returns the AuthorName field if non-nil, zero value otherwise.

### GetAuthorNameOk

`func (o *TicketMessage) GetAuthorNameOk() (*string, bool)`

GetAuthorNameOk returns a tuple with the AuthorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorName

`func (o *TicketMessage) SetAuthorName(v string)`

SetAuthorName sets AuthorName field to given value.

### HasAuthorName

`func (o *TicketMessage) HasAuthorName() bool`

HasAuthorName returns a boolean if a field has been set.

### SetAuthorNameNil

`func (o *TicketMessage) SetAuthorNameNil(b bool)`

 SetAuthorNameNil sets the value for AuthorName to be an explicit nil

### UnsetAuthorName
`func (o *TicketMessage) UnsetAuthorName()`

UnsetAuthorName ensures that no value is present for AuthorName, not even an explicit nil
### GetBody

`func (o *TicketMessage) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *TicketMessage) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *TicketMessage) SetBody(v string)`

SetBody sets Body field to given value.


### GetBodyHtml

`func (o *TicketMessage) GetBodyHtml() string`

GetBodyHtml returns the BodyHtml field if non-nil, zero value otherwise.

### GetBodyHtmlOk

`func (o *TicketMessage) GetBodyHtmlOk() (*string, bool)`

GetBodyHtmlOk returns a tuple with the BodyHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBodyHtml

`func (o *TicketMessage) SetBodyHtml(v string)`

SetBodyHtml sets BodyHtml field to given value.

### HasBodyHtml

`func (o *TicketMessage) HasBodyHtml() bool`

HasBodyHtml returns a boolean if a field has been set.

### SetBodyHtmlNil

`func (o *TicketMessage) SetBodyHtmlNil(b bool)`

 SetBodyHtmlNil sets the value for BodyHtml to be an explicit nil

### UnsetBodyHtml
`func (o *TicketMessage) UnsetBodyHtml()`

UnsetBodyHtml ensures that no value is present for BodyHtml, not even an explicit nil
### GetChannelId

`func (o *TicketMessage) GetChannelId() string`

GetChannelId returns the ChannelId field if non-nil, zero value otherwise.

### GetChannelIdOk

`func (o *TicketMessage) GetChannelIdOk() (*string, bool)`

GetChannelIdOk returns a tuple with the ChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelId

`func (o *TicketMessage) SetChannelId(v string)`

SetChannelId sets ChannelId field to given value.

### HasChannelId

`func (o *TicketMessage) HasChannelId() bool`

HasChannelId returns a boolean if a field has been set.

### SetChannelIdNil

`func (o *TicketMessage) SetChannelIdNil(b bool)`

 SetChannelIdNil sets the value for ChannelId to be an explicit nil

### UnsetChannelId
`func (o *TicketMessage) UnsetChannelId()`

UnsetChannelId ensures that no value is present for ChannelId, not even an explicit nil
### GetCreatedAt

`func (o *TicketMessage) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TicketMessage) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TicketMessage) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDirection

`func (o *TicketMessage) GetDirection() MessageDirection`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *TicketMessage) GetDirectionOk() (*MessageDirection, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *TicketMessage) SetDirection(v MessageDirection)`

SetDirection sets Direction field to given value.


### GetExternalId

`func (o *TicketMessage) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *TicketMessage) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *TicketMessage) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *TicketMessage) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *TicketMessage) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *TicketMessage) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetIsInternal

`func (o *TicketMessage) GetIsInternal() bool`

GetIsInternal returns the IsInternal field if non-nil, zero value otherwise.

### GetIsInternalOk

`func (o *TicketMessage) GetIsInternalOk() (*bool, bool)`

GetIsInternalOk returns a tuple with the IsInternal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsInternal

`func (o *TicketMessage) SetIsInternal(v bool)`

SetIsInternal sets IsInternal field to given value.


### GetMessageType

`func (o *TicketMessage) GetMessageType() MessageType`

GetMessageType returns the MessageType field if non-nil, zero value otherwise.

### GetMessageTypeOk

`func (o *TicketMessage) GetMessageTypeOk() (*MessageType, bool)`

GetMessageTypeOk returns a tuple with the MessageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageType

`func (o *TicketMessage) SetMessageType(v MessageType)`

SetMessageType sets MessageType field to given value.


### GetMetadata

`func (o *TicketMessage) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *TicketMessage) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *TicketMessage) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *TicketMessage) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *TicketMessage) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetTenantId

`func (o *TicketMessage) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *TicketMessage) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *TicketMessage) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetTicketId

`func (o *TicketMessage) GetTicketId() string`

GetTicketId returns the TicketId field if non-nil, zero value otherwise.

### GetTicketIdOk

`func (o *TicketMessage) GetTicketIdOk() (*string, bool)`

GetTicketIdOk returns a tuple with the TicketId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTicketId

`func (o *TicketMessage) SetTicketId(v string)`

SetTicketId sets TicketId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


