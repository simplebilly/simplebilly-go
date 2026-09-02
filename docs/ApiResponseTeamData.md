# ApiResponseTeamData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**Id** | **string** |  | 
**Name** | **string** |  | 
**ParentTeamId** | Pointer to **NullableString** |  | [optional] 
**TenantId** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewApiResponseTeamData

`func NewApiResponseTeamData(createdAt time.Time, id string, name string, tenantId string, updatedAt time.Time, ) *ApiResponseTeamData`

NewApiResponseTeamData instantiates a new ApiResponseTeamData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseTeamDataWithDefaults

`func NewApiResponseTeamDataWithDefaults() *ApiResponseTeamData`

NewApiResponseTeamDataWithDefaults instantiates a new ApiResponseTeamData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *ApiResponseTeamData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ApiResponseTeamData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ApiResponseTeamData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *ApiResponseTeamData) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ApiResponseTeamData) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ApiResponseTeamData) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ApiResponseTeamData) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ApiResponseTeamData) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ApiResponseTeamData) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetId

`func (o *ApiResponseTeamData) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApiResponseTeamData) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApiResponseTeamData) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ApiResponseTeamData) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiResponseTeamData) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiResponseTeamData) SetName(v string)`

SetName sets Name field to given value.


### GetParentTeamId

`func (o *ApiResponseTeamData) GetParentTeamId() string`

GetParentTeamId returns the ParentTeamId field if non-nil, zero value otherwise.

### GetParentTeamIdOk

`func (o *ApiResponseTeamData) GetParentTeamIdOk() (*string, bool)`

GetParentTeamIdOk returns a tuple with the ParentTeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentTeamId

`func (o *ApiResponseTeamData) SetParentTeamId(v string)`

SetParentTeamId sets ParentTeamId field to given value.

### HasParentTeamId

`func (o *ApiResponseTeamData) HasParentTeamId() bool`

HasParentTeamId returns a boolean if a field has been set.

### SetParentTeamIdNil

`func (o *ApiResponseTeamData) SetParentTeamIdNil(b bool)`

 SetParentTeamIdNil sets the value for ParentTeamId to be an explicit nil

### UnsetParentTeamId
`func (o *ApiResponseTeamData) UnsetParentTeamId()`

UnsetParentTeamId ensures that no value is present for ParentTeamId, not even an explicit nil
### GetTenantId

`func (o *ApiResponseTeamData) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *ApiResponseTeamData) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *ApiResponseTeamData) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetUpdatedAt

`func (o *ApiResponseTeamData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ApiResponseTeamData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ApiResponseTeamData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


