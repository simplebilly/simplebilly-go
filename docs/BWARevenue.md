# BWARevenue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RevenueBreakdown** | [**[]RevenueItem**](RevenueItem.md) |  | 
**TotalRevenue** | **string** |  | 

## Methods

### NewBWARevenue

`func NewBWARevenue(revenueBreakdown []RevenueItem, totalRevenue string, ) *BWARevenue`

NewBWARevenue instantiates a new BWARevenue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBWARevenueWithDefaults

`func NewBWARevenueWithDefaults() *BWARevenue`

NewBWARevenueWithDefaults instantiates a new BWARevenue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRevenueBreakdown

`func (o *BWARevenue) GetRevenueBreakdown() []RevenueItem`

GetRevenueBreakdown returns the RevenueBreakdown field if non-nil, zero value otherwise.

### GetRevenueBreakdownOk

`func (o *BWARevenue) GetRevenueBreakdownOk() (*[]RevenueItem, bool)`

GetRevenueBreakdownOk returns a tuple with the RevenueBreakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenueBreakdown

`func (o *BWARevenue) SetRevenueBreakdown(v []RevenueItem)`

SetRevenueBreakdown sets RevenueBreakdown field to given value.


### GetTotalRevenue

`func (o *BWARevenue) GetTotalRevenue() string`

GetTotalRevenue returns the TotalRevenue field if non-nil, zero value otherwise.

### GetTotalRevenueOk

`func (o *BWARevenue) GetTotalRevenueOk() (*string, bool)`

GetTotalRevenueOk returns a tuple with the TotalRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRevenue

`func (o *BWARevenue) SetTotalRevenue(v string)`

SetTotalRevenue sets TotalRevenue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


