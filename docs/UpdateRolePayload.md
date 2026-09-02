# UpdateRolePayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | **string** |  | 
**SyncPermissions** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewUpdateRolePayload

`func NewUpdateRolePayload(role string, ) *UpdateRolePayload`

NewUpdateRolePayload instantiates a new UpdateRolePayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateRolePayloadWithDefaults

`func NewUpdateRolePayloadWithDefaults() *UpdateRolePayload`

NewUpdateRolePayloadWithDefaults instantiates a new UpdateRolePayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *UpdateRolePayload) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *UpdateRolePayload) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *UpdateRolePayload) SetRole(v string)`

SetRole sets Role field to given value.


### GetSyncPermissions

`func (o *UpdateRolePayload) GetSyncPermissions() bool`

GetSyncPermissions returns the SyncPermissions field if non-nil, zero value otherwise.

### GetSyncPermissionsOk

`func (o *UpdateRolePayload) GetSyncPermissionsOk() (*bool, bool)`

GetSyncPermissionsOk returns a tuple with the SyncPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncPermissions

`func (o *UpdateRolePayload) SetSyncPermissions(v bool)`

SetSyncPermissions sets SyncPermissions field to given value.

### HasSyncPermissions

`func (o *UpdateRolePayload) HasSyncPermissions() bool`

HasSyncPermissions returns a boolean if a field has been set.

### SetSyncPermissionsNil

`func (o *UpdateRolePayload) SetSyncPermissionsNil(b bool)`

 SetSyncPermissionsNil sets the value for SyncPermissions to be an explicit nil

### UnsetSyncPermissions
`func (o *UpdateRolePayload) UnsetSyncPermissions()`

UnsetSyncPermissions ensures that no value is present for SyncPermissions, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


