# CreateChannelDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChannelType** | **string** |  | 
**Config** | **interface{}** |  | 
**Name** | **string** |  | 

## Methods

### NewCreateChannelDto

`func NewCreateChannelDto(channelType string, config interface{}, name string, ) *CreateChannelDto`

NewCreateChannelDto instantiates a new CreateChannelDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChannelDtoWithDefaults

`func NewCreateChannelDtoWithDefaults() *CreateChannelDto`

NewCreateChannelDtoWithDefaults instantiates a new CreateChannelDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChannelType

`func (o *CreateChannelDto) GetChannelType() string`

GetChannelType returns the ChannelType field if non-nil, zero value otherwise.

### GetChannelTypeOk

`func (o *CreateChannelDto) GetChannelTypeOk() (*string, bool)`

GetChannelTypeOk returns a tuple with the ChannelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelType

`func (o *CreateChannelDto) SetChannelType(v string)`

SetChannelType sets ChannelType field to given value.


### GetConfig

`func (o *CreateChannelDto) GetConfig() interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateChannelDto) GetConfigOk() (*interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateChannelDto) SetConfig(v interface{})`

SetConfig sets Config field to given value.


### SetConfigNil

`func (o *CreateChannelDto) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *CreateChannelDto) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetName

`func (o *CreateChannelDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateChannelDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateChannelDto) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


