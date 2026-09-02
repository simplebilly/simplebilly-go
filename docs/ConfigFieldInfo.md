# ConfigFieldInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | [**ConfigFieldKind**](ConfigFieldKind.md) |  | 
**Label** | **string** |  | 
**Name** | **string** |  | 
**Placeholder** | Pointer to **NullableString** |  | [optional] 
**Required** | **bool** |  | 

## Methods

### NewConfigFieldInfo

`func NewConfigFieldInfo(kind ConfigFieldKind, label string, name string, required bool, ) *ConfigFieldInfo`

NewConfigFieldInfo instantiates a new ConfigFieldInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigFieldInfoWithDefaults

`func NewConfigFieldInfoWithDefaults() *ConfigFieldInfo`

NewConfigFieldInfoWithDefaults instantiates a new ConfigFieldInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *ConfigFieldInfo) GetKind() ConfigFieldKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ConfigFieldInfo) GetKindOk() (*ConfigFieldKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ConfigFieldInfo) SetKind(v ConfigFieldKind)`

SetKind sets Kind field to given value.


### GetLabel

`func (o *ConfigFieldInfo) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ConfigFieldInfo) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ConfigFieldInfo) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetName

`func (o *ConfigFieldInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConfigFieldInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConfigFieldInfo) SetName(v string)`

SetName sets Name field to given value.


### GetPlaceholder

`func (o *ConfigFieldInfo) GetPlaceholder() string`

GetPlaceholder returns the Placeholder field if non-nil, zero value otherwise.

### GetPlaceholderOk

`func (o *ConfigFieldInfo) GetPlaceholderOk() (*string, bool)`

GetPlaceholderOk returns a tuple with the Placeholder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaceholder

`func (o *ConfigFieldInfo) SetPlaceholder(v string)`

SetPlaceholder sets Placeholder field to given value.

### HasPlaceholder

`func (o *ConfigFieldInfo) HasPlaceholder() bool`

HasPlaceholder returns a boolean if a field has been set.

### SetPlaceholderNil

`func (o *ConfigFieldInfo) SetPlaceholderNil(b bool)`

 SetPlaceholderNil sets the value for Placeholder to be an explicit nil

### UnsetPlaceholder
`func (o *ConfigFieldInfo) UnsetPlaceholder()`

UnsetPlaceholder ensures that no value is present for Placeholder, not even an explicit nil
### GetRequired

`func (o *ConfigFieldInfo) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *ConfigFieldInfo) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *ConfigFieldInfo) SetRequired(v bool)`

SetRequired sets Required field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


