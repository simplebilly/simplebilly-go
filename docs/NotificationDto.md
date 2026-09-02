# NotificationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** |  | 
**Id** | **string** |  | 
**IsRead** | **bool** |  | 
**Message** | Pointer to **NullableString** |  | [optional] 
**SentViaEmail** | **bool** |  | 
**TenantId** | **string** |  | 
**Title** | **string** |  | 
**UserId** | **string** |  | 

## Methods

### NewNotificationDto

`func NewNotificationDto(createdAt time.Time, id string, isRead bool, sentViaEmail bool, tenantId string, title string, userId string, ) *NotificationDto`

NewNotificationDto instantiates a new NotificationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotificationDtoWithDefaults

`func NewNotificationDtoWithDefaults() *NotificationDto`

NewNotificationDtoWithDefaults instantiates a new NotificationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *NotificationDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *NotificationDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *NotificationDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *NotificationDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NotificationDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NotificationDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsRead

`func (o *NotificationDto) GetIsRead() bool`

GetIsRead returns the IsRead field if non-nil, zero value otherwise.

### GetIsReadOk

`func (o *NotificationDto) GetIsReadOk() (*bool, bool)`

GetIsReadOk returns a tuple with the IsRead field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRead

`func (o *NotificationDto) SetIsRead(v bool)`

SetIsRead sets IsRead field to given value.


### GetMessage

`func (o *NotificationDto) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *NotificationDto) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *NotificationDto) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *NotificationDto) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *NotificationDto) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *NotificationDto) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetSentViaEmail

`func (o *NotificationDto) GetSentViaEmail() bool`

GetSentViaEmail returns the SentViaEmail field if non-nil, zero value otherwise.

### GetSentViaEmailOk

`func (o *NotificationDto) GetSentViaEmailOk() (*bool, bool)`

GetSentViaEmailOk returns a tuple with the SentViaEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentViaEmail

`func (o *NotificationDto) SetSentViaEmail(v bool)`

SetSentViaEmail sets SentViaEmail field to given value.


### GetTenantId

`func (o *NotificationDto) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *NotificationDto) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *NotificationDto) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetTitle

`func (o *NotificationDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *NotificationDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *NotificationDto) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUserId

`func (o *NotificationDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *NotificationDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *NotificationDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


