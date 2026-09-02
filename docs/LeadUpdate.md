# LeadUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Company** | Pointer to **NullableString** |  | [optional] 
**ConvertedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**FirstContactAt** | Pointer to **NullableTime** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**Score** | Pointer to **NullableInt32** |  | [optional] 
**Source** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableLeadStatus**](LeadStatus.md) |  | [optional] 
**Tags** | Pointer to **interface{}** |  | [optional] 
**TenantId** | Pointer to **NullableString** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewLeadUpdate

`func NewLeadUpdate() *LeadUpdate`

NewLeadUpdate instantiates a new LeadUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLeadUpdateWithDefaults

`func NewLeadUpdateWithDefaults() *LeadUpdate`

NewLeadUpdateWithDefaults instantiates a new LeadUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompany

`func (o *LeadUpdate) GetCompany() string`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *LeadUpdate) GetCompanyOk() (*string, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *LeadUpdate) SetCompany(v string)`

SetCompany sets Company field to given value.

### HasCompany

`func (o *LeadUpdate) HasCompany() bool`

HasCompany returns a boolean if a field has been set.

### SetCompanyNil

`func (o *LeadUpdate) SetCompanyNil(b bool)`

 SetCompanyNil sets the value for Company to be an explicit nil

### UnsetCompany
`func (o *LeadUpdate) UnsetCompany()`

UnsetCompany ensures that no value is present for Company, not even an explicit nil
### GetConvertedAt

`func (o *LeadUpdate) GetConvertedAt() time.Time`

GetConvertedAt returns the ConvertedAt field if non-nil, zero value otherwise.

### GetConvertedAtOk

`func (o *LeadUpdate) GetConvertedAtOk() (*time.Time, bool)`

GetConvertedAtOk returns a tuple with the ConvertedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedAt

`func (o *LeadUpdate) SetConvertedAt(v time.Time)`

SetConvertedAt sets ConvertedAt field to given value.

### HasConvertedAt

`func (o *LeadUpdate) HasConvertedAt() bool`

HasConvertedAt returns a boolean if a field has been set.

### SetConvertedAtNil

`func (o *LeadUpdate) SetConvertedAtNil(b bool)`

 SetConvertedAtNil sets the value for ConvertedAt to be an explicit nil

### UnsetConvertedAt
`func (o *LeadUpdate) UnsetConvertedAt()`

UnsetConvertedAt ensures that no value is present for ConvertedAt, not even an explicit nil
### GetCreatedAt

`func (o *LeadUpdate) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LeadUpdate) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LeadUpdate) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *LeadUpdate) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *LeadUpdate) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *LeadUpdate) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetEmail

`func (o *LeadUpdate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *LeadUpdate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *LeadUpdate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *LeadUpdate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *LeadUpdate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *LeadUpdate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetFirstContactAt

`func (o *LeadUpdate) GetFirstContactAt() time.Time`

GetFirstContactAt returns the FirstContactAt field if non-nil, zero value otherwise.

### GetFirstContactAtOk

`func (o *LeadUpdate) GetFirstContactAtOk() (*time.Time, bool)`

GetFirstContactAtOk returns a tuple with the FirstContactAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstContactAt

`func (o *LeadUpdate) SetFirstContactAt(v time.Time)`

SetFirstContactAt sets FirstContactAt field to given value.

### HasFirstContactAt

`func (o *LeadUpdate) HasFirstContactAt() bool`

HasFirstContactAt returns a boolean if a field has been set.

### SetFirstContactAtNil

`func (o *LeadUpdate) SetFirstContactAtNil(b bool)`

 SetFirstContactAtNil sets the value for FirstContactAt to be an explicit nil

### UnsetFirstContactAt
`func (o *LeadUpdate) UnsetFirstContactAt()`

UnsetFirstContactAt ensures that no value is present for FirstContactAt, not even an explicit nil
### GetName

`func (o *LeadUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LeadUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LeadUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *LeadUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *LeadUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *LeadUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetNotes

`func (o *LeadUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *LeadUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *LeadUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *LeadUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *LeadUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *LeadUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPhone

`func (o *LeadUpdate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *LeadUpdate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *LeadUpdate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *LeadUpdate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *LeadUpdate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *LeadUpdate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetScore

`func (o *LeadUpdate) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *LeadUpdate) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *LeadUpdate) SetScore(v int32)`

SetScore sets Score field to given value.

### HasScore

`func (o *LeadUpdate) HasScore() bool`

HasScore returns a boolean if a field has been set.

### SetScoreNil

`func (o *LeadUpdate) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *LeadUpdate) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetSource

`func (o *LeadUpdate) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *LeadUpdate) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *LeadUpdate) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *LeadUpdate) HasSource() bool`

HasSource returns a boolean if a field has been set.

### SetSourceNil

`func (o *LeadUpdate) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *LeadUpdate) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetStatus

`func (o *LeadUpdate) GetStatus() LeadStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LeadUpdate) GetStatusOk() (*LeadStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LeadUpdate) SetStatus(v LeadStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LeadUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *LeadUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *LeadUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetTags

`func (o *LeadUpdate) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *LeadUpdate) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *LeadUpdate) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *LeadUpdate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *LeadUpdate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *LeadUpdate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTenantId

`func (o *LeadUpdate) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *LeadUpdate) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *LeadUpdate) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *LeadUpdate) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *LeadUpdate) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *LeadUpdate) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetUpdatedAt

`func (o *LeadUpdate) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LeadUpdate) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LeadUpdate) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *LeadUpdate) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *LeadUpdate) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *LeadUpdate) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


