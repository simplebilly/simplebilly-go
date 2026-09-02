# Lead

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Company** | Pointer to **NullableString** |  | [optional] 
**ConvertedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**Email** | Pointer to **NullableString** |  | [optional] 
**FirstContactAt** | **time.Time** |  | 
**Name** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**Score** | **int32** |  | 
**Source** | **string** |  | 
**Status** | [**LeadStatus**](LeadStatus.md) |  | 
**Tags** | **interface{}** |  | 
**TenantId** | **string** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewLead

`func NewLead(createdAt time.Time, firstContactAt time.Time, name string, score int32, source string, status LeadStatus, tags interface{}, tenantId string, ) *Lead`

NewLead instantiates a new Lead object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLeadWithDefaults

`func NewLeadWithDefaults() *Lead`

NewLeadWithDefaults instantiates a new Lead object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompany

`func (o *Lead) GetCompany() string`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *Lead) GetCompanyOk() (*string, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *Lead) SetCompany(v string)`

SetCompany sets Company field to given value.

### HasCompany

`func (o *Lead) HasCompany() bool`

HasCompany returns a boolean if a field has been set.

### SetCompanyNil

`func (o *Lead) SetCompanyNil(b bool)`

 SetCompanyNil sets the value for Company to be an explicit nil

### UnsetCompany
`func (o *Lead) UnsetCompany()`

UnsetCompany ensures that no value is present for Company, not even an explicit nil
### GetConvertedAt

`func (o *Lead) GetConvertedAt() time.Time`

GetConvertedAt returns the ConvertedAt field if non-nil, zero value otherwise.

### GetConvertedAtOk

`func (o *Lead) GetConvertedAtOk() (*time.Time, bool)`

GetConvertedAtOk returns a tuple with the ConvertedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedAt

`func (o *Lead) SetConvertedAt(v time.Time)`

SetConvertedAt sets ConvertedAt field to given value.

### HasConvertedAt

`func (o *Lead) HasConvertedAt() bool`

HasConvertedAt returns a boolean if a field has been set.

### SetConvertedAtNil

`func (o *Lead) SetConvertedAtNil(b bool)`

 SetConvertedAtNil sets the value for ConvertedAt to be an explicit nil

### UnsetConvertedAt
`func (o *Lead) UnsetConvertedAt()`

UnsetConvertedAt ensures that no value is present for ConvertedAt, not even an explicit nil
### GetCreatedAt

`func (o *Lead) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Lead) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Lead) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetEmail

`func (o *Lead) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Lead) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Lead) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *Lead) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *Lead) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *Lead) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetFirstContactAt

`func (o *Lead) GetFirstContactAt() time.Time`

GetFirstContactAt returns the FirstContactAt field if non-nil, zero value otherwise.

### GetFirstContactAtOk

`func (o *Lead) GetFirstContactAtOk() (*time.Time, bool)`

GetFirstContactAtOk returns a tuple with the FirstContactAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstContactAt

`func (o *Lead) SetFirstContactAt(v time.Time)`

SetFirstContactAt sets FirstContactAt field to given value.


### GetName

`func (o *Lead) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Lead) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Lead) SetName(v string)`

SetName sets Name field to given value.


### GetNotes

`func (o *Lead) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Lead) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Lead) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Lead) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *Lead) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *Lead) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPhone

`func (o *Lead) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *Lead) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *Lead) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *Lead) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *Lead) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *Lead) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetScore

`func (o *Lead) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *Lead) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *Lead) SetScore(v int32)`

SetScore sets Score field to given value.


### GetSource

`func (o *Lead) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Lead) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Lead) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *Lead) GetStatus() LeadStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Lead) GetStatusOk() (*LeadStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Lead) SetStatus(v LeadStatus)`

SetStatus sets Status field to given value.


### GetTags

`func (o *Lead) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Lead) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Lead) SetTags(v interface{})`

SetTags sets Tags field to given value.


### SetTagsNil

`func (o *Lead) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *Lead) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTenantId

`func (o *Lead) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *Lead) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *Lead) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetUpdatedAt

`func (o *Lead) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Lead) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Lead) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Lead) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Lead) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Lead) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


