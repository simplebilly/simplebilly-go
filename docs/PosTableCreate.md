# PosTableCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentOrderNumber** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**Status** | Pointer to [**PosTableStatus**](PosTableStatus.md) |  | [optional] 

## Methods

### NewPosTableCreate

`func NewPosTableCreate(name string, ) *PosTableCreate`

NewPosTableCreate instantiates a new PosTableCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPosTableCreateWithDefaults

`func NewPosTableCreateWithDefaults() *PosTableCreate`

NewPosTableCreateWithDefaults instantiates a new PosTableCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentOrderNumber

`func (o *PosTableCreate) GetCurrentOrderNumber() string`

GetCurrentOrderNumber returns the CurrentOrderNumber field if non-nil, zero value otherwise.

### GetCurrentOrderNumberOk

`func (o *PosTableCreate) GetCurrentOrderNumberOk() (*string, bool)`

GetCurrentOrderNumberOk returns a tuple with the CurrentOrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentOrderNumber

`func (o *PosTableCreate) SetCurrentOrderNumber(v string)`

SetCurrentOrderNumber sets CurrentOrderNumber field to given value.

### HasCurrentOrderNumber

`func (o *PosTableCreate) HasCurrentOrderNumber() bool`

HasCurrentOrderNumber returns a boolean if a field has been set.

### SetCurrentOrderNumberNil

`func (o *PosTableCreate) SetCurrentOrderNumberNil(b bool)`

 SetCurrentOrderNumberNil sets the value for CurrentOrderNumber to be an explicit nil

### UnsetCurrentOrderNumber
`func (o *PosTableCreate) UnsetCurrentOrderNumber()`

UnsetCurrentOrderNumber ensures that no value is present for CurrentOrderNumber, not even an explicit nil
### GetName

`func (o *PosTableCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PosTableCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PosTableCreate) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *PosTableCreate) GetStatus() PosTableStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PosTableCreate) GetStatusOk() (*PosTableStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PosTableCreate) SetStatus(v PosTableStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PosTableCreate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


