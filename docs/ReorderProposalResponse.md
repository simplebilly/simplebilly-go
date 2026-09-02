# ReorderProposalResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **time.Time** |  | 
**Lines** | [**[]ReorderProposalLine**](ReorderProposalLine.md) |  | 
**TotalSuggestedQuantity** | **int64** |  | 

## Methods

### NewReorderProposalResponse

`func NewReorderProposalResponse(generatedAt time.Time, lines []ReorderProposalLine, totalSuggestedQuantity int64, ) *ReorderProposalResponse`

NewReorderProposalResponse instantiates a new ReorderProposalResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReorderProposalResponseWithDefaults

`func NewReorderProposalResponseWithDefaults() *ReorderProposalResponse`

NewReorderProposalResponseWithDefaults instantiates a new ReorderProposalResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGeneratedAt

`func (o *ReorderProposalResponse) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *ReorderProposalResponse) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *ReorderProposalResponse) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetLines

`func (o *ReorderProposalResponse) GetLines() []ReorderProposalLine`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *ReorderProposalResponse) GetLinesOk() (*[]ReorderProposalLine, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *ReorderProposalResponse) SetLines(v []ReorderProposalLine)`

SetLines sets Lines field to given value.


### GetTotalSuggestedQuantity

`func (o *ReorderProposalResponse) GetTotalSuggestedQuantity() int64`

GetTotalSuggestedQuantity returns the TotalSuggestedQuantity field if non-nil, zero value otherwise.

### GetTotalSuggestedQuantityOk

`func (o *ReorderProposalResponse) GetTotalSuggestedQuantityOk() (*int64, bool)`

GetTotalSuggestedQuantityOk returns a tuple with the TotalSuggestedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSuggestedQuantity

`func (o *ReorderProposalResponse) SetTotalSuggestedQuantity(v int64)`

SetTotalSuggestedQuantity sets TotalSuggestedQuantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


