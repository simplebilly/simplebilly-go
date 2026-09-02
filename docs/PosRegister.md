# PosRegister

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Status** | Pointer to [**PosRegisterStatus**](PosRegisterStatus.md) |  | [optional] 

## Methods

### NewPosRegister

`func NewPosRegister(name string, ) *PosRegister`

NewPosRegister instantiates a new PosRegister object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPosRegisterWithDefaults

`func NewPosRegisterWithDefaults() *PosRegister`

NewPosRegisterWithDefaults instantiates a new PosRegister object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PosRegister) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PosRegister) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PosRegister) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *PosRegister) GetStatus() PosRegisterStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PosRegister) GetStatusOk() (*PosRegisterStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PosRegister) SetStatus(v PosRegisterStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PosRegister) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


