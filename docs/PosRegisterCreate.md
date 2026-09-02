# PosRegisterCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Status** | Pointer to [**PosRegisterStatus**](PosRegisterStatus.md) |  | [optional] 

## Methods

### NewPosRegisterCreate

`func NewPosRegisterCreate(name string, ) *PosRegisterCreate`

NewPosRegisterCreate instantiates a new PosRegisterCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPosRegisterCreateWithDefaults

`func NewPosRegisterCreateWithDefaults() *PosRegisterCreate`

NewPosRegisterCreateWithDefaults instantiates a new PosRegisterCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PosRegisterCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PosRegisterCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PosRegisterCreate) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *PosRegisterCreate) GetStatus() PosRegisterStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PosRegisterCreate) GetStatusOk() (*PosRegisterStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PosRegisterCreate) SetStatus(v PosRegisterStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PosRegisterCreate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


