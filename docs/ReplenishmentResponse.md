# ReplenishmentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **time.Time** |  | 
**Lines** | [**[]ReplenishmentSuggestionLine**](ReplenishmentSuggestionLine.md) |  | 
**TargetWarehouseId** | **string** |  | 
**TotalSuggestedQuantity** | **int64** |  | 

## Methods

### NewReplenishmentResponse

`func NewReplenishmentResponse(generatedAt time.Time, lines []ReplenishmentSuggestionLine, targetWarehouseId string, totalSuggestedQuantity int64, ) *ReplenishmentResponse`

NewReplenishmentResponse instantiates a new ReplenishmentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReplenishmentResponseWithDefaults

`func NewReplenishmentResponseWithDefaults() *ReplenishmentResponse`

NewReplenishmentResponseWithDefaults instantiates a new ReplenishmentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGeneratedAt

`func (o *ReplenishmentResponse) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *ReplenishmentResponse) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *ReplenishmentResponse) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetLines

`func (o *ReplenishmentResponse) GetLines() []ReplenishmentSuggestionLine`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *ReplenishmentResponse) GetLinesOk() (*[]ReplenishmentSuggestionLine, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *ReplenishmentResponse) SetLines(v []ReplenishmentSuggestionLine)`

SetLines sets Lines field to given value.


### GetTargetWarehouseId

`func (o *ReplenishmentResponse) GetTargetWarehouseId() string`

GetTargetWarehouseId returns the TargetWarehouseId field if non-nil, zero value otherwise.

### GetTargetWarehouseIdOk

`func (o *ReplenishmentResponse) GetTargetWarehouseIdOk() (*string, bool)`

GetTargetWarehouseIdOk returns a tuple with the TargetWarehouseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetWarehouseId

`func (o *ReplenishmentResponse) SetTargetWarehouseId(v string)`

SetTargetWarehouseId sets TargetWarehouseId field to given value.


### GetTotalSuggestedQuantity

`func (o *ReplenishmentResponse) GetTotalSuggestedQuantity() int64`

GetTotalSuggestedQuantity returns the TotalSuggestedQuantity field if non-nil, zero value otherwise.

### GetTotalSuggestedQuantityOk

`func (o *ReplenishmentResponse) GetTotalSuggestedQuantityOk() (*int64, bool)`

GetTotalSuggestedQuantityOk returns a tuple with the TotalSuggestedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSuggestedQuantity

`func (o *ReplenishmentResponse) SetTotalSuggestedQuantity(v int64)`

SetTotalSuggestedQuantity sets TotalSuggestedQuantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


