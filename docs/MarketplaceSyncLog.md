# MarketplaceSyncLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**ConnectionId** | **string** | References the marketplace connection entity. | 
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 
**ItemsFailed** | **int32** |  | 
**ItemsSynced** | **int32** |  | 
**Platform** | **string** |  | 
**StartedAt** | **time.Time** |  | 
**Status** | [**SyncLogStatus**](SyncLogStatus.md) |  | 
**SyncType** | [**SyncType**](SyncType.md) |  | 

## Methods

### NewMarketplaceSyncLog

`func NewMarketplaceSyncLog(connectionId string, itemsFailed int32, itemsSynced int32, platform string, startedAt time.Time, status SyncLogStatus, syncType SyncType, ) *MarketplaceSyncLog`

NewMarketplaceSyncLog instantiates a new MarketplaceSyncLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMarketplaceSyncLogWithDefaults

`func NewMarketplaceSyncLogWithDefaults() *MarketplaceSyncLog`

NewMarketplaceSyncLogWithDefaults instantiates a new MarketplaceSyncLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *MarketplaceSyncLog) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *MarketplaceSyncLog) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *MarketplaceSyncLog) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *MarketplaceSyncLog) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *MarketplaceSyncLog) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *MarketplaceSyncLog) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetConnectionId

`func (o *MarketplaceSyncLog) GetConnectionId() string`

GetConnectionId returns the ConnectionId field if non-nil, zero value otherwise.

### GetConnectionIdOk

`func (o *MarketplaceSyncLog) GetConnectionIdOk() (*string, bool)`

GetConnectionIdOk returns a tuple with the ConnectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionId

`func (o *MarketplaceSyncLog) SetConnectionId(v string)`

SetConnectionId sets ConnectionId field to given value.


### GetErrorMessage

`func (o *MarketplaceSyncLog) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *MarketplaceSyncLog) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *MarketplaceSyncLog) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *MarketplaceSyncLog) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *MarketplaceSyncLog) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *MarketplaceSyncLog) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetItemsFailed

`func (o *MarketplaceSyncLog) GetItemsFailed() int32`

GetItemsFailed returns the ItemsFailed field if non-nil, zero value otherwise.

### GetItemsFailedOk

`func (o *MarketplaceSyncLog) GetItemsFailedOk() (*int32, bool)`

GetItemsFailedOk returns a tuple with the ItemsFailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsFailed

`func (o *MarketplaceSyncLog) SetItemsFailed(v int32)`

SetItemsFailed sets ItemsFailed field to given value.


### GetItemsSynced

`func (o *MarketplaceSyncLog) GetItemsSynced() int32`

GetItemsSynced returns the ItemsSynced field if non-nil, zero value otherwise.

### GetItemsSyncedOk

`func (o *MarketplaceSyncLog) GetItemsSyncedOk() (*int32, bool)`

GetItemsSyncedOk returns a tuple with the ItemsSynced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsSynced

`func (o *MarketplaceSyncLog) SetItemsSynced(v int32)`

SetItemsSynced sets ItemsSynced field to given value.


### GetPlatform

`func (o *MarketplaceSyncLog) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *MarketplaceSyncLog) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *MarketplaceSyncLog) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetStartedAt

`func (o *MarketplaceSyncLog) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *MarketplaceSyncLog) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *MarketplaceSyncLog) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *MarketplaceSyncLog) GetStatus() SyncLogStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MarketplaceSyncLog) GetStatusOk() (*SyncLogStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MarketplaceSyncLog) SetStatus(v SyncLogStatus)`

SetStatus sets Status field to given value.


### GetSyncType

`func (o *MarketplaceSyncLog) GetSyncType() SyncType`

GetSyncType returns the SyncType field if non-nil, zero value otherwise.

### GetSyncTypeOk

`func (o *MarketplaceSyncLog) GetSyncTypeOk() (*SyncType, bool)`

GetSyncTypeOk returns a tuple with the SyncType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncType

`func (o *MarketplaceSyncLog) SetSyncType(v SyncType)`

SetSyncType sets SyncType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


