# PosTable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentOrderNumber** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**Status** | Pointer to [**PosTableStatus**](PosTableStatus.md) |  | [optional] 

## Methods

### NewPosTable

`func NewPosTable(name string, ) *PosTable`

NewPosTable instantiates a new PosTable object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPosTableWithDefaults

`func NewPosTableWithDefaults() *PosTable`

NewPosTableWithDefaults instantiates a new PosTable object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentOrderNumber

`func (o *PosTable) GetCurrentOrderNumber() string`

GetCurrentOrderNumber returns the CurrentOrderNumber field if non-nil, zero value otherwise.

### GetCurrentOrderNumberOk

`func (o *PosTable) GetCurrentOrderNumberOk() (*string, bool)`

GetCurrentOrderNumberOk returns a tuple with the CurrentOrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentOrderNumber

`func (o *PosTable) SetCurrentOrderNumber(v string)`

SetCurrentOrderNumber sets CurrentOrderNumber field to given value.

### HasCurrentOrderNumber

`func (o *PosTable) HasCurrentOrderNumber() bool`

HasCurrentOrderNumber returns a boolean if a field has been set.

### SetCurrentOrderNumberNil

`func (o *PosTable) SetCurrentOrderNumberNil(b bool)`

 SetCurrentOrderNumberNil sets the value for CurrentOrderNumber to be an explicit nil

### UnsetCurrentOrderNumber
`func (o *PosTable) UnsetCurrentOrderNumber()`

UnsetCurrentOrderNumber ensures that no value is present for CurrentOrderNumber, not even an explicit nil
### GetName

`func (o *PosTable) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PosTable) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PosTable) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *PosTable) GetStatus() PosTableStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PosTable) GetStatusOk() (*PosTableStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PosTable) SetStatus(v PosTableStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PosTable) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


