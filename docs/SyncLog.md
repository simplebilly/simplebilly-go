# SyncLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**ConnectionId** | **string** |  | 
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 
**ItemsFailed** | **int32** |  | 
**ItemsSynced** | **int32** |  | 
**LogId** | **string** |  | 
**Platform** | **string** |  | 
**StartedAt** | **time.Time** |  | 
**Status** | **string** |  | 
**SyncType** | **string** |  | 

## Methods

### NewSyncLog

`func NewSyncLog(connectionId string, itemsFailed int32, itemsSynced int32, logId string, platform string, startedAt time.Time, status string, syncType string, ) *SyncLog`

NewSyncLog instantiates a new SyncLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncLogWithDefaults

`func NewSyncLogWithDefaults() *SyncLog`

NewSyncLogWithDefaults instantiates a new SyncLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *SyncLog) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *SyncLog) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *SyncLog) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *SyncLog) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *SyncLog) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *SyncLog) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetConnectionId

`func (o *SyncLog) GetConnectionId() string`

GetConnectionId returns the ConnectionId field if non-nil, zero value otherwise.

### GetConnectionIdOk

`func (o *SyncLog) GetConnectionIdOk() (*string, bool)`

GetConnectionIdOk returns a tuple with the ConnectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionId

`func (o *SyncLog) SetConnectionId(v string)`

SetConnectionId sets ConnectionId field to given value.


### GetErrorMessage

`func (o *SyncLog) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *SyncLog) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *SyncLog) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *SyncLog) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *SyncLog) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *SyncLog) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetItemsFailed

`func (o *SyncLog) GetItemsFailed() int32`

GetItemsFailed returns the ItemsFailed field if non-nil, zero value otherwise.

### GetItemsFailedOk

`func (o *SyncLog) GetItemsFailedOk() (*int32, bool)`

GetItemsFailedOk returns a tuple with the ItemsFailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsFailed

`func (o *SyncLog) SetItemsFailed(v int32)`

SetItemsFailed sets ItemsFailed field to given value.


### GetItemsSynced

`func (o *SyncLog) GetItemsSynced() int32`

GetItemsSynced returns the ItemsSynced field if non-nil, zero value otherwise.

### GetItemsSyncedOk

`func (o *SyncLog) GetItemsSyncedOk() (*int32, bool)`

GetItemsSyncedOk returns a tuple with the ItemsSynced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsSynced

`func (o *SyncLog) SetItemsSynced(v int32)`

SetItemsSynced sets ItemsSynced field to given value.


### GetLogId

`func (o *SyncLog) GetLogId() string`

GetLogId returns the LogId field if non-nil, zero value otherwise.

### GetLogIdOk

`func (o *SyncLog) GetLogIdOk() (*string, bool)`

GetLogIdOk returns a tuple with the LogId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogId

`func (o *SyncLog) SetLogId(v string)`

SetLogId sets LogId field to given value.


### GetPlatform

`func (o *SyncLog) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *SyncLog) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *SyncLog) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetStartedAt

`func (o *SyncLog) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *SyncLog) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *SyncLog) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *SyncLog) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SyncLog) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SyncLog) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSyncType

`func (o *SyncLog) GetSyncType() string`

GetSyncType returns the SyncType field if non-nil, zero value otherwise.

### GetSyncTypeOk

`func (o *SyncLog) GetSyncTypeOk() (*string, bool)`

GetSyncTypeOk returns a tuple with the SyncType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncType

`func (o *SyncLog) SetSyncType(v string)`

SetSyncType sets SyncType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


