# TeamCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**ParentTeamId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTeamCreate

`func NewTeamCreate(name string, ) *TeamCreate`

NewTeamCreate instantiates a new TeamCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTeamCreateWithDefaults

`func NewTeamCreateWithDefaults() *TeamCreate`

NewTeamCreateWithDefaults instantiates a new TeamCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *TeamCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TeamCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TeamCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *TeamCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *TeamCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *TeamCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *TeamCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TeamCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TeamCreate) SetName(v string)`

SetName sets Name field to given value.


### GetParentTeamId

`func (o *TeamCreate) GetParentTeamId() string`

GetParentTeamId returns the ParentTeamId field if non-nil, zero value otherwise.

### GetParentTeamIdOk

`func (o *TeamCreate) GetParentTeamIdOk() (*string, bool)`

GetParentTeamIdOk returns a tuple with the ParentTeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentTeamId

`func (o *TeamCreate) SetParentTeamId(v string)`

SetParentTeamId sets ParentTeamId field to given value.

### HasParentTeamId

`func (o *TeamCreate) HasParentTeamId() bool`

HasParentTeamId returns a boolean if a field has been set.

### SetParentTeamIdNil

`func (o *TeamCreate) SetParentTeamIdNil(b bool)`

 SetParentTeamIdNil sets the value for ParentTeamId to be an explicit nil

### UnsetParentTeamId
`func (o *TeamCreate) UnsetParentTeamId()`

UnsetParentTeamId ensures that no value is present for ParentTeamId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


