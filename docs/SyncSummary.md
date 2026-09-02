# SyncSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 
**ItemsFailed** | Pointer to **int32** |  | [optional] 
**ItemsSynced** | Pointer to **int32** |  | [optional] 

## Methods

### NewSyncSummary

`func NewSyncSummary() *SyncSummary`

NewSyncSummary instantiates a new SyncSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncSummaryWithDefaults

`func NewSyncSummaryWithDefaults() *SyncSummary`

NewSyncSummaryWithDefaults instantiates a new SyncSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorMessage

`func (o *SyncSummary) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *SyncSummary) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *SyncSummary) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *SyncSummary) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *SyncSummary) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *SyncSummary) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetItemsFailed

`func (o *SyncSummary) GetItemsFailed() int32`

GetItemsFailed returns the ItemsFailed field if non-nil, zero value otherwise.

### GetItemsFailedOk

`func (o *SyncSummary) GetItemsFailedOk() (*int32, bool)`

GetItemsFailedOk returns a tuple with the ItemsFailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsFailed

`func (o *SyncSummary) SetItemsFailed(v int32)`

SetItemsFailed sets ItemsFailed field to given value.

### HasItemsFailed

`func (o *SyncSummary) HasItemsFailed() bool`

HasItemsFailed returns a boolean if a field has been set.

### GetItemsSynced

`func (o *SyncSummary) GetItemsSynced() int32`

GetItemsSynced returns the ItemsSynced field if non-nil, zero value otherwise.

### GetItemsSyncedOk

`func (o *SyncSummary) GetItemsSyncedOk() (*int32, bool)`

GetItemsSyncedOk returns a tuple with the ItemsSynced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsSynced

`func (o *SyncSummary) SetItemsSynced(v int32)`

SetItemsSynced sets ItemsSynced field to given value.

### HasItemsSynced

`func (o *SyncSummary) HasItemsSynced() bool`

HasItemsSynced returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


