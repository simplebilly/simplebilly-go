# ApplicationStatusDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PostingId** | Pointer to **NullableString** |  | [optional] 
**Status** | **string** |  | 

## Methods

### NewApplicationStatusDto

`func NewApplicationStatusDto(status string, ) *ApplicationStatusDto`

NewApplicationStatusDto instantiates a new ApplicationStatusDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationStatusDtoWithDefaults

`func NewApplicationStatusDtoWithDefaults() *ApplicationStatusDto`

NewApplicationStatusDtoWithDefaults instantiates a new ApplicationStatusDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPostingId

`func (o *ApplicationStatusDto) GetPostingId() string`

GetPostingId returns the PostingId field if non-nil, zero value otherwise.

### GetPostingIdOk

`func (o *ApplicationStatusDto) GetPostingIdOk() (*string, bool)`

GetPostingIdOk returns a tuple with the PostingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostingId

`func (o *ApplicationStatusDto) SetPostingId(v string)`

SetPostingId sets PostingId field to given value.

### HasPostingId

`func (o *ApplicationStatusDto) HasPostingId() bool`

HasPostingId returns a boolean if a field has been set.

### SetPostingIdNil

`func (o *ApplicationStatusDto) SetPostingIdNil(b bool)`

 SetPostingIdNil sets the value for PostingId to be an explicit nil

### UnsetPostingId
`func (o *ApplicationStatusDto) UnsetPostingId()`

UnsetPostingId ensures that no value is present for PostingId, not even an explicit nil
### GetStatus

`func (o *ApplicationStatusDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ApplicationStatusDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ApplicationStatusDto) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


