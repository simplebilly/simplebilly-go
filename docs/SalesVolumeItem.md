# SalesVolumeItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactId** | **string** |  | 
**ContactType** | **string** |  | 
**LastPurchaseDate** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**TotalInvoices** | **int32** |  | 
**TotalRevenue** | **string** |  | 

## Methods

### NewSalesVolumeItem

`func NewSalesVolumeItem(contactId string, contactType string, name string, totalInvoices int32, totalRevenue string, ) *SalesVolumeItem`

NewSalesVolumeItem instantiates a new SalesVolumeItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSalesVolumeItemWithDefaults

`func NewSalesVolumeItemWithDefaults() *SalesVolumeItem`

NewSalesVolumeItemWithDefaults instantiates a new SalesVolumeItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactId

`func (o *SalesVolumeItem) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *SalesVolumeItem) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *SalesVolumeItem) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### GetContactType

`func (o *SalesVolumeItem) GetContactType() string`

GetContactType returns the ContactType field if non-nil, zero value otherwise.

### GetContactTypeOk

`func (o *SalesVolumeItem) GetContactTypeOk() (*string, bool)`

GetContactTypeOk returns a tuple with the ContactType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactType

`func (o *SalesVolumeItem) SetContactType(v string)`

SetContactType sets ContactType field to given value.


### GetLastPurchaseDate

`func (o *SalesVolumeItem) GetLastPurchaseDate() string`

GetLastPurchaseDate returns the LastPurchaseDate field if non-nil, zero value otherwise.

### GetLastPurchaseDateOk

`func (o *SalesVolumeItem) GetLastPurchaseDateOk() (*string, bool)`

GetLastPurchaseDateOk returns a tuple with the LastPurchaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPurchaseDate

`func (o *SalesVolumeItem) SetLastPurchaseDate(v string)`

SetLastPurchaseDate sets LastPurchaseDate field to given value.

### HasLastPurchaseDate

`func (o *SalesVolumeItem) HasLastPurchaseDate() bool`

HasLastPurchaseDate returns a boolean if a field has been set.

### SetLastPurchaseDateNil

`func (o *SalesVolumeItem) SetLastPurchaseDateNil(b bool)`

 SetLastPurchaseDateNil sets the value for LastPurchaseDate to be an explicit nil

### UnsetLastPurchaseDate
`func (o *SalesVolumeItem) UnsetLastPurchaseDate()`

UnsetLastPurchaseDate ensures that no value is present for LastPurchaseDate, not even an explicit nil
### GetName

`func (o *SalesVolumeItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SalesVolumeItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SalesVolumeItem) SetName(v string)`

SetName sets Name field to given value.


### GetTotalInvoices

`func (o *SalesVolumeItem) GetTotalInvoices() int32`

GetTotalInvoices returns the TotalInvoices field if non-nil, zero value otherwise.

### GetTotalInvoicesOk

`func (o *SalesVolumeItem) GetTotalInvoicesOk() (*int32, bool)`

GetTotalInvoicesOk returns a tuple with the TotalInvoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalInvoices

`func (o *SalesVolumeItem) SetTotalInvoices(v int32)`

SetTotalInvoices sets TotalInvoices field to given value.


### GetTotalRevenue

`func (o *SalesVolumeItem) GetTotalRevenue() string`

GetTotalRevenue returns the TotalRevenue field if non-nil, zero value otherwise.

### GetTotalRevenueOk

`func (o *SalesVolumeItem) GetTotalRevenueOk() (*string, bool)`

GetTotalRevenueOk returns a tuple with the TotalRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRevenue

`func (o *SalesVolumeItem) SetTotalRevenue(v string)`

SetTotalRevenue sets TotalRevenue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


