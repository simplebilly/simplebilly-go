# SupportTicket

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedTo** | Pointer to **NullableString** |  | [optional] 
**ChannelId** | Pointer to **NullableString** |  | [optional] 
**ChannelType** | Pointer to [**NullableSupportChannelType**](SupportChannelType.md) |  | [optional] 
**ClosedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**CustomerEmail** | Pointer to **NullableString** |  | [optional] 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**CustomerName** | Pointer to **NullableString** |  | [optional] 
**ExternalId** | Pointer to **NullableString** |  | [optional] 
**FirstMessageAt** | **time.Time** |  | 
**LastMessageAt** | **time.Time** |  | 
**LeadId** | Pointer to **NullableString** | References the lead entity. | [optional] 
**MessageCount** | **int32** |  | 
**OrderRef** | Pointer to **NullableString** |  | [optional] 
**Priority** | [**TicketPriority**](TicketPriority.md) |  | 
**Resolution** | Pointer to **NullableString** |  | [optional] 
**Status** | [**SupportTicketStatus**](SupportTicketStatus.md) |  | 
**Subject** | **string** |  | 
**Tags** | **interface{}** |  | 
**TenantId** | **string** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewSupportTicket

`func NewSupportTicket(createdAt time.Time, firstMessageAt time.Time, lastMessageAt time.Time, messageCount int32, priority TicketPriority, status SupportTicketStatus, subject string, tags interface{}, tenantId string, ) *SupportTicket`

NewSupportTicket instantiates a new SupportTicket object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupportTicketWithDefaults

`func NewSupportTicketWithDefaults() *SupportTicket`

NewSupportTicketWithDefaults instantiates a new SupportTicket object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedTo

`func (o *SupportTicket) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *SupportTicket) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *SupportTicket) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *SupportTicket) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### SetAssignedToNil

`func (o *SupportTicket) SetAssignedToNil(b bool)`

 SetAssignedToNil sets the value for AssignedTo to be an explicit nil

### UnsetAssignedTo
`func (o *SupportTicket) UnsetAssignedTo()`

UnsetAssignedTo ensures that no value is present for AssignedTo, not even an explicit nil
### GetChannelId

`func (o *SupportTicket) GetChannelId() string`

GetChannelId returns the ChannelId field if non-nil, zero value otherwise.

### GetChannelIdOk

`func (o *SupportTicket) GetChannelIdOk() (*string, bool)`

GetChannelIdOk returns a tuple with the ChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelId

`func (o *SupportTicket) SetChannelId(v string)`

SetChannelId sets ChannelId field to given value.

### HasChannelId

`func (o *SupportTicket) HasChannelId() bool`

HasChannelId returns a boolean if a field has been set.

### SetChannelIdNil

`func (o *SupportTicket) SetChannelIdNil(b bool)`

 SetChannelIdNil sets the value for ChannelId to be an explicit nil

### UnsetChannelId
`func (o *SupportTicket) UnsetChannelId()`

UnsetChannelId ensures that no value is present for ChannelId, not even an explicit nil
### GetChannelType

`func (o *SupportTicket) GetChannelType() SupportChannelType`

GetChannelType returns the ChannelType field if non-nil, zero value otherwise.

### GetChannelTypeOk

`func (o *SupportTicket) GetChannelTypeOk() (*SupportChannelType, bool)`

GetChannelTypeOk returns a tuple with the ChannelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelType

`func (o *SupportTicket) SetChannelType(v SupportChannelType)`

SetChannelType sets ChannelType field to given value.

### HasChannelType

`func (o *SupportTicket) HasChannelType() bool`

HasChannelType returns a boolean if a field has been set.

### SetChannelTypeNil

`func (o *SupportTicket) SetChannelTypeNil(b bool)`

 SetChannelTypeNil sets the value for ChannelType to be an explicit nil

### UnsetChannelType
`func (o *SupportTicket) UnsetChannelType()`

UnsetChannelType ensures that no value is present for ChannelType, not even an explicit nil
### GetClosedAt

`func (o *SupportTicket) GetClosedAt() time.Time`

GetClosedAt returns the ClosedAt field if non-nil, zero value otherwise.

### GetClosedAtOk

`func (o *SupportTicket) GetClosedAtOk() (*time.Time, bool)`

GetClosedAtOk returns a tuple with the ClosedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosedAt

`func (o *SupportTicket) SetClosedAt(v time.Time)`

SetClosedAt sets ClosedAt field to given value.

### HasClosedAt

`func (o *SupportTicket) HasClosedAt() bool`

HasClosedAt returns a boolean if a field has been set.

### SetClosedAtNil

`func (o *SupportTicket) SetClosedAtNil(b bool)`

 SetClosedAtNil sets the value for ClosedAt to be an explicit nil

### UnsetClosedAt
`func (o *SupportTicket) UnsetClosedAt()`

UnsetClosedAt ensures that no value is present for ClosedAt, not even an explicit nil
### GetCreatedAt

`func (o *SupportTicket) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SupportTicket) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SupportTicket) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomerEmail

`func (o *SupportTicket) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *SupportTicket) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *SupportTicket) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *SupportTicket) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *SupportTicket) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *SupportTicket) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetCustomerId

`func (o *SupportTicket) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *SupportTicket) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *SupportTicket) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *SupportTicket) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *SupportTicket) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *SupportTicket) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerName

`func (o *SupportTicket) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *SupportTicket) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *SupportTicket) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *SupportTicket) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *SupportTicket) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *SupportTicket) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetExternalId

`func (o *SupportTicket) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *SupportTicket) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *SupportTicket) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *SupportTicket) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *SupportTicket) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *SupportTicket) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetFirstMessageAt

`func (o *SupportTicket) GetFirstMessageAt() time.Time`

GetFirstMessageAt returns the FirstMessageAt field if non-nil, zero value otherwise.

### GetFirstMessageAtOk

`func (o *SupportTicket) GetFirstMessageAtOk() (*time.Time, bool)`

GetFirstMessageAtOk returns a tuple with the FirstMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstMessageAt

`func (o *SupportTicket) SetFirstMessageAt(v time.Time)`

SetFirstMessageAt sets FirstMessageAt field to given value.


### GetLastMessageAt

`func (o *SupportTicket) GetLastMessageAt() time.Time`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *SupportTicket) GetLastMessageAtOk() (*time.Time, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *SupportTicket) SetLastMessageAt(v time.Time)`

SetLastMessageAt sets LastMessageAt field to given value.


### GetLeadId

`func (o *SupportTicket) GetLeadId() string`

GetLeadId returns the LeadId field if non-nil, zero value otherwise.

### GetLeadIdOk

`func (o *SupportTicket) GetLeadIdOk() (*string, bool)`

GetLeadIdOk returns a tuple with the LeadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadId

`func (o *SupportTicket) SetLeadId(v string)`

SetLeadId sets LeadId field to given value.

### HasLeadId

`func (o *SupportTicket) HasLeadId() bool`

HasLeadId returns a boolean if a field has been set.

### SetLeadIdNil

`func (o *SupportTicket) SetLeadIdNil(b bool)`

 SetLeadIdNil sets the value for LeadId to be an explicit nil

### UnsetLeadId
`func (o *SupportTicket) UnsetLeadId()`

UnsetLeadId ensures that no value is present for LeadId, not even an explicit nil
### GetMessageCount

`func (o *SupportTicket) GetMessageCount() int32`

GetMessageCount returns the MessageCount field if non-nil, zero value otherwise.

### GetMessageCountOk

`func (o *SupportTicket) GetMessageCountOk() (*int32, bool)`

GetMessageCountOk returns a tuple with the MessageCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageCount

`func (o *SupportTicket) SetMessageCount(v int32)`

SetMessageCount sets MessageCount field to given value.


### GetOrderRef

`func (o *SupportTicket) GetOrderRef() string`

GetOrderRef returns the OrderRef field if non-nil, zero value otherwise.

### GetOrderRefOk

`func (o *SupportTicket) GetOrderRefOk() (*string, bool)`

GetOrderRefOk returns a tuple with the OrderRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderRef

`func (o *SupportTicket) SetOrderRef(v string)`

SetOrderRef sets OrderRef field to given value.

### HasOrderRef

`func (o *SupportTicket) HasOrderRef() bool`

HasOrderRef returns a boolean if a field has been set.

### SetOrderRefNil

`func (o *SupportTicket) SetOrderRefNil(b bool)`

 SetOrderRefNil sets the value for OrderRef to be an explicit nil

### UnsetOrderRef
`func (o *SupportTicket) UnsetOrderRef()`

UnsetOrderRef ensures that no value is present for OrderRef, not even an explicit nil
### GetPriority

`func (o *SupportTicket) GetPriority() TicketPriority`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *SupportTicket) GetPriorityOk() (*TicketPriority, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *SupportTicket) SetPriority(v TicketPriority)`

SetPriority sets Priority field to given value.


### GetResolution

`func (o *SupportTicket) GetResolution() string`

GetResolution returns the Resolution field if non-nil, zero value otherwise.

### GetResolutionOk

`func (o *SupportTicket) GetResolutionOk() (*string, bool)`

GetResolutionOk returns a tuple with the Resolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolution

`func (o *SupportTicket) SetResolution(v string)`

SetResolution sets Resolution field to given value.

### HasResolution

`func (o *SupportTicket) HasResolution() bool`

HasResolution returns a boolean if a field has been set.

### SetResolutionNil

`func (o *SupportTicket) SetResolutionNil(b bool)`

 SetResolutionNil sets the value for Resolution to be an explicit nil

### UnsetResolution
`func (o *SupportTicket) UnsetResolution()`

UnsetResolution ensures that no value is present for Resolution, not even an explicit nil
### GetStatus

`func (o *SupportTicket) GetStatus() SupportTicketStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SupportTicket) GetStatusOk() (*SupportTicketStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SupportTicket) SetStatus(v SupportTicketStatus)`

SetStatus sets Status field to given value.


### GetSubject

`func (o *SupportTicket) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *SupportTicket) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *SupportTicket) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetTags

`func (o *SupportTicket) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *SupportTicket) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *SupportTicket) SetTags(v interface{})`

SetTags sets Tags field to given value.


### SetTagsNil

`func (o *SupportTicket) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *SupportTicket) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTenantId

`func (o *SupportTicket) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *SupportTicket) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *SupportTicket) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetUpdatedAt

`func (o *SupportTicket) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SupportTicket) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SupportTicket) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *SupportTicket) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *SupportTicket) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *SupportTicket) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


