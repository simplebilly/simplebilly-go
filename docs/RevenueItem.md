# RevenueItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **string** |  | 
**Category** | **string** |  | 
**Percentage** | **float64** |  | 

## Methods

### NewRevenueItem

`func NewRevenueItem(amount string, category string, percentage float64, ) *RevenueItem`

NewRevenueItem instantiates a new RevenueItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRevenueItemWithDefaults

`func NewRevenueItemWithDefaults() *RevenueItem`

NewRevenueItemWithDefaults instantiates a new RevenueItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *RevenueItem) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *RevenueItem) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *RevenueItem) SetAmount(v string)`

SetAmount sets Amount field to given value.


### GetCategory

`func (o *RevenueItem) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *RevenueItem) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *RevenueItem) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetPercentage

`func (o *RevenueItem) GetPercentage() float64`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *RevenueItem) GetPercentageOk() (*float64, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *RevenueItem) SetPercentage(v float64)`

SetPercentage sets Percentage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


