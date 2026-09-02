# LaborCostRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cost** | **string** |  | 
**EmployeeId** | Pointer to **NullableString** |  | [optional] 
**GroupKey** | **string** |  | 
**Hours** | **string** |  | 
**Name** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewLaborCostRow

`func NewLaborCostRow(cost string, groupKey string, hours string, ) *LaborCostRow`

NewLaborCostRow instantiates a new LaborCostRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLaborCostRowWithDefaults

`func NewLaborCostRowWithDefaults() *LaborCostRow`

NewLaborCostRowWithDefaults instantiates a new LaborCostRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCost

`func (o *LaborCostRow) GetCost() string`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *LaborCostRow) GetCostOk() (*string, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *LaborCostRow) SetCost(v string)`

SetCost sets Cost field to given value.


### GetEmployeeId

`func (o *LaborCostRow) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *LaborCostRow) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *LaborCostRow) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *LaborCostRow) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### SetEmployeeIdNil

`func (o *LaborCostRow) SetEmployeeIdNil(b bool)`

 SetEmployeeIdNil sets the value for EmployeeId to be an explicit nil

### UnsetEmployeeId
`func (o *LaborCostRow) UnsetEmployeeId()`

UnsetEmployeeId ensures that no value is present for EmployeeId, not even an explicit nil
### GetGroupKey

`func (o *LaborCostRow) GetGroupKey() string`

GetGroupKey returns the GroupKey field if non-nil, zero value otherwise.

### GetGroupKeyOk

`func (o *LaborCostRow) GetGroupKeyOk() (*string, bool)`

GetGroupKeyOk returns a tuple with the GroupKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupKey

`func (o *LaborCostRow) SetGroupKey(v string)`

SetGroupKey sets GroupKey field to given value.


### GetHours

`func (o *LaborCostRow) GetHours() string`

GetHours returns the Hours field if non-nil, zero value otherwise.

### GetHoursOk

`func (o *LaborCostRow) GetHoursOk() (*string, bool)`

GetHoursOk returns a tuple with the Hours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHours

`func (o *LaborCostRow) SetHours(v string)`

SetHours sets Hours field to given value.


### GetName

`func (o *LaborCostRow) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LaborCostRow) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LaborCostRow) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *LaborCostRow) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *LaborCostRow) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *LaborCostRow) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


