# RfqCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **string** |  | [optional] 
**LineItems** | **interface{}** | JSON array of &#x60;{product_id, name, sku, quantity, requested_unit_price?, quoted_unit_price?}&#x60;. | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**RequestedDate** | **string** |  | 
**ResponseDate** | Pointer to **NullableString** |  | [optional] 
**RfqNumber** | **string** |  | 
**Status** | [**RfqStatus**](RfqStatus.md) | One of: draft | sent | offer_received | rejected | converted | 
**SupplierContactId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewRfqCreate

`func NewRfqCreate(lineItems interface{}, requestedDate string, rfqNumber string, status RfqStatus, ) *RfqCreate`

NewRfqCreate instantiates a new RfqCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRfqCreateWithDefaults

`func NewRfqCreateWithDefaults() *RfqCreate`

NewRfqCreateWithDefaults instantiates a new RfqCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *RfqCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *RfqCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *RfqCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *RfqCreate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetLineItems

`func (o *RfqCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *RfqCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *RfqCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *RfqCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *RfqCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *RfqCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *RfqCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *RfqCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *RfqCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *RfqCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *RfqCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetRequestedDate

`func (o *RfqCreate) GetRequestedDate() string`

GetRequestedDate returns the RequestedDate field if non-nil, zero value otherwise.

### GetRequestedDateOk

`func (o *RfqCreate) GetRequestedDateOk() (*string, bool)`

GetRequestedDateOk returns a tuple with the RequestedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDate

`func (o *RfqCreate) SetRequestedDate(v string)`

SetRequestedDate sets RequestedDate field to given value.


### GetResponseDate

`func (o *RfqCreate) GetResponseDate() string`

GetResponseDate returns the ResponseDate field if non-nil, zero value otherwise.

### GetResponseDateOk

`func (o *RfqCreate) GetResponseDateOk() (*string, bool)`

GetResponseDateOk returns a tuple with the ResponseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseDate

`func (o *RfqCreate) SetResponseDate(v string)`

SetResponseDate sets ResponseDate field to given value.

### HasResponseDate

`func (o *RfqCreate) HasResponseDate() bool`

HasResponseDate returns a boolean if a field has been set.

### SetResponseDateNil

`func (o *RfqCreate) SetResponseDateNil(b bool)`

 SetResponseDateNil sets the value for ResponseDate to be an explicit nil

### UnsetResponseDate
`func (o *RfqCreate) UnsetResponseDate()`

UnsetResponseDate ensures that no value is present for ResponseDate, not even an explicit nil
### GetRfqNumber

`func (o *RfqCreate) GetRfqNumber() string`

GetRfqNumber returns the RfqNumber field if non-nil, zero value otherwise.

### GetRfqNumberOk

`func (o *RfqCreate) GetRfqNumberOk() (*string, bool)`

GetRfqNumberOk returns a tuple with the RfqNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRfqNumber

`func (o *RfqCreate) SetRfqNumber(v string)`

SetRfqNumber sets RfqNumber field to given value.


### GetStatus

`func (o *RfqCreate) GetStatus() RfqStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RfqCreate) GetStatusOk() (*RfqStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RfqCreate) SetStatus(v RfqStatus)`

SetStatus sets Status field to given value.


### GetSupplierContactId

`func (o *RfqCreate) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *RfqCreate) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *RfqCreate) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *RfqCreate) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *RfqCreate) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *RfqCreate) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *RfqCreate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *RfqCreate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *RfqCreate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *RfqCreate) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *RfqCreate) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *RfqCreate) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


