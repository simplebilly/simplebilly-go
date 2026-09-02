# SupportTicketUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedTo** | Pointer to **NullableString** |  | [optional] 
**ChannelId** | Pointer to **NullableString** |  | [optional] 
**ChannelType** | Pointer to [**NullableSupportChannelType**](SupportChannelType.md) |  | [optional] 
**ClosedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**CustomerEmail** | Pointer to **NullableString** |  | [optional] 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**CustomerName** | Pointer to **NullableString** |  | [optional] 
**ExternalId** | Pointer to **NullableString** |  | [optional] 
**FirstMessageAt** | Pointer to **NullableTime** |  | [optional] 
**LastMessageAt** | Pointer to **NullableTime** |  | [optional] 
**LeadId** | Pointer to **NullableString** | References the lead entity. | [optional] 
**MessageCount** | Pointer to **NullableInt32** |  | [optional] 
**OrderRef** | Pointer to **NullableString** |  | [optional] 
**Priority** | Pointer to [**NullableTicketPriority**](TicketPriority.md) |  | [optional] 
**Resolution** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableSupportTicketStatus**](SupportTicketStatus.md) |  | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **interface{}** |  | [optional] 
**TenantId** | Pointer to **NullableString** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewSupportTicketUpdate

`func NewSupportTicketUpdate() *SupportTicketUpdate`

NewSupportTicketUpdate instantiates a new SupportTicketUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupportTicketUpdateWithDefaults

`func NewSupportTicketUpdateWithDefaults() *SupportTicketUpdate`

NewSupportTicketUpdateWithDefaults instantiates a new SupportTicketUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedTo

`func (o *SupportTicketUpdate) GetAssignedTo() string`

GetAssignedTo returns the AssignedTo field if non-nil, zero value otherwise.

### GetAssignedToOk

`func (o *SupportTicketUpdate) GetAssignedToOk() (*string, bool)`

GetAssignedToOk returns a tuple with the AssignedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedTo

`func (o *SupportTicketUpdate) SetAssignedTo(v string)`

SetAssignedTo sets AssignedTo field to given value.

### HasAssignedTo

`func (o *SupportTicketUpdate) HasAssignedTo() bool`

HasAssignedTo returns a boolean if a field has been set.

### SetAssignedToNil

`func (o *SupportTicketUpdate) SetAssignedToNil(b bool)`

 SetAssignedToNil sets the value for AssignedTo to be an explicit nil

### UnsetAssignedTo
`func (o *SupportTicketUpdate) UnsetAssignedTo()`

UnsetAssignedTo ensures that no value is present for AssignedTo, not even an explicit nil
### GetChannelId

`func (o *SupportTicketUpdate) GetChannelId() string`

GetChannelId returns the ChannelId field if non-nil, zero value otherwise.

### GetChannelIdOk

`func (o *SupportTicketUpdate) GetChannelIdOk() (*string, bool)`

GetChannelIdOk returns a tuple with the ChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelId

`func (o *SupportTicketUpdate) SetChannelId(v string)`

SetChannelId sets ChannelId field to given value.

### HasChannelId

`func (o *SupportTicketUpdate) HasChannelId() bool`

HasChannelId returns a boolean if a field has been set.

### SetChannelIdNil

`func (o *SupportTicketUpdate) SetChannelIdNil(b bool)`

 SetChannelIdNil sets the value for ChannelId to be an explicit nil

### UnsetChannelId
`func (o *SupportTicketUpdate) UnsetChannelId()`

UnsetChannelId ensures that no value is present for ChannelId, not even an explicit nil
### GetChannelType

`func (o *SupportTicketUpdate) GetChannelType() SupportChannelType`

GetChannelType returns the ChannelType field if non-nil, zero value otherwise.

### GetChannelTypeOk

`func (o *SupportTicketUpdate) GetChannelTypeOk() (*SupportChannelType, bool)`

GetChannelTypeOk returns a tuple with the ChannelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelType

`func (o *SupportTicketUpdate) SetChannelType(v SupportChannelType)`

SetChannelType sets ChannelType field to given value.

### HasChannelType

`func (o *SupportTicketUpdate) HasChannelType() bool`

HasChannelType returns a boolean if a field has been set.

### SetChannelTypeNil

`func (o *SupportTicketUpdate) SetChannelTypeNil(b bool)`

 SetChannelTypeNil sets the value for ChannelType to be an explicit nil

### UnsetChannelType
`func (o *SupportTicketUpdate) UnsetChannelType()`

UnsetChannelType ensures that no value is present for ChannelType, not even an explicit nil
### GetClosedAt

`func (o *SupportTicketUpdate) GetClosedAt() time.Time`

GetClosedAt returns the ClosedAt field if non-nil, zero value otherwise.

### GetClosedAtOk

`func (o *SupportTicketUpdate) GetClosedAtOk() (*time.Time, bool)`

GetClosedAtOk returns a tuple with the ClosedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosedAt

`func (o *SupportTicketUpdate) SetClosedAt(v time.Time)`

SetClosedAt sets ClosedAt field to given value.

### HasClosedAt

`func (o *SupportTicketUpdate) HasClosedAt() bool`

HasClosedAt returns a boolean if a field has been set.

### SetClosedAtNil

`func (o *SupportTicketUpdate) SetClosedAtNil(b bool)`

 SetClosedAtNil sets the value for ClosedAt to be an explicit nil

### UnsetClosedAt
`func (o *SupportTicketUpdate) UnsetClosedAt()`

UnsetClosedAt ensures that no value is present for ClosedAt, not even an explicit nil
### GetCreatedAt

`func (o *SupportTicketUpdate) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SupportTicketUpdate) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SupportTicketUpdate) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SupportTicketUpdate) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *SupportTicketUpdate) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *SupportTicketUpdate) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetCustomerEmail

`func (o *SupportTicketUpdate) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *SupportTicketUpdate) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *SupportTicketUpdate) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *SupportTicketUpdate) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *SupportTicketUpdate) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *SupportTicketUpdate) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetCustomerId

`func (o *SupportTicketUpdate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *SupportTicketUpdate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *SupportTicketUpdate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *SupportTicketUpdate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *SupportTicketUpdate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *SupportTicketUpdate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerName

`func (o *SupportTicketUpdate) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *SupportTicketUpdate) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *SupportTicketUpdate) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *SupportTicketUpdate) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *SupportTicketUpdate) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *SupportTicketUpdate) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetExternalId

`func (o *SupportTicketUpdate) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *SupportTicketUpdate) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *SupportTicketUpdate) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *SupportTicketUpdate) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *SupportTicketUpdate) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *SupportTicketUpdate) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetFirstMessageAt

`func (o *SupportTicketUpdate) GetFirstMessageAt() time.Time`

GetFirstMessageAt returns the FirstMessageAt field if non-nil, zero value otherwise.

### GetFirstMessageAtOk

`func (o *SupportTicketUpdate) GetFirstMessageAtOk() (*time.Time, bool)`

GetFirstMessageAtOk returns a tuple with the FirstMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstMessageAt

`func (o *SupportTicketUpdate) SetFirstMessageAt(v time.Time)`

SetFirstMessageAt sets FirstMessageAt field to given value.

### HasFirstMessageAt

`func (o *SupportTicketUpdate) HasFirstMessageAt() bool`

HasFirstMessageAt returns a boolean if a field has been set.

### SetFirstMessageAtNil

`func (o *SupportTicketUpdate) SetFirstMessageAtNil(b bool)`

 SetFirstMessageAtNil sets the value for FirstMessageAt to be an explicit nil

### UnsetFirstMessageAt
`func (o *SupportTicketUpdate) UnsetFirstMessageAt()`

UnsetFirstMessageAt ensures that no value is present for FirstMessageAt, not even an explicit nil
### GetLastMessageAt

`func (o *SupportTicketUpdate) GetLastMessageAt() time.Time`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *SupportTicketUpdate) GetLastMessageAtOk() (*time.Time, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *SupportTicketUpdate) SetLastMessageAt(v time.Time)`

SetLastMessageAt sets LastMessageAt field to given value.

### HasLastMessageAt

`func (o *SupportTicketUpdate) HasLastMessageAt() bool`

HasLastMessageAt returns a boolean if a field has been set.

### SetLastMessageAtNil

`func (o *SupportTicketUpdate) SetLastMessageAtNil(b bool)`

 SetLastMessageAtNil sets the value for LastMessageAt to be an explicit nil

### UnsetLastMessageAt
`func (o *SupportTicketUpdate) UnsetLastMessageAt()`

UnsetLastMessageAt ensures that no value is present for LastMessageAt, not even an explicit nil
### GetLeadId

`func (o *SupportTicketUpdate) GetLeadId() string`

GetLeadId returns the LeadId field if non-nil, zero value otherwise.

### GetLeadIdOk

`func (o *SupportTicketUpdate) GetLeadIdOk() (*string, bool)`

GetLeadIdOk returns a tuple with the LeadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadId

`func (o *SupportTicketUpdate) SetLeadId(v string)`

SetLeadId sets LeadId field to given value.

### HasLeadId

`func (o *SupportTicketUpdate) HasLeadId() bool`

HasLeadId returns a boolean if a field has been set.

### SetLeadIdNil

`func (o *SupportTicketUpdate) SetLeadIdNil(b bool)`

 SetLeadIdNil sets the value for LeadId to be an explicit nil

### UnsetLeadId
`func (o *SupportTicketUpdate) UnsetLeadId()`

UnsetLeadId ensures that no value is present for LeadId, not even an explicit nil
### GetMessageCount

`func (o *SupportTicketUpdate) GetMessageCount() int32`

GetMessageCount returns the MessageCount field if non-nil, zero value otherwise.

### GetMessageCountOk

`func (o *SupportTicketUpdate) GetMessageCountOk() (*int32, bool)`

GetMessageCountOk returns a tuple with the MessageCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageCount

`func (o *SupportTicketUpdate) SetMessageCount(v int32)`

SetMessageCount sets MessageCount field to given value.

### HasMessageCount

`func (o *SupportTicketUpdate) HasMessageCount() bool`

HasMessageCount returns a boolean if a field has been set.

### SetMessageCountNil

`func (o *SupportTicketUpdate) SetMessageCountNil(b bool)`

 SetMessageCountNil sets the value for MessageCount to be an explicit nil

### UnsetMessageCount
`func (o *SupportTicketUpdate) UnsetMessageCount()`

UnsetMessageCount ensures that no value is present for MessageCount, not even an explicit nil
### GetOrderRef

`func (o *SupportTicketUpdate) GetOrderRef() string`

GetOrderRef returns the OrderRef field if non-nil, zero value otherwise.

### GetOrderRefOk

`func (o *SupportTicketUpdate) GetOrderRefOk() (*string, bool)`

GetOrderRefOk returns a tuple with the OrderRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderRef

`func (o *SupportTicketUpdate) SetOrderRef(v string)`

SetOrderRef sets OrderRef field to given value.

### HasOrderRef

`func (o *SupportTicketUpdate) HasOrderRef() bool`

HasOrderRef returns a boolean if a field has been set.

### SetOrderRefNil

`func (o *SupportTicketUpdate) SetOrderRefNil(b bool)`

 SetOrderRefNil sets the value for OrderRef to be an explicit nil

### UnsetOrderRef
`func (o *SupportTicketUpdate) UnsetOrderRef()`

UnsetOrderRef ensures that no value is present for OrderRef, not even an explicit nil
### GetPriority

`func (o *SupportTicketUpdate) GetPriority() TicketPriority`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *SupportTicketUpdate) GetPriorityOk() (*TicketPriority, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *SupportTicketUpdate) SetPriority(v TicketPriority)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *SupportTicketUpdate) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### SetPriorityNil

`func (o *SupportTicketUpdate) SetPriorityNil(b bool)`

 SetPriorityNil sets the value for Priority to be an explicit nil

### UnsetPriority
`func (o *SupportTicketUpdate) UnsetPriority()`

UnsetPriority ensures that no value is present for Priority, not even an explicit nil
### GetResolution

`func (o *SupportTicketUpdate) GetResolution() string`

GetResolution returns the Resolution field if non-nil, zero value otherwise.

### GetResolutionOk

`func (o *SupportTicketUpdate) GetResolutionOk() (*string, bool)`

GetResolutionOk returns a tuple with the Resolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolution

`func (o *SupportTicketUpdate) SetResolution(v string)`

SetResolution sets Resolution field to given value.

### HasResolution

`func (o *SupportTicketUpdate) HasResolution() bool`

HasResolution returns a boolean if a field has been set.

### SetResolutionNil

`func (o *SupportTicketUpdate) SetResolutionNil(b bool)`

 SetResolutionNil sets the value for Resolution to be an explicit nil

### UnsetResolution
`func (o *SupportTicketUpdate) UnsetResolution()`

UnsetResolution ensures that no value is present for Resolution, not even an explicit nil
### GetStatus

`func (o *SupportTicketUpdate) GetStatus() SupportTicketStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SupportTicketUpdate) GetStatusOk() (*SupportTicketStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SupportTicketUpdate) SetStatus(v SupportTicketStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SupportTicketUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *SupportTicketUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *SupportTicketUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSubject

`func (o *SupportTicketUpdate) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *SupportTicketUpdate) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *SupportTicketUpdate) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *SupportTicketUpdate) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *SupportTicketUpdate) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *SupportTicketUpdate) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetTags

`func (o *SupportTicketUpdate) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *SupportTicketUpdate) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *SupportTicketUpdate) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *SupportTicketUpdate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *SupportTicketUpdate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *SupportTicketUpdate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTenantId

`func (o *SupportTicketUpdate) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *SupportTicketUpdate) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *SupportTicketUpdate) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *SupportTicketUpdate) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *SupportTicketUpdate) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *SupportTicketUpdate) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetUpdatedAt

`func (o *SupportTicketUpdate) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SupportTicketUpdate) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SupportTicketUpdate) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *SupportTicketUpdate) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *SupportTicketUpdate) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *SupportTicketUpdate) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


