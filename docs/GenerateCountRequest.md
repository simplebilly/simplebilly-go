# GenerateCountRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Notes** | Pointer to **NullableString** |  | [optional] 
**ProductIds** | Pointer to **[]string** |  | [optional] 
**WarehouseId** | **string** |  | 

## Methods

### NewGenerateCountRequest

`func NewGenerateCountRequest(warehouseId string, ) *GenerateCountRequest`

NewGenerateCountRequest instantiates a new GenerateCountRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGenerateCountRequestWithDefaults

`func NewGenerateCountRequestWithDefaults() *GenerateCountRequest`

NewGenerateCountRequestWithDefaults instantiates a new GenerateCountRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotes

`func (o *GenerateCountRequest) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *GenerateCountRequest) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *GenerateCountRequest) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *GenerateCountRequest) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *GenerateCountRequest) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *GenerateCountRequest) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetProductIds

`func (o *GenerateCountRequest) GetProductIds() []string`

GetProductIds returns the ProductIds field if non-nil, zero value otherwise.

### GetProductIdsOk

`func (o *GenerateCountRequest) GetProductIdsOk() (*[]string, bool)`

GetProductIdsOk returns a tuple with the ProductIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductIds

`func (o *GenerateCountRequest) SetProductIds(v []string)`

SetProductIds sets ProductIds field to given value.

### HasProductIds

`func (o *GenerateCountRequest) HasProductIds() bool`

HasProductIds returns a boolean if a field has been set.

### SetProductIdsNil

`func (o *GenerateCountRequest) SetProductIdsNil(b bool)`

 SetProductIdsNil sets the value for ProductIds to be an explicit nil

### UnsetProductIds
`func (o *GenerateCountRequest) UnsetProductIds()`

UnsetProductIds ensures that no value is present for ProductIds, not even an explicit nil
### GetWarehouseId

`func (o *GenerateCountRequest) GetWarehouseId() string`

GetWarehouseId returns the WarehouseId field if non-nil, zero value otherwise.

### GetWarehouseIdOk

`func (o *GenerateCountRequest) GetWarehouseIdOk() (*string, bool)`

GetWarehouseIdOk returns a tuple with the WarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarehouseId

`func (o *GenerateCountRequest) SetWarehouseId(v string)`

SetWarehouseId sets WarehouseId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


